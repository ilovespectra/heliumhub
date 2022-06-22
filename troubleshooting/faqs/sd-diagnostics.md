# SD / Diagnostics

### **I’m unable to run a** [**diagnostic**](../../helium-glossary.md#diagnostic)**.**

_See_ [_Bluetooth Pairing_](../hotspot/sd-diagnostics/bluetooth-pairing.md)__

### **I'm unable to** [**pair**](../../helium-glossary.md#pair) **via** [**Bluetooth**](../../helium-glossary.md#bluetooth)**.**

_See_ [_Bluetooth Pairing_](../hotspot/sd-diagnostics/bluetooth-pairing.md)__

### **I** [**reflashed**](../../helium-glossary.md#reflash) **the** [**card**](../../helium-glossary.md#sd-card)**, but I'm still not** [**mining**](../../helium-glossary.md#mining)**!**

_See_ [_SD / Diagnostics_ ](../hotspot/sd-diagnostics/)__

It may take a few hours or even a couple of days to connect to a [validator](../../helium-glossary.md#validator) and begin [mining](../../helium-glossary.md#mining). Before waiting it out, retrace your steps carefully and make sure you covered these key bases:

* If you used your computer's onboard [SD card](../../helium-glossary.md#sd-card) reader on your computer for the [reformat](../../helium-glossary.md#reformat) or [flash](../../helium-glossary.md#flash) process, try again using a high-speed Plug-in [USB SD card reader](../../helium-glossary.md#usb-sd-card-reader). _See_[ _SD / Diagnostics_](../hotspot/sd-diagnostics/)__
* If you ordered a pre-flashed [SD card](../../helium-glossary.md#sd-card), it was ready to go. So if you [flashed](../../helium-glossary.md#flash) the SD upon receiving it, you will need to perform an [overwrite format ](../../helium-glossary.md#overwrite-format)and flash the card again. _See_ [_SD / Diagnostics_](../hotspot/sd-diagnostics/)__
* If you are not connected to [ethernet](../../helium-glossary.md#ethernet), reconfigure your[ Wi-Fi](../../helium-glossary.md#wi-fi). _See_ [_SD / Diagnostics_](../hotspot/sd-diagnostics/)

### **I’m receiving an SD card error (MNTD.)**

If you diagnose your hotspot and the "Disk" field in the report has a "Read-Only" status, your SD card needs replacement. It has run through its lifecycle (SD cards have a limited number of write cycles by design). You have two options for the new card:

1. Buy one pre-flashed with the firmware written on it already from the RAK store&#x20;
2. Provision one yourself (SanDisk High Endurance 64GB recommended) and flash using [this guide.](../hotspot/sd-diagnostics/replace-your-sd.md)

### **Why am I going inactive/offline?**

There could be many causes. Typically it is regarding your connection to your validator. If you're on [Wi-Fi](../../helium-glossary.md#wi-fi), the issue is likely due to an unstable connection. We strongly recommend connecting your hotspot via ethernet. You can run a speed test to determine internet speeds. _See_ [_Internet_](broken-reference)__
