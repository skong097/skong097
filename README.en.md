<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22314E,100:0A7CFF&height=220&section=header&text=23%20Years%20of%20Infrastructure%20·%20Next%2020%20with%20Physical%20AI&fontSize=28&fontColor=ffffff&fontAlignY=34&desc=A%2023-year%20infrastructure%20engineer%20stepping%20into%20Physical%20AI&descSize=18&descAlignY=58" width="100%"/>

### Stephen Kong (공국진) : **skong097 @ gmail.com**

> 23 years of large-scale infrastructure operations · now transitioning to Physical AI for the next 20 years

[![Blog](https://img.shields.io/badge/Blog-Stephen's_Robotics_Lab-5eead4?style=for-the-badge&logo=githubpages&logoColor=5eead4&labelColor=0a0e1a)](https://skong097.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:skong097@gmail.com)

[![KR](https://img.shields.io/badge/🇰🇷_한국어-555555?style=for-the-badge)](README.md)
[![EN](https://img.shields.io/badge/🇺🇸_English-0A7CFF?style=for-the-badge)](README.en.md)

</div>

---

## About Me

**An engineer who has owned the zero-downtime operation of large-scale IT infrastructure for 23 years.**
For the next 20 years, I want to put that experience to work in **Physical AI systems that directly help people.**

- **Past 19y** — Data cluster team lead · ~18PB Hadoop multi-cluster · zero-downtime migrations · ML prediction system on operational logs
- **Past 6m** — Completed a Physical AI engineering (ROS2 · Vision AI · VLA) training program (2026-06-04)
- **Cloud** — Microsoft Azure AZ-900 (2025), AZ-104 in progress
- **Blogging weekly** on robotics, ROS2, and Vision AI

---

## Featured Project

<div align="center">

### MoCa — Cafe NPC Solicitation System

**ROS2 Jazzy workspace integrating a Behavior Tree–driven engagement funnel for service robots.**

</div>

A 5-stage engagement funnel (`IDLE → APPROACH → ICEBREAK → MINIGAME → OFFER → LEAD-IN`)
grounded in a 6-layer academic framework (Isla 2005, Russell 1980, Salichs 2014, Castro-González 2016, Marzinotto 2014, Iovino 2022).

| Component | Status | Tech |
|-----------|--------|------|
| BT Node Headers (7 nodes) | Complete | C++ / BehaviorTree.CPP 4.8.3 |
| `bt_executor` + XML + Launch | Complete | ROS2 Jazzy |
| Tick sequence verification | Verified | rclcpp |
| Nav2 Action Client integration | In progress | Nav2 |
| 6 dobi_npc packages | Scaffolded | C++ / Python |

```
ROS_DOMAIN_ID=22  ·  BehaviorTree.CPP 4.8.3  ·  Phase 1 W2
```

---

## Tech Stack

**Infrastructure & Operations** — Linux · Windows · Networking (TCP/IP · DNS · VPN) · HA · DR · Virtualization

**Data Platform** — Hadoop (HDFS · RBF · Hive · Impala · HBase · YARN) · Kafka · NiFi · ELK · Grafana · InfluxDB

**ML / MLOps** — XGBoost · LightGBM · MLflow · Random Forest · ST-GCN · YOLO · PyTorch · CUDA 12.8 · OpenCV · MediaPipe

**Robotics & Middleware** — ROS2 Jazzy · Nav2 · MoveIt2 · BehaviorTree.CPP 4.8 · Fast DDS · Zenoh

**Voice & LLM** — faster-whisper STT · Porcupine · Ollama · Korean natural-language control

**Edge / IoT** — ESP32 · ESP32-CAM · AES encryption · TCP · Serial

**VLA & Imitation Learning** *(Research · In Progress)* — LeRobot 0.5 · ACT Policy · SmolVLA · Pi0

**Cloud** — Microsoft Azure (AZ-900 certified, AZ-104 in progress)

**Languages & Dev Tools** — Python · C++ · Ubuntu · VS Code · Jupyter · Git

```text
Infrastructure       ████████████████████░  19y · ~18PB · 99.98% uptime
Data Platform        ████████████████████░  Hadoop · Kafka · NiFi · ELK
MLOps Pipeline       ███████████████░░░░░░  MLflow Level 1 (prediction system)
Vision AI            █████████████████░░░░  YOLO · ST-GCN · OpenCV · MediaPipe
Robotics Stack       ████████████████░░░░░  ROS2 · Nav2 · MoveIt2 · BT.CPP
VLA / IL (Research)  ████████░░░░░░░░░░░░░  LeRobot · ACT · SmolVLA · Pi0
```

---

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### [vision_ai](https://github.com/skong097/vision_ai)
**Home Care Vision AI · Fall Detection**

ST-GCN · Random Forest · YOLO v11 Pose · FastAPI

Extracts static and time-series features on top of YOLO v11 Pose keypoints → comparative analysis of RF vs ST-GCN.
On a ~4.6:1 normal-vs-fall imbalanced dataset, compares 4 strategies (undersampling + class weighting).

**ST-GCN (Fine-tuned) 99.63% · Recall 99.40%** — outperforms RF (97.99% · Recall 94.30%).
RF infers ~34× faster. PYSKL transfer learning (based on a model pretrained on ~56,000 videos).

</td>
<td width="50%" valign="top">

### [MoCa](https://github.com/skong097/moca_pai)
**Cafe NPC Behavior Tree System**

ROS2 Jazzy · BT.CPP 4.8.3 · C++ · Nav2

5-stage engagement funnel for café service robots, grounded in published HRI research.
Emotion-recognition pipeline (confidence-weighted EMA + hysteresis): robust to noise, sensitive to negative reactions.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [smartgate](https://github.com/skong097/smartgate)
**Face + Gesture Recognition 2-Factor Authentication**

Security gate for the Voice IoT project.
Authored the design doc (`voice_iot_plan_v2.md`) + core implementation · part of the WebSocket communication.

</td>
<td width="50%" valign="top">

### [voice_iot_home](https://github.com/skong097/voice_iot_home)
**IoT-Based Smart Home Controller**

Face authentication + part of the WebSocket communication design/implementation (Voice IoT Team 1).
ESP32 · ESP32-CAM edge + Korean voice control.

</td>
</tr>
</table>

---

## Certifications

- **HP LINUX ASE** · **HP Master ASE** (High Availability) · **HP CSA** (HP-UX)
- **MCSE** · **MCDBA** · **OCP** (Oracle) · **SCSA** (Solaris)
- **ITIL Foundation** · **Network Manager Level 2** (KR)
- **Microsoft Azure AZ-900** (2025) · AZ-104 in progress
- IELTS Overall 5.5 (2025-07)

---

## Latest from the Blog

<!-- BLOG-POST-LIST:START -->
<!-- Auto-populated via gautamkrishnar/blog-post-workflow GitHub Action -->
<!-- BLOG-POST-LIST:END -->

> Maintaining a rolling cycle of ~10 posts (5 published / 5 in reserve) each week on robotics & AI.

---

<div align="center">

### Let's Connect

Open to collaboration on **manufacturing DX infrastructure**, **robotics**, and **MLOps for operations** projects.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A7CFF,100:22314E&height=100&section=footer" width="100%"/>

</div>
