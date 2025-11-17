# MASN: Solar Meshtastic Node DIY

![MASN featured image](./assets/masn-featured.jpg)

## Overview

MASN is a solar-powered Meshtastic node designed for anyone to build easily. This repository provides downloadable 3D model and PCB design to help you assemble your own device. The project aims to make decentralized, solar-powered communication accessible and open.

## Features

- [3D printable enclosure adaptor](3D/masn-box-adaptor.stl)
- Two PCB versions available:
  - **Core-1262 version**: [PCB files](pcb/core-1262/Gerber_masn-core-1262.zip) | [Schematic](pcb/core-1262/Schematic_masn-core-1262.pdf) (Waveshare Core-1262 module)
  - **HT-RA62 version**: [PCB files](pcb/ht-ra62/Gerber_masn-ht-ra62.zip) | [Schematic](pcb/ht-ra62/Schematic_masn-ht-ra62.pdf) (HT-RA62 module - same as RAK Faketec)
- Open hardware and open documentation
- Easy to replicate and customize

<div align="center">
  <img src="./assets/masn-pcb-core-1262.webp" alt="MASN Core-1262 Version" width="300" style="margin: 10px;">
  <img src="./assets/masn-pcb-ht-ra62.webp" alt="MASN HT-RA62 Version" width="300" style="margin: 10px;">
</div>
<p align="center">
  <em>Core-1262 version (left) and HT-RA62 version (right)</em>
</p>

## Full Documentation & Article

For detailed instructions, photos, and the full story behind the project, read the original article:

- [🇬🇧 MASN: A Simple and Open-Source Solar Node for Meshtastic](https://danielpcostas.dev/masn-a-simple-and-open-source-solar-node-for-meshtastic/)
- [🇪🇸 MASN: un nodo solar Meshtastic que cualquiera puede montar](https://danielpcostas.dev/es/masn-nodo-solar-meshtastic-que-cualquiera-puede-montar/)

## Contributing

If you want to contribute to this project, please fork the repository, create a new branch, and submit a pull request. Contributions are welcome!

## License Information

This project includes several hardware and 3D model files, each with its own license:

### Original Work (CERN License)

The `MASN PCB` designs (both Core-1262 and HT-RA62 versions) and the `masn-box-adaptor.stl` file are original creations developed and designed for this project. These files are licensed under the CERN Open Hardware Licence Version 2 - Strongly Reciprocal (CERN-OHL-S v2).

This license allows you to:

- **Use** the hardware design for any purpose
- **Study** how the hardware works
- **Modify** the design to suit your needs
- **Share** copies of the original or modified design

The "Strongly Reciprocal" condition means that if you distribute products based on this design, you must also share any modifications under the same license, ensuring the hardware remains open.

## Disclaimer

This project is shared as-is, without warranty. Each person is responsible for assembling and using their own node. If you decide to deploy it, make sure you comply with your local radio regulations.
