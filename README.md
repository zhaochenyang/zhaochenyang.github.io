# zhaochenyang.github.io

个人主页「记忆小溪」，基于 Hexo（Next 主题）构建，仓库中存放的是构建产物，由 GitHub Pages 直接发布。

## 站点结构

- `/` — 博客首页（技术笔记）
- `/cs329z/` — **CS329Z 中文教程专栏**：Stanford《Engineering AI Agents》讲义的中文讲解教程
  - `/cs329z/lecture01/` — 第一讲：Intro to Agentic Systems（71 页幻灯片 + 中文讲解）
  - 课程源头：[cs329z.stanford.edu](https://cs329z.stanford.edu/)
- `/archives/` — 文章归档
- `/css/custom-site.css` — 全站自定义皮肤（墨绿简约风格，覆盖主题默认样式）

## 已集成模块

| 模块 | 说明 |
|---|---|
| 访问统计 | Google Analytics (GA4)，注入于全站页面 `</head>` 前。**占位符 `G-XXXXXXXXXX` 需替换为自己的测量 ID** |
| 评论 | [Giscus](https://giscus.app)（基于 GitHub Discussions，映射方式为 pathname），注入于文章页与 cs329z 专栏页 `</body>` 前 |
| 皮肤 | `/css/custom-site.css`，全站页面通过 `<link rel="stylesheet">` 引用 |

## 维护说明

- 本仓库为构建产物，如需修改文章内容，请在 Hexo 源码仓库中修改后重新构建发布；仅小修（标题、注入片段等）可直接改本仓库 HTML。
- cs329z 专栏教程为自包含 HTML（内联 CSS + 相对路径图片），可直接在本地离线阅读，制作规范见专栏项目中的 `CONVENTIONS.md`。
