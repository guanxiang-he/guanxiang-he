<div align="center">

# Hi there, I'm Guanxiang He (贺冠翔) 👋

**M.Sc. Electrical Engineering & Information Technology @ Universität Stuttgart**  
*Intelligent Sensor Systems · Hardware Verification & Messtechnik · Industrial Automation (PLC/HMI)*

[![Location](https://img.shields.io/badge/Location-Stuttgart%2C%20Germany-004B93?style=flat-square&logo=googlemaps&logoColor=white)](https://www.uni-stuttgart.de/)
[![University](https://img.shields.io/badge/Uni%20Stuttgart-M.Sc.%20EI%20(Intelligente%20Sensorik)-004B93?style=flat-square)](https://www.ei.uni-stuttgart.de/)
[![Languages](https://img.shields.io/badge/Languages-Deutsch%20(C1)%20%7C%20English%20(B2)%20%7C%20中文-2ea44f?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Open%20for%20Werkstudent%20%2F%20HiWi%20%2F%20Praktikum-f59e0b?style=flat-square)](#)
[![Email](https://img.shields.io/badge/Email-st203613%40stud.uni--stuttgart.de-EA4335?style=flat-square&logo=minutemailer&logoColor=white)](mailto:st203613@stud.uni-stuttgart.de)

</div>

---

## 🧭 About Me / Kurzprofil

<table>
<tr>
<td width="50%" valign="top">

### 🇬🇧 English
- 🎓 **M.Sc. Student in Electrical Engineering and Information Technology** at the **University of Stuttgart** (Focus: *Intelligent Sensor Systems / Intelligente Sensorik*).
- 🔬 **1 Year of Industry Experience as a Baseband Hardware Engineer** at **Fibocom Wireless Inc.** — hands-on hardware verification, RF/baseband testing, eye-diagram & power profiling of **4G/5G IoT modules** (Qualcomm, UNISOC, Eigencomm), and board-level fault analysis & microscope rework down to **01005 SMD / ICs**.
- ⚙️ **Team Leader in the Siemens Cup (CIM Competition)** — architected and implemented a **6-car, 10-floor elevator group control system** using **Siemens TIA Portal V18 (S7-1500, WinCC, PLCSIM Advanced)**.
- 🎯 **Currently seeking:** A **Werkstudent / HiWi / Internship** role in the Stuttgart region (or across Germany) in **Electronic Measurement & Hardware Testing**, **Sensor Systems / Analog & Mixed-Signal IC**, or **Industrial Automation & Control**.

</td>
<td width="50%" valign="top">

### 🇩🇪 Deutsch
- 🎓 **Masterstudent der Elektrotechnik und Informationstechnik** an der **Universität Stuttgart** (Schwerpunkt: *Intelligente Sensorik*).
- 🔬 **1 Jahr Berufserfahrung als Basisband-Hardware-Ingenieur** bei **Fibocom Wireless Inc.** — praktische Erfahrung in der Hardware-Verifikation und im Testing von **4G/5G-IoT-Modulen** (Qualcomm, UNISOC, Eigencomm), Augendiagramm-/Low-Power-/ESD-Messungen sowie Board-Level-Debugging und Mikroskop-Rework bis Bauform **01005**.
- ⚙️ **Teamleiter beim „Siemens-Cup“ (China Intelligent Manufacturing Challenge)** — Entwurf und Implementierung einer **Sechsfach-Aufzugsgruppensteuerung (10 Etagen)** mit **Siemens TIA Portal V18 (S7-1500, WinCC, PLCSIM Advanced)**.
- 🎯 **Aktuell auf der Suche nach:** Einer **Werkstudenten- / HiWi-Stelle oder einem Praktikum** im Raum Stuttgart / Deutschland in den Bereichen **Messtechnik & Hardware-Testing**, **Sensorsysteme / IC-Entwurf** oder **Automatisierungstechnik**.

</td>
</tr>
</table>

---

## 🛠️ Technical Skills / Kompetenzen & Werkzeuge

| Domain / Bereich | Tools, Instruments & Technologies |
| :--- | :--- |
| **🔬 Measurement & Hardware Verification**<br>*(Messtechnik & Hardware-Testing)* | **Oscilloscope** (Eye-Diagram, Signal Integrity, SIM Timing), **Spectrum Analyzer**, **Precision Power Supply** (Low-Power / Sleep-Current Profiling), **Digital Multimeter**, **ESD Immunity Testing**, **High/Low-Temperature Chamber Testing** |
| **🔧 Prototyping & Board-Level Rework**<br>*(Hardware-Aufbau & Fehlersuche)* | Board-Level Fault Analysis, Schematic & PCB Bring-Up, Microscope Rework & Manual Soldering of **ICs (CPU, MCU, PMU)** and **SMD Passives down to 01005**, **Qualcomm / UNISOC / Eigencomm** 4G & 5G IoT Platforms |
| **⚙️ Industrial Automation & Control**<br>*(Automatisierungstechnik & SPS)* | **Siemens TIA Portal V18**, **SIMATIC S7-1500** (`LAD` / `FBD` / `SCL`), **S7-PLCSIM Advanced**, **WinCC RT Advanced** (HMI Screen Design & `VBScript`), Multi-Agent Dispatch & State-Machine Control |
| **💻 Simulation, IC Design & Coding**<br>*(Simulation, IC-Entwurf & Programmierung)* | **MATLAB / Simulink**, **Python** (Data Processing & Test Automation), **C** (Embedded Interfaces), **CMOS Analog & Mixed-Signal IC Design**, **Git & GitHub** |
| **🌍 Languages**<br>*(Sprachkenntnisse)* | **Deutsch** (C1 – fließend in Studium & Labor), **English** (B2 – technical & professional working proficiency), **Chinese** (Native / Muttersprache) |

---

## 🚀 Featured Engineering Projects / Ausgewählte Projekte

### 1. [🏢 Siemens-Cup 6-Car 10-Floor Elevator Group Control System (TIA Portal V18)](https://github.com/guanxiang-he/siemens-cup-elevator-group-control)
> **Role:** Team Leader (Logic Algorithm Track) · **Tech:** `Siemens S7-1500` · `TIA Portal V18` · `WinCC RT Advanced` · `S7-PLCSIM Advanced` · `VBScript`

- **Multi-Car Dispatching & Minimum Waiting Time (`FB`/`FC`):** Designed a deterministic PLC group dispatcher evaluating real-time upward/downward stop counts (`停站次数计算`), turnaround floors, and estimated travel + dwell times (`最短时间计算`) across 6 elevators and 10 floors.
- **Safety Interlocks & Peak Scheduling:** Implemented overload bypass (`超载`), all-car fire emergency recall to Floor 1 (`消防迫降`), single-car maintenance locking (`锁梯`), and ground-floor up-peak traffic scheduling (`高峰模式`).
- **Full Source Code & 10-Chapter Engineering Guide:**
  - 📦 [**Download TIA Portal V18 Project (`v1.0.0` Release `.zip`)**](https://github.com/guanxiang-he/siemens-cup-elevator-group-control/releases/tag/v1.0.0) | 📂 [**Browse `src/整合/整合.ap18`**](https://github.com/guanxiang-he/siemens-cup-elevator-group-control/tree/main/src/%E6%95%B4%E5%90%88)
  - 📖 [**English Documentation (`README_EN.md`)**](https://github.com/guanxiang-he/siemens-cup-elevator-group-control/blob/main/README_EN.md) | 📘 [**中文完整图文教程（10 章 + 107 张原图）**](https://github.com/guanxiang-he/siemens-cup-elevator-group-control)

### 2. [📓 Engineering & Scientific Computing Notes (`tech-notes`)](https://github.com/guanxiang-he/tech-notes)
> **Tech:** `MATLAB` · `Numerical Data Pipelines` · `Academic Research Workflows`

- Practical guides on MATLAB data ingestion (`load`, `importdata`, `xlsread`, matrix construction) and structured AI-assisted literature review & mathematical modeling workflows for engineering master's theses.

---

## 💼 Experience & Education / Werdegang & Bildungsweg

| Period / Zeitraum | Role & Institution / Position & Institution | Highlights / Schwerpunkte |
| :--- | :--- | :--- |
| **10/2026 – 09/2028** *(expected)* | **M.Sc. Elektrotechnik und Informationstechnik**<br>*Universität Stuttgart, Germany* | • **Focus:** *Intelligente Sensorik (Intelligent Sensor Systems)*<br>• **Core Modules:** CMOS Analog & Mixed-Signal IC Design (AMSIP), Automatisierungstechnik II (AT2), Radio Frequency Technology (RFT), Semiconductor Devices (EDS) |
| **02/2024 – 02/2025** | **Baseband Engineer / Basisband-Ingenieur**<br>*Fibocom Wireless Inc. (广和通), Xi'an* | • Hardware verification & baseband testing of **4G/5G IoT modules** (Qualcomm, UNISOC, Eigencomm)<br>• Eye-diagram & SIM interface timing, low-power current profiling, ESD & thermal reliability testing<br>• Board-level fault analysis & microscope rework of ICs (CPU/MCU/PMU) and SMD components down to **01005** |
| **09/2020 – 07/2024** | **B.Eng. Electronic Science and Technology**<br>*Jiangxi University of Science and Technology, China* | • Team Leader, *Siemens-Cup China Intelligent Manufacturing Challenge* (Logic Algorithm Track, 2023) |

---

## 📫 Contact / Kontakt

- 📍 **Location:** Stuttgart, Baden-Württemberg, Germany
- 📧 **University Email:** [st203613@stud.uni-stuttgart.de](mailto:st203613@stud.uni-stuttgart.de)
- 💻 **GitHub:** [github.com/guanxiang-he](https://github.com/guanxiang-he)
