# The Ultimate Codex Resource List

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools, skills, plugins, clients, MCP integrations, automation projects, SDKs, session utilities, and practical guides for OpenAI Codex. Resources are grouped by use case and ordered by GitHub Stars within each category.

**Resources:** 450  
**Updated:** 2026-09-10

> GitHub Star counts reflect the latest metadata refresh and may change over time.

## Table of Contents

- [Official Codex Resources](#category-c01)
- [Skills, Plugins & Collections](#category-c02)
- [Project Instructions, Configuration & Context](#category-c03)
- [Clients, Editors & Remote Access](#category-c04)
- [Workflow Automation & Agent Coordination](#category-c05)
- [MCP Servers & Service Integrations](#category-c06)
- [Usage, Monitoring & Session Tools](#category-c07)
- [SDKs, Adapters & Runtime Infrastructure](#category-c08)
- [Guides, Examples & Learning](#category-c09)

---

<a id="category-c01"></a>
## Official Codex Resources

Start with OpenAI's own documentation, repositories, plugins, and examples for the Codex surface you use.

<!-- resource-id: codex-openai-cli-repository -->
- [**codex**](https://github.com/openai/codex) - (121.6k ⭐) - Lightweight coding agent that runs in your terminal.
<!-- resource-id: codex-openai-claude-code-plugin -->
- [**codex-plugin-cc**](https://github.com/openai/codex-plugin-cc) - (32.8k ⭐) - Use Codex from Claude Code to review code or delegate tasks.
<!-- resource-id: codex-deferred-65f6d9f3ec75 -->
- [**codex-security**](https://github.com/openai/codex-security) - (10.4k ⭐) - OpenAI's Codex Security CLI and TypeScript SDK for finding, validating, and fixing security vulnerabilities.
<!-- resource-id: codex-openai-plugins-repository -->
- [**plugins**](https://github.com/openai/plugins) - (5.4k ⭐) - OpenAI Plugins.
<!-- resource-id: codex-deferred-adb27e84af49 -->
- [**gpt-5-coding-examples**](https://github.com/openai/gpt-5-coding-examples) - (1.9k ⭐) - GPT-5 coding examples.
<!-- resource-id: codex-awesome-openai-codex-universal -->
- [**codex-universal**](https://github.com/openai/codex-universal) - (1.1k ⭐) - Base docker image used in Codex environments.
<!-- resource-id: codex-openai-role-specific-plugins -->
- [**role-specific-plugins**](https://github.com/openai/role-specific-plugins) - (526 ⭐) - Role-specific Codex plugin templates.
<!-- resource-id: codex-openai-agents-md-docs -->
- [**AGENTS.md documentation for Codex**](https://learn.chatgpt.com/docs/agent-configuration/agents-md) - The AGENTS.md guide explains how Codex discovers and layers project instructions from global, repository, and nested directories.
<!-- resource-id: codex-openai-build-skills-docs -->
- [**Build skills for Codex**](https://learn.chatgpt.com/docs/build-skills) - The skills guide explains how to package reusable Codex capabilities with SKILL.md, supporting scripts, and assets.
<!-- resource-id: codex-openai-app-docs -->
- [**Codex app documentation**](https://learn.chatgpt.com/docs/app) - The Codex app documentation explains the desktop workspace for local coding tasks, project context, approvals, and shared Codex settings.
<!-- resource-id: codex-openai-app-server-docs -->
- [**Codex app server documentation**](https://learn.chatgpt.com/docs/app-server) - App server documentation describes the JSON-RPC interface behind Codex clients.
<!-- resource-id: codex-openai-cli-docs -->
- [**Codex CLI documentation**](https://learn.chatgpt.com/docs/codex/cli) - OpenAI's CLI documentation explains local repository work, approvals, sandboxing, skills, plugins, MCP connections, and repeatable terminal workflows.
<!-- resource-id: codex-openai-cloud-docs -->
- [**Codex cloud documentation**](https://learn.chatgpt.com/docs/cloud) - Codex cloud documentation describes delegated repository tasks that run in hosted environments, including setup, repository access, and review of generated changes.
<!-- resource-id: codex-openai-ide-docs -->
- [**Codex IDE documentation**](https://learn.chatgpt.com/docs/codex/ide) - OpenAI's IDE documentation explains how to use Codex inside supported code editors, including installation, sign-in, task execution, and editor-specific controls.
<!-- resource-id: codex-openai-mcp-docs -->
- [**Codex MCP documentation**](https://learn.chatgpt.com/docs/extend/mcp?surface=cli) - OpenAI's MCP guide shows how Codex connects to local and remote MCP servers.
<!-- resource-id: codex-openai-plugins-docs -->
- [**Codex plugins documentation**](https://learn.chatgpt.com/docs/plugins) - The plugins guide explains installable bundles that combine skills, connectors, MCP servers, and related assets.
<!-- resource-id: codex-openai-sdk-docs -->
- [**Codex SDK documentation**](https://learn.chatgpt.com/docs/codex-sdk) - The Codex SDK documentation covers the @openai/codex-sdk package for starting Codex programmatically, managing threads, and reading results.
<!-- resource-id: codex-openai-subagents-docs -->
- [**Codex subagents documentation**](https://learn.chatgpt.com/docs/agent-configuration/subagents) - The subagents guide describes Codex's delegated sessions, configuration, permissions, and workflow boundaries.

---

<a id="category-c02"></a>
## Skills, Plugins & Collections

Install skills and plugins, or browse collections that group reusable Codex capabilities.

<!-- resource-id: codex-deferred-c6cf066bb876 -->
- [**ui-ux-pro-max-skill**](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill) - (125.1k ⭐) - An AI skill that provides design intelligence for building professional UI/UX across multiple platforms.
<!-- resource-id: codex-juliusbrussee-caveman -->
- [**caveman**](https://github.com/JuliusBrussee/caveman) - (103.8k ⭐) - why use many token when few token do trick, Claude Code skill that cuts 65% of tokens by talking like caveman.
<!-- resource-id: codex-deferred-35dedba68491 -->
- [**agent-skills**](https://github.com/addyosmani/agent-skills) - (92.3k ⭐) - Production-grade engineering skills for AI coding agents.
<!-- resource-id: codex-deferred-2df00a1ac50b -->
- [**obsidian-skills**](https://github.com/kepano/obsidian-skills) - (47.9k ⭐) - Agent skills for Obsidian.
<!-- resource-id: codex-deferred-7ed04bf244b2 -->
- [**hallmark**](https://github.com/Nutlope/hallmark) - (28.1k ⭐) - Anti-AI-slop design skill for Claude Code, Cursor, and Codex.
<!-- resource-id: codex-deferred-c07e6c50b9c8 -->
- [**compound-engineering-plugin**](https://github.com/EveryInc/compound-engineering-plugin) - (24.8k ⭐) - Official Compound Engineering plugin for Claude Code, Codex, Cursor, and more.
<!-- resource-id: codex-composio-community-awesome-codex-skills -->
- [**awesome-codex-skills**](https://github.com/composio-community/awesome-codex-skills) - (16.3k ⭐) - A curated list of practical Codex skills for automating workflows across the Codex CLI and API.
<!-- resource-id: codex-deferred-b3ea5ac3d08d -->
- [**AI-Research-SKILLs**](https://github.com/Orchestra-Research/AI-Research-SKILLs) - (12.3k ⭐) - Comprehensive open-source library of AI research and engineering skills for any AI model.
<!-- resource-id: codex-petergyang-no-ai-slop -->
- [**no-ai-slop**](https://github.com/petergyang/no-ai-slop) - (8k ⭐) - Removes 20+ patterns of AI slop from any piece of writing.
<!-- resource-id: codex-deferred-0d9a9720d2f1 -->
- [**video-shotcraft**](https://github.com/Vincentwei1021/video-shotcraft) - (7.5k ⭐) - AI video skill for Claude Code & Codex, cinematic product videos with Remotion: 152 shot recipe cards, 209 motion previews, a production-ready template.
<!-- resource-id: codex-awesome-voltagent-awesome-codex-subagents -->
- [**awesome-codex-subagents**](https://github.com/VoltAgent/awesome-codex-subagents) - (6.1k ⭐) - A collection of 130+ specialized Codex subagents covering a wide range of development use cases.
<!-- resource-id: codex-diffusionstudio-lottie -->
- [**lottie**](https://github.com/diffusionstudio/lottie) - (5.4k ⭐) - Generate production-ready Lottie animations with Claude Code or Codex.
<!-- resource-id: codex-conorbronsdon-avoid-ai-writing -->
- [**avoid-ai-writing**](https://github.com/conorbronsdon/avoid-ai-writing) - (4.1k ⭐) - Skill that audits and rewrites content to remove AI writing patterns.
<!-- resource-id: codex-deferred-0098753d34ca -->
- [**serenity-skill**](https://github.com/muxuuu/serenity-skill) - (4k ⭐) - Serenity-inspired Agent Skill for supply-chain bottleneck stock research.
<!-- resource-id: codex-aminblg-simpleenglish -->
- [**SimpleEnglish**](https://github.com/AminBlg/SimpleEnglish) - (3.2k ⭐) - Agent skill: make LLMs write docs in ASD-STE100 Simplified Technical.
<!-- resource-id: codex-plannotator-effective-html -->
- [**effective-html**](https://github.com/plannotator/effective-html) - (3k ⭐) - Agent skills for useful HTML artifacts, wireframes, interactive prototypes, plans, and diagrams.
<!-- resource-id: codex-bergside-design-md-chrome -->
- [**design-md-chrome**](https://github.com/bergside/design-md-chrome) - (2.8k ⭐) - Chrome extension to extract styles from any website and generate DESIGN.md files and design skills for AI based on TypeUI.
<!-- resource-id: codex-bergside-awesome-design-skills -->
- [**awesome-design-skills**](https://github.com/bergside/awesome-design-skills) - (2.7k ⭐) - List of 67 awesome DESIGN.md and SKILL.md design skill files for agentic tools like Claude Design, Google Stitch, Codex, Cursor, and other AI tools.
<!-- resource-id: codex-drcathicks-learning-opportunities -->
- [**learning-opportunities**](https://github.com/DrCatHicks/learning-opportunities) - (2.4k ⭐) - A Claude or Codex skill for deliberate skill development during AI-assisted coding.
<!-- resource-id: codex-nanako0129-sepia -->
- [**sepia**](https://github.com/Nanako0129/sepia) - (2.2k ⭐) - De-AI writing skill for any Agent Skills-compatible agent (77+ via the Skills CLI), with native plugins for Claude Code, Codex, Grok Build, and Antigravity.
<!-- resource-id: codex-deferred-093528b5f056 -->
- [**zsh_codex**](https://github.com/tom-doerr/zsh_codex) - (1.7k ⭐) - This is a ZSH plugin that enables you to use OpenAI's Codex AI in the command line.
<!-- resource-id: codex-rohitg00-skillkit -->
- [**skillkit**](https://github.com/rohitg00/skillkit) - (1.5k ⭐) - Supercharge AI coding agents with portable skills.
<!-- resource-id: codex-liyue-aigc-female-portrait-director -->
- [**female-portrait-director**](https://github.com/liyue-aigc/female-portrait-director) - (1.5k ⭐) - A modular Codex Skill for directing and expanding detailed AI female portrait prompts.
<!-- resource-id: codex-awesome-hyhmrright-brooks-lint -->
- [**brooks-lint**](https://github.com/hyhmrright/brooks-lint) - (1.5k ⭐) - AI code reviews grounded in 12 classic engineering books, decay risk diagnostics with book citations, severity labels, and 6 analysis modes including full-sweep auto-fix.
<!-- resource-id: codex-deferred-47e28c704c70 -->
- [**skill-codex**](https://github.com/skills-directory/skill-codex) - (1.4k ⭐) - A claude code skill to delegate prompts to codex.
<!-- resource-id: codex-skill-manager -->
- [**CodexSkillManager**](https://github.com/Dimillian/CodexSkillManager) - (1.4k ⭐) - macOS app to manage your Codex skills.
<!-- resource-id: codex-mohitagw15856-pm-claude-skills -->
- [**pm-claude-skills**](https://github.com/mohitagw15856/pm-claude-skills) - (1.3k ⭐) - 1098 professional Agent Skills for Claude, ChatGPT, Gemini, Cursor & Codex, from PRDs and postmortems to appealing a disability benefit, building a go-bag, and settling into a new country.
<!-- resource-id: codex-nyxtides-ppt-image-first -->
- [**ppt-image-first**](https://github.com/NyxTides/ppt-image-first) - (1.2k ⭐) - PPT image-first skill for Codex/Claude Code/Opencode CLI.
<!-- resource-id: codex-deferred-18d6e8addeac -->
- [**codex-first-customer-finder-skill**](https://github.com/Kappaemme-git/codex-first-customer-finder-skill) - (1k ⭐) - A Codex skill that finds evidence-backed potential first customers from recent public signals.
<!-- resource-id: codex-awesome-plugins-collection -->
- [**awesome-codex-plugins**](https://github.com/hashgraph-online/awesome-codex-plugins) - (935 ⭐) - A curated list of awesome OpenAI Codex / ChatGPT plugins, skills, and resources.
<!-- resource-id: codex-kajisho5-ffmpeg-skill -->
- [**ffmpeg-skill**](https://github.com/kajisho5/ffmpeg-skill) - (596 ⭐) - Give your coding agent a video editor.
<!-- resource-id: codex-kulaxyz-token-diet -->
- [**token-diet**](https://github.com/Kulaxyz/token-diet) - (472 ⭐) - Always-on token-efficiency skill for coding agents (Claude Code, Codex, Cursor, Windsurf, Cline).
<!-- resource-id: codex-awesome-akin-ozer-cc-devops-skills -->
- [**cc-devops-skills**](https://github.com/akin-ozer/cc-devops-skills) - (306 ⭐) - DevOps skills for Claude Code and Codex.
<!-- resource-id: codex-deferred-f39cec6c68d8 -->
- [**dspy-agent-skills**](https://github.com/intertwine/dspy-agent-skills) - (277 ⭐) - Production-grade DSPy 3.2.x agent skills + validated end-to-end examples for Claude Code and Codex CLI, fundamentals, evaluation, GEPA, BetterTogether, and RLM.
<!-- resource-id: codex-neovim -->
- [**codex.nvim**](https://github.com/johnseth97/codex.nvim) - (260 ⭐) - OpenAI Codex plugin for Neovim.
<!-- resource-id: codex-awesome-cathrynlavery-codex-skill -->
- [**codex-skill**](https://github.com/cathrynlavery/codex-skill) - (208 ⭐) - Give Claude Code a second opinion using OpenAI Codex - automatic plan review via hooks.
<!-- resource-id: codex-awesome-avivsinai-bitbucket-cli -->
- [**bitbucket-cli**](https://github.com/avivsinai/bitbucket-cli) - (200 ⭐) - Bitbucket CLI with gh-like ergonomics.
<!-- resource-id: codex-lersent001-holo-card -->
- [**holo-card**](https://github.com/LerSent001/holo-card) - (200 ⭐) - A Codex skill for layered holographic cards with parallax, contour glow, and an optional API workflow.
<!-- resource-id: codex-awesome-source-naodeng-awesome-qa-skills -->
- [**awesome-qa-skills**](https://github.com/naodeng/awesome-qa-skills) - (194 ⭐) - Awesome QA Skills, a bilingual (zh/en) AI testing Agent Skills library for Codex, Cursor, Claude Code, Kiro, OpenCode, and Trae.
<!-- resource-id: codex-aaron-he-zhu-seo-geo-claude-skills -->
- [**seo-geo-claude-skills**](https://github.com/aaron-he-zhu/seo-geo-claude-skills) - (193 ⭐) - Signpost to the 16 SEO/GEO agent skills live in aaron-marketing-skills; this repo's standalone 20-skill line is preserved at tag v9.9.12.
<!-- resource-id: codex-deferred-45305dca266b -->
- [**awesome-ai-plugins**](https://github.com/hashgraph-online/awesome-ai-plugins) - (183 ⭐) - A curated list of awesome plugins for AI assistants including Claude Code, OpenAI Codex / ChatGPT, Gemini, Antigravity, Pi / Oh My Pi, Grok, OpenCode and More.
<!-- resource-id: codex-awesome-xhluca-agent-talk -->
- [**agent-talk**](https://github.com/xhluca/agent-talk) - (182 ⭐) - agent-talk enables any coding agent to talk to each other.
<!-- resource-id: codex-deferred-d61114b81ff9 -->
- [**agent-skills-cli**](https://github.com/Karanjot786/agent-skills-cli) - (180 ⭐) - Universal CLI for Agent Skills.
<!-- resource-id: codex-awesome-voidful-academic-skills -->
- [**academic-skills**](https://github.com/voidful/academic-skills) - (126 ⭐) - A complete academic research Skill suite.

---

<a id="category-c03"></a>
## Project Instructions, Configuration & Context

Shape project behavior with AGENTS.md files, configuration templates, and context tools.

<!-- resource-id: codex-graphify-labs-graphify -->
- [**graphify**](https://github.com/Graphify-Labs/graphify) - (115.1k ⭐) - Turn any codebase, with its docs, SQL schemas, configs, and PDFs, into a queryable knowledge graph.
<!-- resource-id: codex-deferred-76bb6dfa0923 -->
- [**Understand-Anything**](https://github.com/Egonex-AI/Understand-Anything) - (81.6k ⭐) - Graphs that teach > graphs that impress.
<!-- resource-id: codex-colbymchenry-codegraph -->
- [**codegraph**](https://github.com/colbymchenry/codegraph) - (69.7k ⭐) - Pre-indexed code knowledge graph, auto syncs on code changes, for Claude Code, Codex, Gemini, Cursor, OpenCode, AntiGravity, Kiro, CoPilot, and Hermes Agent, fewer tokens, fewer tool calls, 100% local.
<!-- resource-id: codex-deferred-7e4d515f4163 -->
- [**scientific-agent-skills**](https://github.com/K-Dense-AI/scientific-agent-skills) - (42.8k ⭐) - Turn any AI agent into an AI Scientist.
<!-- resource-id: codex-deferred-1f12bba6865e -->
- [**codebase-memory-mcp**](https://github.com/DeusData/codebase-memory-mcp) - (42.3k ⭐) - High-performance code intelligence MCP server.
<!-- resource-id: codex-trailhq-graft -->
- [**Graft**](https://github.com/trailhq/Graft) - (5.6k ⭐) - Turbocharge Claude Code, Cursor, Codex, Gemini & every coding agent: faster, cheaper, with contextual understanding specific to your codebase.
<!-- resource-id: codex-awesome-bfly123-claude-code-bridge -->
- [**claude_code_bridge**](https://github.com/bfly123/claude_code_bridge) - (3.5k ⭐) - Visible multi-agent CLI workspace for mixing Codex, Claude, Gemini, Kimi, Qwen, Cursor, Copilot, Pi, OpenCode, and other AI coding agents.
<!-- resource-id: codex-deferred-3222c9e2608d -->
- [**pro-workflow**](https://github.com/rohitg00/pro-workflow) - (2.8k ⭐) - Claude Code learns from your corrections: self-correcting memory that compounds over 50+ sessions.
<!-- resource-id: codex-awesome-folke-sidekick-nvim -->
- [**sidekick.nvim**](https://github.com/folke/sidekick.nvim) - (2.8k ⭐) - Your Neovim AI sidekick.
<!-- resource-id: codex-feiskyer-claude-code-settings -->
- [**claude-code-settings**](https://github.com/feiskyer/claude-code-settings) - (1.6k ⭐) - Curated skills, sub-agents, and config templates that supercharge Claude Code, research, image gen, GitHub automation & more.
<!-- resource-id: codex-nagisanzenin-engram -->
- [**engram**](https://github.com/nagisanzenin/engram) - (1.4k ⭐) - Evidence-based learning engine, first-principles curricula, free-recall verification with receipts, FSRS-scheduled memory, and explorable artifacts.
<!-- resource-id: codex-huytieu-cog-second-brain -->
- [**COG-second-brain**](https://github.com/huytieu/COG-second-brain) - (1.2k ⭐) - Self-evolving second brain with 33 AI skills, 10 agents, and people CRM.
<!-- resource-id: codex-n-skills -->
- [**n-skills**](https://github.com/numman-ali/n-skills) - (1k ⭐) - Curated plugin marketplace for AI agents - works with Claude Code, Codex, and openskills.
<!-- resource-id: codex-deferred-248686287bc4 -->
- [**Citadel**](https://github.com/SethGammon/Citadel) - (916 ⭐) - The operating layer for Claude Code + OpenAI Codex: persistent project memory, intent routing, safety hooks, cost telemetry, and parallel agent fleets.
<!-- resource-id: codex-codebendkit-codeseek -->
- [**codeseek**](https://github.com/CodeBendKit/codeseek) - (765 ⭐) - Rust-powered code intelligence CLI for AI coding agents.
<!-- resource-id: codex-deferred-243aac99209a -->
- [**memorix**](https://github.com/AVIDS2/memorix) - (725 ⭐) - Open-source cross-agent memory layer for coding agents via MCP.
<!-- resource-id: codex-awesome-ooples-token-optimizer-mcp -->
- [**token-optimizer-mcp**](https://github.com/ooples/token-optimizer-mcp) - (507 ⭐) - Measure token savings per AI coding agent, optimize context, and share a live local knowledge graph across 16 CLI clients.
<!-- resource-id: codex-awesome-waybarrios-opencode-power-pack -->
- [**opencode-power-pack**](https://github.com/waybarrios/opencode-power-pack) - (490 ⭐) - 54 rigorous skills for Codex, OpenCode, and Pi: code review, security audit, feature development, frontend design, MCP tools, Hugging Face ML/training, and more.
<!-- resource-id: codex-awesome-aannoo-hcom -->
- [**hcom**](https://github.com/aannoo/hcom) - (479 ⭐) - Let AI agents message, watch, and spawn each other across terminals.
<!-- resource-id: codex-awesome-regenrek-codex-1up -->
- [**codex-1up**](https://github.com/regenrek/codex-1up) - (438 ⭐) - Give your Codex CLI an extra life.
<!-- resource-id: codex-autoloops-greplica -->
- [**greplica**](https://github.com/Autoloops/greplica) - (434 ⭐) - Persistent, searchable engineering memory for AI coding agents.
<!-- resource-id: codex-settings-workbench -->
- [**codex-settings**](https://github.com/feiskyer/codex-settings) - (237 ⭐) - Curated skills, profiles, and config templates that supercharge Codex CLI, multi-model, deep research, image gen & browser automation.
<!-- resource-id: codex-awesome-tinqiao-oss-engramory -->
- [**engramory**](https://github.com/tinqiao-oss/engramory) - (186 ⭐) - A portable memory protocol for AI agents, load it as standing rules; a curation discipline + reference spec + optional cap hook.
<!-- resource-id: codex-deferred-e8a4c3ece44c -->
- [**ai-rules-sync**](https://github.com/PanisHandsome/ai-rules-sync) - (119 ⭐) - Keep one source of truth for your AI coding-agent rules.

---

<a id="category-c04"></a>
## Clients, Editors & Remote Access

Open Codex from an editor, desktop client, terminal interface, or remote control.

<!-- resource-id: codex-deferred-2e6f8494903b -->
- [**everything-claude-code**](https://github.com/affaan-m/everything-claude-code) - (250.1k ⭐) - The agent harness performance optimization system.
<!-- resource-id: codex-deferred-c8240f914ead -->
- [**cc-switch**](https://github.com/farion1231/cc-switch) - (131.1k ⭐) - A cross-platform desktop All-in-One assistant for Claude Code, Codex, OpenCode, OpenClaw, Grok Build & Hermes Agent.
<!-- resource-id: codex-nexu-io-open-design -->
- [**open-design**](https://github.com/nexu-io/open-design) - (94.2k ⭐) - Best DeepSeek Harness Design Plugin.
<!-- resource-id: codex-deferred-ba525917aba4 -->
- [**ruflo**](https://github.com/ruvnet/ruflo) - (70.5k ⭐) - The original agent meta-harness.
<!-- resource-id: codex-deferred-dfb1df9f6743 -->
- [**OmniRoute**](https://github.com/diegosouzapw/OmniRoute) - (61.4k ⭐) - Never stop coding.
<!-- resource-id: codex-deferred-ed5355c7eb11 -->
- [**marketingskills**](https://github.com/coreyhaines31/marketingskills) - (46.9k ⭐) - Marketing skills for Claude Code and AI agents.
<!-- resource-id: codex-deferred-c22638187f70 -->
- [**ToolJet**](https://github.com/ToolJet/ToolJet) - (40.8k ⭐) - Open-source foundation of ToolJet AI - the enterprise app generation platform for internal tools, dashboards, business applications, workflows and AI agents.
<!-- resource-id: codex-cathrynlavery-diagram-design -->
- [**diagram-design**](https://github.com/cathrynlavery/diagram-design) - (31.3k ⭐) - 38 editorial diagram types for Claude Code, Codex, and Pi.
<!-- resource-id: codex-iofficeai-officecli -->
- [**OfficeCLI**](https://github.com/iOfficeAI/OfficeCLI) - (29.9k ⭐) - OfficeCLI is the first and best Office suite purpose-built for AI agents to read, edit, and automate Word, Excel, and PowerPoint files.
<!-- resource-id: codex-awesome-garrytan-gbrain -->
- [**gbrain**](https://github.com/garrytan/gbrain) - (29.6k ⭐) - Garry's Opinionated OpenClaw/Hermes Agent Brain.
<!-- resource-id: codex-deferred-c9fc273b0dd3 -->
- [**guizang-ppt-skill**](https://github.com/op7418/guizang-ppt-skill) - (25.7k ⭐) - AI-agent Skill for generating polished HTML slide decks: editorial magazine and Swiss layouts, image prompts, social covers, and a WebGL/low-power presentation runtime.
<!-- resource-id: codex-deferred-c00aaf2f9d2c -->
- [**screenpipe**](https://github.com/screenpipe/screenpipe) - (21.4k ⭐) - YC (S26), Open Computer History, Record your screen continuously locally and provide context to your agents (Claude, Codex, Openclaw, Hermes, Runner.).
<!-- resource-id: codex-deferred-a7a027dd0b93 -->
- [**notebooklm-py**](https://github.com/teng-lin/notebooklm-py) - (19.2k ⭐) - Unofficial Python API and agentic skill for Google Gemini Notebook.
<!-- resource-id: codex-krillinai-opencreator -->
- [**OpenCreator**](https://github.com/krillinai/OpenCreator) - (11.3k ⭐) - Open-source AI workspace for creators, powered by Codex.
<!-- resource-id: codex-deferred-79e30d2cc622 -->
- [**omnigent**](https://github.com/omnigent-ai/omnigent) - (9.7k ⭐) - Omnigent is an open-source AI agent framework and meta-harness.
<!-- resource-id: codex-deferred-6e81baa561fd -->
- [**html-anything**](https://github.com/nexu-io/html-anything) - (8.7k ⭐) - The agentic HTML editor, your local AI agent writes the HTML, you ship it.
<!-- resource-id: codex-opencoworkai-open-codesign -->
- [**open-codesign**](https://github.com/OpenCoworkAI/open-codesign) - (7.9k ⭐) - Open-source Claude Design alternative.
<!-- resource-id: codex-liamgvchi-gc-minimal-zine-poster -->
- [**gc-minimal-zine-poster**](https://github.com/LiamGvchi/gc-minimal-zine-poster) - (6.9k ⭐) - Codex skill for generating quiet minimal zine-style editorial poster prompts and images.
<!-- resource-id: codex-heilcheng-awesome-agent-skills -->
- [**awesome-agent-skills**](https://github.com/heilcheng/awesome-agent-skills) - (6.2k ⭐) - Tutorials, Guides and Agent Skills Directories.
<!-- resource-id: codex-deferred-9d7bf81116d9 -->
- [**skills-manager**](https://github.com/xingkongliang/skills-manager) - (4.5k ⭐) - A lightweight desktop app to manage, sync, and organize AI agent skills across 50+ coding tools, Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.
<!-- resource-id: codex-awesome-ilysenko-codex-desktop-linux -->
- [**codex-desktop-linux**](https://github.com/ilysenko/codex-desktop-linux) - (3.8k ⭐) - Unofficial ChatGPT desktop app for Linux (formerly the Codex app), built locally from OpenAI's official macOS app.
<!-- resource-id: codex-deferred-c2a3fe2fce40 -->
- [**remodex**](https://github.com/Emanuele-web04/remodex) - (3.3k ⭐) - Remote Control for Codex.
<!-- resource-id: codex-deferred-535bd37d2980 -->
- [**nexu**](https://github.com/nexu-io/nexu) - (3.3k ⭐) - The simplest desktop client for OpenClaw, bridge your Agent to WeChat, Feishu, Slack & Discord in one click.
<!-- resource-id: codex-awesome-wendy7756-ai-video-transcriber -->
- [**AI-Video-Transcriber**](https://github.com/wendy7756/AI-Video-Transcriber) - (3.2k ⭐) - Transcribe and summarize videos and podcasts using AI.
<!-- resource-id: codex-deferred-d26bd742f7a1 -->
- [**codeg**](https://github.com/xintaofei/codeg) - (3.2k ⭐) - Collaborative multi-agent AI coding workspace: aggregate sessions from Claude Code, Codex, OpenCode, Pi, Grok Build, etc.
<!-- resource-id: codex-njbrake-agent-of-empires -->
- [**agent-of-empires**](https://github.com/agent-of-empires/agent-of-empires) - (3.2k ⭐) - Manage multiple Claude Code, OpenCode agents from either TUI or Web for easy access on mobile.
<!-- resource-id: codex-agent-rules-books -->
- [**agent-rules-books**](https://github.com/ciembor/agent-rules-books) - (2.7k ⭐) - AGENTS.md rules / skills for AI coding agents: Codex, Cursor & Claude Code.
<!-- resource-id: codex-awesome-oxsecurity-megalinter -->
- [**megalinter**](https://github.com/oxsecurity/megalinter) - (2.6k ⭐) - MegaLinter analyzes 50 languages, 22 formats, 21 tooling formats, excessive copy-pastes, spelling mistakes and security issues in your repository sources with a GitHub Action, other CI tools or locally.
<!-- resource-id: codex-wondelai-skills -->
- [**skills**](https://github.com/wondelai/skills) - (2.1k ⭐) - Wondel.ai Agent Skills, Business, Marketing, UX & Coding Frameworks from Bestselling Books.
<!-- resource-id: codex-maxritter-pilot-shell -->
- [**pilot-shell**](https://github.com/maxritter/pilot-shell) - (2.1k ⭐) - Professional context and harness engineering for Claude Code and OpenAI Codex.
<!-- resource-id: codex-deferred-8c689a8e9328 -->
- [**open-vibe-island**](https://github.com/Octane0411/open-vibe-island) - (2k ⭐) - Native macOS control center for AI coding agents, monitor sessions, approve actions, and jump back instantly.
<!-- resource-id: codex-nimbalyst-nimbalyst -->
- [**nimbalyst**](https://github.com/nimbalyst/nimbalyst) - (1.6k ⭐) - Nimbalyst - The open-source visual workspace for Claude Code, Codex, and OpenCode.
<!-- resource-id: codex-deferred-019417a9628d -->
- [**OpenChatCut**](https://github.com/0xsline/OpenChatCut) - (1.6k ⭐) - Open-source, local-first conversational AI video editor with a professional multi-track timeline, Agent Skills, MCP integration, and Remotion rendering.
<!-- resource-id: codex-deferred-afc4e0bb5495 -->
- [**drawio-scientific-illustrator**](https://github.com/icebird1998/drawio-scientific-illustrator) - (1.4k ⭐) - Live MCP control of the visible draw.io canvas for step-by-step scientific illustration in Codex.
<!-- resource-id: codex-kbwo-ccmanager -->
- [**ccmanager**](https://github.com/kbwo/ccmanager) - (1.2k ⭐) - Coding Agent Session Manager for Claude Code / Gemini CLI / Codex CLI / Cursor Agent / Copilot CLI / Cline CLI / OpenCode / Kimi CLI.
<!-- resource-id: codex-deferred-0f0e842533f3 -->
- [**cli-agent-orchestrator**](https://github.com/awslabs/cli-agent-orchestrator) - (1.2k ⭐) - Multi-agent orchestration for AI coding CLIs, Claude Code, Kiro, Codex, and more, coordinated in isolated tmux sessions.
<!-- resource-id: codex-deferred-3e0a98518c21 -->
- [**slides-grab**](https://github.com/NomaDamas/slides-grab) - (1.2k ⭐) - Best harness + editor + linter for generating slides in Claude Code / Codex - Claude Design Open Source Alternative.
<!-- resource-id: codex-awesome-dpearson2699-swift-ios-skills -->
- [**swift-ios-skills**](https://github.com/dpearson2699/swift-ios-skills) - (1.1k ⭐) - Agent Skills for iOS 26+, Swift 6.3, SwiftUI, and modern Apple frameworks.
<!-- resource-id: codex-awesome-johannesjo-parallel-code -->
- [**parallel-code**](https://github.com/johannesjo/parallel-code) - (1k ⭐) - Run Claude Code, Codex, and Gemini side by side, each in its own git worktree.
<!-- resource-id: codex-deferred-0d003aeb75f2 -->
- [**solomd**](https://github.com/zhitongblog/solomd) - (1k ⭐) - A markdown editor, and the bridge to your LLM.
<!-- resource-id: codex-deferred-7f150ff637c6 -->
- [**claude-delegator**](https://github.com/jarrodwatts/claude-delegator) - (996 ⭐) - Delegate tasks to Codex and Gemini directly from within Claude Code.
<!-- resource-id: codex-deferred-24d29ae7692f -->
- [**Skills-Manager**](https://github.com/jiweiyeah/Skills-Manager) - (977 ⭐) - Free, open-source desktop manager for AI Agent Skills.
<!-- resource-id: codex-deferred-9f93147039b5 -->
- [**imcodes**](https://github.com/im4codes/imcodes) - (973 ⭐) - The IM for agents.
<!-- resource-id: codex-deferred-e863c064e0bb -->
- [**codexia**](https://github.com/milisp/codexia) - (910 ⭐) - Lightweight Agent Workstation for Codex CLI + Claude Code, with task scheduler, git worktree & remote control.
<!-- resource-id: codex-maxbogo-awesome-ai-tools-for-ui -->
- [**awesome-ai-tools-for-ui**](https://github.com/maxbogo/awesome-ai-tools-for-ui) - (857 ⭐) - Curated list of awesome AI tools to build beautiful UI/UX.
<!-- resource-id: codex-deferred-f03d1ace6bc9 -->
- [**codex.docs**](https://github.com/codex-team/codex.docs) - (846 ⭐) - Free Docs app powered by Editor.js ecosystem.
<!-- resource-id: codex-deferred-a64231abe426 -->
- [**agent-sessions**](https://github.com/jazzyalex/agent-sessions) - (845 ⭐) - Local-first macOS app to browse, search, analyze, and resume supported AI coding-agent session history across Codex, Claude Code, OpenCode, Cursor Agent, Hermes, OpenClaw, Copilot CLI, and more.
<!-- resource-id: codex-asheshgoplani-agent-deck -->
- [**agent-deck**](https://github.com/asheshgoplani/agent-deck) - (843 ⭐) - Terminal session manager for AI coding agents.
<!-- resource-id: codex-vshulcz-deja-vu -->
- [**deja-vu**](https://github.com/vshulcz/deja-vu) - (776 ⭐) - Memory for coding agents built from the session history already on disk: Claude Code, Codex, Cursor, Copilot CLI, OpenClaw and 17 more.
<!-- resource-id: codex-0xranx-opencontext -->
- [**OpenContext**](https://github.com/0xranx/OpenContext) - (756 ⭐) - A personal context store for AI agents and assistants, reuse your existing coding agent CLI (Codex/Claude/OpenCode) with builtin Skills/tools and a desktop GUI to capture.
<!-- resource-id: codex-infragate-capa -->
- [**capa**](https://github.com/infragate/capa) - (737 ⭐) - One capabilities.yaml wires skills, tools, rules, sub-agents, MCP servers, and plugins into Cursor, Claude Code, Codex, Windsurf, GitHub Copilot, and 30+ other AI coding agents.
<!-- resource-id: codex-awesome-lampese-codex-switcher -->
- [**codex-switcher**](https://github.com/Lampese/codex-switcher) - (703 ⭐) - A Desktop Application for Managing Multiple OpenAI Codex CLI Accounts.
<!-- resource-id: codex-swarmclawai-swarmvault -->
- [**swarmvault**](https://github.com/swarmclawai/swarmvault) - (679 ⭐) - The local-first LLM Wiki: open-source knowledge graph builder, RAG knowledge base, and agent memory store.
<!-- resource-id: codex-awesome-skillmatic-ai-awesome-agent-skills -->
- [**awesome-agent-skills**](https://github.com/skillmatic-ai/awesome-agent-skills) - (669 ⭐) - The definitive resource for Agent Skills - modular capabilities revolutionizing AI agent architecture.
<!-- resource-id: codex-awesome-loocor-codmate -->
- [**codmate**](https://github.com/loocor/codmate) - (667 ⭐) - CodMate is a macOS SwiftUI app for managing CLI AI sessions: browse, search, organize, resume, and review work produced by Codex, Claude Code, and Gemini CLI.
<!-- resource-id: codex-deferred-3379cde7e085 -->
- [**airship**](https://github.com/0xnyn/airship) - (660 ⭐) - Figma like visual editor built for Claude Code, Codex and OpenCode.
<!-- resource-id: codex-mcp-server-tuannvm -->
- [**codex-mcp-server**](https://github.com/tuannvm/codex-mcp-server) - (630 ⭐) - MCP server wrapper for OpenAI Codex CLI that enables Claude Code to leverage Codex's AI capabilities directly.
<!-- resource-id: codex-awesome-tura-ai-tura -->
- [**tura**](https://github.com/Tura-AI/tura) - (613 ⭐) - Build agent that uses 80% less token and delivers better results.
<!-- resource-id: codex-awesome-aldefy-compose-skill -->
- [**compose-skill**](https://github.com/aldefy/compose-skill) - (577 ⭐) - Jetpack Compose Agent Skill, AI-powered coding guidance with actual androidx/androidx source code receipts.
<!-- resource-id: codex-deferred-4 -->
- [**claw-orchestrator**](https://github.com/Enderfga/claw-orchestrator) - (566 ⭐) - Run Claude Code, Codex, Antigravity, Cursor Agent and OpenCode as one runtime, persistent sessions, multi-agent councils, an OpenAI-compatible endpoint, an MCP server, and an ACP agent any editor can drive.
<!-- resource-id: codex-observedobserver-async-code -->
- [**async-code**](https://github.com/ObservedObserver/async-code) - (535 ⭐) - Use Claude Code / CodeX CLI to perform multiple tasks in parallel with a Codex-style UI.
<!-- resource-id: codex-deferred-e61fe19b6d35 -->
- [**ok-skills**](https://github.com/mxyhi/ok-skills) - (480 ⭐) - Curated AI coding agent skills and AGENTS.md playbooks for Codex, Claude Code, Cursor, OpenClaw, and other SKILL.md-compatible tools.
<!-- resource-id: codex-deferred-12b7a936cb62 -->
- [**agent-rules-books**](https://github.com/mattpocock/agent-rules-books) - (444 ⭐) - AGENTS.md rules / skills for AI coding agents: Codex, Cursor & Claude Code.
<!-- resource-id: codex-deferred-4a8e08c587a3 -->
- [**BossConsole**](https://github.com/risa-labs-inc/BossConsole) - (439 ⭐) - Open-source, multi-platform harness for AI agents.
<!-- resource-id: codex-deferred-a0a85bbe0fe9 -->
- [**apm-studio**](https://github.com/apm-studio/apm-studio) - (435 ⭐) - Local editor for importing, managing, running, and injecting APM-backed assistant packages.
<!-- resource-id: codex-yoanwai-agent-manager -->
- [**agent-manager**](https://github.com/YoanWai/agent-manager) - (421 ⭐) - The fastest workflow for every AI coding agent.
<!-- resource-id: codex-deferred-760a60a7376d -->
- [**agnix**](https://github.com/avifenesh/agnix) - (404 ⭐) - The missing linter and lsp for AI coding assistants.
<!-- resource-id: codex-deferred-d7f9a3fb5f8f -->
- [**codex-chatgpt-control**](https://github.com/adamallcock/codex-chatgpt-control) - (390 ⭐) - Unofficial SDK for Codex agents controlling visible ChatGPT web sessions.
<!-- resource-id: codex-deferred-52ca95511bd2 -->
- [**amux**](https://github.com/mixpeek/amux) - (386 ⭐) - Open-source control plane for AI coding agents.
<!-- resource-id: codex-deferred-43c4ba4a6f10 -->
- [**photo-relic-editorial**](https://github.com/wnby/photo-relic-editorial) - (361 ⭐) - A Codex skill for transforming real photos into Photo Relic artworks: truthful photographs paired with quiet paper-memory prints.
<!-- resource-id: codex-awesome-linhay-harmony-next-skills -->
- [**harmony-next.skills**](https://github.com/linhay/harmony-next.skills) - (343 ⭐) - Expert guidance for HarmonyOS NEXT (API 12+) development.
<!-- resource-id: codex-deferred-eb10d629712f -->
- [**cc-sessions-viewer**](https://github.com/jerrywu001/cc-sessions-viewer) - (342 ⭐) - support cc/codex/grok build/kimicode/pi/antigravity cli/opencode sessions viewer, token usage statistics, global search, resume, and export to html.
<!-- resource-id: codex-awesome-milisp-mcp-linker -->
- [**mcp-linker**](https://github.com/milisp/mcp-linker) - (322 ⭐) - mcp store manager, add & syncs MCP server configurations across clients like Claude code, Cursormcphub.
<!-- resource-id: codex-awesome-noizefield-audio-plugin-coder -->
- [**audio-plugin-coder**](https://github.com/Noizefield/audio-plugin-coder) - (315 ⭐) - Audio Plugin Coder (APC) is a groundbreaking, open-source framework that enables musicians, producers, sound designers, and developers to create professional VST3/AU audio plugins using natural language and AI assistance.
<!-- resource-id: codex-deferred-24f88ab34ad7 -->
- [**ditto**](https://github.com/ohad6k/ditto) - (288 ⭐) - Mine your Claude Code and Codex logs into a local you.md agent profile.
<!-- resource-id: codex-deferred-981bc2d9abec -->
- [**vim_codex**](https://github.com/tom-doerr/vim_codex) - (286 ⭐) - Supercharge your Vim editor with AI-powered code completion using OpenAI Codex.
<!-- resource-id: codex-deferred-3f508ac3909f -->
- [**editorjs-php**](https://github.com/editor-js/editorjs-php) - (263 ⭐) - PHP backend for Editor.js.
<!-- resource-id: codex-deferred-4b806b96b678 -->
- [**funplay-unity-mcp**](https://github.com/FunplayAI/funplay-unity-mcp) - (233 ⭐) - The Most Advanced MCP Server for Unity Editor with execute_code, prompts/resources, input simulation, screenshots, and play mode automation.
<!-- resource-id: codex-deferred-66b440eb911f -->
- [**skills**](https://github.com/qdrant/skills) - (230 ⭐) - Agent skills for Qdrant vector search: scaling, performance optimization, search quality, monitoring, deployment, model migration, version upgrades, and SDK usage across Python, TypeScript, Rust, Go,.NET, Java.
<!-- resource-id: codex-awesome-talkstream-ru-text -->
- [**ru-text**](https://github.com/talkstream/ru-text) - (223 ⭐) - Russian text quality for AI agents, neuroslop cleanup, typography, information style, editorial standards, UX writing, business correspondence.
<!-- resource-id: codex-lkbaba-claude-code-chatinwindows -->
- [**Claude-code-ChatInWindows**](https://github.com/LKbaba/Claude-code-ChatInWindows) - (221 ⭐) - Full-featured GUI for Claude Code CLI in VS Code, Windows (no WSL) & macOS.
<!-- resource-id: codex-deferred-d77925fba063 -->
- [**agentnotch**](https://github.com/AppGram/agentnotch) - (215 ⭐) - AgentNotch is a sleek macOS menu bar app that lives in your Mac's notch, providing real-time visibility into your AI coding assistants.
<!-- resource-id: codex-awesome-xquik-dev-x-twitter-scraper -->
- [**x-twitter-scraper**](https://github.com/Xquik-dev/x-twitter-scraper) - (193 ⭐) - X (Twitter) scraper API & X API alternative with REST, MCP, SDKs & webhooks.
<!-- resource-id: codex-deferred-85b20574f8ad -->
- [**runjam**](https://github.com/peintune/runjam) - (186 ⭐) - One desktop for all your AI coding Agent, Claude Code, Codex CLI & Gemini CLI.
<!-- resource-id: codex-awesome-techygarg-lattice -->
- [**lattice**](https://github.com/techygarg/lattice) - (185 ⭐) - Install engineering discipline into any AI coding assistant.
<!-- resource-id: codex-awesome-milisp-awesome-claude-dxt -->
- [**awesome-claude-dxt**](https://github.com/milisp/awesome-claude-dxt) - (178 ⭐) - Awesome Claude Desktop Extensions (dxt) (not only Claude) mcpb.
<!-- resource-id: codex-deferred-f915c2f8b4ee -->
- [**agentic-os**](https://github.com/KbWen/agentic-os) - (157 ⭐) - Governance framework for AI coding agents.
<!-- resource-id: codex-deferred-783e6cdeb56f -->
- [**trace-mcp**](https://github.com/nikolai-vysotskyi/trace-mcp) - (150 ⭐) - Framework-aware code intelligence MCP server for Claude Code and Codex, 90.6% fewer input tokens to review a pull request, median over 60 merged PRs in repos we don't own.
<!-- resource-id: codex-deferred-e2d00cc64991 -->
- [**codex.notes**](https://github.com/codex-team/codex.notes) - (148 ⭐) - WIP: crossplatform desktop notes application based on Electron and Editor.js.
<!-- resource-id: codex-sculptdotfun-viberank -->
- [**viberank**](https://github.com/sculptdotfun/viberank) - (115 ⭐) - The AI coding usage leaderboard, Claude Code, Codex, Gemini CLI & more.
<!-- resource-id: codex-saaranshm-unsnooze -->
- [**unsnooze**](https://github.com/saaranshM/unsnooze) - (109 ⭐) - Automatically resume Claude Code, Codex CLI, Grok, Qwen Code, Kimi CLI, OpenCode, and Antigravity sessions when 5-hour or weekly usage limits reset, across tmux, Zellij, VS Code, and desktop apps.
<!-- resource-id: codex-awesome-beefiker-superloopy -->
- [**superloopy**](https://github.com/beefiker/superloopy) - (108 ⭐) - Lightweight Codex/Claude loop harness with strict evidence gates.
<!-- resource-id: codex-deferred-951f83058e99 -->
- [**paper-operators**](https://github.com/Alexsun1one/paper-operators) - (107 ⭐) - Chinese-first Codex Skill for article illustrations with faceless folded-paper action characters.

---

<a id="category-c05"></a>
## Workflow Automation & Agent Coordination

Set up repeatable Codex jobs with actions, review loops, schedulers, and agent coordination.

<!-- resource-id: codex-deferred-6c2323005e19 -->
- [**taste-skill**](https://github.com/Leonxlnx/taste-skill) - (84.5k ⭐) - Taste-Skill - gives your AI good taste.
<!-- resource-id: codex-tt-a1i-archify -->
- [**archify**](https://github.com/tt-a1i/archify) - (48.7k ⭐) - Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams, self-contained HTML with motion and crisp export.
<!-- resource-id: codex-agentic-marketplace -->
- [**agents**](https://github.com/wshobson/agents) - (39.4k ⭐) - Multi-harness agentic plugin marketplace for Claude Code, Codex, Cursor, OpenCode, GitHub Copilot, and Google Antigravity.
<!-- resource-id: codex-composio-awesome-skills -->
- [**awesome-codex-skills**](https://github.com/ComposioHQ/awesome-codex-skills) - (16.3k ⭐) - A curated list of practical Codex skills for automating workflows across the Codex CLI and API.
<!-- resource-id: codex-deferred-f286ab0362e7 -->
- [**loop-engineering**](https://github.com/cobusgreyling/loop-engineering) - (11k ⭐) - Practical patterns, starters & CLI tools for loop engineering with AI coding agents.
<!-- resource-id: codex-awesome-trailofbits-skills -->
- [**skills**](https://github.com/trailofbits/skills) - (7k ⭐) - Trail of Bits Claude Code skills for security research, vulnerability detection, and audit workflows.
<!-- resource-id: codex-deferred-621628fd8634 -->
- [**Product-Manager-Skills**](https://github.com/deanpeters/Product-Manager-Skills) - (6.8k ⭐) - Product Management skills framework built on battle-tested methods for Claude Code, Cowork, Codex, and AI agents.
<!-- resource-id: codex-awesome-ufomiao-zcf -->
- [**zcf**](https://github.com/UfoMiao/zcf) - (6.1k ⭐) - Zero-Config Code Flow for Claude code & Codex.
<!-- resource-id: codex-deferred-949fb7a83c7d -->
- [**Skills**](https://github.com/MengTo/Skills) - (5.8k ⭐) - Agent skills for designers and builders using Codex, Claude, Cursor, and other AI coding agents.
<!-- resource-id: codex-0x0funky-agent-sprite-forge -->
- [**agent-sprite-forge**](https://github.com/0x0funky/agent-sprite-forge) - (4k ⭐) - Agent Skill for generating 2D sprite sheets and map, transparent PNG frames, and animated GIFs from prompts.
<!-- resource-id: codex-tutti-os-tutti -->
- [**tutti**](https://github.com/tutti-os/tutti) - (3.7k ⭐) - Where people and agents build in tune.
<!-- resource-id: codex-gotalab-cc-sdd -->
- [**cc-sdd**](https://github.com/gotalab/cc-sdd) - (3.7k ⭐) - Turn approved specs into long-running autonomous implementation.
<!-- resource-id: codex-deferred-e99a045d2e44 -->
- [**awesome-ChatGPT-repositories**](https://github.com/taishi-i/awesome-ChatGPT-repositories) - (3.2k ⭐) - A curated list of open source GitHub repositories related to ChatGPT, the OpenAI API, and Codex.
<!-- resource-id: codex-deferred-6d90b64510ca -->
- [**skills**](https://github.com/NVIDIA/skills) - (3.2k ⭐) - Agent Skills for NVIDIA products, install into Claude Code, Codex, and other coding agents to run Physical AI, robotics, simulation, CUDA, and RAG workflows end to end.
<!-- resource-id: codex-forward-future-loopy -->
- [**loopy**](https://github.com/Forward-Future/loopy) - (3.1k ⭐) - A library of practical AI-agent loops and an installable skill for finding, adapting, and designing repeatable agent workflows.
<!-- resource-id: codex-deferred-868dd5807f24 -->
- [**codex-with-chatgpt**](https://github.com/XiaoDuoYa/codex-with-chatgpt) - (2.5k ⭐) - ChatGPT thinks.
<!-- resource-id: codex-awesome-agentsmesh-agentsmesh -->
- [**AgentsMesh**](https://github.com/AgentsMesh/AgentsMesh) - (2.3k ⭐) - The AI Agent Workforce Platform.
<!-- resource-id: codex-opencode-auth -->
- [**opencode-openai-codex-auth**](https://github.com/numman-ali/opencode-openai-codex-auth) - (2.2k ⭐) - OAuth authentication plugin for personal coding assistance with ChatGPT Plus/Pro subscriptions - uses OpenAI's official authentication method.
<!-- resource-id: codex-qoderai-better-harness -->
- [**better-harness**](https://github.com/QoderAI/better-harness) - (2.2k ⭐) - An open-source Harness Engineering platform for coding agents, define harnesses as code, run controlled experiments, inspect evidence, and compare outcomes.
<!-- resource-id: codex-deferred-d194dc063029 -->
- [**Deep-Research-skills**](https://github.com/Weizhena/Deep-Research-skills) - (2.1k ⭐) - Structured deep research skill for Claude Code/Open Code/Codex with human-in-the-loop control.
<!-- resource-id: codex-deferred-1b9c7d083801 -->
- [**scroll-craft**](https://github.com/nateherkai/scroll-craft) - (1.9k ⭐) - An agent skill for building premium, immersive, scroll-driven websites.
<!-- resource-id: codex-deferred-15196d05fb17 -->
- [**awesome-llm-skills**](https://github.com/Prat011/awesome-llm-skills) - (1.7k ⭐) - A curated list of awesome LLM and AI Agent Skills, resources and tools for customising AI Agent workflows - that works with Claude Code, Codex, Gemini CLI and your custom AI Agents.
<!-- resource-id: codex-besty0728-unity-skills -->
- [**Unity-Skills**](https://github.com/Besty0728/Unity-Skills) - (1.7k ⭐) - AI automation skills specifically designed for Unity.
<!-- resource-id: codex-awesome-callstackincubator-agent-skills -->
- [**agent-skills**](https://github.com/callstackincubator/agent-skills) - (1.6k ⭐) - A collection of agent-optimized React Native skills for AI coding assistants.
<!-- resource-id: codex-deferred-bdeff2187349 -->
- [**claudex-loop**](https://github.com/chaseai-yt/claudex-loop) - (1.6k ⭐) - Claude Code skill: four-phase plan hardening (recon, interrogate, Codex adversarial review.
<!-- resource-id: codex-amap-ml-longhorizon-harness -->
- [**LongHorizon-Harness**](https://github.com/AMAP-ML/LongHorizon-Harness) - (1.5k ⭐) - The long-horizon computer-use harness.
<!-- resource-id: codex-awesome-aklofas-kicad-happy -->
- [**kicad-happy**](https://github.com/aklofas/kicad-happy) - (1.1k ⭐) - AI coding agent skills for KiCad electronics design.
<!-- resource-id: codex-deferred-13ed0a2fdd1f -->
- [**agentsys**](https://github.com/agent-sh/agentsys) - (982 ⭐) - AI writes code.
<!-- resource-id: codex-awesome-bhanunamikaze-agentic-seo-skill -->
- [**Agentic-SEO-Skill**](https://github.com/Bhanunamikaze/Agentic-SEO-Skill) - (889 ⭐) - An LLM-first SEO analysis skill for Antigravity, Codex, Claude with 16 specialized sub-skills, 10 specialist agents, and 88 optional utility scripts used as evidence collectors.
<!-- resource-id: codex-awesome-alibaba-skill-up -->
- [**skill-up**](https://github.com/alibaba/skill-up) - (851 ⭐) - An evaluation and evolution tool for Agent Skills.
<!-- resource-id: codex-awesome-huggingface-upskill -->
- [**upskill**](https://github.com/huggingface/upskill) - (741 ⭐) - Generate and evaluate agent skills for code agents like Claude Code, Open Code, OpenAI Codex.
<!-- resource-id: codex-deferred-6019441b1be8 -->
- [**claude-review-loop**](https://github.com/hamelsmu/claude-review-loop) - (724 ⭐) - Claude Code plugin: automated code review loop with Codex.
<!-- resource-id: codex-deferred-286baede0a41 -->
- [**agents-md**](https://github.com/FerroxLabs/agents-md) - (679 ⭐) - Drop-in AGENTS.md that makes every coding agent behave like a senior engineer instead of an eager intern.
<!-- resource-id: codex-codejunkie99-fable-orchestrator -->
- [**fable-orchestrator**](https://github.com/codejunkie99/fable-orchestrator) - (594 ⭐) - Fable 5.1 orchestrates.
<!-- resource-id: codex-deferred-6461ac9d3eec -->
- [**metaswarm**](https://github.com/dsifry/metaswarm) - (413 ⭐) - A self-improving multi-agent orchestration framework for Claude Code, Gemini CLI, and Codex CLI, 18 agents, 13 skills, 15 commands, TDD enforcement, quality gates, spec-driven development.
<!-- resource-id: codex-awesome-u-ichi-reviewable-html-workbench -->
- [**reviewable-html-workbench**](https://github.com/u-ichi/reviewable-html-workbench) - (295 ⭐) - Claude Code / Codex CLI plugin for generating reviewable HTML documents with preview, inline review comments, and agent feedback ingestion.
<!-- resource-id: codex-deferred-15ce30a23e17 -->
- [**oc-chatgpt-multi-auth**](https://github.com/ndycode/oc-chatgpt-multi-auth) - (185 ⭐) - OpenCode plugin for ChatGPT Plus/Pro OAuth with Codex/GPT-5 routing, multi-account rotation, account switching, health checks, diagnostics, and recovery tools.
<!-- resource-id: codex-jobflow -->
- [**jobflow-for-codex**](https://github.com/laok775/jobflow-for-codex) - (182 ⭐) - JobFlow for Codex: a local job-search workflow plugin for Codex.
<!-- resource-id: codex-deferred-116bed1bf1bb -->
- [**vibepod-cli**](https://github.com/VibePod/vibepod-cli) - (144 ⭐) - Unified CLI for running AI coding agents in isolated containers.
<!-- resource-id: codex-awesome-proflead-codex-skills-library -->
- [**codex-skills-library**](https://github.com/proflead/codex-skills-library) - (141 ⭐) - Codex Skills Library is a curated library of reusable Codex skills for developers, individuals, and teams.
<!-- resource-id: codex-awesome-jturntdev-krypton -->
- [**krypton**](https://github.com/jturntdev/krypton) - (130 ⭐) - Goal-based planning and proof gate for AI coding agents.
<!-- resource-id: codex-deferred-31fbac4f006c -->
- [**pdf-trad-to-simp-preserve-layout-kit**](https://github.com/superpilot69/pdf-trad-to-simp-preserve-layout-kit) - (117 ⭐) - PDF traditional-to-simplified Chinese conversion kit with layout-preserving scripts, Codex skill, and example source/output PDFs.
<!-- resource-id: codex-awesome-manavmishra-zeroslop -->
- [**ZeroSlop**](https://github.com/manavmishra/ZeroSlop) - (110 ⭐) - Open-source Agent Skill that scores AI-sounding writing 0, 100, edits it with your assistant, and checks source details locally.

---

<a id="category-c06"></a>
## MCP Servers & Service Integrations

Connect Codex to browsers, data, and other services through MCP and documented bridges.

<!-- resource-id: codex-awesome-garrytan-gstack -->
- [**gstack**](https://github.com/garrytan/gstack) - (131.6k ⭐) - Use Garry Tan's exact Claude Code setup: 23 opinionated tools that serve as CEO, Designer, Eng Manager, Release Manager, Doc Engineer, and QA.
<!-- resource-id: codex-deferred-14feb4173df6 -->
- [**serena**](https://github.com/oraios/serena) - (28.9k ⭐) - A powerful MCP toolkit for coding, providing semantic retrieval and editing capabilities - the IDE for your agent.
<!-- resource-id: codex-deferred-d1a988be1b5e -->
- [**holaOS**](https://github.com/holaboss-ai/holaOS) - (11.1k ⭐) - Open-source agentic workspace enterprises can make their own.
<!-- resource-id: codex-deferred-e2246e5bf9ca -->
- [**notebooklm-mcp**](https://github.com/PleasePrompto/notebooklm-mcp) - (3.4k ⭐) - MCP server for NotebookLM - Let your AI agents (Claude Code, Codex) research documentation directly with grounded, citation-backed answers from Gemini.
<!-- resource-id: codex-awesome-intellectronica-ruler -->
- [**ruler**](https://github.com/intellectronica/ruler) - (2.9k ⭐) - Ruler, apply the same rules to all coding agents.
<!-- resource-id: codex-cocoindex-io-cocoindex-code -->
- [**cocoindex-code**](https://github.com/cocoindex-io/cocoindex-code) - (2.7k ⭐) - A super light-weight embedded code search engine CLI (AST based) that just works - improves speed and efficiency for coding agent.
<!-- resource-id: codex-scrapecreators-social-media-research-skills -->
- [**social-media-research-skills**](https://github.com/ScrapeCreators/social-media-research-skills) - (2.1k ⭐) - AI agent skills for social media research.
<!-- resource-id: codex-m0n0x41d-haft -->
- [**haft**](https://github.com/m0n0x41d/haft) - (1.4k ⭐) - Engineering decisions engine that know when they're stale.
<!-- resource-id: codex-awesome-rely-ai-org-caliber -->
- [**caliber**](https://github.com/rely-ai-org/caliber) - (1.3k ⭐) - Continuously sync your AI setups with one command.
<!-- resource-id: codex-caliber-ai-org-ai-setup -->
- [**ai-setup**](https://github.com/caliber-ai-org/ai-setup) - (1.3k ⭐) - Continuously sync your AI setups with one command.
<!-- resource-id: codex-awesome-tencentcloudbase-cloudbase-ai-toolkit -->
- [**CloudBase-AI-Toolkit**](https://github.com/TencentCloudBase/CloudBase-AI-Toolkit) - (1.1k ⭐) - Backend for AI coding agents on CloudBase, database, auth, functions via Plugin, Skills & MCP.
<!-- resource-id: codex-wzyn20051216-solidworks-automation-skill -->
- [**solidworks-automation-skill**](https://github.com/wzyn20051216/solidworks-automation-skill) - (833 ⭐) - Python automation toolkit for SolidWorks API.
<!-- resource-id: codex-icebird1998-scientific-illustrator -->
- [**scientific-illustrator**](https://github.com/icebird1998/scientific-illustrator) - (753 ⭐) - Editable scientific figures in PowerPoint and draw.io via Codex/MCP with Designer-Drawer-Reviewer-Corrector quality gates.
<!-- resource-id: codex-deferred-996b248ecd3d -->
- [**codex-seo**](https://github.com/AgriciDaniel/codex-seo) - (682 ⭐) - Codex-first SEO skill suite.
<!-- resource-id: codex-agent-sh-agnix -->
- [**agnix**](https://github.com/agent-sh/agnix) - (402 ⭐) - The missing linter and lsp for AI coding assistants.
<!-- resource-id: codex-awesome-mrphrazer-agentic-malware-analysis -->
- [**agentic-malware-analysis**](https://github.com/mrphrazer/agentic-malware-analysis) - (299 ⭐) - Agentic malware analysis environment with MCP-connected disassemblers, RE tooling, and structured workflows for Claude Code and Codex CLI.
<!-- resource-id: codex-awesome-wildcard-official-deepcontext-mcp -->
- [**deepcontext-mcp**](https://github.com/Wildcard-Official/deepcontext-mcp) - (276 ⭐) - DeepContext is an MCP server that adds symbol-aware semantic search to Claude Code, Codex CLI, and other agents for faster, smarter context on large codebases.
<!-- resource-id: codex-awesome-teabranch-open-responses-server -->
- [**open-responses-server**](https://github.com/teabranch/open-responses-server) - (185 ⭐) - Wraps any OpenAI API interface as Responses with MCPs support so it supports Codex.
<!-- resource-id: codex-awesome-miroapp-miro-ai -->
- [**miro-ai**](https://github.com/miroapp/miro-ai) - (151 ⭐) - Official Miro AI developer tools and integrations.
<!-- resource-id: codex-awesome-jasoncolapietro-suede-creator-skills -->
- [**suede-creator-skills**](https://github.com/JasonColapietro/suede-creator-skills) - (130 ⭐) - 74 open-source Agent Skills for Claude Code and Codex.

---

<a id="category-c07"></a>
## Usage, Monitoring & Session Tools

Inspect sessions, transcripts, token usage, logs, diagnostics, and recovery data.

<!-- resource-id: codex-career-ops-hq-career-ops -->
- [**career-ops**](https://github.com/career-ops-hq/career-ops) - (70.2k ⭐) - Open-source AI job search: scan job portals, evaluate listings into a structured A-H report with a global 1-5 score.
<!-- resource-id: codex-deferred-cc7c7d1d0d14 -->
- [**oh-my-openagent**](https://github.com/code-yeongyu/oh-my-openagent) - (68.7k ⭐) - OmO: Drop your tokens.
<!-- resource-id: codex-awesome-sickn33-antigravity-awesome-skills -->
- [**antigravity-awesome-skills**](https://github.com/sickn33/antigravity-awesome-skills) - (46k ⭐) - AAS Core is the local, agent-first control plane for complete catalog discovery, agent-owned selection, stack validation, and planning, backed by 2,100+ agentic skills.
<!-- resource-id: codex-deferred-40f29554daa1 -->
- [**awesome-agent-skills**](https://github.com/VoltAgent/awesome-agent-skills) - (33.8k ⭐) - A curated collection of 1000+ agent skills from official dev teams and the community, compatible with Claude Code, Codex, Gemini CLI, Cursor, and more.
<!-- resource-id: codex-manaflow-ai-cmux -->
- [**cmux**](https://github.com/manaflow-ai/cmux) - (26.8k ⭐) - Open source Ghostty-based macOS terminal with vertical tabs and notifications for AI coding agents.
<!-- resource-id: codex-deferred-b5e072514518 -->
- [**planning-with-files**](https://github.com/OthmanAdi/planning-with-files) - (26.6k ⭐) - Persistent file-based planning for AI coding agents and long-running tasks.
<!-- resource-id: codex-deferred-64942b4caa49 -->
- [**Auto-claude-code-research-in-sleep**](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) - (15.7k ⭐) - ARIS (Auto-Research-In-Sleep), Lightweight Markdown-only skills for autonomous ML research: cross-model review loops, idea discovery, and experiment automation.
<!-- resource-id: codex-deferred-cf4464551247 -->
- [**codeburn**](https://github.com/getagentseal/codeburn) - (10.9k ⭐) - Free, local tool to track AI coding token usage and cost across 37 tools and agents (Claude Code, Cursor, Codex, Gemini and more), by model, project, and task.
<!-- resource-id: codex-ppt-skill -->
- [**codex-ppt-skill**](https://github.com/ningzimu/codex-ppt-skill) - (5.6k ⭐) - GPT-Image-2 PPT Generator Skill for Creating Image-Based PowerPoint Presentations in Codex and Other Skill-Compatible Agents.
<!-- resource-id: codex-galaxy-dawn-claude-scholar -->
- [**claude-scholar**](https://github.com/Galaxy-Dawn/claude-scholar) - (5.3k ⭐) - Semi-automated research assistant for academic research and software development.
<!-- resource-id: codex-peonping-peon-ping -->
- [**peon-ping**](https://github.com/PeonPing/peon-ping) - (5k ⭐) - Warcraft III Peon voice notifications (+ more!) for Claude Code, Codex, IDEs, and any AI agent.
<!-- resource-id: codex-deferred-bd7b80aa8fff -->
- [**ip-as-logo-skill**](https://github.com/s1dashu/ip-as-logo-skill) - (4.9k ⭐) - A compact Agent Skill for highly simplified, rounded, subtly neo-skeuomorphic IP mascot logos.
<!-- resource-id: codex-deferred-3663fc10c62f -->
- [**codex-chatgpt-web**](https://github.com/miuuyy/codex-chatgpt-web) - (4.8k ⭐) - Use ChatGPT Web (including Pro) as a native model in the Codex app, with context, tools, streaming and images beyond Codex usage limits.
<!-- resource-id: codex-deferred-9f854464cea4 -->
- [**SwiftUI-Agent-Skill**](https://github.com/twostraws/SwiftUI-Agent-Skill) - (4.7k ⭐) - SwiftUI agent skill for Claude Code, Codex, and other AI tools.
<!-- resource-id: codex-deferred-8748ead302fd -->
- [**Skills**](https://github.com/Dimillian/Skills) - (3.9k ⭐) - My Codex Skills.
<!-- resource-id: codex-awesome-nowork-studio-notfair -->
- [**NotFair**](https://github.com/nowork-studio/NotFair) - (3.5k ⭐) - Open-source SEO, GEO, and marketing skills for AI agents.
<!-- resource-id: codex-deferred-cdef314ec42c -->
- [**abtop**](https://github.com/graykode/abtop) - (3.5k ⭐) - Like htop, but for AI coding agents.
<!-- resource-id: codex-pacifio-atlas -->
- [**atlas**](https://github.com/pacifio/atlas) - (3.2k ⭐) - Source control for agents.
<!-- resource-id: codex-samber-cc-skills-golang -->
- [**cc-skills-golang**](https://github.com/samber/cc-skills-golang) - (3.2k ⭐) - A collection of Golang agentic skills that works.
<!-- resource-id: codex-awesome-ryfinez-codex-session-patcher -->
- [**codex-session-patcher**](https://github.com/ryfineZ/codex-session-patcher) - (2.7k ⭐) - A lightweight Python tool to clean AI refusal responses from Codex CLI session files.
<!-- resource-id: codex-deferred-41bf0adc0909 -->
- [**pi-skills**](https://github.com/badlogic/pi-skills) - (2.5k ⭐) - Skills for pi coding agent (compatible with Claude Code and Codex CLI).
<!-- resource-id: codex-deferred-b59920924976 -->
- [**codex-autoresearch**](https://github.com/leo-lilinxiao/codex-autoresearch) - (2.4k ⭐) - Codex Autoresearch Skill, A self-directed iterative system for Codex that continuously cycles through: modify, verify, retain or discard, and repeat indefinitely.
<!-- resource-id: codex-observal-observal -->
- [**Observal**](https://github.com/Observal/Observal) - (2.4k ⭐) - Observal is self-hosted registry for your coding agent extensions with a built in insight engine.
<!-- resource-id: codex-ningzimu-image-to-editable-ppt-skill -->
- [**image-to-editable-ppt-skill**](https://github.com/ningzimu/image-to-editable-ppt-skill) - (2.4k ⭐) - Codex skill for converting slide images, PDFs, and image-based PPTX files into editable PowerPoint decks.
<!-- resource-id: codex-astro-han-karpathy-llm-wiki -->
- [**karpathy-llm-wiki**](https://github.com/Astro-Han/karpathy-llm-wiki) - (2.2k ⭐) - Agent Skills-compatible LLM wiki for Claude Code, Cursor, and Codex.
<!-- resource-id: codex-awesome-pchalasani-claude-code-tools -->
- [**claude-code-tools**](https://github.com/pchalasani/claude-code-tools) - (2k ⭐) - Practical productivity tools for Claude Code, Codex-CLI, and similar CLI coding agents.
<!-- resource-id: codex-deferred-15b9862f4e73 -->
- [**token-monitor**](https://github.com/Javis603/token-monitor) - (1.9k ⭐) - Local-first desktop widget for tracking token usage, costs, and limits across 35+ AI coding tools, including Claude Code, Codex, Cursor, OpenCode, and OpenClaw, with multi-device sync.
<!-- resource-id: codex-amelnagdy-delegate-skills -->
- [**delegate-skills**](https://github.com/amElnagdy/delegate-skills) - (1.7k ⭐) - Delegate a coding task to a separate coding agent CLI, review the diff, land the commit yourself, one per implementer.
<!-- resource-id: codex-awesome-deadwavewave-opencove -->
- [**opencove**](https://github.com/DeadWaveWave/opencove) - (1.6k ⭐) - Your infinite canvas workspace for agents, tasks, knowledge, and research.
<!-- resource-id: codex-awesome-flux159-mcp-server-kubernetes -->
- [**mcp-server-kubernetes**](https://github.com/Flux159/mcp-server-kubernetes) - (1.6k ⭐) - MCP Server for kubernetes management commands.
<!-- resource-id: codex-kaelio-ktx -->
- [**ktx**](https://github.com/Kaelio/ktx) - (1.6k ⭐) - ktx is an executable context layer for data and analytics agents Allow Claude Code, Codex, or other AI agents to query analytical databases accurately and with full context of your company.
<!-- resource-id: codex-keep-fast -->
- [**keep-codex-fast**](https://github.com/vibeforge1111/keep-codex-fast) - (1.6k ⭐) - A backup-first Codex skill for keeping local Codex state fast, clean, and recoverable.
<!-- resource-id: codex-deferred-8eb99cdd3b56 -->
- [**minutes**](https://github.com/silverstein/minutes) - (1.5k ⭐) - Open-source, local-first Granola/Otter alternative that Claude Code, Codex, Cursor, and any MCP client can query.
<!-- resource-id: codex-houseofmvps-codesight -->
- [**codesight**](https://github.com/Houseofmvps/codesight) - (1.4k ⭐) - Universal AI context generator.
<!-- resource-id: codex-awesome-ganyuanran-aegis -->
- [**Aegis**](https://github.com/GanyuanRan/Aegis) - (1.2k ⭐) - Make AI coding agents architecture-aware: baseline-first, evidence-verified, drift-checked, and safe across long tasks.
<!-- resource-id: codex-deferred-c3ce5cb93c50 -->
- [**tokentab**](https://github.com/damejan80/tokentab) - (1.2k ⭐) - A CLI that reads Claude Code, Codex, and Gemini CLI session logs and works out how much they cost, by model, project, and day.
<!-- resource-id: codex-awesome-sergebulaev-linkedin-skills -->
- [**linkedin-skills**](https://github.com/sergebulaev/linkedin-skills) - (1.1k ⭐) - Claude skills for LinkedIn.
<!-- resource-id: codex-deferred-3de7037a4993 -->
- [**ctx**](https://github.com/ctxrs/ctx) - (1.1k ⭐) - Instant recall for coding agents.
<!-- resource-id: codex-deferred-d93334134c24 -->
- [**ccpocket**](https://github.com/K9i-0/ccpocket) - (1.1k ⭐) - Mobile client for Codex and Claude, control coding agents from your phone via WebSocket bridge.
<!-- resource-id: codex-awesome-kunal12203-codex-cli-compact -->
- [**Codex-CLI-Compact**](https://github.com/kunal12203/Codex-CLI-Compact) - (1k ⭐) - Compounding Context for AI Coding Assistants, MCP graph engine for Claude Code, Cursor, Copilot, Gemini, OpenCode.
<!-- resource-id: codex-hoangsonww-claude-code-agent-monitor -->
- [**Claude-Code-Agent-Monitor**](https://github.com/hoangsonww/Claude-Code-Agent-Monitor) - (972 ⭐) - A real-time monitoring dashboard for Claude Code & Codex, built with SQLite3, Node.js, Express, React, Vite, TailwindCSS, & WebSockets.
<!-- resource-id: codex-deferred-6c73b727cbfe -->
- [**iai-personal-memory-engine**](https://github.com/CodeAbra/iai-personal-memory-engine) - (851 ⭐) - A cyber brain for your AI.
<!-- resource-id: codex-quoroom-ai-room -->
- [**room**](https://github.com/quoroom-ai/room) - (837 ⭐) - Open-source earning-focused swarm intelligence engine.
<!-- resource-id: codex-deferred-cf707a6e1f18 -->
- [**claude-replay**](https://github.com/es617/claude-replay) - (826 ⭐) - Convert AI coding agent sessions (Claude Code, Cursor, Codex, Gemini, OpenCode, Kimi Code, Hermes) into self-contained, embeddable HTML replays.
<!-- resource-id: codex-deferred-1809a7a5421b -->
- [**projectmem**](https://github.com/riponcm/projectmem) - (797 ⭐) - Open-source coding agent memory.
<!-- resource-id: codex-awesome-garethmanning-education-agent-skills -->
- [**education-agent-skills**](https://github.com/GarethManning/education-agent-skills) - (734 ⭐) - 165 evidence-grounded AI skills for teachers, school leaders and EdTech builders, pedagogy, learning science, curriculum, assessment and regeneration.
<!-- resource-id: codex-appllama-appllama-skills -->
- [**appllama-skills**](https://github.com/Appllama/appllama-skills) - (730 ⭐) - A builder, not just a researcher.
<!-- resource-id: codex-agentic-box-memora -->
- [**memora**](https://github.com/agentic-box/memora) - (715 ⭐) - Give your AI agents persistent, collective memory, with deduplicating absorb, supersession lineage, semantic search, and a graph UI.
<!-- resource-id: codex-deferred-fbff000459f2 -->
- [**horizon**](https://github.com/peters/horizon) - (701 ⭐) - GPU-accelerated terminal board that puts all your sessions on an infinite canvas.
<!-- resource-id: codex-deferred-6b7c134e1ca5 -->
- [**figwright**](https://github.com/awdr74100/figwright) - (682 ⭐) - Free, two-way Figma MCP server.
<!-- resource-id: codex-sodiumsun-agenttrail -->
- [**agenttrail**](https://github.com/sodiumsun/agenttrail) - (647 ⭐) - An infinite canvas for your AI coding agents.
<!-- resource-id: codex-awesome-samvallad33-vestige -->
- [**vestige**](https://github.com/samvallad33/vestige) - (616 ⭐) - Vestige enhances agents by deterministic root-cause retrieval that reaches backward through time to find the quiet change, decision, or service that caused today's failure, not the lookalike.
<!-- resource-id: codex-bawadou-ai-data-extractor -->
- [**ai-data-extractor**](https://github.com/bawadou/ai-data-extractor) - (553 ⭐) - Free open-source extractor for AI coding assistant chat histories.
<!-- resource-id: codex-deferred-86fa1596ef4d -->
- [**agentops**](https://github.com/boshu2/agentops) - (433 ⭐) - The operations layer for agentic engineering, portable skills and contracts connecting intent, agents, software factories, and independent judgment.
<!-- resource-id: codex-awesome-razzant-claudexor -->
- [**claudexor**](https://github.com/razzant/claudexor) - (433 ⭐) - Multi-harness control plane for Claude Code, Codex, Cursor, and OpenCode: quota-aware rotation across multiple Claude/Codex subscriptions, shared thread context, and cross-model review.
<!-- resource-id: codex-deferred-48fc1cbb25f4 -->
- [**codex_workflow**](https://github.com/viettran-edgeAI/codex_workflow) - (392 ⭐) - A swarm orchestration system in Codex, drastically reduce overall token usage.
<!-- resource-id: codex-awesome-shelpuk-ai-technology-consulting-kindly-web-search-mcp-server -->
- [**kindly-web-search-mcp-server**](https://github.com/Shelpuk-AI-Technology-Consulting/kindly-web-search-mcp-server) - (382 ⭐) - Kindly Web Search MCP Server: Web search + robust content retrieval for AI coding tools (Claude Code, Codex, Cursor, GitHub Copilot, Gemini, etc.) and AI agents (Claude Desktop, OpenClaw, Hermes, etc).
<!-- resource-id: codex-deferred-dfa9e9129125 -->
- [**Usage4Claude**](https://github.com/f-is-h/Usage4Claude) - (381 ⭐) - Monitor all your Claude/Codex usage limits in real-time from your macOS menu bar - supports 5-hour, 7-day, extra usage, 7-day Opus and 7-day Sonnet quotas.
<!-- resource-id: codex-deferred-cfe271c93d0b -->
- [**TokenBar**](https://github.com/Nanako0129/TokenBar) - (327 ⭐) - AI token usage & quota monitor for the macOS menu bar, native Swift, Liquid Glass, 3D contribution graph.
<!-- resource-id: codex-deferred-12795b2c73b8 -->
- [**codex-island**](https://github.com/ericjypark/codex-island) - (320 ⭐) - CodexIsland - AI usage limits in your MacBook notch.
<!-- resource-id: codex-awesome-waltstephen-argusbot -->
- [**ArgusBot**](https://github.com/waltstephen/ArgusBot) - (316 ⭐) - ArgusBot: A 24/7 supervisor Agent for Codex CLI and Claude Code CLI that keeps agents running, reviewing, and planning until the job is actually done.
<!-- resource-id: codex-deferred-fd9a5bcb5ac7 -->
- [**usage**](https://github.com/aqua5230/usage) - (308 ⭐) - macOS menu bar & Windows tray app pinning Claude Code, Codex & Antigravity quota, burn rate, and cost to your screen.
<!-- resource-id: codex-awesome-nicepkg-ai-workflow -->
- [**ai-workflow**](https://github.com/nicepkg/ai-workflow) - (282 ⭐) - 170+ pre-built skills for Claude Code, Cursor, Codex & 14+ AI tools.
<!-- resource-id: codex-green-pt-honey-for-devs -->
- [**honey-for-devs**](https://github.com/Green-PT/honey-for-devs) - (282 ⭐) - Honey (I Shrunk the AI) by GreenPT.
<!-- resource-id: codex-deferred-8fd291945274 -->
- [**signetai**](https://github.com/Signet-AI/signetai) - (266 ⭐) - Sync and store memories, shared identity files (AGENTS.md, CLAUDE.md), session transcripts, institutional knowledge, and secrets between all of your favorite harnesses and models.
<!-- resource-id: codex-awesome-milanglacier-yarepl-nvim -->
- [**yarepl.nvim**](https://github.com/milanglacier/yarepl.nvim) - (251 ⭐) - Versatile REPL/CLI manager.
<!-- resource-id: codex-piebald-ai-splitrail -->
- [**splitrail**](https://github.com/Piebald-AI/splitrail) - (219 ⭐) - Fast, cross-platform, real-time token usage tracker and cost monitor for Claude Code / Codex CLI / Antigravity CLI / Qwen Code / Cline / Zoo Code / Kilo Code / GitHub Copilot.
<!-- resource-id: codex-zippoxer-recall -->
- [**recall**](https://github.com/zippoxer/recall) - (199 ⭐) - Full-text search and resume for Claude/Codex conversations.
<!-- resource-id: codex-deferred-c5cecfd0c9d4 -->
- [**codex-usage-tracker**](https://github.com/douglasmonsky/codex-usage-tracker) - (192 ⭐) - Local-first MCP tools and dashboard for investigating Codex token usage, credits, costs, caching, and thread patterns.
<!-- resource-id: codex-dicklesworthstone-coding-agent-account-manager -->
- [**coding_agent_account_manager**](https://github.com/Dicklesworthstone/coding_agent_account_manager) - (191 ⭐) - Sub-100ms auth switching for AI coding CLIs (Claude Code, Codex, Gemini): swap subscription accounts instantly when you hit usage limits.
<!-- resource-id: codex-niclasvestlund-yt-vibepulse -->
- [**vibepulse**](https://github.com/niclasvestlund-YT/vibepulse) - (187 ⭐) - ESP32-S3 AMOLED for Claude Code & Codex usage, live agent activity, and answerable NEEDS YOU alerts.
<!-- resource-id: codex-awesome-frankieli123-grok-skill -->
- [**grok-skill**](https://github.com/Frankieli123/grok-skill) - (182 ⭐) - Codex skill: aggressive web research via OpenAI-compatible Grok endpoint (2api).
<!-- resource-id: codex-deferred-f6adaf44db39 -->
- [**codex-mcp-server**](https://github.com/cexll/codex-mcp-server) - (179 ⭐) - Codex Mcp Server.
<!-- resource-id: codex-deferred-bb92c64a3b42 -->
- [**claude-codex-usage-dashboard**](https://github.com/frankchiu-dev/claude-codex-usage-dashboard) - (171 ⭐) - A local Windows dashboard for Claude Code and Codex usage limits.
<!-- resource-id: codex-deferred-00109eb9aedd -->
- [**mcp-codex-dev**](https://github.com/FYZAFH/mcp-codex-dev) - (166 ⭐) - MCP Server for Codex CLI integration - stateful code writing and review workflows.
<!-- resource-id: codex-awesome-digital-process-tools-claude-remember -->
- [**claude-remember**](https://github.com/Digital-Process-Tools/claude-remember) - (165 ⭐) - Persistent memory for Claude Code, identity, context, and continuity across sessions.
<!-- resource-id: codex-deferred-21c876559be7 -->
- [**connectors**](https://github.com/zapier/connectors) - (165 ⭐) - Connect your agent to the apps you already use - with or without Zapier.
<!-- resource-id: codex-awesome-pattern-ai-labs-agentcall -->
- [**agentcall**](https://github.com/pattern-ai-labs/agentcall) - (155 ⭐) - AgentCall lets AI Agents join meetings with voice, video & screen-share to build together.
<!-- resource-id: codex-deferred-2a15526b843a -->
- [**cc-clip**](https://github.com/ShunmeiCho/cc-clip) - (151 ⭐) - Paste images into remote Claude Code & Codex CLI over SSH, clipboard bridging for macOS and Windows.
<!-- resource-id: codex-mangiapanejohn-dev-quotalens -->
- [**QuotaLens**](https://github.com/mangiapanejohn-dev/QuotaLens) - (149 ⭐) - See your AI usage clearly, a macOS menu-bar gauge for Claude & Codex quotas.
<!-- resource-id: codex-awesome-st0012-cctop -->
- [**cctop**](https://github.com/st0012/cctop) - (148 ⭐) - A keyboard-first menubar app to monitor and jump between AI coding sessions, minimum setup required.
<!-- resource-id: codex-awesome-mohamedabdallah-14-unslop -->
- [**unslop**](https://github.com/MohamedAbdallah-14/unslop) - (127 ⭐) - Make AI output sound human.
<!-- resource-id: codex-deferred-2af19f93db54 -->
- [**codex-wrapped**](https://github.com/numman-ali/codex-wrapped) - (121 ⭐) - Generate a personalized Spotify Wrapped-style summary of your Codex usage.
<!-- resource-id: codex-juliantanx-aiusage -->
- [**aiusage**](https://github.com/juliantanx/aiusage) - (119 ⭐) - Open-source AI usage tracker, tokens, cost, and sessions across Claude Code, Codex, Hermes, Qoder, and more.
<!-- resource-id: codex-awesome-ducksss-codex-profiles -->
- [**codex-profiles**](https://github.com/Ducksss/codex-profiles) - (117 ⭐) - Named CODEX_HOME profiles and ChatGPT Desktop windows with separate local state, without copying tokens.
<!-- resource-id: codex-awesome-burakdede-aisw -->
- [**aisw**](https://github.com/burakdede/aisw) - (112 ⭐) - AISW, AI Switcher - Switch between multiple Claude Code, Codex CLI, Antigravity and Gemini CLI accounts in one command.
<!-- resource-id: codex-deferred-9457303ea93f -->
- [**codex-reset-watcher**](https://github.com/jordan-edai/codex-reset-watcher) - (107 ⭐) - Local-first macOS menu bar app for Codex usage limits and reset credits.
<!-- resource-id: codex-awesome-necmttn-ax -->
- [**ax**](https://github.com/Necmttn/ax) - (105 ⭐) - the agent experience layer, observability + memory for AI coding agents (Claude Code + Codex), local-first, typed, yours.
<!-- resource-id: codex-deferred-62efccbf2c5e -->
- [**Codex-Usage**](https://github.com/MacSteini/Codex-Usage) - (105 ⭐) - Local Python CLI for reset credits, rate-limit windows, local usage metadata, read-only online usage/profile data, and optional API organisation usage.
<!-- resource-id: codex-awesome-avivsinai-langfuse-mcp -->
- [**langfuse-mcp**](https://github.com/avivsinai/langfuse-mcp) - (105 ⭐) - A Model Context Protocol (MCP) server for Langfuse, enabling AI agents to query Langfuse trace data for enhanced debugging and observability.
<!-- resource-id: codex-cobb04-codex-level -->
- [**Codex-Level**](https://github.com/Cobb04/Codex-Level) - (104 ⭐) - A macOS menu bar app that turns lifetime Codex usage into QQ-style levels and progress.
<!-- resource-id: codex-deferred-b9dab4609ce6 -->
- [**codex-pet-usage-companion**](https://github.com/Nemo0000/codex-pet-usage-companion) - (104 ⭐) - A lightweight Windows companion for switching Codex pets and viewing ChatGPT-backed usage limits.
<!-- resource-id: codex-deferred-af89bf557553 -->
- [**claude-codex-battery**](https://github.com/dennykim123/claude-codex-battery) - (103 ⭐) - macOS menu bar widget showing Claude Code & Codex usage limits as battery icons.

---

<a id="category-c08"></a>
## SDKs, Adapters & Runtime Infrastructure

Build applications and runtimes around Codex with SDKs, adapters, gateways, and containers.

<!-- resource-id: codex-deferred-d57d2570b6a6 -->
- [**awesome-claude-skills**](https://github.com/ComposioHQ/awesome-claude-skills) - (74.5k ⭐) - A curated list of awesome Claude Skills, resources, and tools for customizing Claude AI workflows.
<!-- resource-id: codex-alishahryar1-free-claude-code -->
- [**free-claude-code**](https://github.com/Alishahryar1/free-claude-code) - (53.2k ⭐) - Use Claude Code, Codex, Pi, and OpenCode and more for free (1.3B+ free tokens) from your terminal, app, IDE, or phone like OpenClaw (voice supported + ToS friendly).
<!-- resource-id: codex-router-for-me-cliproxyapi -->
- [**CLIProxyAPI**](https://github.com/router-for-me/CLIProxyAPI) - (50.5k ⭐) - Wrap Antigravity, ChatGPT Codex, Claude Code, Grok Build as an OpenAI/Gemini/Claude/Codex compatible API service, allowing you to enjoy the free Gemini 3.1 Pro, GPT 5.6 Series, Grok 4.5, Claude model through API.
<!-- resource-id: codex-oh-my-codex -->
- [**oh-my-codex**](https://github.com/Yeachan-Heo/oh-my-codex) - (33k ⭐) - OmX - Oh My codeX: Your codex is not alone.
<!-- resource-id: codex-deferred-747c022ab640 -->
- [**Anthropic-Cybersecurity-Skills**](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) - (32.2k ⭐) - 817 structured cybersecurity skills for AI agents, Mapped to 6 frameworks.
<!-- resource-id: codex-deferred-387ea3f4f71a -->
- [**agentmemory**](https://github.com/rohitg00/agentmemory) - (28k ⭐) - #1 Persistent memory for AI coding agents based on real-world benchmarks.
<!-- resource-id: codex-deferred-a0d9fa7f1f10 -->
- [**9router**](https://github.com/decolua/9router) - (27.1k ⭐) - Unlimited FREE AI coding.
<!-- resource-id: codex-codexbar -->
- [**CodexBar**](https://github.com/steipete/CodexBar) - (20.9k ⭐) - Show usage stats for OpenAI Codex and Claude Code, without having to login.
<!-- resource-id: codex-skillspector -->
- [**SkillSpector**](https://github.com/NVIDIA/SkillSpector) - (16.2k ⭐) - Security scanner for AI agent skills.
<!-- resource-id: codex-deferred-bf5718932e52 -->
- [**paseo**](https://github.com/getpaseo/paseo) - (16.1k ⭐) - Orchestrate multiple coding agents from desktop and mobile.
<!-- resource-id: codex-chenhg5-cc-connect -->
- [**cc-connect**](https://github.com/chenhg5/cc-connect) - (15.4k ⭐) - Bridge local AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) to messaging platforms (Feishu/Lark, DingTalk, Slack, Telegram, Discord, LINE, WeChat Work).
<!-- resource-id: codex-deferred-c03909776929 -->
- [**claudian**](https://github.com/YishenTu/claudian) - (15.2k ⭐) - An Obsidian plugin that embeds Claude Code/Codex as an AI collaborator in your vault.
<!-- resource-id: codex-fei-away-codex-dream-skin -->
- [**Codex-Dream-Skin**](https://github.com/Fei-Away/Codex-Dream-Skin) - (14.3k ⭐) - Codex Dream Skin.
<!-- resource-id: codex-deferred-0ab5e99eecfe -->
- [**superset**](https://github.com/superset-sh/superset) - (13.8k ⭐) - Superset is an agentic IDE to orchestrate 100+ coding agents in parallel.
<!-- resource-id: codex-deferred-a9a05a3c4ab2 -->
- [**opencodex**](https://github.com/lidge-jun/opencodex) - (13.4k ⭐) - Universal provider proxy for OpenAI Codex & Claude Code, use any LLM (Claude, Gemini, Grok, DeepSeek, Ollama.) with Codex CLI, App, SDK, and Claude Code.
<!-- resource-id: codex-academic-research-skills -->
- [**academic-research-skills-codex**](https://github.com/Imbad0202/academic-research-skills-codex) - (10k ⭐) - Codex-native Academic Research Skills suite for human-in-the-loop academic research workflows.
<!-- resource-id: codex-deferred-0e82f66e5a72 -->
- [**AIClient2API**](https://github.com/justlovemaki/AIClient2API) - (8.7k ⭐) - Self-hosted multi-protocol AI API proxy for Antigravity, Codex, Grok, Kiro, OpenAI, Claude, and custom providers.
<!-- resource-id: codex-builderz-labs-mission-control -->
- [**mission-control**](https://github.com/builderz-labs/mission-control) - (6.2k ⭐) - Self-hosted control plane for AI agents: dispatch tasks, review runs, track spend, and operate OpenClaw, Claude Code, Codex, and other runtimes.
<!-- resource-id: codex-zseven-w-openpencil -->
- [**openpencil**](https://github.com/ZSeven-W/openpencil) - (5.8k ⭐) - The world's first open-source AI-native vector design tool and the first to feature concurrent Agent Teams.
<!-- resource-id: codex-browser-act-skills -->
- [**skills**](https://github.com/browser-act/skills) - (5.6k ⭐) - Browser automation CLI built for AI agents.
<!-- resource-id: codex-deferred-aace0011b827 -->
- [**yournextstore**](https://github.com/yournextstore/yournextstore) - (5.5k ⭐) - AI-Native Open-Source Next.js commerce.
<!-- resource-id: codex-devin-axis-ipollowork -->
- [**iPolloWork**](https://github.com/Devin-AXIS/iPolloWork) - (5.3k ⭐) - Enterprise-grade, local-first Agent Workbench for people and agent teams.
<!-- resource-id: codex-deferred-8cbec67aa0f2 -->
- [**tokscale**](https://github.com/junhoyeo/tokscale) - (5.3k ⭐) - Track token usage across AI coding agents from your terminal.
<!-- resource-id: codex-deferred-bbaf815a0cad -->
- [**adhd**](https://github.com/UditAkhourii/adhd) - (4.1k ⭐) - ADHD, a skill for coding agents.
<!-- resource-id: codex-awesome-nyldn-claude-octopus -->
- [**claude-octopus**](https://github.com/nyldn/claude-octopus) - (4k ⭐) - Run multiple AI models against the same research, design, or coding task.
<!-- resource-id: codex-deferred-6227f7677500 -->
- [**code**](https://github.com/just-every/code) - (4k ⭐) - Every Code - push frontier AI to it limits.
<!-- resource-id: codex-deferred-a5d312ca85e2 -->
- [**CPA-Manager-Plus**](https://github.com/seakee/CPA-Manager-Plus) - (3.2k ⭐) - A self-hosted CPA / CLIProxyAPI management panel and AI gateway observability dashboard for requests, usage, cost, quota, failures, and account health.
<!-- resource-id: codex-deferred-6887b231c038 -->
- [**codex-lb**](https://github.com/Soju06/codex-lb) - (3k ⭐) - Codex/ChatGPT multiple account load balancer & proxy with usage tracking, dashboard, and OpenCode-compatible endpoints.
<!-- resource-id: codex-deferred-4a277c5c2676 -->
- [**Claude-to-IM-skill**](https://github.com/op7418/Claude-to-IM-skill) - (2.9k ⭐) - Bridge Claude Code / Codex to IM platforms, chat with AI coding agents from Telegram, Discord, or Feishu/Lark.
<!-- resource-id: codex-yilewang-llm-for-zotero -->
- [**llm-for-zotero**](https://github.com/yilewang/llm-for-zotero) - (2.9k ⭐) - An open-sourced research agent system deeply rooted in your Zotero library.
<!-- resource-id: codex-deferred-ce95f33e421c -->
- [**jcodemunch-mcp**](https://github.com/jgravelle/jcodemunch-mcp) - (2.7k ⭐) - Cut AI token costs 95%+ on code exploration.
<!-- resource-id: codex-deferred-dfdb2ea44eb2 -->
- [**agents-best-practices**](https://github.com/DenisSergeevitch/agents-best-practices) - (2.3k ⭐) - Provider-neutral Agent Skill for Codex, Claude Code, and agentic harness design.
<!-- resource-id: codex-deferred-61f3f3f164c3 -->
- [**LiveAgent**](https://github.com/Stack-Cairn/LiveAgent) - (2k ⭐) - A fully functional AI Agent desktop client that supports Webui access and can be creatively customized and expanded!
<!-- resource-id: codex-deferred-ad6338b979f1 -->
- [**vibekit**](https://github.com/superagent-ai/vibekit) - (1.9k ⭐) - Run Claude Code, Gemini, Codex, or any coding agent, in a clean, isolated sandbox with sensitive data redaction and observability baked in.
<!-- resource-id: codex-awesome-standardagents-dmux -->
- [**dmux**](https://github.com/standardagents/dmux) - (1.8k ⭐) - A dev agent multiplexer for git worktrees and coding agents.
<!-- resource-id: codex-awesome-icebear0828-codex-proxy -->
- [**codex-proxy**](https://github.com/icebear0828/codex-proxy) - (1.7k ⭐) - OpenAI-compatible proxy for ChatGPT Codex Responses API.
<!-- resource-id: codex-uber-adr -->
- [**ADR**](https://github.com/uber/ADR) - (1.5k ⭐) - ADR secures enterprise AI agents through observability, security benchmarking, and threat detection.
<!-- resource-id: codex-deferred-3f55b6e77a28 -->
- [**TokenTracker**](https://github.com/xiufengsun/TokenTracker) - (1.5k ⭐) - Local-first AI token usage & cost tracker for 31 coding tools incl.
<!-- resource-id: codex-coder-agentapi -->
- [**agentapi**](https://github.com/coder/agentapi) - (1.5k ⭐) - HTTP API for Claude Code, Goose, Aider, Gemini, Amp, and Codex.
<!-- resource-id: codex-deferred-3a30c9f3d529 -->
- [**ClaudeBar**](https://github.com/tddworks/ClaudeBar) - (1.5k ⭐) - A macOS menu bar application that monitors AI coding assistant usage quotas.
<!-- resource-id: codex-awesome-greensheep01201-claw-empire -->
- [**claw-empire**](https://github.com/GreenSheep01201/claw-empire) - (1.4k ⭐) - Command Your AI Agent Empire from the CEO Desk, A local-first AI agent office simulator that orchestrates CLI, OAuth, and API-connected agents (Claude Code, Codex CLI.
<!-- resource-id: codex-deferred-152b26ebc59b -->
- [**boop-agent**](https://github.com/raroque/boop-agent) - (1.4k ⭐) - iMessage personal agent: choose Claude Agent SDK (Claude Code) or Codex app-server runtime (Codex/ChatGPT), with memory, sub-agents, automations, integrations.
<!-- resource-id: codex-awesome-razzant-ouroboros -->
- [**ouroboros**](https://github.com/razzant/ouroboros) - (1.3k ⭐) - Ouroboros, self-creating AI agent.
<!-- resource-id: codex-awesome-deepmyst-mysti -->
- [**Mysti**](https://github.com/DeepMyst/Mysti) - (1.1k ⭐) - AI coding dream team of agents for VS Code.
<!-- resource-id: codex-deferred-4280bc3d2cb2 -->
- [**claude-codex-settings**](https://github.com/fcakyon/claude-codex-settings) - (1.1k ⭐) - Battle-tested Claude Code, OpenAI Codex, Cursor configs, plugins, hooks and agents with Kimi, MiniMax and GLM API support.
<!-- resource-id: codex-deferred-3746dc7dc6e2 -->
- [**coding_agent_session_search**](https://github.com/Dicklesworthstone/coding_agent_session_search) - (1.1k ⭐) - Unified TUI and CLI to index and search your local coding agent session history across 11+ providers (Codex, Claude, Gemini, Cursor, Aider, etc.).
<!-- resource-id: codex-awesome-chernistry-bernstein -->
- [**bernstein**](https://github.com/chernistry/bernstein) - (1.1k ⭐) - The opensource AI Agents Governance & Orchestration framework: write the rules declaratively, Bernstein enforces them and produces the verifiable, replayable record.
<!-- resource-id: codex-awesome-agentlas-ai-agentlas-os -->
- [**Agentlas-OS**](https://github.com/agentlas-ai/Agentlas-OS) - (1.1k ⭐) - Agent OS: keep specialist agents in a hub, spin up a temporary orchestrator per task.
<!-- resource-id: codex-deferred-801f9eb4d519 -->
- [**Win-CodexBar**](https://github.com/nesszer/Win-CodexBar) - (1k ⭐) - Show usage stats for OpenAI Codex and Claude Code, without having to login.
<!-- resource-id: codex-deferred-c62abeff93ad -->
- [**ccNexus**](https://github.com/lich0821/ccNexus) - (972 ⭐) - Intelligent API gateway for Claude Code and Codex CLI - rotate endpoints, monitor usage, and seamlessly integrate OpenAI, Gemini, and other platforms.
<!-- resource-id: codex-vostride-agent-qa -->
- [**agent-qa**](https://github.com/vostride/agent-qa) - (901 ⭐) - Open-source self-improving QA agent for software teams.
<!-- resource-id: codex-autoresearch -->
- [**codex-autoresearch**](https://github.com/TheGreenCedar/codex-autoresearch) - (836 ⭐) - A codex plugin for running optimization loops inside a codebase.
<!-- resource-id: codex-h-mmer-pentest-agents -->
- [**pentest-agents**](https://github.com/H-mmer/pentest-agents) - (816 ⭐) - Bug bounty agent framework for Claude Code, Codex, Gemini, Cursor, Windsurf, Copilot, and OpenClaw, 48 agents, 26 commands, 19 CLI tools, 2 MCP servers, autonomous hunt loops, exploit chain builder.
<!-- resource-id: codex-awesome-indranilbanerjee-digital-marketing-pro -->
- [**digital-marketing-pro**](https://github.com/indranilbanerjee/digital-marketing-pro) - (792 ⭐) - An open-source AI marketing operating system for strategy, SEO, AEO/GEO, paid media, content, CRM, and analytics - grounded in brand context, human approval, and verifiable outputs.
<!-- resource-id: codex-deferred-5f1a9376aab6 -->
- [**zerobox**](https://github.com/afshinm/zerobox) - (713 ⭐) - Lightweight, cross-platform process sandboxing powered by OpenAI Codex's runtime.
<!-- resource-id: codex-deferred-187cafad461e -->
- [**vscode-unify-chat-provider**](https://github.com/smallmain/vscode-unify-chat-provider) - (708 ⭐) - Integrate multiple LLM API providers into VS Code's GitHub Copilot Chat using the Language Model API.
<!-- resource-id: codex-mikehasa-agentacct -->
- [**agentacct**](https://github.com/mikehasa/agentacct) - (699 ⭐) - See what your coding agents did and what it cost.
<!-- resource-id: codex-hkqr-my-free-code -->
- [**my-free-code**](https://github.com/hkqr/my-free-code) - (633 ⭐) - Open-source multi-provider AI gateway for Claude Code and other coding agents, with model routing, streaming, tools, reasoning, fallbacks, and local model support.
<!-- resource-id: codex-awesome-hashgraph-online-hol-guard -->
- [**hol-guard**](https://github.com/hashgraph-online/hol-guard) - (558 ⭐) - Open-source antivirus for AI agents: block risky tools, secret access, prompt injection, malicious packages, MCP servers, plugins, and skills at runtime.
<!-- resource-id: codex-awesome-mco-org-mco -->
- [**mco**](https://github.com/mco-org/mco) - (513 ⭐) - CLI-first orchestration for AI coding agents: run selected agents and models in parallel, compare raw answers, and coordinate review or implementation workflows.
<!-- resource-id: codex-deferred-85bb7ac03eb4 -->
- [**dario**](https://github.com/askalf/dario) - (506 ⭐) - A local OpenAI- and Anthropic-compatible proxy that serves your Claude AND ChatGPT subscriptions to Cursor.
<!-- resource-id: codex-awesome-codexstar69-bug-hunter -->
- [**bug-hunter**](https://github.com/codexstar69/bug-hunter) - (501 ⭐) - Adversarial AI bug hunter with auto-fix skill for Claude Code, Cursor, Codex CLI, GitHub Copilot CLI, Kiro CLI, Opencode, Pi Coding Agent, and more.
<!-- resource-id: codex-deferred-06a1232269c5 -->
- [**kibitz**](https://github.com/kibitzsh/kibitz) - (495 ⭐) - Real-time decoded feed of AI agent actions, monitor multiple Claude Code & Codex sessions, see exactly what each agent is doing, and coordinate swarms efficiently.
<!-- resource-id: codex-awesome-ndycode-codex-multi-auth -->
- [**codex-multi-auth**](https://github.com/ndycode/codex-multi-auth) - (476 ⭐) - Codex CLI multi-account OAuth manager with account switching, health checks, runtime rotation, diagnostics, and recovery tools for @openai/codex.
<!-- resource-id: codex-awesome-josstei-maestro-orchestrate -->
- [**maestro-orchestrate**](https://github.com/josstei/maestro-orchestrate) - (461 ⭐) - Multi-agent orchestration platform for Gemini CLI, Claude Code, Codex, and Qwen Code, 39 specialists, parallel subagents, persistent sessions, and built-in code review, debugging, security, SEO, accessibility, and compliance tools.
<!-- resource-id: codex-deferred-9a9372e54fbc -->
- [**ductor**](https://github.com/PleasePrompto/ductor) - (454 ⭐) - Control Claude Code, Codex CLI and Gemini CLI from Telegram.
<!-- resource-id: codex-deferred-c401f3f22f1e -->
- [**entroly**](https://github.com/juyterman1000/entroly) - (443 ⭐) - Cut AI context cost without trusting the compressor.
<!-- resource-id: codex-awesome-ikalus1988-misakanet -->
- [**MisakaNet**](https://github.com/Ikalus1988/MisakaNet) - (442 ⭐) - A zero-dependency, git-backed micro-lesson library for AI Agents to asynchronously share and search verified debugging experience.
<!-- resource-id: codex-edouard-claude-snip -->
- [**snip**](https://github.com/edouard-claude/snip) - (434 ⭐) - CLI proxy that reduces LLM token usage by 60-90%.
<!-- resource-id: codex-deferred-823f08b03ee1 -->
- [**clawmetry**](https://github.com/vivekchand/clawmetry) - (406 ⭐) - See your agent think.
<!-- resource-id: codex-acp-adapter -->
- [**codex-acp**](https://github.com/agentclientprotocol/codex-acp) - (348 ⭐) - ACP server implementation that exposes Codex CLI functionality for smoother client and IDE integration.
<!-- resource-id: codex-deferred-3fe3926e53eb -->
- [**codexU**](https://github.com/shanggqm/codexU) - (344 ⭐) - macOS desktop widget for OpenAI Codex usage, quota tracking, token usage, and today task board.
<!-- resource-id: codex-walkingddd-cpa-helper -->
- [**CPA-Helper**](https://github.com/walkingddd/CPA-Helper) - (310 ⭐) - CPA-Helper is a local, self-hosted multi-user management panel designed for CLIProxyAPI users.
<!-- resource-id: codex-deferred-56f60ad1a131 -->
- [**open-browser-use**](https://github.com/iFurySt/open-browser-use) - (259 ⭐) - Platform-neutral Browser Use for AI agents: real Chrome automation with a CLI + SDKs, no lock-in, dead simple.
<!-- resource-id: codex-deferred-0ef8a38285a7 -->
- [**termic**](https://github.com/simion/termic) - (244 ⭐) - Open-source Conductor.build alternative.
<!-- resource-id: codex-deferred-2e5d7cc3d89c -->
- [**agent_hub**](https://github.com/Bitget-AI/agent_hub) - (223 ⭐) - Official Bitget Agent Hub, open-source AI toolkit connecting Claude, Cursor, Codex & ChatGPT to Bitget crypto trading (89 UTA v3 ops) and market analysis.
<!-- resource-id: codex-taisly-agent -->
- [**agent**](https://github.com/taisly/agent) - (219 ⭐) - Taisly Agent Kit: MCP server, CLI, SDK, and agent docs for publishing videos to TikTok, Reels, Shorts, X, and Facebook.
<!-- resource-id: codex-deferred-cc624b3337fb -->
- [**nyro**](https://github.com/nyroway/nyro) - (190 ⭐) - Self-hosted AI Gateway, connect Claude Code, Codex, Gemini CLI and any SDK to any model provider with protocol translation.
<!-- resource-id: codex-janekbaraniewski-openusage -->
- [**openusage**](https://github.com/janekbaraniewski/openusage) - (187 ⭐) - The one dashboard you've been looking for, track spend and usage across Claude, Cursor, OpenRouter, Copilot, Gemini, Codex, and more.
<!-- resource-id: codex-kairyou-agent-tools -->
- [**agent-tools**](https://github.com/kairyou/agent-tools) - (177 ⭐) - Reusable Agent Skills, plus integrations (statusline, provider usage, vision) that install into Codex, Claude Code, and opencode.
<!-- resource-id: codex-oratis-lisa -->
- [**LISA**](https://github.com/oratis/LISA) - (174 ⭐) - An AI agent with a real self, soul she wrote, desires that drive her, a heartbeat for autonomous action, dreams she processes when you're away.
<!-- resource-id: codex-deferred-9c8ac8cf6289 -->
- [**tensorlake-skills**](https://github.com/tensorlakeai/tensorlake-skills) - (174 ⭐) - Coding agent skill for Tensorlake.
<!-- resource-id: codex-deferred-84acdbae125b -->
- [**codex_dspy**](https://github.com/darinkishore/codex_dspy) - (166 ⭐) - DSPy module for OpenAI Codex SDK - signature-driven agentic workflows.
<!-- resource-id: codex-digipulse-engineering-gaai-framework-2 -->
- [**GAAI-framework**](https://github.com/digipulse-engineering/GAAI-framework) - (161 ⭐) - Turns AI coding tools into reliable software delivery systems.
<!-- resource-id: codex-digipulse-engineering-gaai-framework -->
- [**GAAI-framework**](https://github.com/Fr-e-d/GAAI-framework) - (161 ⭐) - Turns AI coding tools into reliable software delivery systems.
<!-- resource-id: codex-deferred-4ac09889eb5d -->
- [**chatgpt2codex**](https://github.com/ezBuilder/chatgpt2codex) - (159 ⭐) - macOS-first local MCP and Actions runtime that gives ChatGPT real coding hands over trusted projects.
<!-- resource-id: codex-awesome-sadjow-codex-cli-nix -->
- [**codex-cli-nix**](https://github.com/sadjow/codex-cli-nix) - (148 ⭐) - Nix flake for OpenAI Codex CLI - native Rust binary, hourly updates, multi-platform caching.
<!-- resource-id: codex-deferred-169006079eb6 -->
- [**adversarial-dev**](https://github.com/coleam00/adversarial-dev) - (131 ⭐) - GAN-inspired three-agent harness that pits a generator against an adversarial evaluator to build applications with quality gates at every step.
<!-- resource-id: codex-self-improving-memory -->
- [**self-improving-for-codex**](https://github.com/GODGOD126/self-improving-for-codex) - (131 ⭐) - A Codex-native self-improving skill based on AGENTS.md, memories, and nightly review automation.
<!-- resource-id: codex-deferred-77264691423f -->
- [**mosoo**](https://github.com/langgenius/mosoo) - (126 ⭐) - The open-source Agent Gallery and Gateway for Codex, Claude Agent SDK, and OpenCode.
<!-- resource-id: codex-deferred-12a4ce52b2ca -->
- [**agentrules-architect**](https://github.com/trevor-nichols/agentrules-architect) - (122 ⭐) - AGENTS.md/CLAUDE.md generator and ExecPlan harness for Codex, Claude Code, Cursor, Antigravity, OpenCode, Pi and other coding agents.
<!-- resource-id: codex-deferred-d3a8391dafb5 -->
- [**juror**](https://github.com/Juror-AI/juror) - (122 ⭐) - Cheaper and better Greptile alternative runs on your own github actions.
<!-- resource-id: codex-awesome-deepbluedynamics-gnosis-container -->
- [**gnosis-container**](https://github.com/DeepBlueDynamics/gnosis-container) - (111 ⭐) - Automate anything with Codex CLI in a local Docker container with cron, file watchers, webhooks, search/indexing, speech, and hundreds of tools on tap.
<!-- resource-id: codex-awesome-hogancv-coordinate-agents -->
- [**coordinate-agents**](https://github.com/hogancv/coordinate-agents) - (102 ⭐) - Coordinate multiple AI coding agents through a local-first, recoverable Agent Bus.
<!-- resource-id: codex-awesome-2718labs-2718lab-devkit -->
- [**2718lab-devkit**](https://github.com/2718labs/2718lab-devkit) - (101 ⭐) - Deterministic project intelligence, durable workflow orchestration, and reusable MCP engineering tools for Codex.
<!-- resource-id: codex-domanski-ai-headroom -->
- [**headroom**](https://github.com/domanski-ai/headroom) - (101 ⭐) - Track and rotate your Claude & Codex usage across accounts from one live dashboard, read live, never spending a token.

---

<a id="category-c09"></a>
## Guides, Examples & Learning

Learn a concrete Codex workflow from maintained guides, examples, courses, and handbooks.

<!-- resource-id: codex-asgeirtj-system-prompts-leaks -->
- [**system_prompts_leaks**](https://github.com/asgeirtj/system_prompts_leaks) - (64.2k ⭐) - Extracted system prompts from Anthropic - Claude Fable 5, Opus 5, Claude Design, Claude Code.
<!-- resource-id: codex-bloopai-vibe-kanban -->
- [**vibe-kanban**](https://github.com/BloopAI/vibe-kanban) - (28k ⭐) - Get 10X more out of Claude Code, Codex or any coding agent.
<!-- resource-id: codex-deferred-fd136499cf85 -->
- [**claude-skills**](https://github.com/alirezarezvani/claude-skills) - (25.6k ⭐) - 380 Claude Code skills & agent skills & plugins (30+ Agents, 70+ custom commands, 380+ skills, customizable references, scripts)for Claude Code, Codex.
<!-- resource-id: codex-deferred-01d50d038e81 -->
- [**happy**](https://github.com/slopus/happy) - (23.6k ⭐) - Mobile and Web client for Codex and Claude Code, with realtime voice, encryption and fully featured.
<!-- resource-id: codex-smtg-ai-claude-squad -->
- [**claude-squad**](https://github.com/smtg-ai/claude-squad) - (8.4k ⭐) - Manage multiple AI terminal agents like Claude Code, Codex, OpenCode, and Amp.
<!-- resource-id: codex-awesome-opactorai-claudable -->
- [**Claudable**](https://github.com/opactorai/Claudable) - (4.1k ⭐) - Claudable is an open-source web builder that leverages local CLI agents, such as Claude Code, Codex, Gemini CLI, Qwen Code, and Cursor Agent, to build and deploy products effortlessly.
<!-- resource-id: codex-deferred-988ad4c8c71f -->
- [**open-codex-computer-use**](https://github.com/iFurySt/open-codex-computer-use) - (1.9k ⭐) - Open Computer Use, Open-Source Alternative to Codex Computer Use.
<!-- resource-id: codex-activeloopai-hivemind -->
- [**hivemind**](https://github.com/activeloopai/hivemind) - (1.6k ⭐) - Hivemind turns your traces into reusable skills across agents.
<!-- resource-id: codex-awesome-shpigford-chops -->
- [**chops**](https://github.com/Shpigford/chops) - (1.6k ⭐) - Your AI agent skills, finally organized.
<!-- resource-id: codex-study8677-repobrain-2 -->
- [**repobrain**](https://github.com/study8677/repobrain) - (1.3k ⭐) - RepoBrain (formerly Antigravity), Give your repo a brain.
<!-- resource-id: codex-slides -->
- [**codex-slides**](https://github.com/nexu-io/codex-slides) - (869 ⭐) - Open-source AI slide studio inside Codex: image-native decks, every slide a full visual canvas.
<!-- resource-id: codex-awesome-codingmoh-open-codex -->
- [**open-codex**](https://github.com/codingmoh/open-codex) - (696 ⭐) - Fully open-source command-line AI assistant inspired by OpenAI Codex, supporting local language models.
<!-- resource-id: codex-awesome-cli-collection -->
- [**awesome-codex-cli**](https://github.com/RoggeOhta/awesome-codex-cli) - (504 ⭐) - Curated list of 150+ tools, skills, subagents & plugins for OpenAI Codex CLI.
<!-- resource-id: codex-awesome-treylom-knowledge-manager -->
- [**knowledge-manager**](https://github.com/treylom/knowledge-manager) - (231 ⭐) - Knowledge Manager Agent for Claude Code - Extract and organize content from web, PDF, social media to Obsidian/Notion.
<!-- resource-id: codex-deferred-eddb3a69f9f7 -->
- [**awesome-agent-loops**](https://github.com/serenakeyitan/awesome-agent-loops) - (206 ⭐) - A curated collection of the best /loop, /goal, and /schedule uses for Claude Code & Codex, real commands sourced from Twitter/X.
<!-- resource-id: codex-awesome-source-kareldo-awesome-codex -->
- [**awesome-codex**](https://github.com/KarelDO/awesome-codex) - (204 ⭐) - A list dedicated to products, demos and articles related to OpenAI's Codex.
<!-- resource-id: codex-awesome-skyworkai-skywork-skills -->
- [**Skywork-Skills**](https://github.com/SkyworkAI/Skywork-Skills) - (202 ⭐) - Skywork Agent Skills for AI office suites, including AI PPT, AI Document, AI Excel, AI Image, AI Search/DeepResearch and AI Music.
<!-- resource-id: codex-awesome-nkmr-jp-prompt-line -->
- [**prompt-line**](https://github.com/nkmr-jp/prompt-line) - (148 ⭐) - Prompt Line is a macOS app developed to improve the prompt input experience in the terminal for CLI-based AI coding agents such as Claude Code, Codex CLI, and Gemini CLI.
<!-- resource-id: codex-awesome-source-milisp-awesome-codex-cli -->
- [**awesome-codex-cli**](https://github.com/milisp/awesome-codex-cli) - (109 ⭐) - A curated list of awesome resources, tools, and tutorials for OpenAI Codex CLI.

---

## Related Resources

- [awesome-coding-agent](https://github.com/jqueryscript/awesome-coding-agent) - A curated ranking of popular AI coding agents, sorted by GitHub stars.
- [codex-commands-cheat-sheet](https://github.com/jqueryscript/codex-commands-cheat-sheet) - OpenAI Codex CLI commands, flags, configuration, sandboxing, MCP, and workflows.
- [Codex Commands Cheat Sheet](https://www.scriptbyai.com/codex-commands-cheat-sheet/)
- [codex-timeline](https://github.com/jqueryscript/codex-timeline) - A source-backed timeline of OpenAI Codex releases, products, and integrations.
- [Codex Timeline](https://www.scriptbyai.com/codex-timeline/)
- [awesome-agent-skills](https://github.com/jqueryscript/awesome-agent-skills) - A curated list of high-star Agent Skills for coding agents and AI workflows.
- [Agent Skills Specification](https://www.scriptbyai.com/agent-skills-specification/)
- [AGENTS.md Guide](https://www.scriptbyai.com/agents-md-guide/)
- [MCP directory](https://www.scriptbyai.com/mcp/)
- [Codex tag archive](https://www.scriptbyai.com/tag/codex/)

## Contributing

Propose a resource with its canonical URL, suggested category, explicit maintainer-owned Codex evidence, and a usage or learning reference. Corrections are reviewed in the ledger and published by regenerating both outputs.
