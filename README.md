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

