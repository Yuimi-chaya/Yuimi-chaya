<h1 align="center">Hi there 👋, I'm</h1>

<p align="center">
  <a href="https://github.com/Yuimi-chaya">
    <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=34&duration=2600&pause=1100&color=7C3AED&center=true&vCenter=true&width=520&height=52&lines=Yuimi+Chaya" alt="Yuimi Chaya" />
  </a>
</p>

<p align="center">
  <strong>Open-source contributions · Agent development policies · LLM role-play</strong><br>
  Turning real use into projects and writing.
</p>

<p align="center">
  <a href="https://yuimi-chaya.github.io">Personal blog / Yuimi Lab</a> ·
  <a href="https://github.com/BigPizzaV3/CodexPlusPlus">CodexPlusPlus</a> ·
  <a href="./README.md">简体中文</a>
</p>

## 👤 About

I'm **Yuimi Chaya**. Most of my work starts with tools I use and problems I encounter: contributing to open source, developing ways of working with agents, and exploring LLM character interaction.

I use **AI agents as my primary implementation tools**. I handle problem decomposition, direction and constraints, interaction quality, acceptance testing, and revisions after review. I also prepare assets, references, and counterexamples to keep the implementation grounded in its intended use.

Paid technical work through online platforms helps fund my open-source maintenance, agent workflows, and LLM role-play research. I write about the process and discoveries on my personal blog.

## 🚀 Open Source & Projects

### 🔧 [CodexPlusPlus](https://github.com/BigPizzaV3/CodexPlusPlus) · Open-source contributions

A third-party desktop tool closely related to Codex CLI and Codex App, with model-provider management, session management, and additional features. I contribute to its ongoing maintenance, taking problems from daily use through to upstream changes.

**30k+ project stars · 29 personal commits merged upstream**<br>
<sub>Project stars recorded on September 9, 2026; personal commit count as of September 8, 2026.</sub>

[Contribution experience and retrospective (Chinese)](https://yuimi-chaya.github.io/blog/codexplusplus-open-source-learning/)

<details>
<summary>Selected merged changes</summary>

- [#1822 · Provider-scoped per-model routing](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1822): added model-specific routing and addressed validation and first-start consistency issues found in review.
- [#1519 · Provider state sync and projectless task recovery](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1519): handled provider switching, session migration, relaunch, and failure recovery.
- [#1556 · Custom-provider web search restoration](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1556): restored custom Responses search behavior and handled `-lite` behavior and provider boundaries.

</details>

### 🧭 [codex-development-guidelines](https://github.com/Yuimi-chaya/codex-development-guidelines) · Agent development policies

A portable **agent development policy reference**, paired with an `adopt-agent-policy` Skill for installing and configuring those policies.

It covers six areas: **context and memory; delegation and tools; media and transport; environment and friction; files and recovery; validation and resources**.

The core distinction is between **how an agent acts during work** and **how those rules should be configured**. Runtime policies govern behavior; the installation Skill asks about user preferences and configures policies for the current environment.

The principles are not tied to a model provider, operating system, or agent product. Installation does not simply overwrite existing instructions. The starting point is always the actual environment and the user's preferences.

### 🧠 [LLM RP Role Prompt Authoring](https://github.com/Yuimi-chaya/llm-rp-role-prompt-authoring) · Character-chat prompt authoring

Inspired by **HDS Interlude (HDSI)**, this project brings together long-running LLM role-play and AstrBot character-interaction service experience through personal experiments. It provides an authoring approach for natural one-to-one character chat, along with a ready-to-use bilingual Skill.

Instead of directly telling the model "you are X" or "you will role-play X," it uses a **writer's perspective**: the model uses the conversation, system prompt, available tools, and user input to continue what the character would say next.

The key is to separate **the person in the conversation** from **the executor running that character**. Platform details, tools, and memory are backstage working conditions; the user-facing output remains the character's direct message. This separation explores a way to reduce switching between those roles and support more coherent, natural interaction.

[Research and practice article (Chinese)](https://yuimi-chaya.github.io/blog/llm-rp-role-prompt-authoring-researchzh-cn/)

### 🎨 [Personal blog / Yuimi Lab](https://yuimi-chaya.github.io) · Design and writing

An **Astro** personal blog with multiple distinct theme designs. Each theme has its own layouts, styles, runtime, and visual language while sharing the same article collection.

I lead **visual acceptance, interaction feel, asset preparation, and styling direction**, with AI assisting code generation. The site includes scroll-driven scenes, audio, and small interactive experiences, with continued attention to responsive layouts, reduced-motion preferences, and performance.

The source is open, and I keep publishing articles about open-source collaboration, agent workflows, and LLM character interaction. The site grows alongside the experiences I document.

[Visit the blog](https://yuimi-chaya.github.io) · [Browse the source](https://github.com/Yuimi-chaya/Yuimi-chaya.github.io)

## 📝 Writing & Retrospectives

The following articles are in Chinese:

- [Beyond rigid agent rules: from a rule set to a way of making decisions](https://yuimi-chaya.github.io/blog/agents-development-guidelines/): AGENTS.md, subagents, media budgets, and portable development policies.
- [The model need not become the character: rethinking LLM private chat from a writer's perspective](https://yuimi-chaya.github.io/blog/llm-rp-role-prompt-authoring-researchzh-cn/): inspiration from HDSI, the writer's perspective, and natural character interaction.
- [Notes on using Codex App in the GPT-5.6 era](https://yuimi-chaya.github.io/blog/codex-app-usage-notes/): experience with projects, threads, notes, and subagents.
- [After building a blog with Vibe Coding, prompt sharing was not the main thing I wanted to discuss](https://yuimi-chaya.github.io/blog/vibe-coding-blog-notes/): ideas, counterexamples, screenshots, assets, and repeated revisions.
- [After a year of AstrBot plugin work, the most valuable part was not the code](https://yuimi-chaya.github.io/blog/astrbot-plugin-dev-experience/): stability, constraints, and real delivery.
- [Writing first-person personas for single-model role-play](https://yuimi-chaya.github.io/blog/astrbot-roleplay-persona-notes/): persona prompts, character expression, and choosing constraints.
