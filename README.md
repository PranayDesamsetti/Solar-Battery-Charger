# Solar-Battery-Charger

![Screenshot 2023-09-09 200152](https://github.com/PranayDesamsetti/Solar-Battery-Charger/assets/126604281/3e01a2cb-e83b-4b3f-9b05-e04859f19e12)
![Solar Battery Charger](![Screenshot 2023-09-09 200152](https://github.com/PranayDesamsetti/Solar-Battery-Charger/assets/126604281/3e01a2cb-e83b-4b3f-9b05-e04859f19e12))

## Overview

Welcome to the Solar Battery Charger project! This project focuses on harnessing the power of the sun to efficiently charge Li-ion cell batteries. It employs cutting-edge technology, including Maximum Power Point Tracking (MPPT), and offers overcurrent and overvoltage protection. The hardware design utilizes reliable Texas Instruments ICs, and the PCB is a meticulously designed 4-layer board. Read on to learn more about the project and how to make the most of it.

## Table of Contents

- [Why Solar Cells?](#why-solar-cells)
- [What is MPPT?](#what-is-mppt)
- [Overcurrent and Overvoltage Protection](#overcurrent-and-overvoltage-protection)
- [Hardware](#hardware)
- [PCB Design](#pcb-design)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Why Solar Cells?

Solar cells, also known as photovoltaic cells, play a pivotal role in the pursuit of renewable energy. They convert sunlight into electrical energy, making them an ideal solution for sustainable power generation. This project optimizes the charging process, ensuring efficient use of solar energy.

## What is MPPT?

MPPT, or Maximum Power Point Tracking, is a sophisticated technique employed in solar charge controllers and power inverters. Its primary purpose is to maximize the power output of solar panels by continuously adjusting the load to match the impedance of the solar cells. This ensures you get the most energy out of your solar panels, even when environmental conditions vary.

## Overcurrent and Overvoltage Protection

Safety is paramount when dealing with electrical circuits and devices. Overcurrent and overvoltage protection mechanisms are integrated into this charger to prevent damage to both the battery and connected devices. These safeguards ensure safe and reliable operation.

## Hardware

The heart of this project comprises various components, including solar panels, an MPPT controller, a Li-ion battery, a boost converter, and a protection circuit. Texas Instruments ICs, known for their reliability and performance, are used to build a robust and efficient charging system. In this project BQ24650, BQ77915 and TPS61040 are used for MPPT charging, battery protection and DC-DC Boost conversion respectively.

## PCB Design

The PCB (Printed Circuit Board) design plays a crucial role in ensuring smooth operation. It's meticulously crafted using Altium Designer and comprises four layers: signal, ground, power, and signal configuration. This design not only optimizes routing but also minimizes interference.

## Usage

Getting started with the Solar Battery Charger is straightforward:

1. Connect your solar panels to the input.
2. Place the solar panels in direct sunlight.
3. The MPPT controller will work its magic, optimizing power output and charging the Li-ion battery.
4. Connect your devices to the 12V output, which benefits from overcurrent and overvoltage protection.

## Contributing

We welcome contributions to this project! Whether you want to improve the code, enhance the documentation, or suggest new features, your input is valued. To contribute, follow these steps:

1. Fork this repository.
2. Create a new branch for your changes.
3. Make your improvements.
4. Submit a pull request with a detailed description of your changes.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify it for educational purposes or practical applications.

## Author
Pranay Desamsetti

## Contact
pranaydesamsetti@gmail.com 

---

*Disclaimer: Please exercise caution when working with electrical circuits and batteries. Safety should always be a top priority. If you're unsure or inexperienced with such projects, seek guidance from experts and follow safety guidelines.*
