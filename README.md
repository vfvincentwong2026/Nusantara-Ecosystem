# 🌏 Nusantara Ecosystem

**AI 驱动的印尼高端设计全案获客与交付闭环**

[![GitHub stars](https://img.shields.io/github/stars/vfvincentwong2026/Nusantara-Ecosystem)](https://github.com/vfvincentwong2026/Nusantara-Ecosystem/stargazers)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

---

## 简介

Nusantara Ecosystem 是一套专为**印尼市场高端别墅全案设计**打造的 OPC（一人公司）数字化工具箱。它通过“主动获客 + 内容引流 + 知识决策 + 品牌承接”四个环节的协同，让个体创业者具备媲美中型企业的精准营销与交付能力。

---

## 生态全景图

```mermaid
graph TD
    A[IndoScout-D-B<br>主动获客引擎] --> D[Nusantara-Atelier<br>品牌前台/转化器]
    C[Nusantara-KG-MCP-Server<br>知识中台/决策大脑] --> A
    C --> D
    C --> E[AiToEarn<br>内容营销自动化]
    E -- 内容引流/线索反哺 --> D
    D -- 案例/数据反哺 --> E
    A -- 潜在客户导入 --> D
    
    subgraph 核心业务流



核心子项目
1. IndoScout-D-B（主动获客引擎）
定位：从 0 到 1 的冷启动获客机。

功能：基于 Google Places API 批量扫描印尼高端商圈及住宅区的潜在业主线索。

AI 评估：引入 Quality × Reach 双维评分模型，筛选高净值、高意愿客户。

触达：一键生成个性化 WhatsApp 破冰话术，将陌生线索转化为可跟进商机。

2. Nusantara-KG-MCP-Server（知识决策中台）
定位：整个生态系统的“大脑”与“百科全书”。

知识图谱：覆盖 8 种顶级设计风格 × 12 类空间 × 53 个 SKU 材料数据，包含工艺标准、工时定额与人工成本。

赋能：

为 Atelier 提供精准的即时估价计算逻辑。

为 IndoScout 提供高情商的商务话术支撑。

为 AiToEarn 提供专业的内容选题与脚本素材。

3. Nusantara-Atelier（品牌前台 & 转化器）
定位：唯一面向客户的“门面”与信任建立平台。

资产展示：沉淀了 25 个真实落地案例 / 231 张实景照片，覆盖法式、现代、侘寂等多种风格。

核心转化：上线 即时估价工具 (P1)，客户上传户型图即可在 30 分钟内获得初步报价。

技术底座：基于 Cloudflare Pages + D1 数据库，三语支持（中/英/印尼）。

4. AiToEarn（内容营销自动化 & 声量放大器）
定位：让“被动客户”主动找上门的流水线。

Create：基于 Atelier 的 231 张实景图，批量生成“30 秒看豪宅”、“Before/After”等高质量短视频素材。

Publish：一键分发至 TikTok、YouTube、Instagram 等 12+ 海外主流平台。

Engage：AI 智能识别评论区“求链接”、“怎么收费”等高意向信号，自动回复并引导至 Atelier 估价页面。

闭环：抓取的线索自动回写至 Atelier D1 数据库，与 IndoScout 线索统一管理。

端到端数据流
双向获客：IndoScout 主动出击抓取名单，AiToEarn 通过内容吸引客户咨询。

统一归集：所有线索流入 Atelier 的 D1 数据库，去重并建立跟进时间线。

智能决策：销售沟通或内容生成时，实时调用 KG-MCP 知识图谱获取专业参数（价格/工艺/风格解析）。

信任转化：客户通过 Atelier 官网看到真实案例并使用估价工具，建立信任并完成初步锁客。

交付反哺：新的落地项目产生新的实景照片，循环回 Atelier 素材库与 KG-MCP 知识库，形成越用越强的数据飞轮。

快速开始
克隆主仓库（含所有子模块）
bash
git clone --recurse-submodules https://github.com/vfvincentwong2026/Nusantara-Ecosystem.git
cd Nusantara-Ecosystem
各子项目独立部署
子项目	部署命令
Atelier (Pages)	cd submodules/Nusantara-Atelier && npm install && npm run deploy
KG-MCP (Server)	cd submodules/Nusantara-KG-MCP-Server && pip install -r requirements.txt && python app.py
IndoScout (Worker)	cd submodules/IndoScout-D-B && npm install && npm run deploy:worker
AiToEarn (Docker)	cd submodules/AiToEarn && docker compose up -d
环境要求：Cloudflare 账户、Node.js 20.18+、Docker、Python 3.9+。

项目状态
子项目	版本	核心进展	下一里程碑
Atelier	v1.0	官网上线，25 案例，估价工具 P1 完成	在线预约设计师
KG-MCP	P0	知识图谱骨架完成，66 核心节点	扩充至 200+ 节点，向量检索
IndoScout	P0	Places API 打通，评分模型验证中	WA 自动化触达 + CRM 看板
AiToEarn	v2.5	基于上游同步，生态接入点预留	深度定制“豪宅装修”模板
战略定位
这不是一套简单的开源代码集合，而是对 “AI 原生一人公司” 形态的探索。

传统装企：重资产、多人销售、依赖线下展会。

Nusantara 模式：轻资产、AI 销售助理（IndoScout）、AI 内容专员（AiToEarn）、AI 设计顾问（KG-MCP）、7×24 小时在线展厅（Atelier）。

本地化优势
文化纵深：深耕印尼市场，深度理解印尼高端业主的审美偏好与决策习惯。

真实数据：拥有印尼本地建材供应链与真实落地案例数据，非虚构。

边缘架构：利用 Cloudflare Workers 实现低成本、高可用的全球/本地加速。

仓库结构
text
Nusantara-Ecosystem/
├── README.md
├── .gitmodules
├── submodules/
│   ├── Nusantara-Atelier/        # 品牌前台
│   ├── IndoScout-D-B/            # 主动获客
│   ├── Nusantara-KG-MCP-Server/  # 知识中台
│   └── AiToEarn/                 # 内容营销自动化
└── docs/
    ├── architecture.md           # 整体架构设计
    └── integration-guide.md      # 集成指南
贡献指南
Fork 本仓库

在对应的子项目目录中进行修改

提交 PR 到子项目的上游仓库（子模块会自动更新）

许可证
各子项目遵循其自身的许可证（MIT / Apache 等），本项目作为元仓库，采用 MIT 许可证。



        D
    end
