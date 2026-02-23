# Devices/Dongles Tested

> [!TIP]
>
> **Legend**
>
> <a id="legend_tbd"></a>
> `TBD` = "To be done", a dataset that still has to be added, and can be done so with little to no effort
>
> <a id="legend_qst"></a>
> `?` = "Unknown", a dataset which is unknown and requires more effort to retrieve
>
> **Legend** - datatypes
>
> ❌ = `U+274C` - false
>
> 🟢 = `U+1F7E2` - true

---

## Test devices
<a id="test_device_deck"></a>
**Steam Deck**
- Variants: LCD, OLED (unless specified otherwise)

<a id="test_device_framework"></a>
**Framework 14 AMD**
- USB: USB4
- CPU: AMD Ryzen

<a id="test_device_usb4_dock_ab"></a>
**Amazon Basics Thunderbolt 4/USB 4 Pro Docking Station**
- Uplink: 40Gb/s USB-C 4.0
- Downstream USB-C: 2x USB-C 40Gb/s
- NIC: 1x 2.5Gb/s LAN
- USB-A: 3x USB 10Gb/s
- HDMI: HDMI 2.1
- Does **not** support CEC on its own, but can be used to test and verify the functionality of external USB-C to HDMI adapters

---

## USB-C to HDMI - working

| Manufacturer | Name                                                                               | Model | IC                                             | Host Connection | Downstream Connections | Supports CEC | Picture                          | Max Res & Hz                                      |
|--------------|------------------------------------------------------------------------------------| --- |------------------------------------------------| --- |------------------------|-------------|----------------------------------|---------------------------------------------------|
| CLUB3D       | USB 3.1 Type C to HDMI 2.0 UHD 4K 60HZ Active Adapter                                                                               |  CAC-2504  | [?](#legend_qst)                               | USB-C | HDMI 2.0    | 🟢          | ![club3d_cac-2504](images/club3d_cac-2504.jpeg) | 4k120 Framework 14 AMD, 1080p120; 4k30 Steam Deck |

## USB-C to - non-working

| Manufacturer  | Name                                                                                            | Model            | IC                                             | Host Connection | Downstream Connections                                 | Supports CEC       | Picture                                                               | Max Res & Hz                       |
|---------------|-------------------------------------------------------------------------------------------------|------------------|------------------------------------------------|-----------------|--------------------------------------------------------|--------------------|-----------------------------------------------------------------------|------------------------------------|
| TUTUO         | N/A                                                                                             | N/A              | [?](#legend_qst)                               | USB-C           | USB-C PD IN, HDMI, USB-A 3.0                           | ❌                  | ![tutuo_3in1](images/tutuo_3in1.jpeg)                                 | [?](#legend_qst)                   |
| Anker         | PowerExpand 6-in-1-USB-C PD Ehternet Hub                                                        | A8365            | [?](#legend_qst)                               | USB-C           | USB-C PD IN, HDMI, USB-C 5Gb/s, 2x USB-A 5Gb/s         | ❌                  | ![A8365](images/anker_a8365.jpeg)                                     | [TBD](#legend_tbd)                 |
| Anker         | PowerExpand+ 5-in-1 USB C Ethernet Hub                                                          | [TBD](#legend_tbd)            | [?](#legend_qst)                               | USB-C           | HDMI                                                   | ❌                  | ![Not A8312](images/anker_not-a8312.jpeg)                             | [TBD](#legend_tbd)                 |
| Anker         | PowerExpand+ USB-C to HDMI Adapter                                                              | A8312            | [?](#legend_qst)                               | USB-C           | HDMI                                                   | ❌                  | ![A8312](images/anker_a8312.jpeg)                                     | [TBD](#legend_tbd)                 |
| Cable Matters | 48Gpbs USB C to HDMI 2.1 Adapter (USB C HDMI Adapter) for 4K 120Hz and 8K 60Hz HDR              | 201388           | [?](#legend_qst)                               | USB-C           | HDMI 2.1                                               | ❌                  | ![cablematters_201388](images/cablematters_201388.jpeg)               | 4k120 Steam Deck, Framework 14 AMD |
| StarTech      | USB-C to HDMI Adapter                                                                           | 112B-USBC-HDMI21 | VL103 (USB-DP_with_Aux), PS196 (CEC Tunneling) | USB-C           | HDMI 2.1                                               | [TBD](#legend_tbd) | ![startech_112B-USBC-HDMI21](images/startech_112B-USBC-HDMI21.jpeg)   | [TBD](#legend_tbd)                 |
| iVANKY        | Docking Station for Steam Deck HDMI 2.1 4k144, 1Gbps Ethernet, 3*USB-A 3.0, 100W USB-C Charging | 112B-USBC-HDMI21 | [TBD](#legend_tbd) | USB-C           | HDMI 2.1, 3x USB-A 5Gb/s, USB-C PD IN 100W, 1Gb/s RJ45 | [TBD](#legend_tbd) | ![ivanky_stem_deck_dock_8in1](images/ivanky_stem_deck_dock_8in1.jpeg) | [TBD](#legend_tbd)                 |
| Amazon Basics | Thunderbolt 4/USB 4 Pro Docking Station                                                         | B0CPT929ZH / DBD1336    | [TBD](#legend_tbd) | USB-C 40Gb/s    | HDMI 2.1, 3x USB-A 10Gb/s, 2x USB-C 40Gb/s, 1Gb/s RJ45 | ❌ | ![DBD1336](images/amazonbasics_dbd1336.jpeg)                          | 4k120 Framework 14 AMD, Steam Deck |


