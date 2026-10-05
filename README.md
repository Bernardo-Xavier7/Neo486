# Neo486
Modern open-source recreation of a mid 90s top tier 486 motherboard.

# Features
- 6x 16-Bit ISA Slots
- 2x 8-Bit ISA Slots
- 2x VLB Slots
- 4x 72-Pin SIMM RAM Slots (up to 128MB, 4x 32MB Sticks)
- Up to 512KB Cache (8x 64KB + 64KB TAG)
- ZIF Socket
- Variable Clock Generator
- CPU Voltage Selection Jumpers (+5V or +3.3V)
- CR2032 CMOS battery
- Custom BIOS

# Chip List
| Role | Preferred Specific IC Model | Package Type | Sourcing Availability |
| --- | --- | --- | --- |
| CPU | Intel 486 | PGA-168 / PGA-237 | NOS / Tested Vintage|
| Core Chipset | SiS 85C471/407 | QFP / PQFP | NOS surplus |
| L2 Cache |  IS61C512 (8x Cache + 1x TAG) | DIP-28 or SOJ-28 | Active stock / NOS |
| KBC Controller | VT82C42 | DIP-40 or PLCC-44 | Active stock / NOS |
| System BIOS | SST39SF010A-70-4C-PHE | DIP-32 or PLCC-32 | Active stock / NOS |
| Clock Generator | AV9107 | DIP-16 | NOS surplus |
| RTC / CMOS | Dallas DS12885 | DIP-24 | Active stock |
| Bus Drivers | 74ACT245, 74ACT573, 74F245 | DIP / SOIC | Active stock |

# Useful Links
- Socket 3 Kicad: https://github.com/ciprian-stingu/Kicad-486-CPU-socket.git  
- 72-Pin RAM Template Kicad: https://github.com/wiretap-retro/72-pin-SIMM-KiCAD-Template.git  
- RetroWeb SiS 85C471/407 Chipset Page: https://theretroweb.com/chipsets/416

## Licensing

The **neo486** project is an open-source hardware recreation. Because different components of the repository fall under different legal frameworks, it is licensed as follows:

* **Hardware & PCB Designs:** Licensed under the **CERN Open Hardware Licence Version 2 - Strong Reciprocal (CERN-OHL-S-2.0)**. Anyone modifying the neo486 motherboard design must share their changes, ensuring the core hardware improvements remain open to the community.
* **Firmware** Licensed under the **GNU General Public License v3.0 (GPL-3.0)**. 
* **Documentation & Wiki:** Licensed under **Creative Commons Attribution 4.0 International (CC BY-SA 4.0)**.

