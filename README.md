﻿<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>
<p align="center">
    <h1 align="center">HEART BEAT SIMULATION PROTEUS</h1>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/Eemayas/Heart_Beat_Simulation_Proteus?style=flat&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/Eemayas/Heart_Beat_Simulation_Proteus?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Eemayas/Heart_Beat_Simulation_Proteus?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Eemayas/Heart_Beat_Simulation_Proteus?style=flat&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	</p>
<hr>

## Quick Links

> - [ Overview](#-overview)
> - [ Features](#-features)
> - [ Repository Structure](#-repository-structure)
> - [ Modules](#-modules)
> - [ Getting Started](#-getting-started)
>   - [ Installation](#-installation)
>   - [ Running Heart_Beat_Simulation_Proteus](#-running-Heart_Beat_Simulation_Proteus)
>   - [ Tests](#-tests)
> - [ Project Roadmap](#-project-roadmap)
> - [ Contributing](#-contributing)
> - [ License](#-license)
> - [ Acknowledgments](#-acknowledgments)

---

## Overview

This project simulates a heart rate monitor using Proteus. The simulation is designed to demonstrate the functionality of a heart rate monitoring device, complete with code and necessary libraries.

---

## Features

- **Realistic Heart Rate Simulation**: A complete simulation of a heart rate monitoring device.
- **Customizable**: Modify the provided code or circuit for experimentation.
- **Proteus Integration**: Ready-to-run simulation project for easy setup.

---

## Repository Structure

```sh
└── Heart_Beat_Simulation_Proteus/
    ├── Heart_Rate Monitor_Report.pdf
    ├── Heart_Rate Monitor.pdsprj
    ├── Heart_Rate Monitor_Demo_Video.mp4
    ├── 80C31
    │   └── main.asm
    ├── Backup Of Project.pdsbak
    ├── Code
    │   ├── HeartBeartCode
    │   │   └── HeartBeartCode.ino
    │   └── HeartBeartCode.ino.hex
    ├── Necessary library
    │   ├── Arduino Proteus Library
    │   │   ├── ARDUINO2.IDX
    │   │   └── ARDUINO2.LIB
    │   ├── Heart Beat Sensor Library for Proteus
    │   │   ├── HeartBeatSensorTEP.HEX
    │   │   ├── HeartBeatSensorTEP.IDX
    │   │   ├── HeartBeatSensorTEP.LIB
    │   │   └── HeartBeatSensorTEP2.HEX
    │   └── TimerOne-1.1.0.zip
    ├── Project.pdsprj
    ├── Project.pdsprj.EEMAYAS.Eemayas.workspace
    └── README.md
```

---

## Getting Started

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Eemayas/Heart_Beat_Simulation_Proteus.git
   ```

2. **Install Proteus**:
   Ensure that Proteus 8 or later is installed on your system.

3. **Setup Libraries**:

   - Navigate to the `Necessary library` folder.
   - Copy the contents of `Arduino Proteus Library` and `Heart Beat Sensor Library for Proteus` to your Proteus library directory.

4. **Open the Project**:
   Open the `Project.pdsprj` file in Proteus to load the simulation.

## Usage

1. **Run the Simulation**:

   - After loading the project in Proteus, press the play button to start the simulation.
   - The heart rate monitor will simulate heartbeat readings on the virtual device.

2. **Load Code**:
   - The `80C31/main.asm` and `Code/HeartBeartCode.ino` files contain the source code for the simulation.
   - If necessary, compile and upload the code to simulate different behaviors.

For detailed instructions on setting up and using the heart rate sensor in Proteus, visit [this guide](https://www.theengineeringprojects.com/2017/09/heart-beat-sensor-library-proteus.html) or you can read the report [`Heart_Rate Monitor_Report.pdf`](./Heart_Rate%20Monitor_Report.pdf).

---

## Dependencies

- **Proteus 8** or later
- **C/C++/Assembly**: Used in the simulation code

---

## Troubleshooting

- **Simulation Not Running**: Ensure that all libraries from the `Necessary library` folder are correctly installed in Proteus.
- **Library Issues**: Follow the guide on setting up the heart rate sensor in Proteus [here](https://www.theengineeringprojects.com/2017/09/heart-beat-sensor-library-proteus.html).

---

## Demo

To view the demo video directly on `Heart_Rate Monitor_Demo_Video.mp4`, click [here](https://github.com/Eemayas/Heart_Beat_Simulation_Proteus/blob/main/Heart_Rate%20Monitor_Demo_Video.mp4).

1. **Heartbeat sensor before simulation**
   ![Heartbeat sensor before simulation](./images/Heartbeat%20sensor%20before%20simulation.png)

2. **Heartbeat sensor during simulation when push button is not pressed**
   ![Heartbeat sensor during simulation when push button is not pressed](./images/Heartbeat%20sensor%20during%20simulation%20when%20push%20button%20is%20not%20pressed.png)
3. **Heartbeat sensor during simulation (Potentiometer 4%)**
   ![Heartbeat sensor during simulation (Potentiometer 4%)](<./images/Heartbeat%20sensor%20during%20simulation%20(Potentiometer%204%25)%20.png>)
4. **Heartbeat sensor during simulation (Potentiometer 25%)**
   ![Heartbeat sensor during simulation (Potentiometer 25%)](<./images/Heartbeat%20sensor%20during%20simulation%20(Potentiometer%2025%25).png>)
5. **Heartbeat sensor during simulation (Potentiometer 48%)**
   ![Heartbeat sensor during simulation (Potentiometer 48%)](<./images/Heartbeat%20sensor%20during%20simulation%20(Potentiometer%2048%25).png>)
6. **Heartbeat sensor during simulation (Potentiometer 81%)**
   ![Heartbeat sensor during simulation (Potentiometer 81%)](<./images/Heartbeat%20sensor%20during%20simulation%20(Potentiometer%2081%25).png>)

---

## Contributing

Contributions are welcome! Here are several ways you can contribute:

- **[Submit Pull Requests](https://github.com/Eemayas/Heart_Beat_Simulation_Proteus/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.
- **[Join the Discussions](https://github.com/Eemayas/Heart_Beat_Simulation_Proteus/discussions)**: Share your insights, provide feedback, or ask questions.
- **[Report Issues](https://github.com/Eemayas/Heart_Beat_Simulation_Proteus/issues)**: Submit bugs found or log feature requests for Heart_Beat_Simulation_Proteus.

### Contributing Guidelines

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**:
   - Clone the forked repository to your local machine using a Git client.
   ```sh
   git clone https://github.com/your-username/Heart_Beat_Simulation_Proteus.git
   ```
   - Replace `your-username` with your GitHub username.
4. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
5. **Make Your Changes**: Develop and test your changes locally.
6. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
7. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
8. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.

Once your PR is reviewed and approved, it will be merged into the main branch.

---

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---
