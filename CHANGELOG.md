# 更新日志 · 蓝纸

所有可感知的版本变化都记录在这里。格式参考 [Keep a Changelog](https://keepachangelog.com/zh-CN/1.1.0/)。

## [v1.1-motion] 2026-09-28 · 动效深化

> 借鉴来源：[morphicons](https://github.com/guillermolg00/morphicons)（⭐2.7k，弹簧物理图标变形，零依赖）与 [awesome-opus-5-5-prompts](https://github.com/TripoGrowthLab/awesome-opus-5-5-prompts)（Opus 5.5 视觉特效 prompt 集，取其"呼吸体 / 行星轨道 / 笔刷扫过"三个创意转化为轻量实现）。

### Added
- **主题切换图标变形**：月亮 ☾ ↔ 太阳 ☀ 用 morphicons 弹簧物理平滑变形（`<morph-icon>` 自定义元素，CDN ESM 引入）；加载失败自动降级为双图标切换，零风险渐进增强。
- **卡片轨道微动**：首屏四张悬浮卡各获得一条错开相位的极慢轨道（8–14s 周期），呼应"行星环绕"意象；与鼠标视差互不干扰（轨道在外层 wrapper，视差在内层 translate）。
- **墨晕呼吸**：首屏两团墨晕升级为多层错相位呼吸（scale + opacity 缓慢起伏），从"静止的晕"变为"活的晕"。
- **墨迹高亮扫过**：首次开信时，标题关键词的蓝色高亮像笔触一样从左到右扫出。

## [v1.0-lanzhi] 2026-09-28 · 蓝纸基线

### Added
- 站点本体：编辑排版风（暖米白纸面 + 墨色 + 点睛蓝），超大标题 + 左右分栏首屏 + 四张悬浮 UI 产物卡。
- 匿名化人格「蓝纸」，栏目诗意化：造物 / 底色 / 札记 / 来路 / 信箱；页脚落款"见字如面。"+ 印章。
- 开信仪式（首访一次性编排：信头线绘出、错峰登场，回访跳过）、信头日期"写于 2026 年秋 · 广州"。
- 造物 5 件（OpenJob / 电商增长分析框架 / Focus Room / 朝夕 / 数据研究两篇），悬停实景预览卡 + "线上体验"入口。
- 底色数据条与三张能力卡；札记 2 篇（大模型三层次 / OpenJob 复盘）+ 数据研究案例页。
- 暗色模式（localStorage 记忆）、阅读进度条、墨晕氛围、跑马灯（视口自适应无缝）、栏目引言。
- 基建：giscus 评论区、RSS / sitemap / robots、自定义 404、不蒜子统计、简历 PDF 下载、OG 分享卡、无障碍（跳转链接 / 焦点样式 / reduced-motion 降级）。
- 部署：GitHub Pages（batianxieshen1.github.io/blog）。
