# Antenna

### **How do I know what** [**antenna**](../../helium-glossary.md#antenna) **connectors I need?**

That depends on the [hotspot](../../helium-glossary.md#hotspot); the stock connection on a [MNTD](../../helium-glossary.md#mntd) hotspot, for example, is a Female [RP](../../helium-glossary.md#rp)-[SMA](../../helium-glossary.md#sma), _meaning the connection to your hotspot will be made with a Male RP-SMA._

### **Should I use a** [**filter**](../../helium-glossary.md#filter) **for my antenna?**

Most [hotspots](../../helium-glossary.md#hotspot) are equipped with a [SAW filter](../../helium-glossary.md#saw-filter) narrowly tuned to your region. Odds are, an additional filter will hinder more than help. In the unique circumstance that your hotspot is located very near a cell tower (i.e. beneath), you may benefit from a[ narrow bandwidth filter](../../helium-glossary.md#narrow-band-filter), which can help reduce the [noise](../../helium-glossary.md#noise) that may be negatively impacting your [TX/RX.](../../helium-glossary.md#tx-rx)

### **Why is my** [**hotspot**](../../helium-glossary.md#hotspot) **not sending** [**beacons**](../../helium-glossary.md#beacon)**?**

Beacons are submitted randomly over the network. [Validators](../../helium-glossary.md#validator) submit [challenges](../../helium-glossary.md#challenge) on behalf of hotspots, and the way these beacons are performed is incalculable and [immutable](../../helium-glossary.md#immutable). The best way to ensure you beacon as often as possible is by leaving your hotspot plugged in and connected to the [internet](../../helium-glossary.md#internet).

### **Why do I have 0** [**witnesses**](../../helium-glossary.md#witness)**?**

If your [beacons](../../helium-glossary.md#beacon) are typically witnessed, and you experience only an occasional 0-witness beacon, your [hotspot](../../helium-glossary.md#hotspot) is likely functioning properly. There are a handful of reasons regarding the way witness receipts are reported that can rarely but occasionally lead to a 0-witness beacon. The issue is [Helium](../../helium-glossary.md#helium) network-related and isn't technically resulting in the loss of any [reward](../../helium-glossary.md#reward) since no [proof of coverage ](../../helium-glossary.md#proof-of-coverage)was provided to the [network](../../helium-glossary.md#network).

1. Updating [Hotspot](../../helium-glossary.md#hotspot) Settings in the[ Helium app ](../../helium-glossary.md#helium-app)will reset your '7 Day Average Beacons' and the list of hotspots that witnessed your beacon, your 'Total Witnessed,' a 72-hour metric.
2. Location/Inactivity could result in [Helium Explorer ](../../helium-glossary.md#helium-explore)displaying 0 witnesses. Your 'Total Witnessed' list is a rolling 3-day window. As periods of inactivity roll through that window, it's normal to see this number fluctuate. [Antennas](../../helium-glossary.md#antenna) that are poorly placed, poorly [grounded](../../helium-glossary.md#ground), or indoors may experience long streaks of 0 witnesses. Learn how to set up your antenna properly[ here.](../antenna/)
3. Antenna Malfunction/Failure is a less common cause but could be why your beacons aren't being witnessed. Learn more about [antenna troubleshooting.](../antenna/)
