<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22314E,100:0A7CFF&height=220&section=header&text=23%20Years%20of%20Infrastructure%20·%20Next%2020%20with%20Physical%20AI&fontSize=28&fontColor=ffffff&fontAlignY=34&desc=23%EB%85%84%EC%B0%A8%20%EC%9D%B8%ED%94%84%EB%9D%BC%20%EC%97%94%EC%A7%80%EB%8B%88%EC%96%B4%EA%B0%80%20%EB%82%98%EC%84%9C%EB%8A%94%20Physical%20AI&descSize=18&descAlignY=58" width="100%"/>

### 공국진 (Stephen Kong) : **skong097 @ gmail.com**

> 23 years of large-scale infrastructure operations · now transitioning to Physical AI for the next 20 years

[![Blog](https://img.shields.io/badge/Blog-Stephen's_Robotics_Lab-5eead4?style=for-the-badge&logo=githubpages&logoColor=5eead4&labelColor=0a0e1a)](https://skong097.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:skong097@gmail.com)

</div>

---

## About Me

**23년간 대규모 IT 인프라의 무중단 운영을 책임져 온 엔지니어**입니다.
다음 20년은 **사람을 직접 돕는 Physical AI 시스템**에 그 경험을 쓰려 합니다.

- **Past 19y** — Data cluster team lead · 약 18PB Hadoop 멀티클러스터 · 무중단 마이그레이션 · 운영로그 ML 예측 시스템
- **Past 6m** — Physical AI 엔지니어링 (ROS2 · Vision AI · VLA) 양성과정 수료 예정 (2026-06)
- **Cloud** — Microsoft Azure AZ-900 (2025), AZ-104 학습 중
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

**Infrastructure & Operations** — Linux · Windows · 네트워크(TCP/IP · DNS · VPN) · HA · DR · 가상화

**Data Platform** — Hadoop (HDFS · RBF · Hive · Impala · HBase · YARN) · Kafka · NiFi · ELK · Grafana · InfluxDB

**ML / MLOps** — XGBoost · LightGBM · MLflow · Random Forest · ST-GCN · YOLO · PyTorch · CUDA 12.8 · OpenCV · MediaPipe

**Robotics & Middleware** — ROS2 Jazzy · Nav2 · MoveIt2 · BehaviorTree.CPP 4.8 · Fast DDS · Zenoh

**Voice & LLM** — faster-whisper STT · Porcupine · Ollama · 한국어 자연어 제어

**Edge / IoT** — ESP32 · ESP32-CAM · AES 암호화 · TCP · Serial

**VLA & Imitation Learning** *(Research · In Progress)* — LeRobot 0.5 · ACT Policy · SmolVLA · Pi0

**Cloud** — Microsoft Azure (AZ-900 보유, AZ-104 학습 중)

**Languages & Dev Tools** — Python · C++ · Ubuntu · VS Code · Jupyter · Git

```text
Infrastructure       ████████████████████░  19y · ~18PB · 99.98% uptime
Data Platform        ████████████████████░  Hadoop · Kafka · NiFi · ELK
MLOps Pipeline       ███████████████░░░░░░  MLflow Level 1 적용 (예측 시스템)
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
**Home Care-Vision AI · 낙상 감지**

ST-GCN · Random Forest · YOLO v11 Pose · FastAPI

YOLO v11 Pose 키포인트 위에 정적·시계열 특징 추출 → RF vs ST-GCN 비교 분석.
정상·낙상 약 4.6:1 불균형 데이터에 언더샘플링 + 클래스 가중치 4가지 전략 비교.

**ST-GCN (Fine-tuned) 99.63% · Recall 99.40%** — RF (97.99% · Recall 94.30%) 대비 우위.
RF는 추론 속도 약 34× 빠름. PYSKL 전이학습 (약 56,000개 영상 사전학습 모델 기반).

</td>
<td width="50%" valign="top">

### [MoCa](https://github.com/skong097/moca)
**Cafe NPC Behavior Tree System**

ROS2 Jazzy · BT.CPP 4.8.3 · C++ · Nav2

5-stage engagement funnel for café service robots, grounded in published HRI research.
감정 인식 파이프라인(신뢰도 가중 EMA + 히스테리시스)로 노이즈에 둔감·부정 반응에 민감한 구조.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [smartgate](https://github.com/skong097/smartgate)
**얼굴 인식 + 제스처 인식 2-factor 인증**

Voice IoT 프로젝트의 보안 게이트.
설계 문서(`voice_iot_plan_v2.md`) 작성 + 핵심 구현 · 웹소켓 통신 일부.

</td>
<td width="50%" valign="top">

### [voice_iot_home](https://github.com/skong097/voice_iot_home)
**IoT 기반 스마트홈 컨트롤러**

얼굴 인증 + 웹소켓 통신 일부 설계·구현 (Voice IoT 1조).
ESP32 · ESP32-CAM 엣지 + 한국어 음성 제어.

</td>
</tr>
</table>

---

## Certifications

- **HP LINUX ASE** · **HP Master ASE** (High Availability) · **HP CSA** (HP-UX)
- **MCSE** · **MCDBA** · **OCP** (Oracle) · **SCSA** (Solaris)
- **ITIL Foundation** · **네트워크관리사 2급**
- **Microsoft Azure AZ-900** (2025) · AZ-104 학습 중
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
