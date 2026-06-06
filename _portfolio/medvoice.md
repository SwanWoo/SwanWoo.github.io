---
title: "MedVoice 医疗语音 AI 平台"
excerpt: "基于 vLLM 的医疗语音 AI Agent 平台，支持医患语音交互、智能问诊辅助等功能。"
collection: portfolio
tags:
  - Python
  - FastAPI
  - vLLM
  - PostgreSQL
  - Docker
  - AI Agent
---

## 项目概述

MedVoice 是一个面向医疗场景的语音 AI Agent 平台，支持医生与患者之间的语音交互，通过大模型实现智能问诊辅助、病历语音转写等功能。

## 核心功能

- **语音交互**：支持实时语音输入与输出，实现医患对话的智能化
- **AI Agent**：基于大模型的智能问诊助手，辅助医生进行诊断决策
- **多数据库支持**：生产环境使用 PostgreSQL，开发环境支持 SQLite
- **数据库迁移**：Alembic 管理数据库版本与 Schema 变更

## 技术架构

- **应用层**：FastAPI 异步框架
- **模型推理**：vLLM 高性能推理引擎
- **数据库**：PostgreSQL（生产）/ SQLite（开发）
- **部署方案**：
  - Gunicorn + Uvicorn Workers（生产推荐）
  - Supervisor 进程管理
  - Systemd 服务
  - Docker 容器化

## 技术栈

`Python` `FastAPI` `vLLM` `PostgreSQL` `SQLite` `Alembic` `Gunicorn` `Docker` `Supervisor`
