<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22314E,100:0A7CFF&height=200&section=header&text=Stephen%20Kong&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Robotics%20Engineer%20%C2%B7%20ROS2%20%C2%B7%20Vision%20AI&descSize=18&descAlignY=60" width="100%"/>

### 공국진 (Stephen Kong) · `skong097`
**skong097 @ gmail.com**

> Building autonomous service robots — from BT-driven NPCs to bimanual manipulation.

[![Blog]([https://img.shields.io/badge/Blog-PinkLAB-FF1493?style=for-the-badge&logo=rss&logoColor=white](https://skong097.github.io/))](https://skong097.github.io/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:skong097@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=skong097&style=flat-square&color=0A7CFF)

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

##  Tech Stack

<div align="center">

### Robotics & Middleware
![ROS2](https://img.shields.io/badge/ROS2_Jazzy-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-3B7DDD?style=for-the-badge)
![MoveIt2](https://img.shields.io/badge/MoveIt2-0A7CFF?style=for-the-badge)
![BehaviorTree.CPP](https://img.shields.io/badge/BT.CPP_4.8-FF6F00?style=for-the-badge)
![Fast DDS](https://img.shields.io/badge/Fast_DDS-005571?style=for-the-badge)
![Zenoh](https://img.shields.io/badge/Zenoh-6A1B9A?style=for-the-badge)

### AI / ML / Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA_12.8-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![LeRobot](https://img.shields.io/badge/LeRobot_0.5-FFD21E?style=for-the-badge)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=for-the-badge)

### Languages & Dev Tools
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## GitHub Stats

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=skong097&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=skong097&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=skong097&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=skong097&theme=tokyo-night&hide_border=true&area=true)

</div>

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

## 📈 Engineering Footprint

```text
Robotics Stack       ████████████████████░  ROS2 · Nav2 · MoveIt2 · BT.CPP
AI / ML              ███████████████████░░  PyTorch · LeRobot · ACT · ST-GCN
Vision AI            ████████████████████░  OpenCV · YOLO · MediaPipe
AIOps / MLOps        ██████████████░░░░░░░  Pipeline · Training Orchestration
Robot Security       ████████████░░░░░░░░░  JWT · HMAC · NIST SP800-213
```

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
