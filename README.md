<div align="center">

# Siratul Islam
**Embedded Systems Engineer • Physics Researcher**

Zephyr RTOS Subsystem Maintainer (Biometrics) | Research Assistant @ SUST

[![Portfolio](https://img.shields.io/badge/🌐_sirat.me-000000?style=flat&logoColor=white)](https://www.sirat.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/siratul-islam)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:email@sirat.me)

</div>

---

### About Me
I am a **Physics undergraduate** and **Embedded Systems Engineer** working at the intersection of **RTOS kernel development**, **Industrial IoT**, and **Robotics**.

Currently, I serve as a **Research Assistant** at the SUST EEE Department, designing autonomous navigation systems and energy-efficient building automation. As an open-source advocate, I am an official contributor to the **Zephyr RTOS** project, maintaining board support for ARM and RISC-V platforms.

---

## 🛠️ Open Source Architecture

### [Linux Foundation - Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr)
**Triage Member & Contributor**

**🚧 Maintainer**
* **[#100139 - Biometrics Subsystem](https://github.com/zephyrproject-rtos/zephyr/pull/100139):** Maintaining the biometrics subsystem.
  
**🔌 Device Drivers (Kernel Development)**
*Implemented low-level drivers from datasheet specifications.*
* **[#97921 - HUB12 LED Display](https://github.com/zephyrproject-rtos/zephyr/pull/97921):** Developed a display subsystem driver for high-refresh rate LED matrices.
* **[#98445 - HUB12 Chaining](https://github.com/zephyrproject-rtos/zephyr/pull/98445):** Implemented horizontal chaining support to allow scalable multi-panel displays.
* **[#96510 - TM1637 Controller](https://github.com/zephyrproject-rtos/zephyr/pull/96510):** Authored a 7-segment display driver for the `auxdisplay` subsystem.

**💻 Board Support (HAL & DeviceTree)**
*Expanded hardware support for 10+ platforms across ARM and RISC-V.*
* **STM32 (ARM):** Added support for WeAct Core [STM32F446](https://github.com/zephyrproject-rtos/zephyr/pull/91886), [STM32WB55](https://github.com/zephyrproject-rtos/zephyr/pull/97435) (BLE), and [STM32G030](https://github.com/zephyrproject-rtos/zephyr/pull/97553).
* **ESP32 (RISC-V/Xtensa):** Added support for C3-Mini, C6-Mini, and S3-Mini boards.
* **Maintainer:** Currently the active maintainer for [9 board support packages](https://docs.zephyrproject.org/).

➡️ **[View All Pull Requests](https://github.com/zephyrproject-rtos/zephyr/pulls?q=is%3Apr+author%3Aheronet)**

### [Espressif ESP-IDF Components](https://components.espressif.com/u/heronet)
* **[RD-03D Radar](https://components.espressif.com/components/heronet/esp_rd-03d):** Published mmWave radar sensor library with signal filtering algorithms.
* **[TM1637](https://components.espressif.com/components/heronet/tm1637):** Low-level bit-banging driver for 7-segment displays.

---

## 🔬 Research & Engineering

**Research Assistant** • *SUST Dept. of Electrical & Electronic Engineering*
*Jun 2025 - Present*

* **Autonomous Vehicle Navigation:** Engineered a ROS2-based navigation stack on **Jetson Orin** with LiDAR sensor fusion. Designed custom **STM32F4** firmware for real-time motor control and micro-ROS communication.
* **Govt. Energy Optimization:** Developing IoT-enabled smart relay systems for cost optimization in government buildings using ESP32 and MQTT.
* **Radar Occupancy Detection:** Implementing RD-03D radar algorithms for automated energy efficiency.

---

## 💻 Technical Arsenal

| Domain | Technologies |
| :--- | :--- |
| **Languages** | ![C](https://img.shields.io/badge/C-00599C?logo=c&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-black?logo=rust&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) |
| **Embedded** | **Zephyr RTOS**, **FreeRTOS**, **STM32 HAL**, **ESP-IDF**, **Embedded Linux** |
| **Hardware** | STM32 (H7/F4/WB), ESP32 (S3/C6/C3), Jetson Orin, RISC-V, LiDAR, Radar |
| **Protocols** | I2C, SPI, UART, MQTT, BLE, LoRa, TCP/IP, micro-ROS |
| **Tools** | CMake, DeviceTree, Kconfig, KiCAD, OpenOCD, GDB, Docker, Git |
| **Web/Cloud** | SvelteKit, Next.js, Django (for IoT Dashboards & Tooling) |

---

## 🏆 Selected Awards

* **Bronze Medal**, International University Physics Competition 2024
    * *Modeled fluid dynamics for space station air evacuation using Poiseuille's Law.*
* **Zephyr Contributors Team**, Official Member (2025)

---

<div align="center">
  <sub>Let's build reliable, real-time systems.</sub>
</div>
