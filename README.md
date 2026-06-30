# OPC 内容自动化发布矩阵

> 一套方案，覆盖四大内容平台。从创作到发布的全自动流水线。

## 概述

OPC 内容自动化发布矩阵是一套基于浏览器自动化的多平台内容分发方案，帮助内容团队在多个内容平台（百家号、小红书、知乎、今日头条）间实现高效、安全、标准化的发布流程。

## 功能特性

| 技能 | 平台 | 核心能力 |
|------|------|----------|
| 百家号发布器 | 百度百家号 | SEO 关键词注入，封面 900x500 |
| 小红书发布器 | 小红书 | 内容精简 ≤1000 字，封面 1080x1440 |
| 知乎发布器 | 知乎 | 文章/回答双模式，轻量 <25MB |
| 今日头条发布器 | 今日头条 | 标题 SEO 优化，封面 1200x750 |

## 快速开始

```bash
# 解压技能包
unzip opcskill_optimized.zip

# 每个技能独立使用，参见各技能目录下的 SKILL.md
```

## 本地访问

直接在浏览器中打开 `index.html` 即可查看客户方案介绍页面。

## GitHub Pages 部署

本仓库已配置 GitHub Actions，推送到 `main` 分支后自动部署到 GitHub Pages。

部署 URL: `https://<你的用户名>.github.io/opc-skill-matrix/`

### 手动部署

```bash
git init
git add .
git commit -m "Initial commit: OPC 内容自动化发布矩阵"
git branch -M main
git remote add origin https://github.com/<你的用户名>/opc-skill-matrix.git
git push -u origin main
```

## 技术栈

- 纯前端 HTML + CSS，零依赖
- Python 自动化脚本（各 skill 目录下）
- 基于 Selenium / Playwright 浏览器自动化
- Pillow 封面图生成
- GitHub Pages 自动部署
