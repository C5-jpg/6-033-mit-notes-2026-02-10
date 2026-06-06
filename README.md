<div align="center">

# 📖 MIT 6.033 — Computer System Engineering 课程笔记

**23 讲完整 LaTeX 笔记 · 原版课件 (23 slides) · 12 篇经典论文 · 作业与考试答案**

[![LaTeX](https://img.shields.io/badge/LaTeX-pdfLaTeX-008080.svg)](https://www.latex-project.org/)
[![MIT](https://img.shields.io/badge/MIT-6.033-A31F34.svg)](https://ocw.mit.edu/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC-green.svg)]()

**MIT 计算机系统工程课程完整自学资料 · 2005/2009 学期**

</div>

---

## 📋 课程概述

本仓库包含 **MIT 6.033 Computer System Engineering** 的全套学习资料：

- 📝 **23 讲详细 LaTeX 笔记** — 涵盖操作系统到分布式系统
- 📊 **23 份原版课件 (slides)** — MIT 官方教学幻灯片
- 📰 **12 篇经典论文** — 包括 End-to-End、System R、UNIX 等里程碑论文
- 📘 **课程教材** — Computer System Design
- 📄 **作业与考试** — 含答案

> 笔记为自学时撰写，侧重于知识梳理而非语法精确性。

### 📚 课程主题

| 模块 | 主题 | 讲次 |
|:---:|------|:---:|
| **操作系统** | OS 基础、UNIX、线程、虚拟内存 | L1-L6 |
| **网络** | 网络基础、路由、TCP/IP、DNS | L7-L12 |
| **安全** | 系统安全、加密、认证 | L13-L16 |
| **分布式** | 分布式系统、一致性、容错 | L17-L20 |
| **综合** | 系统设计原则、案例分析 | L21-L23 |

---

## 📁 项目结构

```
6-033-mit-notes/
│
├── 📝 笔记 (23讲 LaTeX)
│   └── notes/L1/ ... L23/
│       ├── main.tex              # LaTeX 源文件
│       ├── main.pdf              # 编译后 PDF
│       └── images/               # 笔记配图
│
├── 📊 原版课件
│   └── slides/L1.pdf ... L23.pdf   # MIT 官方 slides
│
├── 📘 课程教材
│   └── textbook/
│       ├── computer-system-design.pdf
│       └── chapter7-11.pdf          # 教材章节
│
├── 📄 作业与考试
│   ├── assignments/               # 3 份课后作业
│   └── exams/                     # 2 份考试 (含答案)
│
└── 📰 经典论文 (12篇)
    └── recitations/
        ├── End-to-End Arguments.pdf     # 端到端论证
        ├── System R.pdf                 # 关系数据库
        ├── UNIX Time-Sharing.pdf        # 分时系统
        ├── RAID.pdf                     # 磁盘阵列
        ├── Ethernet.pdf                 # 以太网
        ├── Congestion Control.pdf       # 拥塞控制
        ├── Security.pdf                 # 安全
        └── ...
```

---

## 📰 经典论文列表

| 论文 | 主题 | 影响力 |
|------|------|------|
| **End-to-End Arguments** | 端到端设计原则 | 互联网架构基石 |
| **System R** | 关系数据库实现 | SQL 数据库先驱 |
| **UNIX Time-Sharing** | 分时操作系统 | 现代操作系统鼻祖 |
| **RAID** | 磁盘阵列 | 存储系统基础 |
| **Ethernet** | 局域网技术 | 网络基础设施 |
| **Congestion Control** | TCP 拥塞控制 | 互联网稳定性关键 |
| **Logging** | 日志系统 | 数据恢复基础 |
| **File Sync** | 文件同步 | 分布式文件系统 |
| **Naming** | 命名系统 | 分布式命名服务 |
| **Security** | 系统安全 | 安全架构设计 |

---

## 🚀 使用方法

```bash
# 直接阅读 PDF
open notes/L1/main.pdf              # LaTeX 笔记
open slides/L1.pdf                   # 原版课件
open recitations/End-to-End*.pdf     # 经典论文

# 重新编译笔记 (需要 LaTeX 环境)
cd notes/L1 && latexmk -pdf main.tex
```

---

<div align="center">

**⭐ 如果这些笔记对您的学习有帮助，请给个 Star！**

</div>
