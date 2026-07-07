# Hi, I'm V0rtix

<p align="center">
  <a href="https://github.com/chenbin3625">
    <img src="https://img.shields.io/badge/GitHub-chenbin3625-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Self--hosted%20Tools-2563eb?style=flat-square" alt="Self-hosted Tools" />
  <img src="https://img.shields.io/badge/Stack-Go%20%2B%20React%20%2B%20TypeScript-0f766e?style=flat-square" alt="Stack" />
  <img src="https://img.shields.io/badge/Also-Vue%20%2F%20Automation%20%2F%20NAS-7c3aed?style=flat-square" alt="Also" />
</p>

<p align="center">
  <a href="#中文">中文</a> / <a href="#english">English</a>
</p>

---

## 中文

我主要在做自托管工具、本地优先应用和自动化工作流。最近的仓库更偏向 **Go 后端 + React / TypeScript 前端 + Docker 部署**，关注 NAS、媒体资源管理、同步备份、下载归档、原型评审、数据修复和家庭服务器这些真实使用场景。

我喜欢把工具做成可以长期运行、易部署、状态可见的形态：单二进制、Web UI、任务队列、定时任务、通知、日志、可恢复配置，以及尽量清楚的 README。

### 我在关注

- 自托管应用：NAS、Docker、家庭服务器和局域网工具
- 自动化工作流：同步、备份、归档、订阅、下载、整理
- 本地优先：SQLite / JSON 存储、可迁移数据、低外部依赖
- 工程体验：Web UI、任务状态、SSE 实时反馈、Docker Compose、Release 二进制
- 前端体验：React / TypeScript / Ant Design / Vue 数据可视化

### 技术栈

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vue-42B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Ant%20Design-1677FF?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design" />
</p>

### 代表项目

| 项目 | 简介 | 技术关键词 |
| --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | 面向飞牛 NAS / Docker 的 AList / OpenList 自动同步工具，支持多源多目标同步、定时任务、历史任务、通知和 Docker 部署。 | Go, TypeScript, Docker, AList, OpenList |
| [OpenMovie](https://github.com/chenbin3625/OpenMovie) | 自托管影视资源自动化管理系统，覆盖推荐、搜索、订阅、下载、整理、刮削、日历和通知等媒体库流程。 | Go, React, TypeScript, Ant Design, Automation |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | 本地优先的 X / Twitter 媒体下载器，提供 Web UI、任务队列、SQLite、本地目录、SMB 和 WebDAV 存储支持。 | Go, React, SQLite, SMB, WebDAV |
| [OpenPT](https://github.com/chenbin3625/OpenPT) | 轻量级 BitTorrent Tracker Announce 工具，面向 PT 保种场景，带 Web UI、客户端伪装、上传策略和 Prometheus 指标。 | Go, Web UI, Prometheus, Docker |
| [RP-Viewer](https://github.com/chenbin3625/RP-Viewer) | 自托管原型在线查看及评论平台，支持 Axure / 墨刀等原型浏览、iframe 预览和类 Figma 定点评论。 | Go, React, TypeScript, Ant Design |
| [google-photos-exif-fixer](https://github.com/chenbin3625/google-photos-exif-fixer) | 修复 Google Photos Takeout 导出照片的拍摄时间和 GPS 元数据，并按年月整理照片库。 | Go, EXIF, CLI, Data Recovery |

### 全部仓库索引

| 仓库 | 类型 | 中英双语介绍 | 技术关键词 |
| --- | --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | 原创 / 工具 | 飞牛 NAS / Docker 场景下的 AList / OpenList 自动同步、备份、归档和迁移工具。<br>AList / OpenList sync, backup, archive, and migration tool for fnOS NAS and Docker. | Go, React, TypeScript, Docker |
| [OpenMovie](https://github.com/chenbin3625/OpenMovie) | 原创 / 媒体自动化 | 自托管影视资源自动化系统，集推荐、搜索、订阅、下载、整理、刮削和通知于一体。<br>Self-hosted media automation system for discovery, search, subscriptions, downloads, organization, scraping, and notifications. | Go, React, TypeScript |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | 原创 / 下载归档 | 本地优先的 X / Twitter 媒体下载器，支持单条、用户、列表、关注归档和多存储后端。<br>Local-first X / Twitter media downloader for posts, users, lists, following archives, and multiple storage backends. | Go, React, SQLite, SMB, WebDAV |
| [OpenPT](https://github.com/chenbin3625/OpenPT) | 原创 / PT 工具 | 面向 PT 保种的 BitTorrent Tracker Announce 工具，支持客户端伪装、上传策略、Web UI 和 Prometheus 指标。<br>BitTorrent tracker announce tool for private tracker seeding with client emulation, upload strategies, Web UI, and Prometheus metrics. | Go, BitTorrent, Prometheus |
| [RP-Viewer](https://github.com/chenbin3625/RP-Viewer) | 原创 / 协作评审 | 本地原型在线查看及评论平台，支持原型目录扫描、iframe 预览和定点评论。<br>Self-hosted prototype review platform with folder scanning, iframe preview, and pinned comments. | Go, React, TypeScript, Ant Design |
| [google-photos-exif-fixer](https://github.com/chenbin3625/google-photos-exif-fixer) | 原创 / 数据修复 | 将 Google Photos Takeout 的 JSON 元数据写回照片 EXIF，并按年月整理媒体库。<br>Restores Google Photos Takeout JSON metadata into EXIF and organizes media by year and month. | Go, EXIF, CLI |
| [sandbox-zn-screen](https://github.com/chenbin3625/sandbox-zn-screen) | 原创 / 前端可视化 | Vue 3 智慧大屏沙箱，包含登录、后台管理、监控页和大屏展示原型。<br>Vue 3 smart-screen sandbox for login, admin, monitoring, and full-screen visualization prototypes. | Vue, Vite, ECharts, Pinia |
| [myblog](https://github.com/chenbin3625/myblog) | 原创 / 毕设项目 | 2023 本科毕业设计博客系统，包含博客前台、管理后台和 Express / MongoDB 服务端。<br>Undergraduate thesis blog system with public frontend, admin dashboard, and Express / MongoDB backend. | Vue, TypeScript, Express, MongoDB |
| [chenbin3625](https://github.com/chenbin3625/chenbin3625) | 个人主页 | 当前 GitHub Profile README 仓库。<br>This GitHub profile README repository. | Markdown |
| [NodeWarden](https://github.com/chenbin3625/NodeWarden) | Fork / 上游项目 | Bitwarden 兼容的 Cloudflare Workers 服务端 fork；该 fork 保持上游同步，不在这里改动。<br>Fork of a Bitwarden-compatible Cloudflare Workers server; kept upstream-based and not modified here. | TypeScript, Cloudflare Workers |

### GitHub 数据

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=chenbin3625&show_icons=true&theme=transparent&hide_border=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chenbin3625&layout=compact&theme=transparent&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chenbin3625&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>

---

## English

I build self-hosted tools, local-first applications, and automation workflows. My recent repositories are mostly shaped around **Go backends + React / TypeScript frontends + Docker deployment**, with a practical focus on NAS setups, media management, sync and backup jobs, download archiving, prototype review, data repair, and home-server workflows.

I like tools that can run for a long time and still feel understandable: single binaries, Web UIs, task queues, scheduled jobs, notifications, logs, recoverable configuration, and documentation that helps people actually use the project.

### What I Care About

- Self-hosted apps for NAS, Docker, home servers, and LAN workflows
- Automation for sync, backup, archiving, subscriptions, downloads, and organization
- Local-first design with SQLite / JSON storage, portable data, and minimal dependencies
- Developer and operator experience: Web UI, task state, SSE feedback, Docker Compose, binary releases
- Frontend experience with React, TypeScript, Ant Design, Vue, and data visualization

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vue-42B883?style=flat-square&logo=vuedotjs&logoColor=white" alt="Vue" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Ant%20Design-1677FF?style=flat-square&logo=antdesign&logoColor=white" alt="Ant Design" />
</p>

### Featured Projects

| Project | Description | Keywords |
| --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | An AList / OpenList automation tool for fnOS NAS and Docker environments, with multi-source sync, scheduled jobs, history, notifications, and Docker deployment. | Go, TypeScript, Docker, AList, OpenList |
| [OpenMovie](https://github.com/chenbin3625/OpenMovie) | A self-hosted media automation system covering discovery, search, subscriptions, downloads, organization, metadata scraping, calendars, and notifications. | Go, React, TypeScript, Ant Design, Automation |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | A local-first X / Twitter media downloader with Web UI, task queue, SQLite, local directory, SMB, and WebDAV storage support. | Go, React, SQLite, SMB, WebDAV |
| [OpenPT](https://github.com/chenbin3625/OpenPT) | A lightweight BitTorrent tracker announce tool for private tracker seeding workflows, with Web UI, client emulation, upload strategies, and Prometheus metrics. | Go, Web UI, Prometheus, Docker |
| [RP-Viewer](https://github.com/chenbin3625/RP-Viewer) | A self-hosted prototype review platform for Axure / Mockplus-style exports, with iframe preview and Figma-like pinned comments. | Go, React, TypeScript, Ant Design |
| [google-photos-exif-fixer](https://github.com/chenbin3625/google-photos-exif-fixer) | A CLI tool that restores date-taken and GPS metadata from Google Photos Takeout exports and organizes the output by year and month. | Go, EXIF, CLI, Data Recovery |

### Repository Index

| Repository | Type | Description | Keywords |
| --- | --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | Original / Tooling | AList / OpenList sync, backup, archive, and migration tool for fnOS NAS and Docker. | Go, React, TypeScript, Docker |
| [OpenMovie](https://github.com/chenbin3625/OpenMovie) | Original / Media Automation | Self-hosted media automation system for discovery, search, subscriptions, downloads, organization, scraping, and notifications. | Go, React, TypeScript |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | Original / Download Archive | Local-first X / Twitter media downloader for posts, users, lists, following archives, and multiple storage backends. | Go, React, SQLite, SMB, WebDAV |
| [OpenPT](https://github.com/chenbin3625/OpenPT) | Original / PT Tooling | BitTorrent tracker announce tool for private tracker seeding with client emulation, upload strategies, Web UI, and Prometheus metrics. | Go, BitTorrent, Prometheus |
| [RP-Viewer](https://github.com/chenbin3625/RP-Viewer) | Original / Prototype Review | Self-hosted prototype review platform with folder scanning, iframe preview, and pinned comments. | Go, React, TypeScript, Ant Design |
| [google-photos-exif-fixer](https://github.com/chenbin3625/google-photos-exif-fixer) | Original / Data Repair | Restores Google Photos Takeout JSON metadata into EXIF and organizes media by year and month. | Go, EXIF, CLI |
| [sandbox-zn-screen](https://github.com/chenbin3625/sandbox-zn-screen) | Original / Frontend Visualization | Vue 3 smart-screen sandbox for login, admin, monitoring, and full-screen visualization prototypes. | Vue, Vite, ECharts, Pinia |
| [myblog](https://github.com/chenbin3625/myblog) | Original / Thesis Project | Undergraduate thesis blog system with public frontend, admin dashboard, and Express / MongoDB backend. | Vue, TypeScript, Express, MongoDB |
| [chenbin3625](https://github.com/chenbin3625/chenbin3625) | Profile | This GitHub profile README repository. | Markdown |
| [NodeWarden](https://github.com/chenbin3625/NodeWarden) | Fork / Upstream-based | Fork of a Bitwarden-compatible Cloudflare Workers server; kept upstream-based and not modified here. | TypeScript, Cloudflare Workers |

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=chenbin3625&show_icons=true&theme=transparent&hide_border=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chenbin3625&layout=compact&theme=transparent&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chenbin3625&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>
