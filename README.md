# Serena Design System Skill

这是 Serena 的个人设计 skill，用来让 AI 在制作 HTML 页面、个人网站、教程页、Landing Page、App 型页面和小红书图文卡片时，统一使用 Serena 的品牌色、字体、头像、组件和排版规则。

这个版本基于不二的 Esther Design Skill 改造而来：

https://github.com/esthersjw/esther-design-system

原始工作流和文件结构作为基础保留，`brand-dna.md`、`assets/`、`references/` 和模板文件已按 Serena 的个人 IP 重新调整。

## Demo

这些文件可以直接在浏览器打开，也可以作为 agent 生成页面时的真实参照：

- 组件库全览：`components-preview.html`
- 布局/组件 Playground：`demo-layouts.html`
- 活动页 / Landing 起点：`demo-landing.html`
- App 型 / 功能型起点：`demo-app.html`
- 小红书图文卡片起点：`demo-cards.html`

## 使用方式

做页面前先读 `SKILL.md`，再根据任务类型读取对应场景文件：

- 教程/介绍/科普：`references/scene-tutorial.md`
- 活动页/Landing：`references/scene-landing.md`
- App 型/功能型：`references/scene-app.md`
- 小红书图文卡片：`references/scene-cards.md`

从 `assets/template-*.html` 复制对应模板开始改，不从零写。

组件总览优先打开根目录的 `components-preview.html` 查看；模板源文件仍保留在 `assets/` 目录中。
