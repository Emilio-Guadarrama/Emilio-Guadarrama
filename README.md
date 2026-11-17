<p align="center">
  <a href="https://emilio-guadarrama-portfolio.vercel.app">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
      <img alt="Emilio Guadarrama — Electronics & Semiconductor Engineering, Tec de Monterrey. Click to open the portfolio." src="assets/header-dark.svg" width="100%">
    </picture>
  </a>
</p>

<p align="center">
  <a href="https://emilio-guadarrama-portfolio.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-242424?style=for-the-badge&logo=vercel&logoColor=f0f0f0"></a>
  <a href="https://www.linkedin.com/in/emilioguadarrama/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-242424?style=for-the-badge&logo=linkedin&logoColor=f0f0f0"></a>
  <a href="mailto:emilio.guadarrama@outlook.com"><img alt="Email" src="https://img.shields.io/badge/Email-242424?style=for-the-badge&logo=maildotru&logoColor=f0f0f0"></a>
  <a href="https://emilio-guadarrama-portfolio.vercel.app/brand_assets/Resume_English.pdf"><img alt="CV" src="https://img.shields.io/badge/Download_CV-242424?style=for-the-badge&logo=adobeacrobatreader&logoColor=f0f0f0"></a>
</p>

I design, build and fly **rocket flight computers** — from multilayer PCB layout to lab bring-up, flight testing and failure analysis.

## ⚡ Now

<table>
  <tr>
    <td valign="top">

- 🚀 **Vice President & Electronics & Avionics Lead** at [Ignitia Rocket Lab](https://ignitia.space), leading a 9-member electronics area in a 30-member student team
- 🏆 **LASC 2026** · Brazil — 9th of 25, Rocket Challenge (1 km) · 9th of 50, Satellite Challenge as CanSat Mission Leader
- 🛠️ **Building** the IGNIS flight computer and its MAGNIS ground station
- 🎓 **Studying** B.S. Electronics and Semiconductor Engineering at Tecnológico de Monterrey, class of 2029
- 🤖 **Before university:** three seasons of FIRST Robotics (Team Daedalus 7102), from technician to Mechanical Lead

</td>
    <td width="38%" valign="top">
      <img src="assets/lasc-avionics-bay.jpg" alt="Final avionics-bay integration before launch at LASC 2026" width="100%"><br>
      <sub>Final avionics-bay integration · LASC 2026</sub>
    </td>
  </tr>
</table>

---

## 🔥 Featured — IGNIS Flight Computer

<table>
  <tr>
    <td width="46%" valign="top">
      <img src="assets/ignis-v2.png" alt="IGNIS v2.2 flight computer, assembled" width="100%">
    </td>
    <td valign="top">

Custom flight computer for student rocketry: it senses the flight, detects apogee in real time, fires the recovery charges, streams LoRa telemetry and logs every sample.

`ESP32-S3` `RFM95W LoRa 915 MHz` `GNSS` `IMU` `Barometer` `2× pyro` `4-layer PCB`

- **v2.2** — primary flight computer at **LASC 2026**
- Flight data analyzed in Python to validate apogee detection and telemetry
- Telemetry results drove **MAGNIS**, a dual-antenna ground station
- **v5** — all-SMD, turnkey JLCPCB assembly, Ø75 mm board

**Repos →** [IGNIS v2](https://github.com/IgnitiaRocketLab/IGNIS-v2-FlightComputer) · [IGNIS v5](https://github.com/Emilio-Guadarrama/IGNIS-v5-FlightComputer) · [MAGNIS ground station](https://github.com/Emilio-Guadarrama/MAGNIS-v1-GroundStation)

</td>
  </tr>
</table>

<details>
<summary><b>Revision history v1 → v5</b></summary>

| Rev | Status |
|---|---|
| `v1` | Fabricated; too large for the rocket, redesigned before assembly |
| `v2` | First assembled; bring-up found schematic errors |
| `v2.2` | Corrected revision; **primary flight computer at LASC 2026** |
| `v3` | Incremental update; never fabricated |
| `v4` | Two units built; halted by part availability and a USB-C net error |
| `v5` | Sourcing-first, all-SMD, turnkey; Ø75 mm board |

</details>

---

## 📂 Projects

<table>
  <tr>
    <td width="33%" valign="top">

**[IGNIS v5](https://github.com/Emilio-Guadarrama/IGNIS-v5-FlightComputer)**

Sourcing-first redesign for turnkey assembly: 109 placements, 40 BOM lines, 37 of them stocked by a Mexican distributor.

`SAM-M10Q` `LSM6DSV32X` `DPS368`

</td>
    <td width="33%" valign="top">

**[MAGNIS v1](https://github.com/Emilio-Guadarrama/MAGNIS-v1-GroundStation)**

Ground station for IGNIS: two LoRa receivers with antenna diversity, microSD logging and a live dashboard over USB and Wi-Fi.

`2× RFM95W` `ESP32` `2-layer PCB`

</td>
    <td width="33%" valign="top">

**[Portfolio](https://emilio-guadarrama-portfolio.vercel.app)**

My engineering portfolio: projects, experience and CV, in English and Spanish.

`React` `Vite` `Tailwind CSS`

</td>
  </tr>
</table>

---

## 🧰 Toolbox

| Area | Tools |
|---|---|
| **Hardware & PCB** | Altium Designer · KiCad · Schematic capture · 4-layer layout · RF layout · Power distribution · BOM management |
| **Embedded** | ESP32-S3 · C/C++ · Arduino · SPI · I2C · UART · USB · LoRa · GNSS · Sensor integration |
| **Lab & Test** | Oscilloscope · Signal generator · Bench supply · Board bring-up · Failure analysis |
| **Manufacturing** | DFM for turnkey SMT (JLCPCB/LCSC) · Stencil printing · Reflow · Hot-air rework |
| **Software** | Python (pandas, PySide6) · Verilog · LTspice · NI Multisim · Git |

<p>
  <a href="https://www.altium.com/altium-designer"><img alt="Altium" src="https://img.shields.io/badge/Altium_Designer-242424?style=for-the-badge&logo=altiumdesigner&logoColor=f0f0f0"></a>
  <a href="https://www.kicad.org"><img alt="KiCad" src="https://img.shields.io/badge/KiCad-242424?style=for-the-badge&logo=kicad&logoColor=f0f0f0"></a>
  <a href="https://www.espressif.com/en/products/socs/esp32-s3"><img alt="Espressif" src="https://img.shields.io/badge/ESP32--S3-242424?style=for-the-badge&logo=espressif&logoColor=f0f0f0"></a>
  <a href="https://isocpp.org"><img alt="C++" src="https://img.shields.io/badge/C%2B%2B-242424?style=for-the-badge&logo=cplusplus&logoColor=f0f0f0"></a>
  <a href="https://www.arduino.cc"><img alt="Arduino" src="https://img.shields.io/badge/Arduino-242424?style=for-the-badge&logo=arduino&logoColor=f0f0f0"></a>
  <a href="https://www.python.org"><img alt="Python" src="https://img.shields.io/badge/Python-242424?style=for-the-badge&logo=python&logoColor=f0f0f0"></a>
  <a href="https://git-scm.com"><img alt="Git" src="https://img.shields.io/badge/Git-242424?style=for-the-badge&logo=git&logoColor=f0f0f0"></a>
</p>

---

## 🏆 Highlights

- **LASC 2026** · Brazil — 9th of 25, Rocket Challenge (1 km) · 9th of 50, Satellite Challenge as CanSat Mission Leader
- **ENMICE 2025** — 2nd place, project presentation (WIRIKUTA 1.1 test bench)
- **Tec de Monterrey Engineering Expo 2025** — 1st place, Physical Prototype
- **FIRST World Championship 2024** — qualified by winning the Hermosillo Regional

<p align="center">
  <a href="https://emilio-guadarrama-portfolio.vercel.app">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/footer-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="assets/footer-light.svg">
      <img alt="Open the portfolio: emilio-guadarrama-portfolio.vercel.app" src="assets/footer-dark.svg" width="100%">
    </picture>
  </a>
</p>
