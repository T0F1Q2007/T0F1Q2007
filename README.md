<div align="center">

# Tofiq Valizada

**Systems Software Engineer & Linux Desktop Subsystems Specialist**

```
   ==============================================================================
   *  LINUX KERNEL TELEMETRY  *  PROTOCOL REVERSE ENGINEERING  *  GNOME SHELL  *
   ==============================================================================
```

[![GitHub](https://img.shields.io/badge/GitHub-T0F1Q2007-181717?style=flat-square&logo=github)](https://github.com/T0F1Q2007)
[![Linux](https://img.shields.io/badge/Platform-Linux%20%2F%20x86__64-FCC624?style=flat-square&logo=linux&logoColor=black)](#)
[![GNOME](https://img.shields.io/badge/Environment-GNOME%20Shell%2045%20--%2050-4a86cf?style=flat-square&logo=gnome&logoColor=white)](#)
[![Academic](https://img.shields.io/badge/Institution-ASOIU%20Computer%20Engineering-red?style=flat-square)](#)

</div>

---

## Executive Profile

Systems-focused software engineer specializing in low-level Linux subsystem integration, hardware telemetry extraction, proprietary peripheral protocol reverse engineering, and asynchronous desktop user interface engineering for GNOME Shell.

Primary engineering efforts emphasize non-invasive kernel sampling (e.g., Intel RAPL energy accumulation interfaces), event-driven D-Bus inter-process communication, and hardware-accelerated 2D procedural rendering engines.

---

## Technical Competencies and Tooling

### Core Systems and Programming Languages

```
+-------------------+---------------------------------------------------------+
| DOMAIN            | TECHNOLOGIES & TOOLS                                    |
+-------------------+---------------------------------------------------------+
| Systems & Core    | C, C++20, Python 3 (asyncio / Bleak / dasbus), Shell    |
| Desktop Runtime   | JavaScript (SpiderMonkey ESM / GJS), GObject, Clutter   |
| Graphics & Vector | Cairo 2D Vector Rendering, Procedural Canvas Shaders   |
| Mobile & Security | Kotlin (Android / Jetpack Compose), PAM, Linux Security |
| Audio & Subsystem | BlueZ, PipeWire, WirePlumber, systemd, udev, sysfs      |
+-------------------+---------------------------------------------------------+
```

### Engineering Skillset

<div align="center">

[![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)](#)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](#)
[![Linux](https://img.shields.io/badge/Linux_Kernel-FCC624?style=flat-square&logo=linux&logoColor=black)](#)
[![GNOME](https://img.shields.io/badge/GNOME_Shell-4A86CF?style=flat-square&logo=gnome&logoColor=white)](#)
[![D-Bus](https://img.shields.io/badge/D--Bus_IPC-orange?style=flat-square)](#)
[![Bluetooth](https://img.shields.io/badge/Bluetooth_Classic_%2F_BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)](#)
[![Systemd](https://img.shields.io/badge/systemd-black?style=flat-square)](#)
[![Cairo](https://img.shields.io/badge/Cairo_Graphics-red?style=flat-square)](#)

</div>

---

## Featured Systems Engineering Projects

```
+-----------------------------------------------------------------------------+
|                                                                             |
|  [1] Xiaomi Redmi Buds 8 Pro Linux Control Stack                            |
|      Repository: T0F1Q2007/Redmi-buds-8-pro-linux-software                  |
|      - Reverse-engineered Xiaomi Vela OS M-BAP protocol over RFCOMM SPP     |
|      - Multi-mode Active Noise Cancellation (ANC) & Spatial Audio IPC       |
|      - WirePlumber LHDC v5 jitter buffer stabilization configuration       |
|                                                                             |
|  [2] Intel RAPL Differential Energy Telemetry                               |
|      Repository: T0F1Q2007/cpu-watt-monitor                                 |
|      - Direct sysfs powercap package and SoC energy sampling (dE / dt)      |
|      - Zero-allocation TextDecoder singleton architecture                   |
|      - sub-0.12ms in-process evaluation with systemd DAC hardening         |
|                                                                             |
|  [3] Biometric Visual Interface for Howdy PAM                               |
|      Repository: T0F1Q2007/howdy-face-id-animation                          |
|      - Asynchronous facial recognition visual indicator for Linux PAM       |
|      - 60 FPS procedural Cairo vector rendering canvas with harmonic math   |
|      - $XDG_RUNTIME_DIR tmpfs IPC with debounced inotify state filtering    |
|                                                                             |
|  [4] Xiaomi Redmi Buds 6 Active Telemetry Daemon                            |
|      Repository: T0F1Q2007/redmi-buds-6-active-linux-software               |
|      - Intercepts and parses Google Fast Pair (0xFE2C) BLE GAP advertisements|
|      - Single-task cancellable silence watchdog preventing coroutine churn  |
|      - Asynchronous D-Bus session bus publisher (org.redmibuds.Battery)     |
|                                                                             |
+-----------------------------------------------------------------------------+
```

---

## System Architecture Paradigms

```
+-------------------------------------------------------------------------+
|                        GNOME Shell Desktop Canvas                       |
|           (St.Widget / PanelMenu.Button / QuickSettings.QuickToggle)    |
+------------------------------------^------------------------------------+
                                     |
                    D-Bus Session Bus / tmpfs File Monitor
                                     |
+------------------------------------v------------------------------------+
|                   Asynchronous Background Services                      |
|           (Python asyncio / Bleak / dasbus / C++ Daemons)               |
+------------------------------------^------------------------------------+
                                     |
                Kernel Interfaces (sysfs / BlueZ HCI / PAM)
                                     |
+------------------------------------v------------------------------------+
|                  Underlying Hardware & Peripheral Buses                 |
|       - Intel RAPL Energy Registers (MSRs / powercap)                   |
|       - Bluetooth Classic RFCOMM (SPP Channel 28)                       |
|       - Bluetooth Low Energy GAP / Google Fast Pair (UUID 0xFE2C)       |
|       - Infrared Biometric Sensor Arrays (V4L2 / OpenCV / dlib)         |
+-------------------------------------------------------------------------+
```

---

## GitHub Metrics and Repository Statistics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=T0F1Q2007&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=T0F1Q2007&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" width="48%" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=T0F1Q2007&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="97%" />

</div>

---

## Academic & Professional Contact

* **Academic Affiliation**: Azerbaijan State Oil and Industry University (ASOIU)
* **Primary Focus**: Computer Engineering, Low-Level Systems, Linux Kernel Drivers & Telemetry
* **Email**: [velizadetofiq1@gmail.com](mailto:velizadetofiq1@gmail.com) / [tofiq.valizada@asoiu.edu.az](mailto:tofiq.valizada@asoiu.edu.az)
* **GitHub**: [github.com/T0F1Q2007](https://github.com/T0F1Q2007)

---

<div align="center">
  <sub>Document generated for GitHub Profile presentation. Formatted in academic technical English.</sub>
</div>
