# Zalith Launcher 2 — Unlocked Edition

<p align="center">
  <img src="[https://img.shields.io/github/v/release/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=7C4DFF&logo=github](https://img.shields.io/github/v/release/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=7C4DFF&logo=github)" alt="Release">
  <img src="[https://img.shields.io/github/downloads/dotseksdotseks/ZalithLauncher2/total?style=for-the-badge&color=B388FF&logo=github](https://img.shields.io/github/downloads/dotseksdotseks/ZalithLauncher2/total?style=for-the-badge&color=B388FF&logo=github)" alt="Downloads">
  <img src="[https://img.shields.io/github/repo-size/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=FF4081](https://img.shields.io/github/repo-size/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=FF4081)" alt="Repo Size">
  <img src="[https://img.shields.io/github/languages/top/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=00E676](https://img.shields.io/github/languages/top/dotseksdotseks/ZalithLauncher2?style=for-the-badge&color=00E676)" alt="Top Language">
</p>

---

## 📖 Overview
This repository is a specialized fork of **Zalith Launcher 2**, a modern Minecraft: Java Edition launcher for Android. While maintaining the high-performance **PojavLauncher** core and the sleek **Jetpack Compose** UI of the original project, this version focuses on removing regional and account-based restrictions to provide a more flexible user experience.

> [!IMPORTANT]
> This is an **Unofficial Modified Version**. It is not affiliated with the original ZalithLauncher team.

---

## ✨ Features & Enhancements
*   🔓 **Restriction Bypass:** Hardcoded logic to circumvent mandatory account checks for global users.
*   🌍 **Region Unlocked:** Removed limitations specific to non-China mainland regions.

---

## 📜 Licensing
This project is licensed under the **GNU General Public License v3 (GPL-3.0)**.  
In accordance with **Section 7** of the GPLv3:
1.  **Identification:** This version is clearly marked as "Unofficial" to distinguish it from the original software.
2.  **Attribution:** All original copyright notices and library licenses have been preserved.

---

## 🧬 Technical Modifications
The primary bypass was achieved by modifying the `AccountsManager.kt` logic to ensure the `isOffline` state remains `false` regardless of the environment.

```kotlin
// Example of the implemented logic bypass
val isOffline = false // Circumvents region and account limits
```

---
