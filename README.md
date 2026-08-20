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
<div align="center">

  # 📜 Scriptorium
  
  <p align="center">
    <b>A personal, cross-tradition digital library for sacred and classical texts.</b><br />
    <i>Torah • Bible • Quran • Sahih al-Bukhari • Talmud • Bhagavad Gita</i>
  </p>

  <!-- Animated Typing Header -->
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=F7B267&center=true&vCenter=true&width=500&lines=Read+Scripture+Without+Clutter;100%25+Offline+via+Room+Database;Built+with+Jetpack+Compose+%26+M3;Integrated+Google+Translation" alt="Typing SVG" />
  </a>

  <br /><br />

  <!-- Dynamic Badges -->
  <a href="https://github.com/muhsintags/Stable-Scriptorium/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/muhsintags/Stable-Scriptorium/android.yml?branch=main&style=for-the-badge&logo=github&logoColor=white&color=238636" alt="Build Status" />
  </a>
  <a href="https://github.com/muhsintags/Stable-Scriptorium/releases">
    <img src="https://img.shields.io/github/v/release/muhsintags/Stable-Scriptorium?style=for-the-badge&logo=android&logoColor=white&color=8957E5" alt="Latest Release" />
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge&logo=open-source-initiative&logoColor=white" alt="License" />
  </a>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-db036b00-a547-11eb-9e77-02375b581367.gif" width="100%" />

## 🌟 Key Features

<table>
  <tr>
    <td width="50%">
      <h3>📖 Sacred Texts Hub</h3>
      <p>Access full offline texts for Torah, Bible, Quran, Sahih al-Bukhari, Talmud, and Bhagavad Gita in a single clean interface.</p>
    </td>
    <td width="50%">
      <h3>⚡ Offline-First Architecture</h3>
      <p>Fetch once, read anywhere. All scriptures are cached locally using <b>Room Database</b> for zero latency and offline reading.</p>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🌐 Real-time Translation</h3>
      <p>Integrated Google Translate support enables multi-language study and cross-translation comparison effortlessly.</p>
    </td>
    <td width="50%">
      <h3>🎨 Modern Android UI</h3>
      <p>Built 100% with <b>Jetpack Compose</b> and <b>Material 3</b> guidelines for a responsive, clean, and customizable aesthetic.</p>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack & Architecture

<div align="center">

| Layer | Technology |
| :--- | :--- |
| **Language** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) |
| **UI Framework** | ![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=flat-square&logo=android&logoColor=white) + Material 3 |
| **Architecture** | Model-View-ViewModel (MVVM) |
| **Database** | Room Persistent Library |
| **Networking** | Retrofit + OkHttp |
| **Async & Flow** | Kotlin Coroutines |
| **CI/CD Pipeline** | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Cloud Dev** | ![GitHub Codespaces](https://img.shields.io/badge/Codespaces-181717?style=flat-square&logo=github&logoColor=white) |

</div>

---

## 🚀 Download & Installation

┌────────────────────────────────────────────────────────────────────────┐
│  Automated GitHub Actions Build System                                  │
│  ├── Main Branch Commit ➔ Trigger CI Pipeline                          │
│  └── Generate Signed APK / Debug Artifacts Automatically               │
└────────────────────────────────────────────────────────────────────────┘
</details>
​🗺️ Project Roadmap
​[x] Initial release & core scriptures integration
​[ ] v2.0 Expansion: Add Guru Granth Sahib, Book of Mormon, and Tripitaka / Sutta
​[ ] Commentary Engine: Add Turkish commentary/notes layer for texts
​[ ] Distribution: Publish to APKPure and prepare Google Play submission
​[ ] Optimization: Cleanup unused Firebase dependencies
​🤝 Contributing & Community
​<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%" />
​Although this is a personal passion project, feedback, suggestions, and issue reports are always appreciated!
​💡 Ideas for Your Own Fork:
​🏛️ Philosophy Library: Adapt the core code to host Stoic, Confucian, or Classical philosophy texts.
​🌐 Localization: Add native human translations for your local language.
​⚡ Comparative Reader: Build a side-by-side comparative mode for different scriptures.
​🤖 Built With AI Assistance
​<details>
<summary><b>View AI Collaborators</b></summary>
<br />
​This project was crafted with technical guidance, debugging, and workflow optimization from:
​Claude (Anthropic)
​ChatGPT (OpenAI)
​Google AI Studio / Gemini
​</details>
​<div align="center">
​<sub>Licensed under the MIT License • Built with ☕ and GitHub Actions</sub>
​</div>