<h1 align="center">Hi there 👋, I'm</h1>

<p align="center">
  <a href="https://github.com/Yuimi-chaya">
    <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=34&duration=2600&pause=1100&color=7C3AED&center=true&vCenter=true&width=520&height=52&lines=Yuimi+Chaya" alt="Yuimi Chaya" />
  </a>
</p>

<p align="center">
  <strong>开源贡献 · Agent 开发准则 · LLM 角色交互</strong><br>
</p>

<p align="center">
  <a href="https://yuimi-chaya.github.io">个人博客 / Yuimi Lab</a> ·
  <a href="https://github.com/BigPizzaV3/CodexPlusPlus">CodexPlusPlus</a> ·
  <a href="./README.en.md">English</a>
</p>

## 👤 关于我

我是 **Yuimi Chaya**。我的工作大多从自己正在使用的工具和真实需求开始：参与开源维护、研究 Agent 协作方式，也长期实践 LLM 角色交互。

我以 **AI Agent 为主要实现工具**，负责问题拆解、方向与约束、交互体验判断、测试验收，以及审查后的返工。我也会提供素材、参考与反例，让实现贴合具体的使用场景。

通过线上平台接单解决客户需求，我获得了继续实践的收入，再将所得投入开源项目维护、Agent 工作流和 LLM RP 研究。遇到值得记录的问题，就把过程与发现写进个人博客。

## 🚀 开源与项目

### 🔧 [CodexPlusPlus](https://github.com/BigPizzaV3/CodexPlusPlus) · 开源贡献

与 Codex CLI / Codex App 紧密相关的第三方桌面工具，提供模型供应商管理、会话管理与扩展功能。我持续参与项目维护，将实际使用中遇到的问题推进为上游改动。

**项目 30k+ stars · 个人 30 个上游合并提交**<br>
<sub>项目规模记录于 2026-09-09；个人提交统计截至 2026-09-08。</sub>

[贡献经历与复盘](https://yuimi-chaya.github.io/blog/codexplusplus-open-source-learning/)

<details>
<summary>查看部分合入记录</summary>

- [#1822 · 供应商内按模型路由](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1822)：让不同模型使用各自的路由配置，并根据审查修复校验与首次启动一致性问题。
- [#1519 · 供应商状态同步与无项目任务恢复](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1519)：处理供应商切换、会话迁移、重启与失败恢复。
- [#1556 · 自定义供应商 Web Search 恢复](https://github.com/BigPizzaV3/CodexPlusPlus/pull/1556)：恢复自定义 Responses 的搜索行为，并处理 `-lite` 行为与供应商边界。

</details>

### 🧭 [codex-development-guidelines](https://github.com/Yuimi-chaya/codex-development-guidelines) · Agent 开发准则

一个可移植的 **Agent 开发准则参考库**，以及用于安装、配置这些准则的 `adopt-agent-policy` Skill。

覆盖六个板块：**上下文与记忆、委派与工具、媒体与传输、环境与阻力、文件与恢复、验证与资源**。

核心设计是把 **工作期间如何行动** 与 **这些规则应如何配置** 分开：运行时规范约束 Agent 的行为，安装 Skill 通过询问发现用户偏好，并结合当前环境配置准则。

行为原则不绑定某个模型提供商、操作系统或 Agent 产品；已有指令也不会在安装时被直接覆盖。一切从真实环境与用户偏好出发。

### 🧠 [LLM RP Role Prompt Authoring](https://github.com/Yuimi-chaya/llm-rp-role-prompt-authoring) · 角色聊天 Prompt 方法

受 **HDS Interlude（HDSI）** 启发，将长期 LLM RP 与 AstrBot 角色交互服务中的经验，通过个人实验整理为面向自然一对一角色聊天的 Prompt 作者工程，并提供可直接使用的双语 Skill。

与直接要求模型“你是 XXX”“你将扮演 XXX”相比，这套方法采用**写作者视角**：模型根据上下文、系统提示词、可用工具与用户输入，续写当前角色此刻会说出的话。

重点是分开 **聊天中的人物** 与 **负责运行人物的执行者**：平台、工具和记忆是后台工作条件，面向用户的输出仍然是角色直接发送的消息。通过这种分工，探索如何减少两个身份之间的来回切换，让互动更连贯自然。

[研究与实践文章](https://yuimi-chaya.github.io/blog/llm-rp-role-prompt-authoring-researchzh-cn/)

### 🎨 [个人博客 / Yuimi Lab](https://yuimi-chaya.github.io) · 设计与写作

基于 **Astro** 构建的个人博客，拥有多套风格不同的主题设计。不同主题拥有各自的布局、样式、运行时与视觉语言，共享同一份文章内容。

我主导**视觉验收、交互手感、素材准备与样式方向设计**，AI 协助生成代码。站点包含滚动场景、音频与小型互动，也持续关注响应式适配、低动态偏好与性能。

博客源码开源，文章持续更新。我会把开源协作、Agent 工作流、LLM 角色交互中的经验与发现整理出来，让作品与写作一起积累。

[访问博客](https://yuimi-chaya.github.io) · [查看源码](https://github.com/Yuimi-chaya/Yuimi-chaya.github.io)

## 📝 文章与复盘

- [不把 Agent 写死,从一套规则到一套判断方法](https://yuimi-chaya.github.io/blog/agents-development-guidelines/)：从 AGENTS.md 与子代理，到媒体预算和可迁移的开发准则。
- [不必让模型成为角色：从写作视角重新理解 LLM 私聊](https://yuimi-chaya.github.io/blog/llm-rp-role-prompt-authoring-researchzh-cn/)：HDSI 的启发、写作视角与角色聊天中的自然感。
- [GPT5.6时期 Codex App 的一些使用心得](https://yuimi-chaya.github.io/blog/codex-app-usage-notes/)：项目、线程、笔记与子代理的使用经验。
- [用 Vibe Coding 写博客后,我最想说的不是“分享提示词”](https://yuimi-chaya.github.io/blog/vibe-coding-blog-notes/)：想法、反例、截图、素材与反复返工。
- [我做 AstrBot 插件这一年,最值钱的其实不是代码](https://yuimi-chaya.github.io/blog/astrbot-plugin-dev-experience/)：插件开发中的稳定性、约束与真实交付。
- [适用于单模型角色扮演第一人称人设的写作参考](https://yuimi-chaya.github.io/blog/astrbot-roleplay-persona-notes/)：人设提示词、角色表达与限制词的取舍。
