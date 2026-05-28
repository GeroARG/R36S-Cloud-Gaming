<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=250&color=0:0f172a,50:1d4ed8,100:2563eb&text=R36S%20Cloud%20Gaming&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Portable%20AAA%20Gaming%20Powered%20By%20The%20Cloud&descAlignY=58"/>

<br>

<p align="center">
<img src="https://img.shields.io/badge/R36S-Handheld-2563eb?style=for-the-badge">
<img src="https://img.shields.io/badge/Cloud-Gaming-1d4ed8?style=for-the-badge">
<img src="https://img.shields.io/badge/Moonlight-Streaming-7c3aed?style=for-the-badge">
<img src="https://img.shields.io/badge/Tailscale-VPN-0284c7?style=for-the-badge">
<img src="https://img.shields.io/badge/LineageOS-Supported-059669?style=for-the-badge">
</p>

<h3>
Portable AAA Gaming On Your R36S
</h3>

<p>
Stream demanding PC games directly from the cloud with low latency and high performance.
</p>

<br>

<img src="https://media.tenor.com/7XqO4-zSp3gAAAAC/tf2-team-fortress2.gif" width="65%">

</div>

---

# 📖 Overview

The goal of this project is to transform the **R36S** into a portable cloud gaming device capable of running modern AAA PC games through cloud streaming technology.

Using:

* ☁️ Google Cloud
* 🌐 Tailscale
* 🎥 Sunshine
* 📱 Moonlight

the R36S can stream games such as:

* GTA V
* DOOM Eternal
* Titanfall 2
* Wolfenstein II
* Resident Evil 2 Remake
* Forza Horizon 4

---

# ⚡ Architecture

<div align="center">

```mermaid id="6i3b9j"
flowchart LR
A[Google Cloud VM] --> B[Sunshine Host]
B --> C[Tailscale Network]
C --> D[Moonlight Client]
D --> E[R36S Handheld]
```

</div>

---

# 🛠 Technology Stack

| Component        | Purpose                  |
| :--------------- | :----------------------- |
| **Google Cloud** | Virtual machine hosting  |
| **Sunshine**     | Game streaming host      |
| **Moonlight**    | Streaming client         |
| **Tailscale**    | Secure remote networking |

---

# ⚙️ Installation Guide

## 1️⃣ Create A Google Cloud Notebook

Create a new notebook instance inside Google Cloud.

> Click **New Notebook**

---

## 2️⃣ Import The Notebook File

Download the provided `.ipynb` notebook:

```text id="jlwm7m"
https://drive.google.com/file/d/1TO3Is-qrXugqUVFbtxN86XQ_eFqNdIBq/view?usp=sharing
```

Paste the notebook contents into your Google Colab environment.

---

## 3️⃣ Start The Virtual Machine

Launch the VM and wait until everything finishes loading.

<img src="assets/18.png" width="100%">

> The screenshot interface is currently in Spanish.

---

<div align="center">

<img src="https://media.tenor.com/2bSx4Wzt8WQAAAAC/tf2-spy.gif" width="60%">

</div>

---

# ⚠️ Requirements

Before starting the VM, install:

* Tailscale
* Sunshine

### Supported Operating Systems

| Status        | Operating System |
| :------------ | :--------------- |
| ✅ Supported   | LineageOS        |
| ❌ Unsupported | ArkOS            |
| ❌ Unsupported | DarkOS           |

---

# 💻 Cloud Machine Specifications

<div align="center">

|       GPU       |             CPU             |    RAM   | Operating System |
| :-------------: | :-------------------------: | :------: | :--------------: |
| NVIDIA Tesla T4 | Intel Xeon 2 Cores @ 2.0GHz | 12.67 GB |    Tiny10 LTS    |

</div>

---

# 🎮 Game Showcase

## DOOM Eternal

<img src="assets/4.jpeg" width="100%">

---

## Metal Gear Solid V: The Phantom Pain

<img src="assets/5.png" width="100%">

---

## Titanfall 2

<img src="assets/6.jpeg" width="100%">

---

<div align="center">

<img src="https://media.tenor.com/6sJ7Q6K9n9AAAAAC/tf2-heavy.gif" width="60%">

</div>

---

## Wolfenstein II: The New Colossus

<img src="assets/7.jpeg" width="100%">

---

## Sniper Elite 4

<img src="assets/8.jpeg" width="100%">

---

## Mad Max

<img src="assets/10.jpeg" width="100%">

---

## Batman: Arkham Knight

<img src="assets/9.jpeg" width="100%">

---

## Rise of the Tomb Raider

<img src="assets/11.jpeg" width="100%">

---

<div align="center">

<img src="https://media.tenor.com/kWJzL9XbLJ0AAAAC/tf2-engineer.gif" width="55%">

</div>

---

## Grand Theft Auto V

<img src="assets/3.png" width="100%">

---

## Alien: Isolation

<img src="assets/12.jpeg" width="100%">

---

## Resident Evil 2 Remake

<img src="assets/13.jpeg" width="100%">

---

## Devil May Cry 5

<img src="assets/14.jpeg" width="100%">

---

## BioShock Infinite

<img src="assets/15.jpeg" width="100%">

---

## Hades

<img src="assets/16.jpeg" width="100%">

---

## Forza Horizon 4

<img src="assets/17.jpeg" width="100%">

---

<div align="center">

<img src="https://media.tenor.com/HN5ovTjB9S8AAAAC/team-fortress2-soldier.gif" width="65%">

</div>

---

# 🚧 Future Improvements

* More handheld support
* ArkOS compatibility
* Simplified deployment scripts
* Better streaming optimization
* Automatic setup process

---

<div align="center">

### ⭐ If you like this project, consider giving it a star.

<br>

<img src="https://media.tenor.com/Bpnw5Rpw4x4AAAAC/team-fortress2.gif" width="70%">

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:0f172a,50:1d4ed8,100:2563eb"/>

</div>
