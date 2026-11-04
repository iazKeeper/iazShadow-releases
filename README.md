# iazShadow — The Invisible Meeting Assistant

[![Latest Release](https://img.shields.io/github/v/release/iazKeeper/iazShadow-releases?include_prereleases&style=flat-square)](https://github.com/iazKeeper/iazShadow-releases/releases/latest)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(x64)-blue?style=flat-square)](https://iazshadow.macroera.ru/download)
[![License](https://img.shields.io/badge/license-Freeware%20%2F%20EULA-green?style=flat-square)](https://github.com/iazKeeper/iazShadow-releases/blob/main/LICENSE.txt)
[![Support on Boosty](https://img.shields.io/badge/Support-Boosty-orange?style=flat-square)](https://boosty.to/iaz)

> **iazShadow** — the invisible secretary for your meetings. Live speech-to-text, speaker diarization, and overlap resolution running 100% locally on Windows. No cloud, no bots, zero telemetry.

---

## Key Highlights

- **100% Offline & Private:** Transcription, speaker separation, and storage run entirely on your local CPU. Your audio and conversations never leave your computer.
- **No Bots in the Call:** Works invisibly in the background by listening to Windows audio endpoints (WASAPI). No virtual participants or recording bots join the conference.
- **Universal Compatibility:** Works with any meeting platform — Yandex Telemost, Zoom, Microsoft Teams, Telegram, Google Meet, VK Calls, and browser calls.
- **Real-Time Display:** Text appears on screen seconds after words are spoken.
- **Post-Call Speaker Diarization:** Automatically groups utterances by voice ("Speaker 1", "Speaker 2"). Supports meeting room scenarios with multiple people sharing one microphone.
- **Overlapping Speech Resolution:** Distinguishes simultaneous speech and interruptions using local speech separation neural models.
- **Zero Telemetry:** The application contains no tracking or analytics SDKs. Network access is strictly restricted to user-initiated model downloads and signed application updates.

---

## Downloads

Download the latest version from the **[Releases](https://github.com/iazKeeper/iazShadow-releases/releases/latest)** section.

For each release, the following packages are provided:

| Package | Description |
| --- | --- |
| `iazShadow-<version>-win-x64-ru-RU.msi` | Windows Installer with Russian user interface. Installed per-user (no administrator privileges required). |
| `iazShadow-<version>-win-x64-en-US.msi` | Windows Installer with English user interface. Installed per-user. |
| `iazshadow-update.json` | Cryptographically signed release manifest with SHA-256 checksums for automatic updates. |

### System Requirements

- **Operating System:** Windows 10 (version 1809 or higher) / Windows 11 (64-bit x64).
- **CPU:** Modern 4+ core x64 processor (Intel Core i5/i7/i9 8th Gen+ or AMD Ryzen 3000+ recommended).
- **RAM:** 8 GB minimum (16 GB recommended when running overlap separation models).
- **Disk Space:** ~500 MB for application, ~1–2 GB for local neural models.

---

## Installation & First Run

1. Download `iazShadow-<version>-win-x64-ru-RU.msi` (or `en-US.msi`).
2. Run the installer. It installs the application into your user profile (`%LOCALAPPDATA%\Programs\iazShadow`).
3. Follow the first-run wizard to select audio devices and download speech recognition models.

---

## Verification & Integrity

All official release manifests (`iazshadow-update.json`) are cryptographically signed using **ECDSA P-256 (SHA-256)** by the publisher keys. The application validates package sizes, SHA-256 digests, and manifest signatures before installing any updates.

---

## License

iazShadow is proprietary freeware distributed under the [iazShadow End User License Agreement (EULA)](LICENSE.txt). Free for both personal and commercial use in this version.

---

## Support the Project

iazShadow is free, offline, and privacy-focused, with no ads and no subscription. If it saves you time, you can support its independent development on **[Boosty](https://boosty.to/iaz)** or via **[CloudTips](https://pay.cloudtips.ru/p/7913fd09)**.

Your support helps cover code-signing certificates (to eliminate Windows SmartScreen warnings) and server infrastructure, and accelerates the release of offline meeting summaries and Q&A chat.

---

## Links

- **Website:** [https://iazshadow.macroera.ru](https://iazshadow.macroera.ru)
- **Direct Downloads:** [https://iazshadow.macroera.ru/download](https://iazshadow.macroera.ru/download)
- **Privacy Policy:** [https://iazshadow.macroera.ru/privacy](https://iazshadow.macroera.ru/privacy)
- **Issues & Bug Reports:** [GitHub Issues](https://github.com/iazKeeper/iazShadow-releases/issues)

