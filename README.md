# Hi, I'm V0rtix

<p align="center">
  <a href="https://github.com/chenbin3625">
    <img src="https://img.shields.io/badge/GitHub-chenbin3625-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Self--hosted%20Tools-2563eb?style=flat-square" alt="Self-hosted Tools" />
  <img src="https://img.shields.io/badge/Stack-Go%20%2B%20React%20%2B%20TypeScript-0f766e?style=flat-square" alt="Stack" />
  <img src="https://img.shields.io/badge/Also-NAS%20%2F%20Automation%20%2F%20Vue-7c3aed?style=flat-square" alt="Also" />
</p>

<p align="center">
  <a href="#中文">中文</a> / <a href="#english">English</a>
</p>

---

## 中文

我主要在做自托管工具、本地优先应用和自动化工作流，核心方向是 **Go 后端 + React / TypeScript 前端 + Docker 部署**，落地场景集中在 NAS（尤其是飞牛 fnOS）、文件同步备份、媒体下载归档和家庭服务器。

我在意的是「能长期跑得住」这件事：单二进制、Web UI、任务队列与调度、SSE 实时进度、多渠道通知、执行历史、可恢复配置，以及一份能让人真正用起来的 README。

### 我在关注

- 自托管应用：NAS、fnOS、Docker、家庭服务器与局域网工具
- 自动化工作流：同步、备份、归档、迁移、下载、整理
- 本地优先：SQLite / JSON 存储、数据可迁移、低外部依赖
- 运维体验：Docker Compose、应用包安装、Release 二进制、多架构支持
- 前端体验：React / TypeScript / Ant Design，以及 Vue 数据可视化

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
| [OpenSync](https://github.com/chenbin3625/OpenSync) | 面向飞牛 NAS / 通用 NAS / Docker 的 AList / OpenList 自动化层。通过 OpenList 连接本地目录、云盘、对象存储和 WebDAV，用可视化任务完成备份、镜像、归档与迁移；支持三种同步模式、Cron 调度、SSE 实时进度、执行历史和多渠道通知，提供 x86_64 / ARM64 / ARMv7 多架构镜像。 | Go, React, TypeScript, Docker, AList, OpenList |
| [OpenSync-fnOS](https://github.com/chenbin3625/OpenSync-fnOS) | OpenSync 的飞牛 fnOS 原生应用版本 —— 飞牛下群晖 Cloud Sync 的平替方案。以 `.fpk` 包在飞牛应用中心直接安装，无需 Docker 即可管理 AList / OpenList 存储引擎并跑定期同步。 | Go, fnOS, fpk, AList, OpenList |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | 本地优先的 X / Twitter 媒体下载归档工具。支持单条推文、用户、列表和关注归档，Web UI 操作，SQLite 存储元数据，可落地到本地目录、SMB 或 WebDAV。 | Go, React, SQLite, SMB, WebDAV |

### 全部仓库索引

| 仓库 | 类型 | 中英双语介绍 | 技术关键词 |
| --- | --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | 原创 / 同步工具 | 飞牛 NAS / 通用 NAS / Docker 场景下的 AList / OpenList 自动同步、备份、归档与迁移工具。<br>AList / OpenList sync, backup, archive, and migration automation for fnOS NAS, general NAS, and Docker. | Go, React, TypeScript, Docker |
| [OpenSync-fnOS](https://github.com/chenbin3625/OpenSync-fnOS) | 原创 / 飞牛应用 | OpenSync 的飞牛 fnOS 原生 `.fpk` 应用版本，飞牛下群晖 Cloud Sync 的平替方案。<br>Native fnOS `.fpk` application build of OpenSync — a Cloud Sync replacement for FeiNiu NAS. | Go, fnOS, fpk, AList, OpenList |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | 原创 / 下载归档 | 本地优先的 X / Twitter 媒体下载归档工具，支持推文、用户、列表、关注归档，以及本地目录 / SMB / WebDAV 多种存储后端。<br>Local-first X / Twitter media downloader and archiver for posts, users, lists, and following, with local / SMB / WebDAV storage backends. | Go, React, SQLite, SMB, WebDAV |
| [NodeWarden](https://github.com/chenbin3625/NodeWarden) | Fork / 上游项目 | 运行在 Cloudflare Workers 上的 Bitwarden 兼容服务端 fork，上游为 [shuaiplus/NodeWarden](https://github.com/shuaiplus/NodeWarden)；该 fork 保持与上游同步，不在此处改动。<br>Fork of a Bitwarden-compatible server on Cloudflare Workers, upstream is [shuaiplus/NodeWarden](https://github.com/shuaiplus/NodeWarden); kept in sync with upstream and not modified here. | TypeScript, Cloudflare Workers |
| [chenbin3625](https://github.com/chenbin3625/chenbin3625) | 个人主页 | 当前 GitHub Profile README 仓库。<br>This GitHub profile README repository. | Markdown |

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

I build self-hosted tools, local-first applications, and automation workflows, mostly shaped around **Go backends + React / TypeScript frontends + Docker deployment**, with a practical focus on NAS setups (especially FeiNiu fnOS), file sync and backup, media download archiving, and home-server workflows.

What I care about is whether a tool still holds up after months of running: a single binary, a Web UI, task queues and scheduling, live progress over SSE, multi-channel notifications, execution history, recoverable configuration, and a README that actually helps people use the project.

### What I Care About

- Self-hosted apps for NAS, fnOS, Docker, home servers, and LAN workflows
- Automation for sync, backup, archiving, migration, downloads, and organization
- Local-first design with SQLite / JSON storage, portable data, and minimal dependencies
- Operator experience: Docker Compose, native app packages, release binaries, multi-arch builds
- Frontend experience with React, TypeScript, Ant Design, and Vue data visualization

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
| [OpenSync](https://github.com/chenbin3625/OpenSync) | An AList / OpenList automation layer for fnOS, general NAS, and Docker. It connects local folders, cloud drives, object storage, and WebDAV through OpenList, then runs backup, mirror, archive, and migration as visual jobs — with three sync modes, cron scheduling, live SSE progress, execution history, and multi-channel notifications. Ships multi-arch images for x86_64 / ARM64 / ARMv7. | Go, React, TypeScript, Docker, AList, OpenList |
| [OpenSync-fnOS](https://github.com/chenbin3625/OpenSync-fnOS) | The native fnOS application build of OpenSync — a Cloud Sync replacement for FeiNiu NAS. Install the `.fpk` straight from the fnOS app center and manage AList / OpenList engines with scheduled sync, no Docker required. | Go, fnOS, fpk, AList, OpenList |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | A local-first X / Twitter media downloader and archiver. Handles posts, users, lists, and following archives through a Web UI, stores metadata in SQLite, and can write to a local directory, SMB, or WebDAV. | Go, React, SQLite, SMB, WebDAV |

### Repository Index

| Repository | Type | Description | Keywords |
| --- | --- | --- | --- |
| [OpenSync](https://github.com/chenbin3625/OpenSync) | Original / Tooling | AList / OpenList sync, backup, archive, and migration automation for fnOS NAS, general NAS, and Docker. | Go, React, TypeScript, Docker |
| [OpenSync-fnOS](https://github.com/chenbin3625/OpenSync-fnOS) | Original / fnOS App | Native fnOS `.fpk` application build of OpenSync — a Cloud Sync replacement for FeiNiu NAS. | Go, fnOS, fpk, AList, OpenList |
| [open-Xdownload](https://github.com/chenbin3625/open-Xdownload) | Original / Download Archive | Local-first X / Twitter media downloader and archiver for posts, users, lists, and following, with local / SMB / WebDAV storage backends. | Go, React, SQLite, SMB, WebDAV |
| [NodeWarden](https://github.com/chenbin3625/NodeWarden) | Fork / Upstream-based | Fork of a Bitwarden-compatible server on Cloudflare Workers, upstream is [shuaiplus/NodeWarden](https://github.com/shuaiplus/NodeWarden); kept in sync with upstream and not modified here. | TypeScript, Cloudflare Workers |
| [chenbin3625](https://github.com/chenbin3625/chenbin3625) | Profile | This GitHub profile README repository. | Markdown |

### GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=chenbin3625&show_icons=true&theme=transparent&hide_border=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chenbin3625&layout=compact&theme=transparent&hide_border=true" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chenbin3625&theme=transparent&hide_border=true" alt="GitHub Streak" />
</p>
