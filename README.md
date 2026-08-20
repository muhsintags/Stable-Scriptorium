# 📜 Scriptorium

<p align="center">
  <img src="https://img.shields.io/github/actions/workflow/status/muhsintags/Stable-Scriptorium/android.yml?branch=main&style=for-the-badge&logo=github" alt="Build Status" />
  <img src="https://img.shields.io/github/license/muhsintags/Stable-Scriptorium?style=for-the-badge&color=blue" alt="License" />
  <img src="https://img.shields.io/badge/Kotlin-Native_Android-purple?style=for-the-badge&logo=kotlin" alt="Kotlin" />
  <img src="https://img.shields.io/badge/UI-Jetpack_Compose-green?style=for-the-badge&logo=android" alt="Jetpack Compose" />
</p>

<p align="center">
  <b>A personal digital library for sacred and classical texts.</b><br />
  Torah, Bible, Quran, Sahih al-Bukhari, Talmud, Bhagavad Gita, and integrated translation — all in one clean, offline-friendly app.
</p>

---

## 📸 Screenshots

> *Add screenshots of your app here to showcase your Material 3 UI design.*

| Home & Library | Text Reader | Offline Mode |
| :---: | :---: | :---: |
| _Screenshot 1_ | _Screenshot 2_ | _Screenshot 3_ |

---

## ✨ Features

* **📖 Sacred & Classical Texts:** Access the Torah, Bible, Quran, Sahih al-Bukhari, Talmud, and Bhagavad Gita from a single hub.
* **⚡ Offline First:** Content is fetched once and cached locally via **Room Database**. Read anywhere without an active internet connection.
* **🌐 Integrated Translation:** Instant Google Translate integration for seamless cross-language reading and study.
* **🎨 Modern Material 3 UI:** Built 100% with **Jetpack Compose** for a fluid, clean, and customizable interface.
* **☁️ Cloud Native Workflow:** Configured for seamless development using GitHub Codespaces — no heavy local setup required.

---

## 🛠️ Tech Stack & Architecture

This project follows modern Android development best practices and Clean Architecture principles (MVVM):

* **Language:** Kotlin
* **UI Framework:** Jetpack Compose + Material 3
* **Architecture:** Model-View-ViewModel (MVVM)
* **Local Data:** Room Database
* **Networking:** Retrofit + OkHttp
* **Concurrency:** Kotlin Coroutines & Flow
* **CI/CD:** GitHub Actions (Automated builds & release artifacts)
* **Environment:** GitHub Codespaces

---

## 🚀 Download & Installation

Every push to the `main` branch triggers an automated build via GitHub Actions.

| Channel | Description | Link |
| :--- | :--- | :--- |
| **Stable Release** | Official, signed production builds. | [Releases Page](https://github.com/muhsintags/Stable-Scriptorium/releases) |
| **Dev Builds** | Latest experimental features and fixes. | [GitHub Actions Artifacts](https://github.com/muhsintags/Stable-Scriptorium/actions) |

---

## 💻 Building Locally

You can build the project locally or directly inside **GitHub Codespaces**:

```bash
# Build Debug APK
./gradlew assembleDebug

# Build Release APK (requires local keystore configuration)
./gradlew assembleRelease
