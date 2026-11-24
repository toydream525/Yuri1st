<div align="center">

<img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher_foreground.png" width="96" height="96" alt="Yuri1st 应用图标" />

# Yuri1st · Bangumi 百合作品集

**面向 Bangumi 百合与轻百合标签条目的开源 Android 浏览器**

<p>
  <strong>简体中文</strong> &nbsp;|&nbsp; <a href="./README.en.md">English</a>
</p>

<p>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><img src="https://img.shields.io/github/v/release/toydream525/Yuri1st?display_name=tag&sort=semver&style=flat-square" alt="Latest Release" /></a>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><img src="https://img.shields.io/badge/Android-8.0%2B-3DDC84.svg?style=flat-square&logo=android&logoColor=white" alt="Android 8.0+" /></a>
  <a href="https://github.com/toydream525/Yuri1st/actions/workflows/build-apk.yml"><img src="https://img.shields.io/github/actions/workflow/status/toydream525/Yuri1st/build-apk.yml?style=flat-square&label=CI" alt="CI Build" /></a>
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-9a3c72.svg?style=flat-square" alt="License: MIT" /></a>
  <a href="https://yuriaqua.com/Yuri1st/"><img src="https://img.shields.io/badge/Website-yuriaqua.com-9a3c72.svg?style=flat-square" alt="Website" /></a>
</p>

<p>
  <a href="https://github.com/toydream525/Yuri1st/releases/latest"><strong>⬇️ 下载最新 APK</strong></a> &nbsp;·&nbsp;
  <a href="https://yuriaqua.com/Yuri1st/">🌐 项目官网</a> &nbsp;·&nbsp;
  <a href="./docs/FEATURES.md">📖 完整功能说明</a> &nbsp;·&nbsp;
  <a href="./CHANGELOG.md">📝 更新日志</a>
</p>

</div>

---

## ✨ 项目简介

**Yuri1st** 将动画、漫画、轻小说和游戏集中整理，提供本地搜索、三态封面布局、高级筛选、收藏、屏蔽与 **Bangumi 点格子**；可选的 **AI 百合倾向分析** 用于辅助判断，始终仅供参考。

> [!NOTE]
> **数据来源说明：** 作品目录与条目资料来自 [Bangumi](https://bgm.tv/) 公开接口及用户标签。应用仅按精确 `百合` / `轻百合` 标签收录，不代表 Bangumi 官方推荐，也无法保证内容判断完全准确。

---

## 🚀 核心亮点

| 能力 | 说明 |
| :--- | :--- |
| **📚 百合目录浏览** | 动画、漫画、轻小说、游戏独立浏览；支持本地搜索、Bangumi 链接或 ID 导入、分页与离线基础条目 |
| **🎛️ 三态布局与筛选** | 左上角排版按钮可在「列表 / 两列封面 / 四列密集」间切换；高级筛选支持分类、年份、评分人数、AI/自定义标记及反选 |
| **🤖 AI 百合倾向分析** | 使用用户自行配置的 OpenAI 兼容接口分析真百、轻百、非百倾向；判断偏好以自然语言呈现，可手动分类或恢复跟随 AI（首页仅非百显示提示标记） |
| **✅ Bangumi 点格子** | 将想看、看过、在看、搁置、抛弃同步至个人 Bangumi 账号，支持单条与批量操作并自动限速 |
| **🔒 本地优先与隐私** | 收藏、屏蔽、屏蔽词、赢面/输面与分析结果均保存在设备本地；NSFW 默认关闭 |

---

## 🖼️ 界面预览

| 目录信息流 | 详情与百合倾向分析 |
| :---: | :---: |
| ![Yuri1st 目录信息流，展示 AI 百合倾向与自定义标记](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/01-main-list.jpg) | ![Yuri1st 条目详情页，展示 Bangumi 点格子与 AI 百合倾向分析](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/02-detail-ai-pointgrid.jpg) |

| 批量点格子 | AI 百合倾向分析设置 | 本页批量分析 |
| :---: | :---: | :---: |
| ![Yuri1st 批量点格子操作界面](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/03-batch-pointgrid.jpg) | ![Yuri1st AI 百合倾向分析设置界面](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/04-ai-settings.jpg) | ![Yuri1st 本页批量 AI 百合倾向分析界面](https://cdn.jsdelivr.net/gh/toydream525/Yuri1st@main/docs/screenshots/05-batch-ai.jpg) |

---

## 🆕 v0.4.0 更新要点

- AI 百合倾向分析改用可读、可编辑的「判断偏好」，不再向用户展示技术 JSON。
- 扩大真百 / 轻百的默认判断范围，支持手动设为真百、轻百或非百；首页仅非百显示提示标记。
- 高级筛选支持反选；排版按钮新增「四列密集」布局，可在三种布局间循环切换。
- Room 数据库升级至版本 7，兼容手动分类数据。

👉 完整变更记录请查看 [CHANGELOG.md](CHANGELOG.md)。

---

## 📦 安装与升级

- **系统要求**：Android 8.0（API 26）及以上。
- 前往 [GitHub Releases](https://github.com/toydream525/Yuri1st/releases/latest) 下载最新正式 APK，允许安装未知来源应用后即可打开使用。

> [!WARNING]
> **从 v0.3 调试签名版升级注意：** 若系统提示签名不一致，需先卸载旧调试版，再安装 v0.4.0 正式版。卸载会清除旧版本地数据（收藏、设置与缓存），请先确认需要保留的内容。

---

## 🔒 隐私与安全边界

- Bangumi Access Token 与 AI API Key 使用 **Android Keystore** 加密保存，绝不写入仓库、日志或备份文件。
- 本地收藏、屏蔽、筛选与 AI 缓存保留在设备本地数据库中；卸载应用会按 Android 系统规则移除数据。
- AI 分析仅在你主动触发时调用你配置的兼容接口；模型可能出错或带有偏差，结果仅作辅助参考。
- Bangumi 官方接口不支持删除收藏，点格子仅支持切换五种收藏状态。

---

## 🛠️ 开发构建与文档

**环境要求：** JDK 17、Android SDK 35、项目内置 Gradle Wrapper。

```bash
./gradlew testDebugUnitTest assembleDebug
```

| 文档 | 内容 |
| :--- | :--- |
| [完整功能说明](docs/FEATURES.md) | 目录、筛选、AI 与点格子详细用法 |
| [开发与构建说明](docs/DEVELOPMENT.md) | 技术栈、正式构建 User-Agent、数据流程与边界 |
| [更新日志](CHANGELOG.md) | 版本变更与兼容性说明 |
| [项目官网](https://yuriaqua.com/Yuri1st/) | 产品介绍与当前版本摘要 |

---

## 📜 开源许可与声明

<div align="center">

本项目以 [**MIT License**](LICENSE) 开源 · 运行时依赖与许可详见 [第三方组件清单](THIRD_PARTY_NOTICES.md)<br />
<sub>作品条目数据版权归 <a href="https://bgm.tv/">Bangumi</a> 及各作品权利方所有</sub>

</div>
