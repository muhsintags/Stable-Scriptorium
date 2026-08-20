<div align="center">📜 Scriptorium

A modern digital library for sacred and classical texts

Read. Study. Compare. Preserve.

""Build" (https://img.shields.io/github/actions/workflow/status/muhsintags/Stable-Scriptorium/android.yml?branch=main&style=for-the-badge&logo=github)" (https://github.com/muhsintags/Stable-Scriptorium/actions)
""Release" (https://img.shields.io/github/v/release/muhsintags/Stable-Scriptorium?style=for-the-badge&logo=android)" (https://github.com/muhsintags/Stable-Scriptorium/releases)
""License" (https://img.shields.io/github/license/muhsintags/Stable-Scriptorium?style=for-the-badge)" (https://github.com/muhsintags/Stable-Scriptorium/blob/main/LICENSE)
""Kotlin" (https://img.shields.io/badge/Kotlin-2.x-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)" (https://kotlinlang.org/)
""Jetpack Compose" (https://img.shields.io/badge/Jetpack%20Compose-Material%203-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)" (https://developer.android.com/compose)

<br>Scriptorium is an Android application designed as a unified reading and study environment for major sacred and classical texts.

</div>---

✦ What is Scriptorium?

Scriptorium brings texts from different religious and classical traditions into one focused reading environment.

The project is built around a simple idea:

«A library should make the text the center of the experience.»

Instead of switching between multiple applications and websites, Scriptorium aims to provide a single place for reading, studying, searching and comparing texts.

Included collections

- 📖 Quran
- ✡️ Torah
- ✝️ Bible
- 📜 Sahih al-Bukhari
- 🕎 Talmud
- 🕉️ Bhagavad Gita
- 🌐 Translated and multilingual content where available

Scriptorium is intended as a study and reading tool, not as an authority on religious interpretation.

---

✨ Features

📚 Unified Library

Browse multiple sacred and classical collections from a single application.

📖 Focused Reader

A clean reading experience designed to keep unnecessary interface elements away from the text.

🔎 Search & Navigation

Quickly navigate through large collections and locate relevant passages.

🌐 Translation

Translation functionality allows texts to be studied across languages.

⚡ Offline-Friendly Architecture

Frequently accessed content can be stored locally, reducing the need to repeatedly fetch the same data.

Local persistence is handled through Room Database.

🎨 Modern Material 3 Interface

The interface is built with Jetpack Compose and Material 3, allowing the application to use a modern Android UI architecture.

☁️ Firebase Integration

The project includes Firebase services for application features such as authentication, Firestore and AI-related functionality.

🧪 Testing

The project includes unit testing, Android instrumentation testing and Compose UI testing infrastructure.

---

🏗️ Architecture

Scriptorium follows a modern Android architecture built around separation of concerns.

┌─────────────────────────────────────┐
│              UI Layer               │
│       Jetpack Compose + M3          │
├─────────────────────────────────────┤
│          Presentation Layer         │
│        ViewModels + State           │
├─────────────────────────────────────┤
│             Data Layer              │
│                                     │
│   ┌──────────┐    ┌─────────────┐  │
│   │   Room   │    │ Retrofit /  │  │
│   │ Database │    │   OkHttp    │  │
│   └──────────┘    └─────────────┘  │
│                                     │
├─────────────────────────────────────┤
│          External Services          │
│        Firebase / APIs / Data       │
└─────────────────────────────────────┘

The project uses an MVVM-oriented architecture with reactive state management.

---

🛠️ Technology Stack

Component| Technology
Language| Kotlin
UI| Jetpack Compose
Design System| Material 3
Architecture| MVVM-oriented
Local Database| Room
Networking| Retrofit + OkHttp
JSON| Moshi
Async| Kotlin Coroutines + Flow
Navigation| Navigation Compose
Images| Coil
Backend Services| Firebase
Dependency Injection / Processing| KSP
Testing| JUnit, Robolectric, Compose UI Tests
Screenshot Testing| Roborazzi
CI/CD| GitHub Actions
Development Environment| Android Studio / GitHub Codespaces

The current Android module targets SDK 36 and supports Android API 24 and newer.

---

📱 Platform Requirements

Android

Requirement| Version
Minimum Android| Android 7.0 / API 24
Target SDK| API 36
Compile SDK| API 36.1
Language| Kotlin
UI Toolkit| Jetpack Compose

---

🚀 Installation

Option 1 — Download a Release

Download the latest available APK from:

"GitHub Releases" (https://github.com/muhsintags/Stable-Scriptorium/releases)

Install the APK on an Android device running API 24 or newer.

«Development builds may be unstable. Use release builds for normal usage.»

---

💻 Build From Source

Clone the repository:

git clone https://github.com/muhsintags/Stable-Scriptorium.git
cd Stable-Scriptorium

Make the Gradle wrapper executable on Linux/macOS:

chmod +x gradlew

Build a debug APK:

./gradlew assembleDebug

The generated APK will normally be located under:

app/build/outputs/apk/debug/

Release Build

./gradlew assembleRelease

Release builds use the project's signing configuration and require the appropriate keystore credentials.

Never commit a private keystore, passwords or production secrets to Git.

---

☁️ GitHub Codespaces

Scriptorium can also be developed through GitHub Codespaces.

This makes it possible to work on the project without maintaining a complete Android development environment locally.

Typical workflow:

git clone https://github.com/muhsintags/Stable-Scriptorium.git
cd Stable-Scriptorium
./gradlew assembleDebug

---

🔐 Configuration & Secrets

The project uses environment-based configuration for sensitive values.

A ".env.example" file is provided as a template.

Create your local environment file:

cp .env.example .env

Then configure the required values locally.

Do not commit

.env
*.jks
*.keystore
private credentials
API keys
signing passwords

Production signing credentials should only exist in a secure local or CI environment.

---

🔄 CI/CD

GitHub Actions is used to automate project builds.

Push / Pull Request
        │
        ▼
   GitHub Actions
        │
        ├── Gradle setup
        ├── Dependency resolution
        ├── Build
        ├── Tests
        └── APK artifact

Workflow files are located in:

.github/workflows/

Build status:

"View GitHub Actions" (https://github.com/muhsintags/Stable-Scriptorium/actions)

---

🗂️ Project Structure

Stable-Scriptorium/
│
├── app/
│   └── src/
│       ├── main/
│       │   ├── java/
│       │   └── res/
│       ├── test/
│       └── androidTest/
│
├── gradle/
│   └── wrapper/
│
├── .github/
│   └── workflows/
│
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── .env.example
├── metadata.json
├── LICENSE
└── README.md

---

🧭 Project Goals

Scriptorium is being developed with several long-term goals:

- Create a unified digital library for sacred and classical literature.
- Make large text collections easier to explore.
- Provide a clean and distraction-free reading experience.
- Support multilingual study.
- Reduce dependence on constant internet connectivity.
- Build the application using modern Android technologies.
- Keep the project open to future collections and capabilities.

---

🗺️ Roadmap

The project is under active development.

Reading

- [x] Multi-collection library
- [x] Modern Compose interface
- [x] Local database infrastructure
- [x] Reader foundation
- [ ] Advanced reader customization
- [ ] Bookmarks
- [ ] Reading history
- [ ] Notes and annotations

Search

- [ ] Faster full-text search
- [ ] Advanced filtering
- [ ] Cross-collection search
- [ ] Search history
- [ ] Passage comparison

Translation

- [x] Translation infrastructure
- [ ] Improved multilingual support
- [ ] Side-by-side translations
- [ ] Translation comparison
- [ ] User-selectable translation sources

Offline

- [x] Local persistence infrastructure
- [ ] Complete offline collection packages
- [ ] Download manager
- [ ] Storage management
- [ ] Background synchronization

Personalization

- [ ] Themes
- [ ] Font controls
- [ ] Reading preferences
- [ ] Custom bookmarks
- [ ] Personal notes

---

🧪 Development

Run the available test suites with Gradle:

./gradlew test

For Android instrumentation tests:

./gradlew connectedAndroidTest

For a debug build:

./gradlew assembleDebug

For a release build:

./gradlew assembleRelease

---

🤝 Contributing

Contributions are welcome.

Basic workflow

git checkout -b feature/my-feature

Make your changes, test them, then commit:

git add .
git commit -m "Add my feature"

Push the branch:

git push origin feature/my-feature

Then open a Pull Request.

Before submitting a PR

- Keep changes focused.
- Follow the existing Kotlin and Compose structure.
- Avoid committing secrets.
- Test the application.
- Do not introduce unnecessary dependencies.
- Explain significant architectural changes.

---

📜 Texts & Sources

Scriptorium is a software project for accessing and studying texts.

The application does not claim ownership of the original religious or historical works.

Individual texts, translations, datasets and external services may have their own:

- copyrights
- licenses
- attribution requirements
- public-domain status
- usage restrictions

Always verify the license and provenance of a particular text or translation before redistributing it.

---

⚠️ Disclaimer

Scriptorium is a reading and research application.

It does not replace:

- religious scholarship
- academic research
- historical source criticism
- professional translation
- qualified religious guidance

Translations and digital editions can contain differences from other editions. When accuracy is critical, consult the relevant primary edition or authoritative scholarly source.

---

🔒 Privacy & Security

Scriptorium is designed with security and privacy in mind.

Sensitive credentials should remain outside the repository.

The project uses Firebase and other network services where required by application functionality. The exact data flow depends on the enabled features and service configuration.

Do not place personal API keys, authentication credentials or signing keys into source control.

---

📄 License

This project is licensed under the MIT License.

See ""LICENSE"" (./LICENSE) for the complete license text.

---

🔗 Links

- Repository: https://github.com/muhsintags/Stable-Scriptorium
- Releases: https://github.com/muhsintags/Stable-Scriptorium/releases
- Actions: https://github.com/muhsintags/Stable-Scriptorium/actions
- Issues: https://github.com/muhsintags/Stable-Scriptorium/issues

---

<div align="center">📜 Scriptorium

One library. Many traditions. One focused reading experience.

Built with Kotlin and Jetpack Compose.

</div>