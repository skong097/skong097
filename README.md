<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22314E,100:0A7CFF&height=220&section=header&text=Engineering%20Robots%20That%20Earn%20Trust&fontSize=38&fontColor=ffffff&fontAlignY=34&desc=%E2%80%9C%EC%8B%A0%EB%A2%B0%EB%B0%9B%EB%8A%94%20%EB%A1%9C%EB%B4%87%EC%9D%84%20%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4%E2%80%9D&descSize=18&descAlignY=58" width="100%"/>

### 공국진 (Stephen Kong) : **skong097 @ gmail.com**

> Building autonomous service robots · ROS2 · Vision AI

[![Blog](https://img.shields.io/badge/Blog-Stephen's_Robotics_Lab-5eead4?style=for-the-badge&logo=githubpages&logoColor=5eead4&labelColor=0a0e1a)](https://skong097.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:skong097@gmail.com)


</div>

---

##  About Me

ROS2 기반 자율 서비스 로봇과 Vision AI 시스템을 설계·개발하는 로보틱스 엔지니어입니다.
Behavior Tree 기반의 상호작용형 NPC, 모바일 매니퓰레이터, AIOps/MLOps 파이프라인을 주로 다룹니다.

-  **Currently building** Behavior Tree 기반 카페 NPC 솔리시테이션 시스템 (MoCa)
-  **Researching** VLA-class policies (SmolVLA, Pi0) for bimanual manipulation
-  **Working at** — solo developer across concurrent robotics projects
-  **Blogging weekly** on robotics, ROS2, and Vision AI

---

## Featured Project

<div align="center">

###  MoCa — Cafe NPC Solicitation System

**ROS2 Jazzy workspace integrating a Behavior Tree–driven engagement funnel for service robots.**

</div>

A 5-stage engagement funnel (`IDLE → APPROACH → ICEBREAK → MINIGAME → OFFER → LEAD-IN`)
grounded in a 6-layer academic framework (Isla 2005, Russell 1980, Salichs 2014, Castro-González 2016, Marzinotto 2014, Iovino 2022).

| Component | Status | Tech |
|-----------|--------|------|
| BT Node Headers (7 nodes) | ✅ Complete | C++ / BehaviorTree.CPP 4.8.3 |
| `bt_executor` + XML + Launch | ✅ Complete | ROS2 Jazzy |
| Tick sequence verification | ✅ Verified | rclcpp |
| Nav2 Action Client integration | 🚧 In progress | Nav2 |
| 6 dobi_npc packages | ✅ Scaffolded | C++ / Python |

```
ROS_DOMAIN_ID=22  ·  BehaviorTree.CPP 4.8.3  ·  Phase 1 W2
```

---

## Tech Stack

**Robotics & Middleware** — ROS2 Jazzy · Nav2 · MoveIt2 · BehaviorTree.CPP 4.8 · Fast DDS · Zenoh

**AI / ML / Vision** — PyTorch · CUDA 12.8 · LeRobot 0.5 · OpenCV · YOLO · MediaPipe · ST-GCN · Random Forest · XGBoost · LightGBM

**Voice & LLM** — faster-whisper STT · Porcupine · Ollama · 한국어 자연어 제어

**Edge / IoT** — ESP32 · ESP32-CAM · AES 암호화 · TCP · Serial

**VLA & Imitation Learning** *(Research · Project in Progress)* — LeRobot 0.5 · ACT Policy · SmolVLA · Pi0 · CUDA 12.8

**Languages & Dev Tools** — Python · C++ · Ubuntu · VS Code · Jupyter · Git

```text
Robotics Stack       ████████████████████░  ROS2 · Nav2 · MoveIt2 · BT.CPP
AI / ML              ███████████████████░░  PyTorch · LeRobot · ACT · ST-GCN
Vision AI            ████████████████████░  OpenCV · YOLO · MediaPipe
AIOps / MLOps        ██████████████░░░░░░░  Pipeline · Training Orchestration
Robot Security       ████████████░░░░░░░░░  JWT · HMAC · NIST SP800-213
```

---

## Selected Projects

<table>
<tr>
<td width="50%" valign="top">

### [MoCa](https://github.com/skong097/moca)
**Cafe NPC Behavior Tree System**

ROS2 Jazzy · BT.CPP 4.8.3 · C++ · Nav2

5-stage engagement funnel for café service robots, grounded in published HRI research.

</td>
<td width="50%" valign="top">

###  Robot Catering Service
**Autonomous Barista Robot**

Vic Pinky Pro · OMX 4-DOF Arm · ACT Policy

Full-stack café robot with melamine tray, vision-anchored pick-and-place, and GEFA/GEVA guest analysis.

</td>
</tr>
<tr>
<td width="50%" valign="top">

###  [vision_ai](https://github.com/skong097/vision_ai)
**Home Safe Solution**

ST-GCN · Random Forest · FastAPI

Fall detection pipeline: RF 93.19% (frame-level), Fine-tuned ST-GCN 91.89% (temporal).

</td>
<td width="50%" valign="top">

###  PlayWait
**B2B2C Vision AI Game Platform**

MediaPipe · YOLO · Real-time

10-week roadmap of vision-AI mini-games for café/restaurant waiting areas.

</td>
</tr>
</table>

---

##  Latest from the Blog

<!-- BLOG-POST-LIST:START -->
<!-- Auto-populated via gautamkrishnar/blog-post-workflow GitHub Action -->
<!-- BLOG-POST-LIST:END -->

> Maintaining a rolling cycle of ~10 posts (5 published / 5 in reserve) each week on robotics & AI.

---

<div align="center">

###  Let's Connect

Open to collaboration on **ROS2 service robotics**, **VLA policies**, and **vision-AI HRI** projects.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A7CFF,100:22314E&height=100&section=footer" width="100%"/>

</div>
