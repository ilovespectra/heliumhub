# Online / Offline Status

[Validators](../../helium-glossary.md#validator) run [consensus](../../helium-glossary.md#consensus) programs, challenge [hotspots](../../helium-glossary.md#hotspot) to send [beacons](../../helium-glossary.md#beacon), and add [blocks](../../helium-glossary.md#block) to the [Helium blockchain](../../helium-glossary.md#helium-blockchain). They're responsible for a lot of work, so occasionally, hotspot issues are caused by a failed executable "back of house," if you will. You can take a look at your hotspot's activity by running the command below on this website:

[**Helium ETL**](https://etl.dewi.org/question#eyJkYXRhc2V0X3F1ZXJ5Ijp7ImRhdGFiYXNlIjpudWxsLCJuYXRpdmUiOnsicXVlcnkiOiIiLCJ0ZW1wbGF0ZS10YWdzIjp7fX0sInR5cGUiOiJuYXRpdmUifSwiZGlzcGxheSI6InRhYmxlIiwidmlzdWFsaXphdGlvbl9zZXR0aW5ncyI6e319) ****&#x20;

To check when the last time a hotspot was reactivated by a validator using the Helium ETL, select “Native Query” and then paste this, replacing "HOTSPOTADDRESSHERE" with the hotpot’s address.

_ie- “1135bXFixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxEctv8DwNZ56Efy”_

```
SELECT a.block, a.hash, a.validator
FROM
(
SELECT a.time, a.hash, a.block, json_array_elements_text(a.fields::json->'reactivated_gws') AS gateway, a.fields->>'address' AS validator
FROM public.transactions a
WHERE a."type" = 'validator_heartbeat_v1' AND a.block > 1350665
) as a
WHERE a.gateway='HOTSPOTADDRESSHERE'
ORDER BY a.time DESC

```

_This information helps determine your hotspot's activity relative to a validator and offers the peace of mind of confirming things are going smoothly behind the scenes._
