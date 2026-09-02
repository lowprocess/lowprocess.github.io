Hardware and Embedded Engineer bridging domains, with a passion for delivering effective and simple products and systems. Based in Edinburgh

I have experience in Embedded Electronics going back over 10 years, with a primary focus on microcontroller / mixed signal design. I have developed interests in RF / High Speed design, as well as ASICs through TinyTapeout.

# Project Summary #

## Hardware ##
- **'Bobby' WPT** - H-Bridge wireless power transmitter using an STM32G0, utilising 128MHz timer to acheive phase and frequency control to adjust power input into resonant tank circuit. (2026)
- **RF Test Equipment Design** - Currently scoping and doing feasibility analysis for design blocks. (2026)
- **Low-cost discrete frequency synthesiser** - Pairing a YV257208 (Chinese Supplied VCO) and LMX2487E to acheive exceptionally low cost and low power for a discrete narrow-band RF frequency synthesiser. (2025)
- **Pathfinder** - Second spin of low cost cycling computer, using RP2040 and MapMini. Can read map data in MapForge binary format and render vector roads and paths, getting GPS coordinates from module, pressure sensor and IMU.(2023, Archived)
- **Atlas** - First spin of MCU based cycling computer, had a number of critical design faults identified, but ultimately the chosen platform (STM32H7) was too expensive. Also presented assembly challenges at the time. (2020, Archived)

## Firmware ##
- **MapMini** - Bare-Metal OpenStreetMap vector rendering engine with an ultra-low memory footprint. (2021-2024, Archived)
- **CPP-DEFMT** - Demonstrate implemenation of deffered logging on STM32, using headers to encode log messages and generate artifacts to allow host-side parsing, thus reducing memory, performance and security impacts of logging. (Demo exists)
- **MCU CMake Build System** - Avoiding vendor lock-in, My CMake build system for Cortex-M makes modular firmware design more accessible to configure and maintain.

## Mixed-Signal ASIC Design ##
- **TinyTapeout TT26a** - Experimental SKY130 Digital Synthesis and Tapeout - Implemented a cut-down MIPS CPU external instruction fetch. (In tapeout, expected delivery Dec. 2026)
- **8b SAR ADC** - Currently developing simulation for digital control logic for charge pump DAC. (Active)
- **Frac-N PLL** - Targeting IHP130, simulation of 5GHz CMOS VCO, N Divider Chain with dual-modulus prescaler. (Active)

## RF Experiments ##
- OpenEMS - Using OpenEMS to obtain figures for RF matching of simple structures / traces.
- Also experimenting with use in Antennae design.
- Looking now at Emerge with seems to do a similar job but with more polish.

## Other ##
- **KiCAD Database Library** - Speeding up going from finished design to production BOM with a liteweight-PLM system, tying together part information in a SQL database. Part No. can be tied to specific schematic symbol and footprint.