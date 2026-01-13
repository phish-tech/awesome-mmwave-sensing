# awesome-mmwave-sensing
A Roadmap for Quickstart: Curated resources for Vital Signs &amp; HCI. Maintained by phish-tech.
<!-- ========================= -->
<!-- File: README.md (English) -->
<!-- ========================= -->

# awesome-mmwave-sensing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-community--contributing)

> A curated, research-grade index of **millimeter-wave (mmWave) radar sensing** for **vital signs** (respiration/heartbeat), **HCI & gesture**, and **indoor tracking/imaging**.  
> Built for engineers and researchers who want **credible papers first**, plus datasets, tools, and hardware pointers.

**Language:** **English** | [简体中文](README.zh-CN.md)

---

## Table of Contents

- [🔥 Featured / Recommended](#-featured--recommended)
- [📚 Academic Paper Index](#-academic-paper-index)
  - [Vital Signs](#vital-signs)
  - [HCI / Gesture / Biometrics](#hci--gesture--biometrics)
  - [Imaging / Tracking / Mapping](#imaging--tracking--mapping)
- [🛠 Open Source Tools](#-open-source-tools)
- [💾 Datasets](#-datasets)
- [🔌 Hardware](#-hardware)
- [👥 Community & Contributing](#-community--contributing)
- [🧩 Phish-tech Private Goods (Placed at the End)](#-phish-tech-private-goods-placed-at-the-end)

---

## 🔥 Featured / Recommended

If you only bookmark a few things:

- **Start from Vital Signs fundamentals:** *mmWave FMCW phase-based extraction + multi-person separation.*  
- **For HCI:** *Soli (CHI/SIGGRAPH lineage) + IMWUT arm gesture systems.*
- **For Tracking/Imaging:** *milliMap (MobiSys) + HuPR (WACV) + IMWUT multi-person tracking.*

Broader radar perception lists (non-mmWave-specific but useful for cross-referencing):
- `awesome-radar-perception` (datasets + detection + tracking): https://github.com/ZHOUYI1023/awesome-radar-perception

---

## 📚 Academic Paper Index

**Indexing convention:**  
- **ID** is stable for citation inside this repo (e.g., `VS-03`, `HCI-07`, `TRK-02`).  
- Links prioritize publisher DOI pages; arXiv/project pages are used when appropriate.

### Vital Signs

| ID | Year | Title | Venue | Links |
|---|---:|---|---|---|
| VS-01 | 2016 | Monitoring Vital Signs Using Millimeter Wave | ACM MobiHoc | DOI: https://doi.org/10.1145/2942358.2942381 |
| VS-02 | 2017 | Vital Sign and Sleep Monitoring Using Millimeter Wave | ACM (IMWUT/UbiComp lineage) | DOI: https://doi.org/10.1145/3051124 |
| VS-03 | 2019 | Remote Monitoring of Human Vital Signs Using mm-Wave FMCW Radar | IEEE Access | PDF: https://www.weizmann.ac.il/math/yonina/sites/math.yonina/files/Remote_Monitoring_of_Human_Vital_Signs_Using_mm-Wave_FMCW_Radar.pdf |
| VS-04 | 2020 | Remote Monitoring of Human Vital Signs Based on 77-GHz mm-Wave FMCW Radar | Sensors | DOI: https://doi.org/10.3390/s20102999 |
| VS-05 | 2021 | Non-Contact Monitoring of Human Vital Signs Using FMCW Millimeter Wave Radar in the 120 GHz Band | Sensors | DOI: https://doi.org/10.3390/s21082732 |
| VS-06 | 2022 | High-Precision Vital Signs Monitoring Method Using a FMCW Millimeter-Wave Sensor | Sensors | DOI: https://doi.org/10.3390/s22197543 |
| VS-07 | 2022 | Your Breath Doesn't Lie: Multi-user Authentication by Sensing Respiration Using mmWave Radar | IEEE SECON | DOI: https://doi.org/10.1109/SECON55815.2022.9918606 |
| VS-08 | 2023 | Sparsity-Based Multi-Person Non-Contact Vital Signs Monitoring via FMCW Radar | IEEE JBHI | DOI: https://doi.org/10.1109/JBHI.2023.3255740 |
| VS-09 | 2023 | Pi-ViMo: Physiology-inspired Robust Vital Sign Monitoring using mmWave Radars | ACM TIOT | DOI: https://doi.org/10.1145/3589347 |
| VS-10 | 2025 | Event-level Identification of Sleep Apnea using FMCW Radar | Scientific Reports | DOI: https://doi.org/10.1038/s41598-025-02247-3 |

**More (Vital Signs):**
- Multi-person TI reference (classic industry technical report): https://e2echina.ti.com/cfs-file/__key/communityserver-discussions-components-files/60/Vital-Signs-Monitoring-of-Multiple-People-using-a.pdf

---

### HCI / Gesture / Biometrics

| ID | Year | Title | Venue | Links |
|---|---:|---|---|---|
| HCI-01 | 2016 | Soli: Ubiquitous Gesture Sensing with Millimeter Wave Radar | ACM TOG | DOI: https://doi.org/10.1145/2897824.2925953 |
| HCI-02 | 2020 | Real-time Arm Gesture Recognition in Smart Home Scenarios via Millimeter Wave Sensing (mHomeGes) | ACM IMWUT | DOI: https://doi.org/10.1145/3432235 |
| HCI-03 | 2020 | MU-ID: Multi-user Identification Through Gaits Using 60 GHz Radios | IEEE INFOCOM | DOI: https://doi.org/10.1109/INFOCOM41043.2020.9155456 |
| HCI-04 | 2020 | Handwriting Tracking using 60 GHz mmWave Radar | IEEE WF-IoT | DOI: https://doi.org/10.1109/WF-IoT48130.2020.9221158 |
| HCI-05 | 2021 | Hand Gesture Recognition Using 802.11ad mmWave Sensor in the Mobile Device | IEEE WCNC Workshops | DOI: https://doi.org/10.1109/WCNCW49093.2021.9419978 |
| HCI-06 | 2021 | mmWrite: Passive Handwriting Tracking Using a Single Millimeter-Wave Radio | IEEE IoT-J | DOI: https://doi.org/10.1109/JIOT.2021.3066507 |
| HCI-11 | 2021 | DI-Gesture: A Fine-grained Dataset and Benchmark for Doppler Imaging-based Gesture Recognition | arXiv | https://arxiv.org/abs/2101.05214 |
| HCI-07 | 2022 | mm4Arm: Leveraging Properties of mmWave Signals for 3D Arm Motion Tracking | ACM POMACS | DOI: https://doi.org/10.1145/3570613 |
| HCI-08 | 2022 | GaitCube: Deep Data Cube Learning for Human Recognition With Millimeter-Wave Radio | IEEE IoT-J | DOI: https://doi.org/10.1109/JIOT.2021.3083934 |
| HCI-09 | 2024 | mmSign: mmWave-based Few-Shot Online Handwritten Signature Verification | ACM TOSN | DOI: https://doi.org/10.1145/3605945 |
| HCI-10 | 2025 | mmPencil: Toward Writing-Style-Independent In-Air Handwriting Recognition via mmWave Radar and Large Vision-Language Model | ACM IMWUT | DOI: https://doi.org/10.1145/3749504 |


---

### Imaging / Tracking / Mapping

| ID | Year | Title | Venue | Links |
|---|---:|---|---|---|
| TRK-01 | 2018 | Indoor Localization Using Commercial Off-The-Shelf 60 GHz Access Points | IEEE INFOCOM | DOI: https://doi.org/10.1109/INFOCOM.2018.8486232 |
| TRK-02 | 2019 | RadHAR: Human Activity Recognition from Point Clouds Generated through a Millimeter-wave Radar | ACM mmNets (MobiCom WS) | DOI: https://doi.org/10.1145/3349624.3356768 |
| TRK-03 | 2020 | milliMap: Robust Indoor Mapping with Low-cost mmWave Radar | ACM MobiSys | DOI: https://doi.org/10.1145/3386901.3388945 |
| TRK-04 | 2022 | mTransSee: Enabling Real-time mmWave Sparse Imaging through Non-RF Occluders | ACM IMWUT | DOI: https://doi.org/10.1145/3517231 |
| TRK-05 | 2023 | HuPR: A Benchmark for Human Pose Estimation Using Millimeter Wave Radar | IEEE WACV | PDF: https://openaccess.thecvf.com/content/WACV2023/papers/Lee_HuPR_A_Benchmark_for_Human_Pose_Estimation_Using_Millimeter_Wave_WACV_2023_paper.pdf |
| TRK-06 | 2023 | Environment-aware Multi-person Tracking in Indoor Environments with mmWave Radars | ACM IMWUT | DOI: https://doi.org/10.1145/3610902 |
| TRK-10 | 2023 | MM-Fi: Multi-Modal Non-Intrusive 4D Human Dataset for Wireless Human Sensing | NeurIPS Datasets & Benchmarks / arXiv | Project: https://ntu-aiot-lab.github.io/mm-fi |
| TRK-07 | 2024 | PmTrack: Enabling Personalized mmWave-based Human Tracking in Commodity Smart Home | ACM IMWUT | DOI: https://doi.org/10.1145/3631433 |
| TRK-08 | 2024 | Waffle: Waterproof mmWave-based Sensing Inside Bathrooms with Running Water | ACM IMWUT | DOI: https://doi.org/10.1145/3631458 |
| TRK-09 | 2025 | DragonFly: Drone-based 3D Localization of Backscatter Tags Using mmWave Radar | ACM MobiCom | DOI: https://doi.org/10.1145/3680207.3765269 |
| TRK-11 | 2024 | Fast Human Action Recognition via mmWave Radar Point Clouds | ACM (conference proceedings) | DOI: https://doi.org/10.1145/3627673.3679787 |

---

## 🛠 Open Source Tools

- **OpenRadar** — Open-source radar signal processing modules and examples.  
  https://github.com/PreSenseRadar/OpenRadar
- **pymmw** — Python toolbox for parsing/processing TI mmWave radar data.  
  https://github.com/ibaiGorordo/pymmw
- **open_radar_processing** — Python radar processing examples and utilities.  
  https://github.com/khpeek/open_radar_processing
- **ti_mmwave_rospkg** — ROS integration for TI mmWave sensors.  
  https://github.com/robotics-upo/ti_mmwave_rospkg
- **TI mmWave SDK (official)** — Firmware + reference processing chain for IWR/AWR devices.  
  https://www.ti.com/tool/MMWAVE-SDK
- ⭐ **mmWave Preprocessing Tool for Heartbeat Estimation** 
  https://github.com/phish-tech/mmWave-Heartbeat-Dataset-Preprocessing-Toolbox  
---

## 💾 Datasets

- **RadHAR** (mmWave point-cloud HAR): https://github.com/nesl/RadHAR  
- **HuPR** (mmWave pose benchmark): https://github.com/robert80203/HuPR-A-Benchmark-for-Human-Pose-Estimation-Using-Millimeter-Wave-Radar  
- **MM-Fi** (multi-modal 4D dataset incl. mmWave radar): https://github.com/ybhbingo/MMFi_dataset  
- **mHomeGes-dataset** (mmWave arm gestures in smart homes): https://github.com/GestureMan/mHomeGes-dataset  

---

## 🔌 Hardware

- **Texas Instruments (TI) mmWave (IWR/AWR series)**  
  Example: IWR6843 product page: https://www.ti.com/product/IWR6843
- **Infineon XENSIV™ 60 GHz radar**  
  Example: BGT60TR13C: https://www.infineon.com/part/BGT60TR13C
- **Silicon Radar (122 GHz ISM band devices)**  
  Example: TRX_120_001 datasheet: https://siliconradar.com/datasheets/Datasheet_TRX_120_001.html

---

## 👥 Community & Contributing

Contributions are welcome and appreciated.

**How to add a paper/tool/dataset**
1. Keep scope: **mmWave radar sensing** (vital signs / HCI / tracking & imaging).
2. Prefer peer-reviewed venues (ACM/IEEE/Elsevier/Nature family) and stable links (DOI/project page).
3. Follow the indexing format: add a new ID and a one-line citation.

**Suggested repo files**
- `CONTRIBUTING.md` — contribution rules + formatting
- `CODE_OF_CONDUCT.md` — community policy
- `CITATION.cff` — how to cite this list

---

## 🧩 Phish-tech Present

> The following items are presented by the author of this project.

- ⭐ **mmWave Preprocessing Tool for Heartbeat Estimation** — [https://github.com/phish-tech/mmWave-Heartbeat-Toolbox](https://github.com/phish-tech/mmWave-Heartbeat-Dataset-Preprocessing-Toolbox-)  
  *A lightweight, pure Python framework for TI mmWave radar data processing. Features EEMD for robust vital sign extraction. 🚀 Recommended for Beginners.*
