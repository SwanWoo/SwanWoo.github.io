---
title: "SinoQuant 量化交易平台"
excerpt: "集成多 LLM 提供商的智能量化交易平台，支持股票分析、量化策略回测、智能选股等功能。"
collection: portfolio
tags:
  - Python
  - FastAPI
  - MongoDB
  - Redis
  - LLM
  - Vue.js
  - Docker
---

## 项目概述

SinoQuant 是一个综合性的量化交易平台，集成了股票分析、量化策略构建与回测、智能选股等功能，并通过多 LLM 提供商（DeepSeek、OpenAI、Google、DashScope、Anthropic）实现 AI 驱动的市场洞察。

## 核心功能

- **智能股票分析**：AI 驱动的基本面与技术面分析，自动生成投资建议报告
- **量化策略构建器**：可视化策略编辑器，支持自定义因子、条件组合、回测验证
- **策略回测引擎**：历史数据回测，支持多时间周期、手续费模拟、风险指标计算
- **智能选股器**：基于 AI 的多维度股票筛选，支持自然语言描述选股条件
- **多 LLM 支持**：统一接口适配 DeepSeek、OpenAI、Google Gemini、DashScope、Anthropic 等模型

## 技术架构

- **后端**：FastAPI + MongoDB (Motor 异步驱动) + Redis 缓存
- **认证**：JWT Token 鉴权
- **前端**：Vue.js 单页应用
- **部署**：Docker 一键部署，支持 vLLM 本地模型推理

## 技术栈

`Python` `FastAPI` `MongoDB` `Motor` `Redis` `JWT` `Vue.js` `Docker` `vLLM` `多 LLM API`
