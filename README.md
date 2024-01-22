# PCB Car Lights

## Overview

PCB Car Lights is a project focused on the design and implementation of a printed circuit board (PCB) for controlling the lights of a car. This project provides the schematic and layout for the electronic components needed to efficiently manage car lighting systems.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [Schematic](#schematic)
5. [Layout](#layout)
6. [Components](#components)
7. [Presentation](#presentation)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction

Modern cars rely on sophisticated lighting systems for safety and aesthetics. The PCB Car Lights project aims to streamline the control of car lights, providing a compact and efficient solution through a custom-designed PCB.

## Features

- **Efficient Control:** Optimal management of car lights for improved energy efficiency.

## Getting Started

To get started with the PCB Car Lights project, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/PCBcarlights.git
   ```

2. **Explore the Documentation:**
   Review the documentation files, including the README, to understand the project structure and requirements.

3. **Set Up Development Environment:**
   Ensure you have the necessary tools and software installed for PCB design. Refer to the documentation for specific requirements.

4. **Modify Design:**
   Customize the PCB design according to your car's lighting specifications, making any necessary adjustments to the schematic and layout.

5. **Testing:**
   Before manufacturing the PCB, simulate and test the design using appropriate tools to ensure functionality.

## Schematic

The schematic diagram provides an overview of the electronic components and their connections. Open the schematic file (located in the `schematic` directory) using [design software] to visualize and understand the circuit.

![Schematic Diagram](schematic/pcb_car_lights_schematic.png)

## Layout

The PCB layout file  defines the physical arrangement of components on the board and can be found in the. Open the layout file using [layout software] to review and optimize the placement for manufacturing.

## Components

Some components used in the PCB are shown below. Note that these are not all the components but just provide an example.

| Ref. | Description | Datasheet |
| ------ | ----------------- | ------------------ |
| PIC18F258| Microcontroller.... | [datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/MCHP/MCHPS03028/MCHPS03028-1.pdf?hkey=6D3A4C79FDBF58556ACFDE234799DDF0)|
| LM1117| Regulator.... | [datasheet](https://www.ti.com/general/docs/suppproductinfo.tsp?distId=26&gotoUrl=https://www.ti.com/lit/gpn/lm1117)|
| MCP2551| CAN Transceiver.... | [datasheet](https://www.farnell.com/datasheets/2299423.pdf)|
| PIC18F258| DB9 Connector.... | [datasheet](https://....)|
| G5LE-14-CF| High Power Relay.... | [datasheet](https://omronfs.omron.com/en_US/ecb/products/pdf/en-g5le.pdf)|
| G5NB1A| Low Power Relay.... | [datasheet](https://www.farnell.com/datasheets/2340807.pdf)|
| HC49US| Clock.... | [datasheet](https://www.farnell.com/datasheets/1359171.pdf)|
| L298N| Motor Driver.... | [datasheet](https://www.farnell.com/datasheets/1693054.pdf)|
| ULN2003| Relay Driver.... | [datasheet](https://www.ti.com/lit/ds/symlink/uln2003a.pdf?ts=1679884652584&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FULN2003A%253Futm_source%253Dgoogle%2526utm_medium%253Dcpc%2526utm_campaign%253Dapp-psil-null-prodfolderdynamic-cpc-pf-google-wwe_int%2526utm_content%253Dprodfolddynamic%2526ds_k%253DDYNAMIC%2BSEARCH%2BADS%2526DCM%253Dyes%2526gclid%253DCj0KCQjw2v-gBhC1ARIsAOQdKY2V8NQj1MDO03wHvxCNCnLLP3BTjBXfBt316i6NoYeyX4ZuCcTenmoaAiblEALw_wcB%2526gclsrc%253Daw.ds)|
| VEMD6060X01| Light Sensor.... | [datasheet](https://4donline.ihs.com/images/VipMasterIC/IC/VISH/VISH-S-A0001545403/VISH-S-A0001545403-1.pdf?hkey=6D3A4C79FDBF58556ACFDE234799DDF0)|

## Presentation

Included in this repository is a PDF presentation (`PCB_Car_Lights_Presentation.pdf`) that provides a comprehensive overview of the project. The presentation covers background, design methodology, key features, and potential applications of the PCB Car Lights project.

## Contributing

Contributions to the PCB Car Lights project are welcome! Whether you want to report issues, propose enhancements, or submit pull requests, please review our [contribution guidelines](CONTRIBUTING.md).

## License
This project is licensed under the [MIT License](LICENSE), which means you are free to use, modify, and distribute the project for personal or commercial purposes.

---

Feel free to customize this README to better fit the specifics of your project. Update the placeholders like `[design software]` with the actual software names and provide more detailed information about the components if necessary.
