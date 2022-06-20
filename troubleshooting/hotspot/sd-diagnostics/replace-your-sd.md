# Replace Your SD

This process is for MNTD. Blackspots/Goldspots. **DO NOT ERASE YOUR SD IF YOU HAVE A RAKV1**. You may need to replace or rewrite the [microSD card](../../../helium-glossary.md#sd-card) that comes with your [hotspot](../../../helium-glossary.md#hotspot) if it:

* shows "Disk Error" in the [diagnostics](../../../helium-glossary.md#diagnostic)
* is not booting up (cannot connect over [Bluetooth](../../../helium-glossary.md#bluetooth) anymore after pressing the [pairing](../../../helium-glossary.md#pair) button)
* shows a solid or flashing **green** [status LED](https://docs.rakwireless.com/Product-Categories/WisGate/RAK-Hotspot-Miner-v2/Troubleshooting/)
* shows a very old [block height](../../../helium-glossary.md#block-height) and/or [firmware](../../../helium-glossary.md#firmware) version in [diagnostics](../../../helium-glossary.md#diagnostic)&#x20;
* [power cycling](../../../helium-glossary.md#power-cycle-reboot) has resulted in unknown microSD card errors, such as corrupted files.&#x20;
* If it shows the same [block](../../../helium-glossary.md#block) height in 2 [diagnostics](../../../helium-glossary.md#diagnostic) that were done 24 hours apart&#x20;

\
Steps to take:

\
**1. Download the Firmware file (works best if kept as a ZIP). Current version is 2022.04.19.0:**\
[https://wishm-nextgate.s3.us-west-2.amazonaws.com/images/MNTD\_2022\_04\_19\_0.img.zip](https://wishm-nextgate.s3.us-west-2.amazonaws.com/images/MNTD\_2022\_04\_19\_0.img.zip)&#x20;

**2. Install the** [**Balena Etcher**](https://www.balena.io/etcher/) **** [**flashing** ](../../../helium-glossary.md#flash)**tool you can find Windows, Mac and Linux versions**: (optional) a new replacement [microSD card](../../../helium-glossary.md#sd-card). MNTD. now recommends a SanDisk or Samsung 64[GB](../../../helium-glossary.md#gb) **High Endurance card**.&#x20;

**3. Follow the card replacement procedure:**

1. Power off the [hotspot](../../../helium-glossary.md#hotspot) (unplug from power)
2. Carefully peel off the tape protecting the [microSD card](../../../helium-glossary.md#sd-card) slot, it is below the gold/black sticker on the side of the hotspot where the antenna is, next to the status LEDs.
3. Remove the microSD card inside, there is a small lip on the bottom part which you can use to pull it out, some people prefer to use tweezers.
4. [Flash](../../../helium-glossary.md#flash) [card](../../../helium-glossary.md#sd-card) using balenaEtcher app downloaded above directly with the zipped (compressed) file, this is intuitive:
5.
   * Select the archive
   * Select the [SD card](../../../helium-glossary.md#sd-card)
   * [Flash](../../../helium-glossary.md#flash) and wait for verification
6. Replace card making sure it's correctly inserted all the way **with the brand side down**
7. Connect the [hotspot](../../../helium-glossary.md#hotspot) to your internet router via an [ethernet](../../../helium-glossary.md#ethernet) cable.
8. Power on the hotspot again.

\
**IMPORTANT**: The [Hotspot](../../../helium-glossary.md#hotspot) needs a minimum of **30 minutes** to initialize correctly after an [SD card](../../../helium-glossary.md#sd-card) [flash](../../../helium-glossary.md#flash). During this time please do not [reboot](../../../helium-glossary.md#reboot), or disconnect the power or [internet](../../../helium-glossary.md#internet) connections.  [Bluetooth](../../../helium-glossary.md#bluetooth) will also not show correct data during this time.
