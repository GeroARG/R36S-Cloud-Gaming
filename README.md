<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0f172a,50:1d4ed8,100:2563eb&text=R36S%20Cloud%20Gaming&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Portable%20AAA%20Gaming%20Powered%20By%20The%20Cloud&descAlignY=58"/>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-R36S-2563eb?style=for-the-badge">
  <img src="https://img.shields.io/badge/OS-LineageOS-059669?style=for-the-badge">
  <img src="https://img.shields.io/badge/Streaming-Moonlight-7c3aed?style=for-the-badge">
  <img src="https://img.shields.io/badge/Host-Sunshine-f59e0b?style=for-the-badge">
  <img src="https://img.shields.io/badge/Cloud-Google_Cloud-0284c7?style=for-the-badge">
</p>

<h3>
🎮 Portable AAA Gaming On Your R36S
</h3>

<p>
Transform your handheld console into a cloud gaming machine capable of streaming modern PC games with low latency and high performance.
</p>

<br>

<img src="assets/gifs/WOW.gif" width="65%">

</div>

---

# 📚 Table Of Contents

* Overview
* Features
* Streaming Architecture
* Technology Stack
* Installation Guide
* Requirements
* Supported Operating Systems
* Cloud Specifications
* Game Showcase
* Future Improvements

---

# 📖 Overview

This project aims to turn the **R36S** into a fully functional cloud gaming handheld using a remote virtual machine and game streaming technologies.

Using:

* ☁️ Google Cloud
* 🌐 Tailscale
* 🎥 Sunshine
* 📱 Moonlight

you can remotely stream demanding AAA PC games directly onto your handheld console.

Supported games include:

* Grand Theft Auto V
* DOOM Eternal
* Titanfall 2
* Wolfenstein II
* Resident Evil 2 Remake
* Forza Horizon 4
* Batman: Arkham Knight
* Devil May Cry 5

---

# ✨ Features

✅ Low latency game streaming
✅ Portable AAA gaming experience
✅ Cloud-powered virtual machine
✅ Optimized for LineageOS
✅ Tesla T4 GPU acceleration
✅ Easy deployment using Google Colab

---

# ⚡ Streaming Architecture

<div align="center">

<img src="assets/gifs/Python.gif" width="100%">

</div>

```mermaid id="dr5f3g"
flowchart LR
A[Google Cloud VM] --> B[Sunshine Host]
B --> C[Tailscale VPN]
C --> D[Moonlight Client]
D --> E[R36S Handheld]
```

---

# 🛠 Technology Stack

| Component        | Purpose                          |
| :--------------- | :------------------------------- |
| **Google Cloud** | Hosts the gaming virtual machine |
| **Sunshine**     | Streams the desktop and games    |
| **Moonlight**    | Streaming client for the R36S    |
| **Tailscale**    | Secure VPN networking            |

---

# ⚙️ Installation Guide

## 1️⃣ Create A Google Cloud Notebook

Create a new notebook instance inside Google Cloud.

After opening the dashboard, click:

> **New Notebook**

---

## 2️⃣ Import The Notebook File

Download the provided `.ipynb` notebook:

```text id="wyyfpk"
https://drive.google.com/file/d/1TO3Is-qrXugqUVFbtxN86XQ_eFqNdIBq/view?usp=sharing
```

Then paste the notebook contents into your Google Colab environment.

---

## 3️⃣ Start The Virtual Machine

Launch the virtual machine and wait until the environment finishes loading.

<img src="assets/18.png" width="100%">

> Note: The screenshot interface is currently in Spanish.

---

<div align="center">

<img src="assets/gifs/engineer.gif" width="50%">

</div>

---

# ⚠️ Requirements

Before starting the VM, install the following applications:

| Application | Required |
| :---------- | :------: |
| Tailscale   |     ✅    |
| Sunshine    |     ✅    |

---

# 📱 Supported Operating Systems

| Status        | Operating System |
| :------------ | :--------------- |
| ✅ Supported   | LineageOS        |
| ❌ Unsupported | ArkOS            |
| ❌ Unsupported | DarkOS           |

---

# 💻 Cloud Machine Specifications

<div align="center">

<img src="assets/gifs/computer.gif" width="60%">

</div>

|       GPU       |             CPU             |    RAM   | Operating System |
| :-------------: | :-------------------------: | :------: | :--------------: |
| NVIDIA Tesla T4 | Intel Xeon 2 Cores @ 2.0GHz | 12.67 GB |    Tiny10 LTS    |

---

# 🎮 Game Showcase

## 🔥 DOOM Eternal

<img src="assets/4.jpeg" width="100%">

---

## ⚔️ Metal Gear Solid V: The Phantom Pain

<img src="assets/5.png" width="100%">

---

## 🤖 Titanfall 2

<img src="assets/6.jpeg" width="100%">

<div align="center">

<img src="assets/gifs/tf2-heavy.gif" width="45%">

</div>

---

## 🐺 Wolfenstein II: The New Colossus

<img src="assets/7.jpeg" width="100%">

---

## 🎯 Sniper Elite 4

<img src="assets/8.jpeg" width="100%">

---

## 🚗 Mad Max

<img src="assets/10.jpeg" width="100%">

---

## 🦇 Batman: Arkham Knight

<img src="assets/9.jpeg" width="100%">

---

## 🏹 Rise of the Tomb Raider

<img src="assets/11.jpeg" width="100%">

---

## 🚓 Grand Theft Auto V

<img src="assets/3.png" width="100%">

---

## 👽 Alien: Isolation

<img src="assets/12.jpeg" width="100%">

---

## 🧟 Resident Evil 2 Remake

<img src="assets/13.jpeg" width="100%">

---

## ⚔️ Devil May Cry 5

<img src="assets/14.jpeg" width="100%">

---

## 🌊 BioShock Infinite

<img src="assets/15.jpeg" width="100%">

---

## 🔥 Hades

<img src="assets/16.jpeg" width="100%">

---

## 🏎️ Forza Horizon 4

<img src="assets/17.jpeg" width="100%">

---

<div align="center">

<img src="assets/gifs/tf2-spy.gif" width="45%">

</div>

---

# 🚧 Future Improvements

* Additional handheld support
* ArkOS compatibility
* Easier setup process
* Better streaming optimization
* Automatic deployment scripts
* Custom launcher support

---

# ⭐ Support The Project

If you enjoy this project, consider giving it a star on GitHub.

<div align="center">

<br>

<img src="assets/gifs/star.gif" width="70%">

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0f172a,50:1d4ed8,100:2563eb"/>

</div>
