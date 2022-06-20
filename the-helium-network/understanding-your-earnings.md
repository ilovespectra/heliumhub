# Understanding Your Earnings

[HNT](../helium-glossary.md#hnt), or Helium Native Token, is the [cryptocurrency](../helium-glossary.md#cryptocurrency) [rewarded](../helium-glossary.md#reward) to [hotspots](../helium-glossary.md#hotspot) and [validators](../helium-glossary.md#validator) for performing their designated tasks on the [Helium blockchain](../helium-glossary.md#helium-blockchain). Helium Hotspots perform [Proof-of-Coverage](../helium-glossary.md#proof-of-coverage) and [Data Transfer ](../helium-glossary.md#data-credits)while validators perform [consensus mechanisms](../helium-glossary.md#consensus-mechanism), [challenge](../helium-glossary.md#challenge) hotspots to send [beacons](../helium-glossary.md#beacon), and add new [blocks](../helium-glossary.md#block) to the Helium blockchain itself.\
\
Data Transfer Rewards are issued at a 1:1 ratio to HNT expenditure, and are capped at 30% (in Year 1) of all minted HNT. The remainder is granted to the Proof of Coverage Rewards Pool as a bonus for providing early coverage. All transactions made on the Helium blockchain are paid in [DC](../helium-glossary.md#dc), or Data Credits. Data Credits are produced by burning some amount of HNT. Unlike HNT, which fluctuates with the market, DC are [pegged](../helium-glossary.md#pegged) to the $[USD](../helium-glossary.md#usd). Learn more below:

[HNT and Data Credits](https://www.helium.com/token)

[PoC](../helium-glossary.md#proof-of-coverage), or Proof of coverage, is a novel work algorithm used to determine hotspots are in fact in the location they’ve been asserted. RF has a limited distance, and a calculable strength, which allows the network to interrogate hotspots. There are three distinct roles involved in a [challenge](../helium-glossary.md#challenge):

1. Challenger - The [Validator](../helium-glossary.md#validator) that constructs and issues the PoC Challenge. See [HIP 55](https://github.com/helium/HIP/blob/main/0055-validator-challenges.md) for further information about this change.
2. Beaconer - Sometimes called "Challengee". This Hotspot is the target of the POC challenge and is responsible for [transmitting](../helium-glossary.md#transmission) (or "[beaconing](../helium-glossary.md#beacon)") challenge [packets](../helium-glossary.md#packet) to potentially be [witnessed](../helium-glossary.md#witness) by geographically proximate Hotspots.
3. Witness - Hotspots that are geographically proximate to the Transmitter and report the existence of the challenge packet after it has been transmitted.

“For every epoch, each [reward type](https://docs.helium.com/blockchain/mining) is split amongst Hotspots who had a role in that reward pool.

For example, if your Hotspot was challenged during an epoch, it will be eligible to a portion of the 5.31% of rewards that go to PoC Transmitters. A practical way of thinking about this is that a Hotspot might earn a "reward unit" for succeeding at a challenge. If five additional Hotspots succeeded at a challenge during the epoch and each of them also earned a "reward unit", then each Hotspot gets 1/6th of the 5.31% of rewards in that epoch.”

\
Learn more here: [Helium- Proof of Coverage](https://docs.helium.com/blockchain/proof-of-coverage/)
