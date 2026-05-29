<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=280&color=0:020617,50:1d4ed8,100:7c3aed&text=R36S%20Cloud%20Gaming&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AAA%20Gaming%20In%20Your%20Pocket&descAlignY=58"/>

<br>

<p align="center">
  <img src="https://img.shields.io/badge/R36S-Handheld-2563eb?style=for-the-badge">
  <img src="https://img.shields.io/badge/Cloud-Gaming-1d4ed8?style=for-the-badge">
  <img src="https://img.shields.io/badge/Moonlight-Streaming-7c3aed?style=for-the-badge">
  <img src="https://img.shields.io/badge/Sunshine-Host-f59e0b?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tailscale-VPN-0284c7?style=for-the-badge">
  <img src="https://img.shields.io/badge/LineageOS-Supported-059669?style=for-the-badge">
</p>

<h3>
Portable Cloud Gaming For The R36S
</h3>

<p>
Run your Steam games directly onto your R36S Handheld!
</p>

<br>

<img src="assets/gifs/WOW.gif" width="70%">

<br><br>

<img src="assets/gifs/tf2-heavy.gif" width="45%">

</div>

---

# Overview

The goal of this project is to transform the **R36S** into a portable cloud gaming machine capable of streaming demanding modern PC games using a cloud-hosted virtual machine.

Powered by:

* Google Cloud (Creates VM)
* Tailscale (Connects via VPN both Google Cloud VM and R36S Handheld)
* Sunshine (Streams The PC Image and Connects it)
* Moonlight (Allows you to control the Machine)

this setup allows you to play high-end PC titles directly from your handheld console almost anywhere.

---

# Features

<div align="center">

| Feature            | Description                      |
| :----------------- | :------------------------------- |
| AAA Streaming   | Play demanding PC games remotely |
| Low Latency      | Smooth Moonlight streaming       |
| Cloud Powered   | Google Cloud VM hosting          |
| Portable        | Full handheld gaming experience  |
| GPU Accelerated | NVIDIA Tesla T4                  |
| Customizable    | Easy to modify and improve       |

</div>

---

# Streaming Architecture

<div align="center">

<img src="assets/gifs/Python.gif" width="100%">

</div>

```mermaid id="rq3m7z"
flowchart LR
A[Google Cloud VM] --> B[Sunshine Host]
B --> C[Tailscale VPN]
C --> D[Moonlight Client]
D --> E[R36S Handheld]
```

---

# Technology Stack

| Component        | Purpose                          |
| :--------------- | :------------------------------- |
| **Google Cloud** | Hosts the gaming virtual machine |
| **Sunshine**     | Streams the desktop and games    |
| **Moonlight**    | Streaming client for R36S        |
| **Tailscale**    | Secure VPN networking            |

---

# Installation Guide

## Create A Google Cloud Notebook

Create a new notebook instance inside Google Cloud.

> Click **New Notebook**

---

##  Import The Notebook File

Download the `.ipynb` notebook:

```text id="7vlwqa"
https://drive.google.com/file/d/1TO3Is-qrXugqUVFbtxN86XQ_eFqNdIBq/view?usp=sharing
```

Then paste the notebook contents into your Google Colab environment.

---

## Start The Virtual Machine

Launch the VM and wait until the environment finishes loading.

<img src="assets/18.png" width="100%">

> The screenshot interface is currently in Spanish.

---

<div align="center">

<img src="assets/gifs/engineer.gif" width="45%">

</div>

---

# Requirements

Before starting the VM, install:

<div align="center">

| Application | Required |
| :---------- | :------: |
| Tailscale   |     ✅    |
| Sunshine    |     ✅    |

</div>

---

# Supported Operating Systems

| Status        | Operating System |
| :------------ | :--------------- |
| Supported   | LineageOS        |
| Unsupported | ArkOS            |
| Unsupported | DarkOS           |

---

# Cloud Specifications

<div align="center">


</div>

  |       GPU       |             CPU             |    RAM   | Operating System |
  | :-------------: | :-------------------------: | :------: | :--------------: |
  | NVIDIA Tesla T4 | Intel Xeon 2 Cores @ 2.0GHz | 12.67 GB |    Ubuntu LTS    |

<img src="assets/gifs/computer.gif" width="65%">
---

# Game Showcase

## DOOM Eternal

<img src="assets/4.jpeg" width="100%">

---

## Metal Gear Solid V: The Phantom Pain

<img src="assets/5.png" width="100%">

---

## Titanfall 2

<img src="assets/6.jpeg" width="100%">

<div align="center">

<img src="assets/gifs/tf2-heavy.gif" width="45%">

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

## Cyberpunk 2077

<img src="assets/cyberpunk2077.jpg" width="100%">

---

## Marvel's Spider-Man Remastered

<img src="assets/spiderman.jpg" width="100%">

---

## Elden Ring

<img src="assets/eldenringg.jpeg" width="100%">

<div align="center">

<img src="assets/gifs/tf2-spy.gif" width="45%">

</div>

---

## Red Dead Redemption 2

<img src="assets/rdr2.jpg" width="100%">

---

## Fallout 4

<img src="assets/fallout4.jpg" width="100%">

---

## Dying Light

<img src="assets/dyinglight.jpg" width="100%">

<div align="center">

<img src="assets/gifs/dyinglight.gif" width="55%">

</div>

---

## Halo Infinite

<img src="assets/haloinfinite.jpg" width="100%">

---

## Call Of Duty: Modern Warfare

<img src="assets/mw.jpg" width="100%">

---

## Half-Life 2

<img src="assets/hl2.jpg" width="100%">

---

## Fallout 76

<img src="assets/fallout76.jpg" width="100%">

---

## Hollow Knight (Android and PC)

<img src="assets/hollowknight.jpg" width="100%">

---

# Future Improvements

* Additional handheld support
* ArkOS compatibility
* Easier setup process
* Automatic deployment scripts
* Better latency optimization
* Steam Big Picture integration
* Remote launcher support
* Performance presets

---

# ⭐ Support The Project

<div align="center">

If you like this project, consider giving it a ⭐ on GitHub.

<br><br>

# Frequently Asked Questions (FAQ)
A: How can I play these games on my Handheld?
B: You will have to install Lineage OS on a separate SD Card or the one you own, also you need a wifi dongle and the moonlight and tailscale apk's, You can find them both on the internet.
A: Is the project safe?
B: Yes, the VM is created in Google Colab (Google Cloud) so there will be no major problem.
A: Are the APK's safe?
B: Yes, as long as you watch out from where you are downloading it.

<img src="assets/gifs/cat.gif" width="70%">

<br><br>

<img src="assets/gifs/star.gif" width="45%">

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=140&section=footer&color=0:020617,50:1d4ed8,100:7c3aed"/>

</div>
