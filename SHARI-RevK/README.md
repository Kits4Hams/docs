# SHARI RevK (uses the K4H818 radio module)

The K4H818 radio module covers the 2 m, 1.25 m and 70 cm bands. You set the frequency, CTCSS, squelch and filters from the Raspberry Pi with the K4H818 utilities, and the same tools update the module's firmware. Every K4H818 ships set to 446.100 MHz with a 100 Hz CTCSS tone.

**Changing bands:** the K4H818 covers all three bands, but the low-pass filter and the antenna must match the band you use. On most SHARI RevK models, changing bands means installing the low-pass filter assembly and the antenna for the new band. On the PiHat NeoPi4 and NeoPi5, all three filters are on the board and you pick one with a solder bridge, so only the antenna changes. Low-pass filter assemblies and antennas for each band are sold separately.

Because one module covers all three bands, the SHARI RevK PiX only needs to know which Raspberry Pi you have (Pi 3, Pi 4 or Pi 5). The Pi 4 has its USB connectors on the opposite side from the Pi 3 and Pi 5, so the kit is built differently for each.

## Hardware: kit construction manuals

| Product | Manual |
|---|---|
| SHARI RevK PiX | [SHARI RevK PiX Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiX_Construction_Manual.pdf) |
| SHARI RevK PiZero | [SHARI RevK PiZero Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiZero_Construction_Manual.pdf) |
| SHARI RevK PiHat NeoPi4 | [SHARI RevK PiHat NeoPi4 Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_NeoPi4_Construction_Manual.pdf) |
| SHARI RevK PiHat NeoPi5 | [SHARI RevK PiHat NeoPi5 Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_NeoPi5_Construction_Manual.pdf) |
| SHARI RevK PiHat 52Pi4 | [SHARI RevK PiHat 52Pi4 Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_52Pi4_Construction_Manual.pdf) |
| SHARI RevK PiHat 52Pi5 | [SHARI RevK PiHat 52Pi5 Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_52Pi5_Construction_Manual.pdf) |
| SHARI RevK PiHat Unistorm | [SHARI RevK PiHat Unistorm Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_Unistorm_Construction_Manual.pdf) |
| SHARI RevK PiHat Mod2 Board | [SHARI RevK PiHat Mod2 Board Construction Manual](Hardware/Construction-Manuals/SHARI_RevK_PiHat_Mod2_Board_Construction_Manual.pdf) |

## Hardware: other

- [Installing the Ferrite Filter](Hardware/Other/Installing_the_Ferrite_Filter.pdf)

## Software

| Image | Document |
|---|---|
| ASL3 | [ASL3 Setup Procedure Outline Using the K4H818](Software/ASL3/ASL3_Setup_Outline_SHARI_RevK.pdf) |
| HamVOIP | [HamVOIP Setup Procedure Outline Using the K4H818](Software/HamVOIP/HamVOIP_Setup_Outline_SHARI_RevK.pdf) |

## Operation

- [How to Operate SHARI RevK](Operation/Operating_SHARI_RevK.pdf) *(coming soon)*
- [Updating Your SHARI RevK](Operation/Updating_SHARI_RevK.pdf) *(coming soon)*: how to update the K4H818 firmware and utilities. Written for customers who bought a node already set up by Kits 4 Hams.

---

[Back to all Kits 4 Hams documentation](../README.md)
