# Neo486
Modern open-source recreation of a mid 90s top tier 486 motherboard.

# Chip List
| Role | Preferred Specific IC Model | Package Type | Sourcing Availability|
| --- | --- | --- | ---|
| CPU | Intel / AMD i486DX2-66 | PGA-168 | NOS / Tested Vintage|
| Core Chipset | SiS 85C471 + SiS 85C472 | QFP / PQFP | NOS surplus|
| L2 SRAM | IS61C256AH-15J (x9) | DIP-28 or SOJ-28 | Active stock / NOS|
| Super I/O | Winbond W83787F or SMC FDC37C665 | QFP-100 | NOS / Surplus|
| KBC Controller | VT82C42 / N8042AH | DIP-40 or PLCC-44 | Active stock / NOS|
| System BIOS | SST39SF010A-70-4C-PHE | DIP-32 or PLCC-32 | Active stock (DigiKey/Mouser)|
| Clock Generator | ICS9148 / AV9107 + 14.318 MHz Crystal | DIP-16 / SOIC | NOS / eBay|
| RTC / CMOS | Dallas DS12885 (with CR2032 socket) | DIP-24 | Active stock|
| Bus Drivers | 74ACT245, 74ACT573, 74F245 | DIP / SOIC | Active stock|

# Useful Links
https://github.com/ciprian-stingu/Kicad-486-CPU-socket.git
