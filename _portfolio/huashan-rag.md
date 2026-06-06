---
title: "华山 RAG 文档检索系统"
excerpt: "基于 LlamaIndex + Qdrant 的检索增强生成（RAG）服务，支持文档摄取、语义检索和带引用的智能问答。"
collection: portfolio
tags:
  - Python
  - FastAPI
  - LlamaIndex
  - Qdrant
  - RAG
  - Docker
---

## 项目概述

华山 RAG 系统是一个生产级的检索增强生成服务，使用 LlamaIndex 作为编排框架，Qdrant 作为向量数据库，FastAPI 提供 REST API 接口。系统支持文档摄取、语义检索和带引用来源的智能问答。

## 技术架构

- **编排层**：LlamaIndex — 文档解析、Chunking 策略、检索与生成管线
- **向量数据库**：Qdrant — 高性能向量存储与相似度检索
- **API 层**：FastAPI — 异步 REST 端点（ingest / retrieve / chat）
- **部署**：Docker Compose 一键部署

## 核心特性

- **编号标题解析器**：自定义 Parser 处理带编号的 Markdown 标题
- **Chunk 前缀注入**：为每个 Chunk 注入 `[PAGES]`、`[DOC]`、`[PATH_IDS]` 等上下文元数据
- **可追溯元数据**：Qdrant payload 中存储完整文档溯源信息
- **PDF 引用定位**：返回引用所在的精确页码和段落位置
- **幂等 Upsert**：重复摄取同一文档不会产生冗余数据

## 技术栈

`Python` `FastAPI` `LlamaIndex` `Qdrant` `Docker` `AsyncIO`
