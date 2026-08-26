# Yuimi Chaya

<p align="center">
  <strong>Open-source engineering · Interactive frontend · Hands-on LLM / Agent practice</strong><br>
  开源工程 · 交互式前端 · LLM 与 Agent 实践
</p>

<p align="center">
  <a href="https://yuimi-chaya.github.io">Yuimi Lab</a> ·
  <a href="https://github.com/Yuimi-chaya/Yuimi-chaya.github.io">Blog source</a> ·
  <a href="https://github.com/BigPizzaV3/CodexPlusPlus">CodexPlusPlus</a>
</p>

## About / 关于我

I'm **Yuimi Chaya**, an independent developer working across open-source engineering, interactive frontend experiences, and practical LLM / Agent experimentation.

我是 **Yuimi Chaya**，一名独立开发者，主要进行开源工程、交互式前端体验，以及 LLM 与 Agent 的实践探索。

Most of my work starts with something I actually use. I trace the behavior through an existing system, turn the problem into a concrete implementation, test it in real use, and keep iterating through review.

我的很多工作都从真实使用中遇到的问题开始：沿着现有系统追踪行为，把问题落实为可运行的实现，在实际环境中测试，并根据审查与反馈继续迭代。

## Working Areas / 实践方向

| Area / 方向 | What I work on / 实践内容 |
| --- | --- |
| **Open-source engineering / 开源工程** | Desktop developer tools, runtime behavior, compatibility fixes, state consistency, and maintainable changes inside existing codebases.<br>桌面开发者工具、运行时行为、兼容性修复、状态一致性，以及尊重既有架构的可维护改动。 |
| **Interactive frontend / 交互式前端** | Multi-theme web experiences, state-driven motion, Canvas / WebGL, audio, responsive behavior, and interaction details.<br>多主题 Web 体验、状态驱动动效、Canvas / WebGL、音频、响应式适配与交互细节。 |
| **LLM / Agent practice / LLM 与 Agent 实践** | Persona prompts, tool-use continuity, memory behavior, model failure modes, and AI-assisted developer workflows.<br>人设提示词、工具调用连续性、记忆行为、模型失效模式与 AI 辅助开发工作流。 |

## Selected Work / 代表工作

### [CodexPlusPlus](https://github.com/BigPizzaV3/CodexPlusPlus) - Open-source engineering / 开源工程

I contribute to the ongoing maintenance of a real-world Tauri desktop project. My merged work crosses Rust core logic, React / TypeScript UI, Tauri commands, SQLite state, renderer integration, tests, and CI.

我参与这个真实使用中的 Tauri 桌面项目的持续维护。已合入的工作横跨 Rust 核心逻辑、React / TypeScript 界面、Tauri 命令、SQLite 状态、渲染层集成、测试与 CI。

- [Provider-scoped per-model routing (#1822)](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1822): added routing at model granularity, then fixed validation and first-start consistency issues found during review with restart, rollback, and regression tests.
- [Live provider state sync and projectless task recovery (#1519)](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1519): handled provider switching, session migration, transactional persistence, relaunch behavior, rollback, and diagnostics.
- [Custom Responses web search restoration (#1556)](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1556): restored web-search behavior for custom providers, added `-lite` handling, and protected provider boundaries with tests and CI coverage.
- Other merged work includes task-index cleanup safeguards, Codex model compatibility, image overlay modes, and animated pet runtime compatibility.

这些贡献并不只展示最终代码，也保留了从真实问题、实现、外部审查、修正到合入的完整过程。

### [Yuimi Lab](https://yuimi-chaya.github.io) - Interactive personal site / 交互式个人站点

[Source](https://github.com/Yuimi-chaya/Yuimi-chaya.github.io) · `Astro` `TypeScript` `Canvas` `WebGL` `Pagefind`

Yuimi Lab is a multi-theme personal site where writing, themed presentation, sound, scenes, and small interactive experiences live together. Its themes are not recolors: each owns its layouts, styles, runtime, and visual language while sharing the same content collection.

Yuimi Lab 是一个把文章、主题化呈现、声音、场景与小型互动放在一起的多主题个人站点。不同主题并非简单换色，而是各自拥有独立的布局、样式、运行时和视觉语言，同时共享同一份内容。

The site includes scroll-driven scenes, Canvas and WebGL effects, persistent audio controls, mini-games, responsive layouts, reduced-motion handling, lifecycle cleanup, and performance checks.

站点包含滚动驱动场景、Canvas 与 WebGL 效果、持久化音频控制、小游戏、响应式布局、低动态偏好适配、生命周期清理与性能检查。

### LLM, Agent, and developer-practice notes / LLM、Agent 与开发实践记录

These notes document hands-on observations and experiments from real LLM / Agent use. They focus on persona-prompt design, role-play consistency, memory and tool-use failures, plugin reliability, and ways of organizing AI-assisted development.

这些文章记录真实 LLM 与 Agent 使用中的实践观察和实验，主要涉及人设提示词设计、角色扮演一致性、记忆与工具调用问题、插件可靠性，以及 AI 辅助开发的组织方式。

- [给 AstrBot 写人设提示词这件事，我踩过的一些坑](https://yuimi-chaya.github.io/blog/astrbot-roleplay-persona-notes/)
- [我做 AstrBot 插件这一年，最值钱的其实不是代码](https://yuimi-chaya.github.io/blog/astrbot-plugin-dev-experience/)
- [用 Vibe Coding 写博客后，我最想说的不是“分享提示词”](https://yuimi-chaya.github.io/blog/vibe-coding-blog-notes/)
- [Codex App 用久以后，我留下的这些使用习惯](https://yuimi-chaya.github.io/blog/codex-app-usage-notes/)

## How I Work / 我的工作方式

AI is part of my implementation workflow, but it does not replace product or engineering judgment. I define the direction and constraints, provide references and counterexamples, inspect the source and diffs, test real behavior, and decide whether a result is actually acceptable.

AI 是我实现工作流的一部分，但不会替代产品与工程判断。我负责确定方向与约束、提供参考和反例、检查源码与差异、测试真实行为，并判断结果是否真正达到要求。

`Rust` · `TypeScript` · `React` · `Tauri` · `Astro` · `SQLite` · `Canvas` · `WebGL`

---

<p align="center">
  <sub>Start from real use. Keep the evidence inspectable.<br>从真实使用出发，让能力留下可以核验的证据。</sub>
</p>
