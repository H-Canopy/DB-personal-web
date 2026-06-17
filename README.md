
[DB-personal-web-README.md](https://github.com/user-attachments/files/29028471/DB-personal-web-README.md)
<div align="center">

# DB — AI × Content × Dev

邓博文 · 个人数字门户

<img src="https://img.shields.io/badge/AI_Agent-C5A880?style=flat-square" alt="">
<img src="https://img.shields.io/badge/Content_Creator-C5A880?style=flat-square" alt="">
<img src="https://img.shields.io/badge/Full_Stack_Dev-C5A880?style=flat-square" alt="">
<img src="https://img.shields.io/badge/Vanilla_JS-C5A880?style=flat-square" alt="">

</div>

---
DB🌐 在线网站 https://h-canopy.github.io/DB-personal-web/
## 这是什么

一份**个人品牌网站**。一个 HTML 文件，双击浏览器打开就能看到全貌。

它不是简历，不是作品集 PDF，是一个**可交互的数字身份**：从鎏金圣纹开屏的仪式感，到 Canvas 粒子场的沉浸浏览，到项目时间线的结构化展示——每个模块都在回答一个问题：「这个人是谁、能做什么、为什么值得信赖。」

> 配色：`#0E0E0E` / `#C5A880` / `#F5F4F0` · 字体：Syne · Bodoni Moda · Plus Jakarta Sans

---

## 它长什么样

12 个板块，从仪式感到信息密度逐层展开：

```
   鎏金圣纹开屏       →  点击拉幕，仪式感入场
   Dark Hero          →  Canvas 粒子场 + 二进制纹理 + 随机格言
   Light Hero         →  个人定位 + 数据指标 + 轨道技能标签
   能力矩阵            →  AI / 内容 / 开发 三栏卡片
   关键词 Marquee      →  双向滚动品牌词
   盟友圈              →  深度共创伙伴
   项目 & 竞赛         →  6 项作品时间线
   关于                →  学术背景 + 神话太阳图腾
   视觉实验场           →  预留作品展示位
   Growth Engine       →  破圈资料领取卡片
   同频共振            →  联系方式 + 拖拽徽章
   Footer              →  导航 · 品牌 · 连接
```

---

## 视觉模块速览

| 模块 | 技术 | 一句话 |
|------|------|--------|
| 鎏金圣纹开屏 | SVG + CSS Animation | 八芒星魂环、丁达尔光束、金粒飘散、幕布拉开入场 |
| 粒子 Dark Hero | Canvas 2D | 鼠标驱散粒子群、二进制数字雨纹理、格言浮层 |
| 奇点轨道图 | SVG + CSS Keyframes | 技术标签沿 6 条椭圆轨道公转、4 层深度、脉冲光晕 |
| 神话太阳图腾 | SVG Animation | 四层火焰独立摇曳、hover 褪色过渡 |
| 拖拽徽章 | JS Drag API | SVG 文字路径环绕、可拖拽 |
| 鼠标跟随太阳 | Mouse Events | 光标双层反向旋转太阳 |
| 双行 Marquee | CSS Animation | 正反向无限滚动关键词 |
| 滚动渐入 | Intersection Observer | fade-up 序列化入场 |

---

## 数据一览

| | | | |
|:---:|:---:|:---:|:---:|
| 🏫 湖北文理学院 | 🎓 大二在读 | 📍 湖北 · 襄阳 | 🎂 20 岁 |
| 计算机科学与技术 | 2024 – 2028 | CET-4 | |

| 内容发布 | 小红书 | 公众号 | 竞赛 |
|:---:|:---:|:---:|:---:|
| **24 篇** | **10 篇 · 3K+** | **14 篇 · 300 粉** | **6 项** |

---

## 项目 & 竞赛

| № | 项目 | 标签 | 时间 |
|:---:|---|------|:---:|
| 01 | **睿抗机器人开发者大赛** — 大模型及智能体应用，技术开发负责人，搭建配套网站 | `国家级` | 2026 |
| 02 | **计算机设计大赛 · 微课《走进重庆》** — 策划·拍摄·剪辑全流程独立完成 | `微课类` | 2026 |
| 03 | **微信小程序开发** — AI 辅助编程全栈实践，个人独立开发者 | `个人项目` | — |
| 04 | **校园二手交易平台** — Spring Boot + MySQL 前后端全栈 | `全栈` | — |
| 05 | **美国大学生数模竞赛 (MCM/ICM)** — 团队数学建模 | `建模` | — |
| 06 | **蓝桥杯 · Java 组** — 算法与数据结构，省级选拔 | `算法` | — |

---

## 技术栈

| 层级 | 内容 |
|:---:|------|
| 语言 | HTML5 · CSS3 · Vanilla JavaScript (ES6+) |
| 动画 | CSS Keyframes · SVG Animation · Canvas 2D · `requestAnimationFrame` |
| 交互 | Intersection Observer · Drag API · Mouse Events |
| 字体 | Syne · Bodoni Moda · Plus Jakarta Sans (Google Fonts) |
| 配色 | `#0E0E0E` · `#C5A880` · `#F5F4F0` · `#161616` · `#7A7A77` |
| 部署 | GitHub Pages / 任意静态服务器 |

---

## 本地运行

```bash
git clone https://github.com/H-Canopy/DB-personal-web.git
cd DB-personal-web

# macOS
open DB-web.html
# Windows
start DB-web.html
# 或任意静态服务
npx serve .
```

> 单文件 · 零依赖 · 零构建 · 浏览器直接打开

---

## 三个设计约束

用这套视觉的人需要守住三条底线——它们不是建议，是边界：

1. **暖金 #C5A880 不超过画面 10%** — 它是锚点，不是装饰色
2. **黑不是纯黑** — 用 `#0E0E0E` 而非 `#000`，避免刺眼的死黑感
3. **✦ 只用在签名和关键转折** — 不当装饰符号到处撒

破了任意一条，这套黑金美学的克制感就散了。

---

## 怎么用

### 用法 1：直接看

```bash
git clone https://github.com/H-Canopy/DB-personal-web.git
open DB-web.html
```

### 用法 2：参考它的设计规范

这份 HTML 本身就是一份**可执行的设计规范**——CSS 变量区定义了全部色彩/字体/间距，`section` 结构定义了页面节奏。fork 之后改 `:root` 里的 5 个色值，你就能得到一套完全不同配色但结构完整的个人网站。

### 用法 3：搭配通用模版启动你自己的

同仓库提供了一份[个人品牌网站通用 HTML 模版](https://github.com/H-Canopy/DB-personal-web)，保留了 Hero / About / Capabilities / Projects / Contact / Footer 六大板块结构，去掉了个性化动效，任何人都能 10 分钟填完上线。

### 用法 4：喂给 AI Agent 生成衍生品

把这份 HTML 扔给 Claude Code / 牛马 AI，告诉它：「按 DB-web.html 的配色和字体规范，给我生成一张小红书封面」——它能读懂。

---

## 设计哲学

```
黑金体系
  黑 (#0E0E0E) = 技术深度、专注、克制
  金 (#C5A880) = 温度、质感、人文

东西融合
  鎏金圣纹 · 太阳图腾 × Syne · Bodoni Moda

叙事节奏
  不开屏直接看 = 工具站
  开屏 → 粒子 → 信息 = 品牌叙事

纯原生
  不用 React/Vue 不是不会
  是这个场景不需要
```

---

## 联系方式

| | |
|---|---|
| 📕 小红书 | **@邓博文** |
| 📰 公众号 | 技术向内容 |
| 📧 Email | 见网页内联系方式 |
| 🐙 GitHub | [@H-Canopy](https://github.com/H-Canopy) |

---

## License

MIT — fork、改写、商用均可。

但如果你基于它做自己的网站，请把你的名字、色彩、定位写清楚，别让它退化回「感觉对了就行」。

---

<div align="center">
  <sub>Built with ✦ by Deng Bowen · 2025 – 2026</sub>
</div>
