# Communicator EX

<p align="center">
  <img src="https://img.shields.io/github/license/chernex/Communicator_EX?style=for-the-badge&color=2eb872" alt="License">
  <img src="https://img.shields.io/github/stars/chernex/Communicator_EX?style=for-the-badge&color=f4d160" alt="Stars">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue?style=for-the-badge" alt="Platforms">
  <img src="https://img.shields.io/badge/Architecture-Self--Hosted%20%7C%20P2P-orange?style=for-the-badge" alt="Architecture">
</p>

<p align="center">
  <strong>An open-source, high-performance real-time communication platform focused on secure voice, video, and ultra-low-latency desktop screen sharing.</strong>
</p>

<p align="center">
  🌐 <strong>Official Website:</strong> <a href="http://communicator-ex.ru/">communicator-ex.ru</a>
</p>

---

## 🖥️ Project Showcase

<p align="center">
  <img src="assets/screenshots/title windows 11 pc.png" width="32%" alt="Main Client UI" title="Main Client Interface">
  <img src="assets/screenshots/screen-sharing.png" width="32%" alt="1080p Screen Sharing" title="Ultra-Low Latency Screen Sharing">
  <img src="assets/screenshots/room call windows pc.png" width="32%" alt="Voice & Video Room" title="Voice & Video Conference Room">
</p>

<p align="center">
  <em>Application Interface: Standalone Client Dashboard | 1080p 60 FPS Screen Sharing | Low-Latency Call Infrastructure</em>
</p>

---

## 🎯 About & Core Philosophy

**Communicator EX** is a next-generation desktop communication environment engineered from the ground up to challenge heavy corporate alternatives. By combining a native-like desktop runtime with a robust Go-based WebRTC signaling ecosystem, the platform delivers enterprise-grade media transmission while maintaining absolute data ownership through self-hosted deployments.

### Key Highlights
* **High-FPS Media Capture:** Native desktop streaming supporting up to 1080p 60 FPS with hardware acceleration.
* **Privacy by Design:** Zero reliance on forced third-party cloud infrastructure for demo evaluation or core data routing.
* **AI-Ready Architecture:** Designed with modular pipelines to seamlessly integrate advanced LLMs and automated voice/text assistants directly into communication channels.

---

## 🛠️ Technology Stack

The project utilizes a modern, decoupled stack optimized for low resource consumption and massive throughput:

* **Frontend & Client Runtime:** Electron, React, HTML5, CSS3 (Modern component-driven UI with cross-platform optimization)
* **Real-Time Media Transport:** WebRTC protocol suite (Secure peer-to-peer and SFU routing)
* **Signaling & Media Backend:** Pion (High-performance Go-based WebRTC implementation)
* **Media Processing Core:** FFmpeg integration (On-the-fly hardware-accelerated encoding/decoding)
* **Environment Control:** Node.js (Robust backend toolchain and local environment orchestration)

---

## 📦 Distribution & Setup

Communicator EX is distributed as a standalone desktop binary (`.exe`, `.dmg`, `.AppImage`). You can download the pre-compiled standalone package directly via the **Releases** section on the right.

```bash
# Clone the repository
git clone [https://github.com/chernex/Communicator_EX.git](https://github.com/chernex/Communicator_EX.git)

# Navigate to the project directory
cd Communicator_EX
