<h1 align="center">Yadnik Bendale</h1>

<p align="center">
  <b>Embedded Systems &amp; Firmware Engineer</b>
  &nbsp;·&nbsp; ARM Cortex-M / STM32
  &nbsp;·&nbsp; MSE, University of Pennsylvania
</p>

<p align="center">
  I build reliable firmware for resource-constrained devices &mdash; from board bring-up to cloud telemetry.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yadnik-bendale/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:yadnik22@gmail.com"><img src="https://img.shields.io/badge/Email-555555?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://drive.google.com/file/d/1d_Tq3pRdVrcT8IUlH9_eBKZUF67QYb-p/view?usp=sharing"><img src="https://img.shields.io/badge/Résumé-2EA44F?style=flat-square&logo=readdotcv&logoColor=white" alt="Résumé"/></a>
  <a href="https://www.youtube.com/channel/UCPee68W5xnyTmCAHwcblU2g"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube"/></a>
</p>

---

## About

```c
struct Engineer yadnik = {
    .name         = "Yadnik Bendale",
    .role         = "Embedded Systems & Firmware Engineer",
    .education    = "MSE, University of Pennsylvania",
    .focus        = { "Bare-metal C", "RTOS", "PCB Design", "Sensor Fusion" },
    .building     = "STM32U5 imaging firmware + 4G-LTE asset tracker",
    .open_to_work = true,
};
```

I work across the full embedded stack: schematic capture, PCB layout in KiCad,
board bring-up, firmware, and the cloud telemetry that turns raw sensor data into
something useful. Most of my work is on ARM Cortex-M (STM32), with regular use of
ESP32, RP2040, and Nordic silicon.

- Developing production **STM32U5** firmware for multi-spectral imaging plus a **4G-LTE asset tracker**
- Comfortable from **register-level bare-metal** through **RTOS** scheduling and **OTA** update pipelines
- **Google Summer of Code 2021** contributor to **Zephyr RTOS** (BeagleConnect Freedom)
- Focus areas: low-power design, sensor fusion, and safety-critical systems

---

## Tech Stack

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-AA1F2E?style=flat-square)

**Microcontrollers &amp; Silicon**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![RP2040](https://img.shields.io/badge/RP2040-7C0A02?style=flat-square&logo=raspberrypi&logoColor=white)
![nRF52](https://img.shields.io/badge/Nordic_nRF-00A9CE?style=flat-square&logo=nordicsemiconductor&logoColor=white)
![ARM Cortex-M](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=flat-square&logo=arm&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white)

**RTOS &amp; Firmware**

![Zephyr](https://img.shields.io/badge/Zephyr_RTOS-7B68EE?style=flat-square&logo=zephyrproject&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-1AAD19?style=flat-square&logo=freertos&logoColor=white)
![Bare Metal](https://img.shields.io/badge/Bare--Metal-2C2C2C?style=flat-square)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)

**Protocols &amp; Interfaces**

![I2C](https://img.shields.io/badge/I²C-444444?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-444444?style=flat-square)
![UART](https://img.shields.io/badge/UART-444444?style=flat-square)
![CAN](https://img.shields.io/badge/CAN_bus-444444?style=flat-square)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![LTE](https://img.shields.io/badge/LTE--M_/_NB--IoT-FF6F00?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

**Tools, Cloud &amp; Hardware**

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![AWS IoT](https://img.shields.io/badge/AWS_IoT-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

#### [Multi-Sensor Imaging Firmware](https://github.com/Yadnik1/torch-sensor-arduino)
STM32U5G9 firmware that fuses RGB and thermal imaging with environmental sensors and cellular uploads. Includes Memfault OTA, an IWDG watchdog, and bank-swap rollback.

`STM32U5` · `C++` · `HDR` · `LTE` · `OTA`

</td>
<td width="50%" valign="top">

#### [Low-Cost Telematics Device](https://github.com/Yadnik1/Low-Cost-Telematics-Device)
Usage-based-insurance telematics that can save drivers up to 30% on premiums. Custom two-layer KiCad PCB, C/CMake firmware, and IMU noise reduction in Python.

`KiCad` · `C` · `CMake` · `IMU` · `UBI`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Overhead Crane Control System](https://github.com/Yadnik1/Overhead-Crane-Control-System)
Safety-focused STM32G030 firmware for crane encoder and decoder units, built for deterministic and reliable industrial control.

`STM32G0` · `Bare-metal` · `Safety` · `RF`

</td>
<td width="50%" valign="top">

#### [Noxious-Gas Detection for Coal Mines](https://github.com/Yadnik1/Noxious-Gas-Detection-System-for-Coal-Mines)
An ESP32 → InfluxDB → Grafana pipeline streaming eight parameters over Wi-Fi, with a Bayesian sensor-fusion algorithm on Raspberry Pi for higher detection accuracy.

`ESP32` · `Sensor Fusion` · `Grafana` · `IoT`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [Flash Memory Driver for STM32](https://github.com/Yadnik1/Flash-Memory-STM32)
Bare-metal STM32 internal-flash driver — page erase, word/buffer writes, and safe read-back for on-device data storage.

`STM32` · `Bare-metal` · `Flash` · `Driver`

</td>
<td width="50%" valign="top">

#### [Through-Wall Detection](https://github.com/Yadnik1/Through-Wall-Detection)
Human-presence sensing through obstructions, combining RF/radar signal processing with embedded data acquisition.

`RF` · `Radar` · `Python` · `DSP`

</td>
</tr>
</table>

<p align="center"><a href="https://github.com/Yadnik1?tab=repositories">View all repositories →</a></p>

---

## GitHub Activity

<div align="center">

<img height="170em" src="https://github-readme-stats-sigma-five.vercel.app/api?username=yadnik1&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117" alt="GitHub stats" />
<img height="170em" src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=yadnik1&layout=compact&theme=github_dark&hide_border=true&bg_color=0D1117&langs_count=8" alt="Top languages" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=yadnik1&bg_color=0D1117&color=58A6FF&line=58A6FF&point=FFFFFF&area=true&area_color=1F6FEB&hide_border=true&custom_title=Contribution%20Activity" alt="Contribution activity graph" width="100%" />

</div>
