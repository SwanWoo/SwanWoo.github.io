---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# 教育经历

- **澳门科技大学** — 应用数学与数据科学（硕士），2026.09 - 2028.07
- **上海第二工业大学** — 网络工程（本科），计算机与信息工程学院，2021.09 - 2026.07
  - GPA：3.8 / 5.00
  - 关键课程：C语言程序设计、数据结构、算法设计与分析、计算机网络、操作系统、面向对象开发与设计

# 荣誉奖项

- 校级二等奖学金（专业前 10%）
- 蓝桥杯市三等奖
- ASC 世界大学生超级计算机竞赛二等奖
- 数学建模竞赛三等奖

# 实习经历

## 优刻得科技股份有限公司 — AI Infra 实习生
**2025.10 - 至今 · 上海**

- 负责大模型推理加速相关工作，基于 vLLM 等推理框架进行性能优化与部署
- 开发 AI Agent 应用，基于 RAG / GraphRAG 架构构建知识检索与智能问答系统
- 参与模型推理链路的端到端优化，包括请求调度、KV Cache 管理、批处理策略等
- 探索 GraphRAG 等新型检索增强方案，提升多跳推理与复杂关联查询能力

## 上海泛超数字科技有限公司 — 初级系统工程师
**2024.07 - 2025.01 · 上海**

- 使用 vLLM 架构部署大模型推理服务，完成系统环境部署，确保应用稳定运行
- 熟练运用 Linux 运维指令，监控系统资源使用率，保障服务器稳定运行
- 分析网络流量数据，识别异常访问模式，预防潜在网络安全风险
- 分析系统运行进程，排查可疑病毒文件，提升系统整体安全性

# 专业技能

## 编程语言
- **Python**：熟悉 FastAPI、LangChain、LlamaIndex 等框架，具备 RAG / GraphRAG 系统和大模型应用开发经验
- **C/C++**：掌握 STL 常见容器原理、编译过程、CMake/Make，具备面向对象设计与泛型编程能力，熟悉 C++11 标准
- **JavaScript**：Vue.js 前端开发经验

## AI Infra
- 大模型推理部署与加速（vLLM、KV Cache 管理、批处理调度、Tensor Parallelism）
- RAG / GraphRAG 架构设计与开发
- AI Agent 应用开发
- 推理性能分析与优化（Profiling、CUDA Graph、Torch Compile）

## Linux 系统
- 熟练使用 Linux 命令行及常用工具
- 掌握服务管理（systemd、Nginx/Apache、SSH、MySQL/PostgreSQL 等）
- 用户权限与安全加固（iptables、防火墙、SSH Key 登录）
- 具备系统监控、日志分析与故障排查能力，具备 GDB 调试、性能分析经验

## 运维与自动化
- Shell/Python 脚本编写
- 定时任务（crontab）、系统监控（top、htop、iostat）
- 容器基础（Docker）、Git（Git Flow 工作流）

## 网络工程
- 熟悉路由器交换机的 ISIS、OSPF、BGP、IGMP、L3VPN、L2VPN 等路由协议及配置
- 熟悉网络管理、网络安全、系统架构

# 项目经历

  <ul>{% for post in site.portfolio reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# 博客文章

  <ul>{% for post in site.posts reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
