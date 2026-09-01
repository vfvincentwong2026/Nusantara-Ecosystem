# 🌴 Nusantara Ecosystem

> **内容驱动型增长生态 · 印尼高端别墅设计**  
> *Content-Driven Growth Ecosystem for OPC · Indonesian High-End Villa Design*

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Cloudflare Pages](https://img.shields.io/badge/Deployed%20on-Cloudflare%20Pages-F38020?logo=cloudflare&logoColor=white)](https://pages.cloudflare.com/)
[![Workers](https://img.shields.io/badge/Workers-Cloudflare-F38020?logo=cloudflare&logoColor=white)](https://workers.cloudflare.com/)
[![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18+-339933?logo=nodedotjs&logoColor=white)](https://nodejs.org/)

---

## 📖 目录 / Table of Contents

- [项目概览 / Overview](#-项目概览--overview)
- [核心理念 / Core Philosophy](#-核心理念--core-philosophy)
- [生态架构 / Ecosystem Architecture](#-生态架构--ecosystem-architecture)
- [四齿轮详解 / The Four Gears](#-四齿轮详解--the-four-gears)
- [内容生成流水线 / Content Generation Pipeline](#-内容生成流水线--content-generation-pipeline)
- [技术栈 / Tech Stack](#-技术栈--tech-stack)
- [快速开始 / Quick Start](#-快速开始--quick-start)
- [项目结构 / Project Structure](#-项目结构--project-structure)
- [部署指南 / Deployment Guide](#-部署指南--deployment-guide)
- [路线图 / Roadmap](#-路线图--roadmap)
- [许可证 / License](#-许可证--license)

---

## 🌟 项目概览 / Overview

### 中文

**Nusantara Ecosystem** 是一套专为印尼市场高端别墅全案设计打造的 **OPC（一人公司）数字化工具箱**。通过 **AI 驱动的内容生成**、**智能获客** 和 **知识驱动的品牌建设**，让个体创业者具备媲美中型企业的精准营销与交付能力。

> 🇮🇩 **nusantara** — 古爪哇语，意为“外岛”，今指整个印尼群岛。

**在线演示 / Live Demo:** [Atelier — 品牌前台 / Brand Front](https://nusantara-atelier.pages.dev)

### English

**Nusantara Ecosystem** is a digital toolchain built for **One-Person Companies (OPC)** operating in Indonesia's high-end villa design market. It transforms a solo entrepreneur into a marketing machine that rivals mid-sized agencies — through **AI-powered content generation**, **intelligent lead acquisition**, and **knowledge-driven brand building**.

> 🇮🇩 **nusantara** — an old Javanese term meaning "outer islands," now representing the Indonesian archipelago.

**Live Demo:** [Nusantara Atelier](https://nusantara-atelier.pages.dev)

---

## 🎯 核心理念 / Core Philosophy

### 一句话定义 / One Sentence

| 中文 | English |
|------|---------|
| 用 AI 驱动的规模化内容生产，替代传统销售开口，让流量主动找上门。 | Scale content with AI, let trust flow inbound. |

### 三大原则 / Three Pillars

| 原则 / Pillar | 说明 / Description |
|---------------|-------------------|
| **内容即销售** / **Content is Sales** | 每条内容都是 24×7 在线的销售代表，用专业度赢得信任 / Every piece of content works as a 24/7 sales representative, building trust through expertise |
| **AI 是引擎** / **AI is the Engine** | AI 嵌入每个环节但不喧宾夺主 — 客户感受到的是专业，而非科技 / AI powers every step behind the scenes — the customer only feels professionalism, not technology |
| **飞轮效应** / **The Flywheel** | 完成的项目产生新素材 → 反哺内容生成 → 吸引更多客户 → 更多项目 / Completed projects generate new assets → Feed content engine → Attract more clients → More projects |

### 战略定位 / Strategic Positioning

| 中文 | English |
|------|---------|
| Nusantara Ecosystem 专注于**内容生成与品牌建设**，用规模化、结构化的设计内容，占领印尼高端别墅市场的流量入口。 | Nusantara Ecosystem focuses on **content generation and brand building** — dominating the traffic gateway of Indonesia's high-end villa market through structured, scalable design content. |

---

## 🏗️ 生态架构 / Ecosystem Architecture
┌─────────────────────────────────────────────────────────────────┐
│ Nusantara Ecosystem │
│ 内容驱动型增长引擎 / Content-Driven Growth Engine │
├─────────────────────────────────────────────────────────────────┤
│ │
│ ┌──────────────────────────────────────────────────────────┐ │
│ │ AiToEarn │ │
│ │ ⭐ 内容引擎 / Content Engine │ │
│ │ (主动轮 / Drive Gear) │ │
│ │ 批量生产 → 多平台分发 → 流量获取 │ │
│ └──────────────────────┬───────────────────────────────────┘ │
│ │ 流量流入 / Traffic Inflow │
│ ▼ │
│ ┌──────────────────────────────────────────────────────────┐ │
│ │ Nusantara-Atelier │ │
│ │ 品牌前台 & 转化器 / Brand Front & Converter │ │
│ │ (承接轮 / Catch Gear) │ │
│ │ 25 案例 / 231 照片 / 三语 / 估价器 │ │
│ └──────────────────────┬───────────────────────────────────┘ │
│ │ 转化成交 / Conversion │
│ ▼ │
│ ┌──────────────────────────────────────────────────────────┐ │
│ │ Nusantara-KG-MCP-Server │ │
│ │ 知识决策大脑 / Knowledge Brain │ │
│ │ (赋能轮 / Enabler Gear) │ │
│ │ 专业智库 → 内容指南针 → 知识资产沉淀 │ │
│ └──────────────────────┬───────────────────────────────────┘ │
│ │ 知识反哺 / Knowledge Feedback │
│ ▼ │
│ ┌──────────────────────────────────────────────────────────┐ │
│ │ IndoScout-D-B │ │
│ │ 主动获客引擎 / Active Prospecting │ │
│ │ (补充轮 / Supplement Gear) │ │
│ │ 精准扫描 → 内容投递 → 线索补充 │ │
│ └──────────────────────────────────────────────────────────┘ │
│ │ │
│ ▼ │
│ ┌─────────────┐ │
│ │ 飞轮闭环 │ │
│ │ New Case → │ │
│ │ New Asset →│ │
│ │ New Content │ │
│ │ → New Client│ │
│ └─────────────┘ │
│ │
└─────────────────────────────────────────────────────────────────┘


---

## ⚙️ 四齿轮详解 / The Four Gears

### 齿轮一 / Gear 1: AiToEarn — ⭐ 内容引擎（主动轮）/ Content Engine (Drive Gear)

| 中文 | English |
|------|---------|
| **定位**：生态的绝对心脏。从"内容自动化工具"升级为"内容驱动型增长引擎"。 | **Position:** The heart of the ecosystem. Upgraded from "content automation tool" to "content-driven growth engine." |

**核心能力 / Core Capabilities:**

| 模块 / Module | 说明 / Description |
|---------------|-------------------|
| **模板化内容工厂** / **Template Factory** | 10 套内容模板（风格解析、预算对比、避坑指南等），AI 自动套用生成 / 10 content templates — AI auto-generates |
| **批量二创** / **Batch Remix** | 1 套实景图 → 10 条不同角度的脚本 + 配乐 + 字幕 + 配音 / 1 set of photos → 10 scripts with BGM, captions, voiceovers |
| **平台差异化分发** / **Platform Adaptation** | 自动适配 TikTok（竖版）/ YouTube（横版）/ 小红书（图文）/ Auto-optimizes for TikTok/YouTube/Xiaohongshu |
| **三语本地化** / **Tri-Lingual** | 印尼语 / 英语 / 中文 — 自动翻译 + 本地化润色 / Indonesian/English/Chinese — auto-translated + localized |
| **内容日历管理** / **Content Calendar** | AI 规划发布节奏，自动定时分发 / AI schedules and auto-publishes |
| **意图检测与自动回复** / **Intent Detection** | 监测互动数据，高意向评论自动触发私信引流 / Monitors engagement — high-intent comments trigger auto-DM |

**技术 / Tech:** Docker 容器化 / Containerized — Web UI / CLI / Self-hosted

---

### 齿轮二 / Gear 2: Nusantara-Atelier — 品牌前台 & 转化器（承接轮）/ Brand Front & Converter (Catch Gear)

| 中文 | English |
|------|---------|
| **定位**：唯一对客户可见的品牌前台。既是信任转化工具，也是内容生产的素材中台。 | **Position:** The only customer-facing brand front. Serves as both a trust conversion tool and a content material hub. |

**核心资产 / Core Assets:**
- ✅ 25 个真实落地案例 / 25 Real Completed Projects
- ✅ 231 张实景照片 / 231 High-Quality Photos
- ✅ 12 类空间体系 / 12 Spatial Categories
- ✅ 三语支持 / Tri-Lingual Support (Bahasa Indonesia / English / 中文)

**已上线功能 / Live Features:**

| 功能 / Feature | 说明 / Description |
|----------------|-------------------|
| **案例详情页** / **Case Gallery** | 25 个项目 SSG 预渲染，全屏灯箱（键盘 ←/→/Esc）/ 25 projects SSG-rendered, full-screen lightbox |
| **房间级标注** / **Spatial Annotation** | 12 类空间体系 + 三语描述 / 12 space types with tri-lingual descriptions |
| **即时估价工具** `/upload` / **Instant Estimator** | 纯客户端，IDR/USD/RMB 三币种 / Client-side only, IDR/USD/RMB |
| **BOM 精报** / **BOM Reporter** | 按空间驱动的物料算量引擎 / Material calculation engine with style selection |

**内容素材中台能力（新增）/ Content Hub Capabilities (New):**
- 每张图片自动打标签 / Auto-tags each image (Style / Space / Material)
- 结构化后通过 API 自动喂给 AiToEarn / Structured data fed to AiToEarn via API
- 成为内容生成的"原材料仓库" / Becomes the "raw material warehouse" for content production

**技术 / Tech:** Cloudflare Pages + D1 + R2

---

### 齿轮三 / Gear 3: Nusantara-KG-MCP-Server — 知识决策大脑（赋能轮）/ Knowledge Brain (Enabler Gear)

| 中文 | English |
|------|---------|
| **定位**：内容生成的"文案智库" — 为 AiToEarn 提供专业术语、风格定义和设计话术，确保 AI 输出内容专业、有深度。 | **Position:** The "copywriting compass" for content generation — provides professional terminology, style definitions, and design scripts to AiToEarn, ensuring AI outputs are professional and insightful. |

**知识覆盖 / Knowledge Coverage:**

| 维度 / Dimension | 内容 / Content | 内容生成用途 / Use in Content Generation |
|------------------|----------------|------------------------------------------|
| 设计美学 / Design Aesthetics | 8 种风格 × 12 类空间 / 8 styles × 12 spaces | 确保 AI 文案风格描述准确 / Ensures accurate style descriptions |
| 专业术语 / Professional Terms | 中英印三语术语库 / ID/EN/CN glossary | 注入文案，提升专业感 / Injects expertise into content |
| 设计话术 / Design Scripts | 专业设计解析话术 / Expert talking points | AI 输出"设计师口吻"/ AI outputs "designer voice" |
| 材料知识 / Material Knowledge | 53 个材料 SKU / 53 material SKUs | 支撑"材料解析"类内容 / Supports "material deep-dive" content |
| 成本知识 / Cost Knowledge | 工序/工时/价格基准 / Labor/process/price baselines | 支撑"预算对比"类内容 / Supports "budget comparison" content |

**数据策略 / Data Strategy:** **用 AI 生成提示词 + 免费大模型批量生成，人工只校对数字。** / **AI-generated prompts + free LLMs for batch generation — humans only validate numbers.**

**技术 / Tech:** Python + MCP Protocol

---

### 齿轮四 / Gear 4: IndoScout-D-B — 主动获客引擎（补充轮）/ Active Prospecting (Supplement Gear)

| 中文 | English |
|------|---------|
| **定位**：从"纯扫客工具"升级为"精准内容投递器"。 | **Position:** Upgraded from "pure scanner" to "precision content deliverer." |

**核心能力 / Core Capabilities:**

| 能力 / Capability | 说明 / Description |
|-------------------|-------------------|
| **Google Places API 扫描** / **Google Places Scanning** | 扫描印尼高端区域（巴厘岛、雅加达、万隆等）/ Scans high-end zones: Bali, Jakarta, Bandung, etc. |
| **Quality × Reach 双维评分** / **Quality × Reach Scoring** | 自动筛选高价值线索，附官网原文证据 / Auto-filters high-value leads with evidence citations |
| **个性化内容包投递** / **Custom Content Delivery** | 生成含同区域/同风格案例的定制化 PDF/视频链接 / Generates tailored PDF/video packages for each prospect |
| **WhatsApp 精准触达** / **WhatsApp Outreach** | 用"内容包"替代纯文本破冰话术 / "Content first" instead of "text first" |

**评分机制 / Scoring Model:**
- **质量分 / Quality Score**: 风格匹配 / Style Match (30%) + 项目体量 / Project Scale (25%) + 全案痛点 / Pain Point (20%) + 介入时机 / Timing (15%) + 核心区域 / Zone (10%)
- **触达分 / Reach Score**: 直连 WhatsApp / Direct WhatsApp (100) > 公司总机 / Company Phone (60) > 仅表单 / Web Form Only (30) > 无 / None (0)

**防幻觉机制 / Anti-Hallucination:** 每个维度打分必须附官网原文证据引文 + 置信度，无引文分数作废。 / Every score must cite original source + confidence. No citation = score void.

**技术 / Tech:** Cloudflare Worker + Google Places API

---

## 🔄 内容生成流水线 / Content Generation Pipeline

核心飞轮 — 每周一个生产闭环 / The core flywheel — one weekly production loop:


┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐ ┌───────────┐
│ 周一 │ │ 周二 │ │ 周三 │ │ 周四 │ │ 周五 │
│ MON │ │ TUE │ │ WED │ │ THU │ │ FRI │
│ 素材入库 │───▶│ AI脚本生成 │───▶│ 批量剪辑 │───▶│ 人工校准 │───▶│ 定时分发 │
│ Ingest │ │ Script │ │ Edit │ │ Polish │ │ Publish │
│ │ │ │ │ │ │ │ │ │
│ Atelier │ │ AiToEarn │ │ AiToEarn │ │ PM/运营 │ │ AiToEarn │
│ 上传新案例│ │ 5篇图文 │ │ 配乐/字幕 │ │ 调核心2-3 │ │ TikTok/IG │
│ 打好标签 │ │ 10条脚本 │ │ 粗剪完成 │ │ 确保调性 │ │ YouTube │
└───────────┘ └───────────┘ └───────────┘ └───────────┘ └───────────┘
│
▼
┌─────────────────────┐
│ 周末 / WEEKEND │
│ 数据回流 / Data │
│ 监测互动/自动回复 │
│ 高互动内容置顶官网 │
└─────────────────────┘


---

## 🛠️ 技术栈 / Tech Stack

| 层级 / Layer | 技术 / Technology | 用途 / Purpose |
|--------------|-------------------|----------------|
| **前端托管 / Frontend Hosting** | Cloudflare Pages | Atelier 品牌官网，全球 CDN 加速 / Atelier brand site, global CDN |
| **数据库 / Database** | Cloudflare D1 | 线索管理、内容元数据 / Lead management, content metadata |
| **对象存储 / Object Storage** | Cloudflare R2 | 图片/视频素材存储，免出口流量费 / Image/video storage, zero egress fees |
| **后端服务 / Backend Service** | Python + MCP Protocol | KG-MCP 知识智库 / KG-MCP knowledge brain |
| **获客引擎 / Prospecting** | Cloudflare Worker + Google Places API | IndoScout 无服务器扫客 / Serverless scanning |
| **内容自动化 / Content Automation** | Docker | AiToEarn 批量生成与分发 / Batch generation & distribution |
| **多语言 / Languages** | ZH / EN / ID | 印尼本地化 + 国际化 / Indonesian localization + international reach |

---

## 🚀 快速开始 / Quick Start

### 前置条件 / Prerequisites

- Cloudflare 账号 / Cloudflare Account (Pages + D1 + R2)
- Google Places API Key
- 域名（可选）/ Domain (optional — `*.pages.dev` 和 `*.trycloudflare.com` 可用)
- Docker（AiToEarn 需要）/ Docker (for AiToEarn)

### 克隆 / Clone

```bash
git clone https://github.com/vfvincentwong2026/Nusantara-Ecosystem.git
cd Nusantara-Ecosystem

各模块独立启动 / Module Setup
1. Atelier（品牌前台 / Brand Front）
bash
cd Nusantara-Atelier
npm install
npm run dev
部署到 Cloudflare Pages / Deploy to Cloudflare Pages:

bash
npm run build
# 在 Cloudflare Dashboard 连接仓库，自动 CI/CD
# Connect your repo in Cloudflare Dashboard → auto CI/CD
2. KG-MCP（知识智库 / Knowledge Brain）
bash
cd Nusantara-KG-MCP-Server
pip install -r requirements.txt
python server.py
3. IndoScout（获客引擎 / Prospecting）
bash
cd IndoScout-D-B
# 配置 wrangler.toml 中的环境变量 / Configure secrets in wrangler.toml
npx wrangler deploy
4. AiToEarn（内容引擎 / Content Engine）
bash
cd AiToEarn
docker-compose up -d
# 访问 / Open http://localhost:3000
📂 项目结构 / Project Structure
text
Nusantara-Ecosystem/
├── Nusantara-Atelier/              # 品牌前台 & 转化器 / Brand Front & Converter
│   ├── src/
│   │   ├── pages/                  # SSG 案例页 / SSG case pages (25 projects)
│   │   ├── components/             # 灯箱/估价/三语切换 / Lightbox/Estimator/Tri-lingual
│   │   └── data/                   # 25 案例 + 231 照片元数据 / 25 cases + 231 photos
│   ├── package.json
│   └── wrangler.toml
│
├── Nusantara-KG-MCP-Server/        # 知识决策大脑 / Knowledge Brain
│   ├── knowledge/
│   │   ├── styles.json             # 8 种设计风格定义 / 8 design style definitions
│   │   ├── materials.json          # 53 个材料 SKU / 53 material SKUs
│   │   └── glossary.json           # 中英印三语术语 / ID/EN/CN terminology
│   ├── server.py                   # MCP 协议服务 / MCP protocol server
│   └── requirements.txt
│
├── IndoScout-D-B/                  # 主动获客引擎 / Active Prospecting
│   ├── src/
│   │   ├── scanner.js              # Google Places API 扫描 / Google Places scanner
│   │   ├── scorer.js               # Quality×Reach 评分 / Quality×Reach scoring
│   │   └── deliverer.js            # 个性化内容包投递 / Custom content delivery
│   └── wrangler.toml
│
├── AiToEarn/                       # 内容生成引擎 / Content Engine
│   ├── modules/
│   │   ├── generator/              # AI 脚本生成 / AI script generation
│   │   ├── editor/                 # 批量剪辑 / Batch video editing
│   │   ├── publisher/              # 多平台发布 / Multi-platform distribution
│   │   └── detector/               # 意图检测 & 自动回复 / Intent detection & auto-reply
│   ├── docker-compose.yml
│   └── Dockerfile
│
└── README.md
🗺️ 部署指南 / Deployment Guide
环境变量配置 / Environment Configuration
各模块按需创建 .env 文件 / Create .env file for each module as needed:

Atelier (Cloudflare Pages)
env
VITE_GOOGLE_MAPS_KEY=your_key
VITE_ESTIMATOR_ENABLED=true
IndoScout (Cloudflare Worker)
toml
# wrangler.toml
[vars]
GOOGLE_PLACES_API_KEY = "your_key"
TARGET_ZONES = "Bali,Jakarta,Bandung"
WHATSAPP_TEMPLATE_ID = "your_template"
KG-MCP
env
MODEL_PATH=./knowledge
MCP_PORT=8080
AiToEarn
env
OPENAI_API_KEY=your_key
TIKTOK_ACCESS_TOKEN=your_token
INSTAGRAM_BUSINESS_ID=your_id
REDIS_URL=redis://redis:6379
Docker Compose 全栈部署 / Full Stack Deployment
yaml
# docker-compose.full.yml
version: '3.8'
services:
  redis:
    image: redis:7-alpine
  postgres:
    image: postgres:14
    environment:
      POSTGRES_DB: nusantara
      POSTGRES_USER: nusantara
      POSTGRES_PASSWORD: secure_pass
  mcp-server:
    build: ./Nusantara-KG-MCP-Server
    ports:
      - "8080:8080"
  aitoearn:
    build: ./AiToEarn
    ports:
      - "3000:3000"
    depends_on:
      - redis
      - postgres
🗺️ 路线图 / Roadmap
阶段 / Phase	周期 / Timeline	关键交付 / Key Deliverables	状态 / Status
P0 — 验证期 / Validation	已完成 / Completed	25 案例 / 231 照片；Atelier v1.0 上线；KG 骨架就绪 / 25 cases / 231 photos; Atelier v1.0 live; KG skeleton ready	✅ 完成 / Done
P1 — 内容引擎升级 / Content Engine	2-3 周 / 2-3 weeks	AiToEarn → 内容工厂；10 套模板；平台差异化分发 / AiToEarn → Content Factory; 10 templates; platform adaptation	🔄 进行中 / In Progress
P2 — 素材中台 / Material Hub	1 周 / 1 week	Atelier → Headless CMS；自动打标签；API 对接 AiToEarn / Atelier → Headless CMS; auto-tagging; API to AiToEarn	📋 计划中 / Planned
P3 — 精准投递 / Precision Delivery	1-2 周 / 1-2 weeks	IndoScout → 内容投递器；替代纯文本话术 / IndoScout → Content Deliverer; replace text-only outreach	📋 计划中 / Planned
P4 — 规模化 / Scale	持续 / Ongoing	案例破 100；内容矩阵铺开；品牌心智占位 / 100+ cases; content matrix expansion; brand dominance	🔮 远期 / Future
📄 许可证 / License
本项目采用 Apache 2.0 License — 详见 LICENSE 文件。
This project is licensed under the Apache 2.0 License — see the LICENSE file for details.

🙏 致谢 / Acknowledgments
由 Cloudflare 驱动 — Pages, Workers, D1, R2 / Powered by Cloudflare — Pages, Workers, D1, R2

AI 能力由 OpenAI / Anthropic 及开源大模型提供 / AI capabilities by OpenAI / Anthropic / various open-source LLMs

受 OPC（一人公司）运动启发 — 事半功倍 / Inspired by the OPC (One-Person Company) movement — do more with less

📬 联系 / Connect
作者 / Author: Vincent Wong

GitHub: @vfvincentwong2026

在线演示 / Live: Nusantara Atelier

<div align="center">
为一人公司而建 · 为印尼而建
Built for OPC · Made with ❤️ for Indonesia

⭐ 如果这个项目对你有帮助，请给它一个 Star！
⭐ If this project helps you, consider giving it a star!

</div> ```
