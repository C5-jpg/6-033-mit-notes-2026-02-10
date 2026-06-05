<div align="center">

# 📖 MIT 6.033 — Computer System Engineering 课程笔记

**23 讲完整 LaTeX 笔记 · 原版课件 · 经典论文 · 作业与考试**

[![LaTeX](https://img.shields.io/badge/LaTeX-pdfLaTeX-008080.svg)](https://www.latex-project.org/)
[![MIT](https://img.shields.io/badge/MIT-6.033-A31F34.svg)](https://ocw.mit.edu/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC-green.svg)]()

**MIT 计算机系统工程课程完整自学资料 (2005/2009 学期)**

</div>

---

## 📋 课程概述

本仓库包含 **MIT 6.033 Computer System Engineering** 课程的全套学习资料，覆盖 23 讲课程内容的详细 LaTeX 笔记、原版课件、课程教材、经典论文阅读材料、作业和考试答案。

> 注意：笔记为自学时撰写，侧重于知识梳理而非语法精确性。

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
│       ├── main.tex         # LaTeX 源文件
│       └── main.pdf         # 编译后 PDF
│
├── 📊 原版课件
│   └── slides/L1.pdf ... L23.pdf
│
├── 📘 课程教材
│   └── textbook/
│       └── computer-system-design.pdf
│
├── 📄 作业与考试
│   ├── assignments/         # 课后作业
│   └── exams/               # 考试及答案
│
└── 📰 经典论文 (12篇)
    └── recitations/
        ├── End-to-End Arguments.pdf
        ├── System R.pdf
        ├── UNIX Time-Sharing.pdf
        ├── RAID.pdf
        └── ...
```

---

## 🚀 使用方法

```bash
# 直接阅读 PDF
open notes/L1/main.pdf
open slides/L1.pdf

# 重新编译笔记 (需要 LaTeX 环境)
cd notes/L1 && latexmk -pdf main.tex
```

---

<div align="center">

**⭐ 如果这些笔记对您的学习有帮助，请给个 Star！**

</div>
