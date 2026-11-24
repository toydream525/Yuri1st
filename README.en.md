<div align="center">

<img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher_foreground.png" width="96" height="96" alt="Yuri1st App Icon" />

# Yuri1st · Bangumi Yuri Catalog

**An open-source Android browser for Bangumi yuri & subtext-yuri anime, manga, light novels, and games**

<p>
  <a href="./README.md">简体中文</a> &nbsp;|&nbsp; <strong>English</strong>
</p>

<p>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><img src="https://img.shields.io/github/v/release/toydream525/Yuri1st?display_name=tag&sort=semver&style=flat-square" alt="Latest Release" /></a>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84.svg?style=flat-square&logo=android&logoColor=white" alt="Android 8.0+" /></a>
  <a href="https://github.com/toydream525/Yuri1st/actions/workflows/build-apk.yml"><img src="https://img.shields.io/github/actions/workflow/status/toydream525/Yuri1st/build-apk.yml?style=flat-square&label=CI" alt="CI Build" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-9a3c72.svg?style=flat-square" alt="License: MIT" /></a>
  <a href="https://yuriaqua.com/Yuri1st/"><img src="https://img.shields.io/badge/Website-yuriaqua.com-9a3c72.svg?style=flat-square" alt="Website" /></a>
</p>

<p>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><strong>⬇️ Download Latest APK</strong></a> &nbsp;·&nbsp;
  <a href="https://yuriaqua.com/Yuri1st/">🌐 Website</a> &nbsp;·&nbsp;
  <a href="./docs/FEATURES.md">📖 Features (CN)</a> &nbsp;·&nbsp;
  <a href="./CHANGELOG.md">📝 Changelog</a>
</p>

</div>

---

## ✨ Overview

**Yuri1st** brings together Bangumi-indexed anime, manga, light novels, and games in a local-first Android app with multi-layout browsing, advanced filtering, favorites, blocklists, and **Bangumi collection tracking**. Optional **AI yuri-tendency analysis** helps assist discovery and is always for reference only.

> [!NOTE]
> **Data Source:** Catalog metadata comes from the [Bangumi](https://bgm.tv/) public API and community tags. Entries are indexed strictly by exact `百合` / `轻百合` tags—not an official Bangumi endorsement, and tag accuracy is not guaranteed.

---

## 🚀 Key Features

| Capability | Details |
| :--- | :--- |
| **📚 Dedicated Catalog** | Browse anime, manga, light novels, and games separately with local search, Bangumi URL/ID import, pagination, and basic offline entries |
| **🎛️ Tri-State Layout & Filters** | Cycle between List, 2-Column Cover, and 4-Column Dense Grid; filter by category, year, rating count, AI/manual tags, and inverted exclusion |
| **🤖 AI Yuri-Tendency Analysis** | Uses your own OpenAI-compatible API endpoint to classify Strong Yuri / Subtext / Non-Yuri with natural-language preferences and manual overrides (home feed only badges Non-Yuri) |
| **✅ Bangumi Collection Sync** | Sync Wish / Collect / Doing / On Hold / Dropped statuses to your Bangumi account, individually or in rate-limited batches |
| **🔒 Local-First Privacy** | Favorites, blocklists, muted keywords, and AI results stay on device; NSFW is off by default |

---

## 🖼️ Screenshots

| Catalog Feed | Detail & AI Analysis |
| :---: | :---: |
| ![Yuri1st Catalog Feed](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/01-main-list.jpg) | ![Yuri1st Detail & Bangumi Sync](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/02-detail-ai-pointgrid.jpg) |

| Batch Collection Sync | AI Preference Settings | Batch Page Analysis |
| :---: | :---: | :---: |
| ![Batch Collection Sync](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/03-batch-pointgrid.jpg) | ![AI Settings](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/04-ai-settings.jpg) | ![Batch AI Analysis](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/05-batch-ai.jpg) |

---

## 🆕 Highlights in v0.4.0

- Replaced raw technical JSON with human-readable, editable AI judgment preferences.
- Broadened default Strong / Subtext yuri detection and added manual overrides (Strong / Subtext / Non-Yuri); home feed now flags Non-Yuri only.
- Added inverted filtering and a new 4-column dense grid view.
- Upgraded Room database to schema v7 with full support for manual classifications.

---

## 📦 Installation & Upgrading

- **Requirements:** Android 8.0 (API 26) or higher.
- Download the latest signed release APK from [GitHub Releases](https://github.com/toydream525/Yuri1st/releases/latest).

> [!WARNING]
> **Upgrading from v0.3 debug builds:** Due to signature differences, uninstall the old debug build before installing the v0.4.0 release APK. Uninstalling removes local favorites, settings, and cache—back up anything you wish to keep first.

---

## 🔒 Privacy & Security

- Bangumi Access Tokens and AI API keys are encrypted via **Android Keystore** and never written to repositories, logs, or backup files.
- AI analysis only triggers when you explicitly invoke it against your configured OpenAI-compatible endpoint.
- The official Bangumi API does not support deleting collections; collection sync switches among the five collection states.

---

## 🛠️ Build from Source

**Prerequisites:** JDK 17, Android SDK 35, included Gradle Wrapper.

```bash
./gradlew testDebugUnitTest assembleDebug
```

See [Development Guide](docs/DEVELOPMENT.md) and [Feature Docs](docs/FEATURES.md) for architecture and release conventions.

---

## 📜 License & Attribution

<div align="center">

Open source under the [**MIT License**](LICENSE) · Third-party dependencies listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)<br />
<sub>Subject metadata and media belong to <a href="https://bgm.tv/">Bangumi</a> and respective copyright holders.</sub>

</div>
