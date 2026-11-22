# Kits 4 Hams Documentation

Construction manuals, setup outlines, data sheets and operating guides for **Kits 4 Hams** products:

- **SHARI and BRIAN**: complete AllStarLink nodes
- **DINAH and PAUL**: AllStarLink interfaces
- **K4H818**: the radio module used in SHARI RevK products

All Kits 4 Hams kits are designed and assembled in Michigan, USA. Visit **[kits4hams.com](https://kits4hams.com)** to see the full product line.

Click any document name below to open it.

---

## Which SHARI do I have?

There are two generations of SHARI. They use different radio modules, so make sure you use the documents for your generation.

| | **SHARI RevK** (current) | **Original SHARI** |
|---|---|---|
| Radio module | K4H818 | SA818 |
| Bands | One module covers 2 m, 1.25 m and 70 cm. The band is set in software, but each band needs a matching low-pass filter and antenna. | Separate UHF and VHF modules |
| Label | Says **SHARI RevK** | Does not say RevK |

**Check the label on your SHARI.** If it says "RevK", it's a SHARI RevK. If it doesn't say "RevK", it's an original SHARI.

---

## SHARI RevK (uses the K4H818 radio module)

The K4H818 radio module covers the 2 m, 1.25 m and 70 cm bands. You set the frequency, CTCSS, squelch and filters from the Raspberry Pi with the K4H818 utilities, and the same tools update the module's firmware. Every K4H818 ships set to 446.100 MHz with a 100 Hz CTCSS tone.

**Changing bands:** the K4H818 covers all three bands, but the low-pass filter and the antenna must match the band you use. On most SHARI RevK models, changing bands means installing the low-pass filter assembly and the antenna for the new band. On the PiHat NeoPi4 and NeoPi5, all three filters are on the board and you pick one with a solder bridge, so only the antenna changes. Low-pass filter assemblies and antennas for each band are sold separately.

Because one module covers all three bands, the SHARI RevK PiX only needs to know which Raspberry Pi you have (Pi 3, Pi 4 or Pi 5). The Pi 4 has its USB connectors on the opposite side from the Pi 3 and Pi 5, so the kit is built differently for each.

### Hardware: kit construction manuals

| Product | Manual |
|---|---|
| SHARI RevK PiX | [SHARI RevK PiX Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiX_Construction_Manual.pdf) |
| SHARI RevK PiZero | [SHARI RevK PiZero Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiZero_Construction_Manual.pdf) |
| SHARI RevK PiHat NeoPi4 | [SHARI RevK PiHat NeoPi4 Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_NeoPi4_Construction_Manual.pdf) |
| SHARI RevK PiHat NeoPi5 | [SHARI RevK PiHat NeoPi5 Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_NeoPi5_Construction_Manual.pdf) |
| SHARI RevK PiHat 52Pi4 | [SHARI RevK PiHat 52Pi4 Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_52Pi4_Construction_Manual.pdf) |
| SHARI RevK PiHat 52Pi5 | [SHARI RevK PiHat 52Pi5 Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_52Pi5_Construction_Manual.pdf) |
| SHARI RevK PiHat Unistorm | [SHARI RevK PiHat Unistorm Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_Unistorm_Construction_Manual.pdf) |
| SHARI RevK PiHat Mod2 Board | [SHARI RevK PiHat Mod2 Board Construction Manual](SHARI-RevK/Hardware/Construction-Manuals/SHARI_RevK_PiHat_Mod2_Board_Construction_Manual.pdf) |

### Hardware: other

- [Installing the Ferrite Filter](SHARI-RevK/Hardware/Other/Installing_the_Ferrite_Filter.pdf)

### Software

| Image | Document |
|---|---|
| ASL3 | [ASL3 Setup Procedure Outline Using the K4H818](SHARI-RevK/Software/ASL3/ASL3_Setup_Outline_SHARI_RevK.pdf) |
| HamVOIP | [HamVOIP Setup Procedure Outline Using the K4H818](SHARI-RevK/Software/HamVOIP/HamVOIP_Setup_Outline_SHARI_RevK.pdf) |

### Operation

- [How to Operate SHARI RevK](SHARI-RevK/Operation/Operating_SHARI_RevK.pdf) *(coming soon)*
- [Updating Your SHARI RevK](SHARI-RevK/Operation/Updating_SHARI_RevK.pdf) *(coming soon)*: how to update the K4H818 firmware and utilities. Written for customers who bought a node already set up by Kits 4 Hams.

---

## Original SHARI (uses the SA818 radio module)

The original SHARI uses separate SA818 modules for UHF and VHF. The model name shows the Pi and the band, e.g. Pi4U = Raspberry Pi 4, UHF.

### Hardware: kit construction manuals

| Product | Manual |
|---|---|
| SHARI PiXX (Pi3U, Pi4U, Pi3V, Pi4V) | [SHARI PiXX Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiXX_Construction_Manual.pdf) |
| SHARI PiZero | [SHARI PiZero Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiZero_Construction_Manual.pdf) |
| SHARI PiHat NeoPi4 | [SHARI PiHat NeoPi4 Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_NeoPi4_Construction_Manual.pdf) |
| SHARI PiHat NeoPi5 | [SHARI PiHat NeoPi5 Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_NeoPi5_Construction_Manual.pdf) |
| SHARI PiHat 52Pi4 | [SHARI PiHat 52Pi4 Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_52Pi4_Construction_Manual.pdf) |
| SHARI PiHat 52Pi5 | [SHARI PiHat 52Pi5 Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_52Pi5_Construction_Manual.pdf) |
| SHARI PiHat Unistorm, straight antenna | [SHARI PiHat Unistorm Straight Antenna Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_Unistorm_Straight_Antenna_Construction_Manual.pdf) |
| SHARI PiHat Unistorm, right-angle antenna | [SHARI PiHat Unistorm Right Angle Antenna Construction Manual](SHARI-SA818/Hardware/Construction-Manuals/SHARI_PiHat_Unistorm_Right_Angle_Antenna_Construction_Manual.pdf) |

### Hardware: other

- [Installing the Ferrite Filter](SHARI-SA818/Hardware/Other/Installing_the_Ferrite_Filter.pdf)

### Software

| Image | Documents |
|---|---|
| ASL3 | [ASL3 Setup Procedure Outline Using the SA818](SHARI-SA818/Software/ASL3/ASL3_Setup_Outline_SHARI_SA818.pdf)<br>[Suggested Settings for SHARI Using the ASL3 Image](SHARI-SA818/Software/ASL3/ASL3_Suggested_Settings_SHARI_SA818.pdf) |
| HamVOIP | [HamVOIP Setup Procedure for SHARI PiHat Using the SA818](SHARI-SA818/Software/HamVOIP/HamVOIP_Setup_Outline_SHARI_SA818.pdf)<br>[HamVOIP Setup Procedure for SHARI PiZero Using the SA818](SHARI-SA818/Software/HamVOIP/HamVOIP_Setup_Outline_SHARI_PiZero_SA818.pdf)<br>[Suggested Settings for SHARI Using the HamVOIP Image](SHARI-SA818/Software/HamVOIP/HamVOIP_Suggested_Settings_SHARI_SA818.pdf) |

### Operation

- [How to Operate SHARI with the ASL3 Image](SHARI-SA818/Operation/Operating_SHARI_with_ASL3.pdf)
- [How to Operate SHARI with the HamVOIP Image](SHARI-SA818/Operation/Operating_SHARI_with_HamVOIP.pdf)

---

## K4H818 Radio Module

An improved replacement for the SA818, designed in the USA by Kits 4 Hams. One module covers 2 m, 1.25 m and 70 cm, and its firmware is field-upgradable from the Raspberry Pi. Used in all SHARI RevK products.

### Hardware

- [K4H818 Features Summary](K4H818/Hardware/K4H818_Features_Summary.pdf)

### Software

The programs that set up and update the K4H818 are in their own repositories:

- **[K4H818_utilities](https://github.com/Kits4Hams/K4H818_utilities)**: programs for setting up the K4H818 and updating its firmware from the Raspberry Pi
- **[K4H818_firmware](https://github.com/Kits4Hams/K4H818_firmware)**: the latest K4H818 firmware, which `K4H818-update` downloads automatically

- [K4H818 User Guide](K4H818/Software/K4H818_User_Guide.pdf) *(coming soon)*: how to install the utilities, read and change the module's settings, update the firmware, and change bands

---

## DINAH

DINAH is an AllStarLink radio interface. It plugs into a USB port on the Raspberry Pi and connects to your radio with a 6-pin mini-DIN cable, which plugs straight into the 6-pin mini-DIN data jack found on many VHF and UHF ham radios. No wiring is needed: connect the cable to the radio and to DINAH, then do your setup. See *DINAH Compatible Radios* below for radios known to work.

### Hardware

- [DINAH USB-A Construction Manual](DINAH/Hardware/DINAH_USB-A_Construction_Manual.pdf)
- [DINAH USB-C Construction Manual](DINAH/Hardware/DINAH_USB-C_Construction_Manual.pdf)

### Other

- [DINAH Compatible Radios](DINAH/Other/DINAH_Compatible_Radios.pdf)

---

## PAUL

PAUL is an AllStarLink radio interface that plugs into a USB port on the Raspberry Pi. It connects to your radio through a DB9 (9-pin D) connector, using a cable you make for your particular radio. On-board potentiometers set the transmit and receive audio levels. See *PAUL Jumper Settings* below for configuring it.

### Hardware

- [PAUL Construction Manual](PAUL/Hardware/PAUL_Construction_Manual.pdf)
- [PAUL Jumper Settings](PAUL/Hardware/PAUL_Jumper_Settings.pdf)

---

## BRIAN

BRIAN is a complete AllStarLink node. Its radio is a Baofeng BF555S circuit board.

### Hardware

- [BRIAN-SM Construction Manual](BRIAN/Hardware/BRIAN-SM_Construction_Manual.pdf)
- [BRIAN-SM Construction Manual Addendum](BRIAN/Hardware/BRIAN-SM_Construction_Manual_Addendum.pdf)

---

## Getting help

1. **[SHARI group on groups.io](https://groups.io/g/shari)**: the best place to start. Kits 4 Hams and the SHARI community both answer questions there, and your question and its answer may help someone else.
2. **Email [kits4hams@gmail.com](mailto:kits4hams@gmail.com)**: for problems specific to your order or your unit.
3. **Help with the node software:**
   - ASL3: the [AllStarLink Community forum](https://community.allstarlink.org)
   - HamVOIP: the [allstar-discussion group on groups.io](https://groups.io/g/allstar-discussion/topics)

---

*Kits 4 Hams, Michigan, USA. [kits4hams.com](https://kits4hams.com)*
