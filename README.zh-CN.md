<div align="center">
  <img src="banner.png" width="100%" alt="Awesome mmWave Sensing Banner">
</div>

# awesome-mmwave-sensing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](#-社区与贡献)

> 面向工程师与研究者的 **mmWave（毫米波）雷达感知**“学术索引式”资源库：  
> 聚焦 **生命体征（呼吸/心跳）**、**HCI/手势交互**、**室内跟踪/成像/建图**。  
> 原则：**论文优先（可溯源、可引用）**，并补充数据集、开源工具与硬件入口。

**语言：** [English](README.md) | **简体中文**

---

## 目录

- [🔥 精选 / 推荐](#-精选--推荐)
- [📚 论文索引（学术索引式）](#-论文索引学术索引式)
  - [生命体征](#生命体征)
  - [HCI / 手势 / 生物特征](#hci--手势--生物特征)
  - [成像 / 跟踪 / 建图](#成像--跟踪--建图)
- [🛠 开源工具](#-开源工具)
- [💾 数据集](#-数据集)
- [🔌 硬件](#-硬件)
- [🎓 从零到一 (学习路径)](#-从零到一)
- [👥 社区与贡献](#-社区与贡献)
- [🧩 Phish-tech 独家呈现](#-phish-tech-独家呈现)
- [🎨 可视化画廊](#-可视化画廊)

---

## 🔥 精选 / 推荐

如果你只想先抓重点：

- **生命体征入门主线**：FMCW 相位/微多普勒体征提取 + 多人分离/稀疏建模路线。
- **交互主线**：Soli（CHI/SIGGRAPH 体系）+ IMWUT 家居手势系统。
- **跟踪/成像主线**：milliMap（MobiSys）+ HuPR（WACV）+ IMWUT 多人跟踪。

更广泛（非 mmWave 专属，但便于交叉检索）的雷达感知索引：
- `awesome-radar-perception`：https://github.com/ZHOUYI1023/awesome-radar-perception

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 📚 论文索引（学术索引式）

**编号规则：**
- 以 **ID** 作为本仓库内的稳定引用键（例如 `VS-03`, `HCI-07`, `TRK-02`）。
- 链接优先使用出版方 DOI；必要时补充 arXiv / 项目页。

### 生命体征

| ID | 年份 | 题目 | Venue | 链接 |
|---|---:|---|---|---|
| VS-01 | 2016 | Monitoring Vital Signs Using Millimeter Wave | ACM MobiHoc | https://doi.org/10.1145/2942358.2942381 |
| VS-02 | 2017 | Vital Sign and Sleep Monitoring Using Millimeter Wave | ACM（IMWUT/UbiComp 体系） | https://doi.org/10.1145/3051124 |
| VS-03 | 2019 | Remote Monitoring of Human Vital Signs Using mm-Wave FMCW Radar | IEEE Access | https://www.weizmann.ac.il/math/yonina/sites/math.yonina/files/Remote_Monitoring_of_Human_Vital_Signs_Using_mm-Wave_FMCW_Radar.pdf |
| VS-04 | 2020 | Remote Monitoring of Human Vital Signs Based on 77-GHz mm-Wave FMCW Radar | Sensors | https://doi.org/10.3390/s20102999 |
| VS-05 | 2021 | Non-Contact Monitoring of Human Vital Signs Using FMCW Millimeter Wave Radar in the 120 GHz Band | Sensors | https://doi.org/10.3390/s21082732 |
| VS-06 | 2022 | High-Precision Vital Signs Monitoring Method Using a FMCW Millimeter-Wave Sensor | Sensors | https://doi.org/10.3390/s22197543 |
| VS-07 | 2022 | Your Breath Doesn't Lie: Multi-user Authentication by Sensing Respiration Using mmWave Radar | IEEE SECON | https://doi.org/10.1109/SECON55815.2022.9918606 |
| VS-08 | 2023 | Sparsity-Based Multi-Person Non-Contact Vital Signs Monitoring via FMCW Radar | IEEE JBHI | https://doi.org/10.1109/JBHI.2023.3255740 |
| VS-09 | 2023 | Pi-ViMo: Physiology-inspired Robust Vital Sign Monitoring using mmWave Radars | ACM TIOT | https://doi.org/10.1145/3589347 |
| VS-10 | 2025 | Event-level Identification of Sleep Apnea using FMCW Radar | Scientific Reports |  https://doi.org/10.3390/bioengineering12040399 |

补充：多人生命体征的经典 TI 技术报告（工程实现很常被引用）  
- https://e2echina.ti.com/cfs-file/__key/communityserver-discussions-components-files/60/Vital-Signs-Monitoring-of-Multiple-People-using-a.pdf

[↑ 回到顶部](#awesome-mmwave-sensing)

---

### HCI / 手势 / 生物特征

| ID | 年份 | 题目 | Venue | 链接 |
|---|---:|---|---|---|
| HCI-01 | 2016 | Soli: Ubiquitous Gesture Sensing with Millimeter Wave Radar | ACM TOG | https://doi.org/10.1145/2897824.2925953 |
| HCI-02 | 2020 | Real-time Arm Gesture Recognition in Smart Home Scenarios via Millimeter Wave Sensing (mHomeGes) | ACM IMWUT | https://doi.org/10.1145/3432235 |
| HCI-03 | 2020 | MU-ID: Multi-user Identification Through Gaits Using 60 GHz Radios | IEEE INFOCOM | https://doi.org/10.1109/INFOCOM41043.2020.9155456 |
| HCI-04 | 2020 | Handwriting Tracking using 60 GHz mmWave Radar | IEEE WF-IoT | https://doi.org/10.1109/WF-IoT48130.2020.9221158 |
| HCI-05 | 2021 | Hand Gesture Recognition Using 802.11ad mmWave Sensor in the Mobile Device | IEEE WCNC Workshops | https://doi.org/10.1109/WCNCW49093.2021.9419978 |
| HCI-06 | 2021 | mmWrite: Passive Handwriting Tracking Using a Single Millimeter-Wave Radio | IEEE IoT-J | https://doi.org/10.1109/JIOT.2021.3066507 |
| HCI-07 | 2021 | DI-Gesture: A Fine-grained Dataset and Benchmark for Doppler Imaging-based Gesture Recognition | arXiv | https://arxiv.org/abs/2101.05214 |
| HCI-08 | 2022 | mm4Arm: Leveraging Properties of mmWave Signals for 3D Arm Motion Tracking | ACM POMACS | https://doi.org/10.1145/3570613 |
| HCI-09 | 2022 | GaitCube: Deep Data Cube Learning for Human Recognition With Millimeter-Wave Radio | IEEE IoT-J | https://doi.org/10.1109/JIOT.2021.3083934 |
| HCI-10 | 2024 | mmSign: mmWave-based Few-Shot Online Handwritten Signature Verification | ACM TOSN | https://doi.org/10.1145/3605945 |
| HCI-11 | 2025 | mmPencil: Toward Writing-Style-Independent In-Air Handwriting Recognition via mmWave Radar and Large Vision-Language Model | ACM IMWUT | https://doi.org/10.1145/3749504 |

[↑ 回到顶部](#awesome-mmwave-sensing)

---

### 成像 / 跟踪 / 建图

| ID | 年份 | 题目 | Venue | 链接 |
|---|---:|---|---|---|
| TRK-01 | 2018 | Indoor Localization Using Commercial Off-The-Shelf 60 GHz Access Points | IEEE INFOCOM | https://doi.org/10.1109/INFOCOM.2018.8486232 |
| TRK-02 | 2019 | RadHAR: Human Activity Recognition from Point Clouds Generated through a Millimeter-wave Radar | ACM mmNets（MobiCom WS） | https://doi.org/10.1145/3349624.3356768 |
| TRK-03 | 2020 | milliMap: Robust Indoor Mapping with Low-cost mmWave Radar | ACM MobiSys | https://doi.org/10.1145/3386901.3388945 |
| TRK-04 | 2022 | mTransSee: Enabling Real-time mmWave Sparse Imaging through Non-RF Occluders | ACM IMWUT | https://doi.org/10.1145/3517231 |
| TRK-05 | 2023 | HuPR: A Benchmark for Human Pose Estimation Using Millimeter Wave Radar | IEEE WACV | https://openaccess.thecvf.com/content/WACV2023/papers/Lee_HuPR_A_Benchmark_for_Human_Pose_Estimation_Using_Millimeter_Wave_WACV_2023_paper.pdf |
| TRK-06 | 2023 | Environment-aware Multi-person Tracking in Indoor Environments with mmWave Radars | ACM IMWUT | https://doi.org/10.1145/3610902 |
| TRK-07 | 2023 | MM-Fi: Multi-Modal Non-Intrusive 4D Human Dataset for Wireless Human Sensing | NeurIPS D&B / 项目页 | https://ntu-aiot-lab.github.io/mm-fi |
| TRK-08 | 2024 | Fast Human Action Recognition via mmWave Radar Point Clouds | ACM（会议论文） | https://doi.org/10.1145/3627673.3679787 |
| TRK-09 | 2024 | PmTrack: Enabling Personalized mmWave-based Human Tracking in Commodity Smart Home | ACM IMWUT | https://doi.org/10.1145/3631433 |
| TRK-10 | 2024 | Waffle: Waterproof mmWave-based Sensing Inside Bathrooms with Running Water | ACM IMWUT | https://doi.org/10.1145/3631458 |
| TRK-11 | 2025 | DragonFly: Drone-based 3D Localization of Backscatter Tags Using mmWave Radar | ACM MobiCom | https://doi.org/10.1145/3680207.3765269 |

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 🛠 开源工具

- **OpenRadar**：https://github.com/PreSenseRadar/OpenRadar  
- **ti_mmwave_rospkg**：https://github.com/robotics-upo/ti_mmwave_rospkg  
- **TI mmWave SDK (官方)**：https://www.ti.com/tool/MMWAVE-SDK  
- ⭐ **mmWave Preprocessing Tool for Heartbeat Estimation** https://github.com/phish-tech/mmWave-Heartbeat-Dataset-Preprocessing-Toolbox  

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 💾 数据集

- **RadHAR**：https://github.com/nesl/RadHAR  
- **HuPR**：https://github.com/robert80203/HuPR-A-Benchmark-for-Human-Pose-Estimation-Using-Millimeter-Wave-Radar  
- **MM-Fi**：https://github.com/ybhbingo/MMFi_dataset  
- **mHomeGes-dataset**：https://github.com/GestureMan/mHomeGes-dataset  

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 🔌 硬件

- **Texas Instruments (IWR/AWR 系列)** 示例：IWR6843 https://www.ti.com/product/IWR6843  
- **Infineon XENSIV™ 60GHz** 示例：BGT60TR13C https://www.infineon.com/part/BGT60TR13C  
- **Silicon Radar (122GHz ISM)** 示例：TRX_120_001 https://siliconradar.com/datasheets/Datasheet_TRX_120_001.html  

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 🎓 从零到一

毫米波雷达新手？跟随这个学习路径，从概念到落地：

1.  **理论基础 (The Basics)** 📖 阅读经典的 **[TI FMCW Radar Basics](https://www.ti.com/lit/wp/spyy005a/spyy005a.pdf)** 白皮书。理解 Range-FFT、Doppler-FFT 和角度估算。
2.  **快速上手 (The Quickstart)** 🛠️ 运行 **[mmWave-Heartbeat-Toolbox](https://github.com/phish-tech/mmWave-Heartbeat-Dataset-Preprocessing-Toolbox)**。它解决了复杂的数据解析问题，并提供了一个可运行的生命体征提取基线。
3.  **学术经典 (The Academic Pillar)** 🎓 阅读奠基之作 **[VS-01 (MobiHoc '16)](#生命体征)**。它定义了目前大多数研究者使用的基于相位的感知流程。
4.  **社区扩展 (The Community)** 🧩 尝试复现 **[OpenRadar](https://github.com/PreSenseRadar/OpenRadar)** 中的案例，探索检测与跟踪技术。

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 👥 社区与贡献

欢迎 PR。

**收录规范（建议）**
1. 范围：mmWave 雷达感知（生命体征 / HCI / 跟踪成像）
2. 论文优先：尽量给 DOI 或出版方页面；若无则给 arXiv/项目页
3. 按索引格式追加：新增 ID + 一行引文信息

**推荐文件**
- `CONTRIBUTING.md` — 贡献规则与格式
- `CODE_OF_CONDUCT.md` — 社区准则
- `CITATION.cff` — 如何引用本列表

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 🧩 Phish-tech 独家呈现

> 以下项目由本仓库作者提供。

- ⭐ **毫米波雷达心跳呼吸解缠绕算法** — [https://github.com/phish-tech/mmWave-Heartbeat-Toolbox](https://github.com/phish-tech/mmWave-Heartbeat-Dataset-Preprocessing-Toolbox-)
  *A lightweight, pure Python framework for TI mmWave radar data processing. Features EEMD for robust vital sign extraction. 🚀 Recommended for Beginners.*

[↑ 回到顶部](#awesome-mmwave-sensing)

---

## 🎨 可视化画廊（敬请期待！）

想看看毫米波的实际效果？  
查看我们的 **[可视化画廊 (Visual Gallery)](GALLERY.md)**：（装修中）
- 🌊 **Range-Doppler 热力图** 可视化。
- 🫀 **实时生命体征** 波形（呼吸与心跳）。
- 🕺 **3D 点云跟踪** 演示。

[![Enter Gallery](https://img.shields.io/badge/Enter-Visual_Gallery-blueviolet?style=for-the-badge&logo=google-photos&logoColor=white)](GALLERY.md)

[↑ 回到顶部](#awesome-mmwave-sensing)
