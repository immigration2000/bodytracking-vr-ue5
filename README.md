<!-- Portfolio showcase — media only. Source code is not included in this repository. -->

<h1 align="center">Eris Project — VR Body-Tracking Experience</h1>
<p align="center"><b>Room-scale VR built in Unreal Engine 5.7 with real-time full-body & hand tracking.</b><br>
<sub>UE 5.7 기반 룸스케일 VR · 실시간 풀바디·핸드 트래킹 · OpenXR / Meta Quest</sub></p>

<p align="center">
  <img src="https://img.shields.io/badge/Unreal_Engine-5.7-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white">
  <img src="https://img.shields.io/badge/Blueprints-Visual_Scripting-1C1C1C?style=for-the-badge&logo=unrealengine&logoColor=white">
  <img src="https://img.shields.io/badge/OpenXR-VR-2C2C2C?style=for-the-badge">
  <img src="https://img.shields.io/badge/Meta_Quest-Hand_Tracking-0467DF?style=for-the-badge&logo=meta&logoColor=white">
  <img src="https://img.shields.io/badge/Room--Scale-VR-5A45FF?style=for-the-badge">
</p>

<p align="center">
  <img src="media/vr-hand-tracking.gif" alt="Real-time VR hand tracking — grabbing objects in a stylized night-water world" width="88%">
  <br><em>Real-time hand tracking — bare-hand grab interaction in room-scale VR</em>
</p>

---

## ⭐ Highlights

- 🕹️ **Real-time hand & body tracking** — bare-hand gestures and motion controllers drive
  natural interaction (grab, throw, manipulate) on Meta Quest via OpenXR.
- 🌌 **Atmospheric real-time world** — reflective water, dynamic night sky, and volumetric
  lighting create a striking, immersive stage.
- 🧩 **Blueprint-engineered VR systems** — motion-controller pawn, hand-tracking, grab
  mechanics, and cross-platform player-height calibration (Vive / Oculus / PSVR).

<sub>핸드·바디 트래킹 · 실시간 몰입형 월드 · 블루프린트 VR 시스템</sub>

---

## 🛠️ Tech Stack

| Area | Details |
|---|---|
| **Engine** | Unreal Engine 5.7.4 |
| **XR** | OpenXR · Meta Quest (Oculus) · room-scale |
| **Tracking** | Full-body + hand tracking, motion controllers |
| **Scripting** | Blueprints (visual scripting) |
| **Input** | Enhanced Input, hand-tracking & motion-controller pawns |
| **Rendering** | Real-time reflective water, dynamic sky, stylized lighting |

---

## 🧠 Engineering — Under the Hood

VR interaction is driven by a **MotionControllerPawn** Blueprint: a `VROrigin → Camera`
rig, per-hand controller & hand-tracking resolution, dynamic hand spawning, grab/release
logic, and a `DefaultPlayerHeight` calibration path for different headsets.

VR 상호작용은 **MotionControllerPawn** 블루프린트로 구동됩니다 — VR 오리진/카메라 리그, 좌·우 컨트롤러
및 핸드 트래킹 처리, 동적 핸드 스폰, Grab/Release 로직, 헤드셋별 플레이어 높이 보정을 포함합니다.

<p align="center">
  <img src="media/blueprint-vr-systems.gif" alt="Unreal Blueprint EventGraph — VR motion controller & hand-tracking systems" width="92%">
  <br><em>MotionControllerPawn EventGraph — hand-tracking & grab systems in Blueprints</em>
</p>

---

## 🌌 The World

<p align="center">
  <img src="media/vr-nightworld-tree.png" alt="Glowing tree over reflective black water" width="49%">
  <img src="media/vr-nightworld-water.png" alt="Wide reflective night-water environment" width="49%">
</p>

A moonlit water world — a luminous centerpiece tree, drifting platforms, and mirror-still
water, all rendered in real time for VR (달빛의 물의 세계 · 발광 오브젝트 · 실시간 반사).

---

## 🎬 Demo Videos

| | |
|:--:|:--:|
| [<img src="media/ue-editor-scene.png" width="380">](media/ue-editor-gameplay.mp4) | [<img src="media/blueprint-motioncontroller.png" width="380">](media/ue-blueprint-vr-systems.mp4) |
| **Editor & VR gameplay** — scene building + hand-tracking interaction | **Blueprint systems** — VR pawn & hand-tracking graphs |

<sub>Click a thumbnail to play the full video on GitHub.</sub>

---

## 👤 My Role

Solo developer — designed and built the experience end to end:

- **VR/XR development** — OpenXR setup, Meta Quest hand & body tracking, room-scale pawn.
- **Blueprint systems** — motion-controller pawn, grab mechanics, cross-headset calibration.
- **Real-time art & lighting** — reflective water, dynamic sky, stylized night mood.

<sub>1인 개발 · VR/XR · 블루프린트 시스템 · 실시간 아트/라이팅</sub>

---

## 📌 Notes

- This repository is a **portfolio showcase** — media and results only.
  **Project source code is not included.** (본 저장소는 포트폴리오 쇼케이스이며 프로젝트 소스는 비공개입니다.)
- Captured on Unreal Engine 5.7.4, OpenXR (Oculus) runtime.

---

<p align="center"><sub>© 2026 immigration2000 · Built with Unreal Engine 5.7</sub></p>
