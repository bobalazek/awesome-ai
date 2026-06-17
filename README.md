# Awesome AI [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of AI tools, providers, platforms, agents, media systems, memory layers, and infrastructure.

This list is organized from user-facing products down to models, data, and infrastructure. Some projects are intentionally cross-listed when they meaningfully span multiple layers, so readers can find them from the angle they care about.

## 📚 Contents

- [🧩 Application layer](#-application-layer)
  - [💬 Chatbots and AI assistants](#-chatbots-and-ai-assistants)
  - [🔎 Search and research](#-search-and-research)
  - [🌐 Browser automation and web agents](#-browser-automation-and-web-agents)
  - [💻 Coding agents, CLIs, and IDEs](#-coding-agents-clis-and-ides)
  - [🧾 Code review and PR assistants](#-code-review-and-pr-assistants)
  - [🛠️ App builders and product tools](#️-app-builders-and-product-tools)
  - [🎨 Design systems and UI prototyping](#-design-systems-and-ui-prototyping)
  - [📚 Developer documentation and knowledge platforms](#-developer-documentation-and-knowledge-platforms)
  - [🌍 Localization and translation](#-localization-and-translation)
  - [👥 Team agents and collaborative tools](#-team-agents-and-collaborative-tools)
  - [📅 Productivity, meeting, and voice assistants](#-productivity-meeting-and-voice-assistants)
  - [🧠 Personal knowledge and memory agents](#-personal-knowledge-and-memory-agents)
- [⚙️ Orchestration and logic layer](#️-orchestration-and-logic-layer)
  - [🔀 Model routing and gateways](#-model-routing-and-gateways)
  - [🔌 Protocols and interoperability](#-protocols-and-interoperability)
  - [🤖 Agent frameworks](#-agent-frameworks)
  - [🧩 Workflow and automation](#-workflow-and-automation)
  - [📐 Prompt, spec, and context engineering](#-prompt-spec-and-context-engineering)
  - [🧪 Evaluation and observability](#-evaluation-and-observability)
  - [🛡️ Safety, guardrails, and governance](#️-safety-guardrails-and-governance)
  - [🛤️ Agentic methodologies and conventions](#️-agentic-methodologies-and-conventions)
- [🧠 Machine learning and model layer](#-machine-learning-and-model-layer)
  - [🧪 AI labs and model creators](#-ai-labs-and-model-creators)
  - [🔌 Model APIs and inference providers](#-model-apis-and-inference-providers)
  - [🏋️ Fine-tuning and post-training](#️-fine-tuning-and-post-training)
  - [🎨 Media and creative labs](#-media-and-creative-labs)
  - [🧬 Embeddings and rerankers](#-embeddings-and-rerankers)
- [🗃️ Data layer](#️-data-layer)
  - [🧠 Memory systems](#-memory-systems)
  - [🗂️ Vector databases](#️-vector-databases)
  - [📚 Retrieval, web search, and RAG tooling](#-retrieval-web-search-and-rag-tooling)
  - [🏷️ Data labeling and evaluation](#️-data-labeling-and-evaluation)
  - [🕸️ Knowledge graphs and structured context](#️-knowledge-graphs-and-structured-context)
  - [📄 Document parsing and ingestion](#-document-parsing-and-ingestion)
- [🧱 Infrastructure and compute layer](#-infrastructure-and-compute-layer)
  - [☁️ GPU cloud and compute](#️-gpu-cloud-and-compute)
  - [🏠 Self-hosted runtimes](#-self-hosted-runtimes)
  - [💻 Local AI apps](#-local-ai-apps)
  - [🚀 Model serving and inference engines](#-model-serving-and-inference-engines)
  - [🌐 Self-hosted AI interfaces](#-self-hosted-ai-interfaces)
- [📏 Benchmarks and evaluation suites](#-benchmarks-and-evaluation-suites)
  - [💬 Assistant and agent benchmarks](#-assistant-and-agent-benchmarks)
  - [🧠 Model and multimodal benchmarks](#-model-and-multimodal-benchmarks)
  - [🗃️ Retrieval, document, and context benchmarks](#️-retrieval-document-and-context-benchmarks)
  - [🧱 System and infrastructure benchmarks](#-system-and-infrastructure-benchmarks)
- [🧭 AI providers and model families](#-ai-providers-and-model-families)
  - [🧮 Model marketplaces, routers, and inference catalogs](#-model-marketplaces-routers-and-inference-catalogs)
  - [🧪 Frontier labs and hosted model families](#-frontier-labs-and-hosted-model-families)
  - [🪶 Open-weight lineages, forks, and derivatives](#-open-weight-lineages-forks-and-derivatives)
  - [🌏 Regional, sovereign, and enterprise model families](#-regional-sovereign-and-enterprise-model-families)
  - [🎛️ Specialized model families](#️-specialized-model-families)

## 🧩 Application layer

### 💬 Chatbots and AI assistants

- [ChatGPT](https://chatgpt.com/) - General-purpose AI assistant for writing, coding, research, and multimodal workflows. · ☁️ hosted · 🔌 api · 💬 chat · 📝 text · 💻 coding · 🖼️ image · 🎧 audio
- [Claude](https://claude.ai/) - Long-context assistant focused on reasoning, writing, analysis, and code-heavy workflows. · ☁️ hosted · 🔌 api · 💬 chat · 📝 text · 💻 coding · 🤖 agents
- [Pi](https://pi.ai/) - Personal AI assistant by Inflection focused on supportive, natural, and high-EQ conversation. · ☁️ hosted · 💬 chat · 🧠 memory · 👥 companion
- [You.com](https://you.com/) - AI-powered search and aggregator providing access to multiple frontier models in one interface. · ☁️ hosted · 🔌 api · 💬 chat · 🔎 search · 📝 text
- [Gemini](https://gemini.google.com/) - Google’s assistant for productivity, multimodal work, and broader consumer AI usage. · ☁️ hosted · 🔌 api · 💬 chat · 📝 text · 🖼️ image · 🎧 audio
- [Poe](https://poe.com/) - Multi-model chat product that lets users access many assistants and generation tools in one place. · ☁️ hosted · 💬 chat · 📝 text · 🖼️ image · 🎬 video · 🎧 audio
- [T3 Chat](https://t3.chat/) - Fast multi-model chat product built around quick responses, model switching, optional search, and lightweight threads. · ☁️ hosted · 💬 chat · 🔎 search · 📝 text · 💻 coding
- [Onyx](https://onyx.app/) - Open-source AI chat workspace connected to your docs, apps, people, and internal knowledge. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💬 chat · 🔎 search · 📚 rag · 🤖 agents
- [Galaxy.ai](https://www.galaxy.ai/) - Aggregated AI workspace that bundles many models and tools behind one interface. · ☁️ hosted · 💬 chat · 📝 text · 🖼️ image · 🎬 video · 🎧 audio
- [DoAnything AI](https://doanything.ai/) - General-purpose agent platform for executing multi-step tasks and workflows via natural language. · ☁️ hosted · 💬 chat · 🤖 agents · 🛠️ workflow
- [Character.ai](https://character.ai/) - Leading platform for roleplaying and interacting with AI-powered fictional and historical personas. · ☁️ hosted · 💬 chat · 🎭 roleplay
- [Kindroid](https://kindroid.ai/) - AI companion platform focused on realistic long-term memory and multimodal interactions. · ☁️ hosted · 💬 chat · 🧠 memory · 👥 companion

### 🔎 Search and research

- [Perplexity](https://www.perplexity.ai/) - Search-first AI product for web research, cited answers, and discovery workflows. · ☁️ hosted · 🔌 api · 💬 chat · 🔎 search · 📝 text
- [Phind](https://www.phind.com/) - Technical search and answer engine aimed at developers and engineering-heavy research. · ☁️ hosted · 💬 chat · 🔎 search · 💻 coding · 📝 text
- [Brave Search](https://search.brave.com/) - Independent web search engine focused on privacy, its own index, and AI-assisted search features like Summarizer and Goggles. · ☁️ hosted · 🔎 search · 📝 text
- [Kagi](https://kagi.com/) - Premium privacy-respecting search engine with personalized ranking controls, lenses, and power-user search workflows. · ☁️ hosted · 🔎 search · 📝 text
- [Mojeek](https://www.mojeek.com/) - Independent no-tracking search engine focused on its own web index and user-controlled search experiences. · ☁️ hosted · 🔎 search · 📝 text
- [Consensus](https://consensus.app/) - AI search engine that finds answers across peer-reviewed scientific papers. · ☁️ hosted · 🔎 search · 🧪 research
- [Elicit](https://elicit.com/) - Automated research assistant that analyzes and summarizes literature at scale. · ☁️ hosted · 🔎 search · 🧪 research
- [SciSpace](https://scispace.com/) - Platform for chatting with PDFs and understanding complex scientific literature. · ☁️ hosted · 🔎 search · 🧪 research
- [Semantic Scholar](https://www.semanticscholar.org/) - Free AI-powered academic search engine and discovery platform for navigating papers, citations, and related scientific work. · ☁️ hosted · 🔎 search · 🧪 research
- [Scite](https://scite.ai/) - Research platform that uses Smart Citations to show whether later papers support or contradict a claim. · ☁️ hosted · 🔎 search · 🧪 research
- [Research Rabbit](https://www.researchrabbit.ai/) - Visual mapping tool for discovering related research papers and authors. · ☁️ hosted · 🔎 search · 🧪 research

### 🌐 Browser automation and web agents

- [HARPA AI](https://harpa.ai/) - Chrome extension that integrates AI models into any tab for web automation, scraping, and monitoring. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Manus AI](https://manus.ai/) - General-purpose action engine for executing complex multi-step tasks autonomously in the browser. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [ChatGPT Atlas](https://openai.com/atlas) - OpenAI's browser-native agent for navigating the web and taking actions on the user's behalf. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Perplexity Comet](https://perplexity.ai/comet) - AI-native browser with built-in assistants for form-filling, research, and calendar management. · ☁️ hosted · 🛠️ workflow · 🤖 agents · 🔎 search

### 💻 Coding agents, CLIs, and IDEs

- [Cursor](https://cursor.com/) - AI-native editor built around repo context, multi-file editing, and agentic workflows. · ☁️ hosted · 💻 coding · 🤖 agents
- [Claude Code](https://claude.com/product/claude-code) - Terminal-first coding agent for codebase work, edits, investigation, and longer-running tasks. · ☁️ hosted · 💻 coding · 🤖 agents
- [Codex](https://openai.com/codex/) - OpenAI’s coding agent for software tasks, code changes, and development workflows. · ☁️ hosted · 💻 coding · 🤖 agents
- [T3 Code](https://t3.codes/) - Minimal open-source GUI for coding agents, currently focused on Codex and Claude-style terminal workflows. · 🔓 open-source · 💻 coding · 🤖 agents
- [GitHub Copilot](https://github.com/features/copilot) - AI coding assistant integrated into IDEs, terminals, GitHub, and code review flows. · ☁️ hosted · 💻 coding · 🤖 agents
- [GitHub Copilot CLI](https://github.com/features/copilot/cli) - GitHub’s terminal coding agent with multi-model support, MCP integrations, autopilot mode, and parallel fleet workflows. · ☁️ hosted · 💻 coding · 🤖 agents
- [Windsurf](https://windsurf.com/) - AI coding product from the Codeium team focused on editor-native agentic development. · ☁️ hosted · 💻 coding · 🤖 agents
- [Amp](https://sourcegraph.com/amp) - Sourcegraph's terminal-first coding agent optimized for search and enterprise scale. · ☁️ hosted · 💻 coding · 🤖 agents
- [Goose](https://goose-docs.ai/) - Open-source AAIF local AI agent with desktop, CLI, and API interfaces, MCP extensions, ACP support, recipes, subagents, and sandboxed automation. · 🔓 open-source · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Pi (shitty-coding-agent)](https://pi.dev) - Minimalist, extensible terminal-first coding agent created by Mario Zechner. · 🔓 open-source · 💻 coding · 🤖 agents
- [Kilo Code](https://kilo.ai/) - Open-source coding agent (formerly Kilo Row) for editors, CLI workflows, and cloud execution. · 🔓 open-source · ☁️ hosted · 💻 coding · 🤖 agents
- [Roo Code](https://roocode.com/) - Open-source AI dev team for VS Code and cloud delegation with role-specific modes, permission-gated tools, and broad model support. · 🔓 open-source · ☁️ hosted · 💻 coding · 🤖 agents
- [Cline](https://cline.bot/) - Agentic coding assistant for editor workflows with tool use and repo awareness. · 🔓 open-source · 💻 coding · 🤖 agents
- [Aider](https://aider.chat/) - Terminal-first coding assistant that edits files directly in Git-aware workflows. · 🔓 open-source · 💻 coding · 🤖 agents
- [Continue](https://www.continue.dev/) - Open-source framework for building custom coding assistants inside existing editors. · 🔓 open-source · 💻 coding · 🤖 agents
- [OpenHands](https://openhands.dev/) - Open platform for coding agents and autonomous repository task execution. · 🔓 open-source · ☁️ hosted · 💻 coding · 🤖 agents
- [OpenCode](https://opencode.ai/) - Open-source coding agent for terminal, IDE, and desktop workflows with multi-session execution and broad provider support. · 🔓 open-source · 💻 coding · 🤖 agents
- [OpenClaude](https://github.com/Gitlawb/openclaude) - Open-source terminal coding-agent CLI for local and cloud providers with MCP, tasks, slash commands, and multi-provider support. · 🔓 open-source · 💻 coding · 🤖 agents
- [Gemini CLI](https://github.com/google/gemini-cli) - Google’s open-source terminal agent for high-speed file manipulation and shell execution. · 🔓 open-source · 💻 coding · 🤖 agents
- [Morph](https://morphllm.com/) - Coding agent utility that provides ultra-fast code search and instant edit application. · ☁️ hosted · 💻 coding · 🤖 agents
- [Plandex](https://plandex.ai/) - Terminal-based AI coding agent designed for complex, multi-file tasks with sandbox planning. · 🔓 open-source · 💻 coding · 🤖 agents
- [Sweep AI](https://sweep.dev/) - AI junior developer that handles GitHub issues by writing plans and creating PRs automatically. · ☁️ hosted · 💻 coding · 🤖 agents
- [Bloop AI](https://bloop.ai/) - AI-powered code search and navigation for understanding large and complex codebases. · ☁️ hosted · 💻 coding · 🔎 search
- [Google Antigravity](https://antigravity.google) - Google’s agent-first IDE (fork of VS Code) with built-in browser agent and manager. · ☁️ hosted · 💻 coding · 🤖 agents

### 🧾 Code review and PR assistants

- [CodeRabbit](https://www.coderabbit.ai/) - AI code review assistant for pull requests with bug finding, review summaries, inline comments, and one-click fixes. · ☁️ hosted · 💻 coding · 🧾 code-review
- [GitHub Copilot code review](https://docs.github.com/copilot/concepts/code-review) - GitHub-native PR review assistant that can be requested manually or configured to automatically review pull requests. · ☁️ hosted · 💻 coding · 🧾 code-review
- [Qodo Merge](https://www.qodo.ai/products/qodo-merge/) - AI code review agent for pull requests, CI, and Git workflows with team rules and code-quality guardrails. · ☁️ hosted · 🔓 open-source · 💻 coding · 🧾 code-review
- [Greptile](https://www.greptile.com/pull-request-review) - Codebase-aware PR reviewer with full-repository context, inline issue detection, and self-hosted deployment options. · ☁️ hosted · 🏠 self-hosted · 💻 coding · 🧾 code-review
- [Graphite Agent](https://graphite.dev/features/ai-reviews/) - AI reviewer embedded in the PR workflow for instant reviews, contextual explanations, and one-click fixes. · ☁️ hosted · 💻 coding · 🧾 code-review
- [PR-Agent](https://github.com/qodo-ai/pr-agent) - Open-source pull request review agent for automated analysis, feedback, summaries, and improvement suggestions. · 🔓 open-source · 💻 coding · 🧾 code-review
- [ClawSweeper](https://github.com/openclaw/clawsweeper) - Open-source GitHub maintenance bot that reviews issues and PRs, proposes safe closes, syncs durable comments, and can run guarded Codex repair/automerge loops. · 🔓 open-source · 🏠 self-hosted · 💻 coding · 🤖 agents · 🧾 code-review · 🛠️ workflow
- [What The Diff](https://whatthediff.ai/) - AI-powered pull request assistant focused on diff summaries, change explanations, and review support in GitHub or GitLab. · ☁️ hosted · 💻 coding · 🧾 code-review
- [Kodus](https://github.com/kodustech/kodus-ai) - Open-source AI code reviewer for GitHub, GitLab, Bitbucket, and Azure Repos with bring-your-own-model support and self-hosted deployment. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💻 coding · 🧾 code-review

### 🛠️ App builders and product tools

- [v0](https://v0.app/) - Prompt-based product and UI builder for components, apps, and front-end flows. · ☁️ hosted · 💻 coding · 🤖 agents
- [Bolt](https://bolt.new/) - Browser-based AI builder for creating full-stack apps and quick prototypes. · ☁️ hosted · 💻 coding · 🤖 agents
- [Lovable](https://lovable.dev/) - Prompt-to-app builder for generating product prototypes and web applications. · ☁️ hosted · 💻 coding · 🤖 agents
- [Replit Agent](https://replit.com/ai) - Agentic browser development environment for building and deploying apps from prompts. · ☁️ hosted · 💻 coding · 🤖 agents
- [LandingHero AI](https://www.landinghero.ai/) - AI landing page and website builder with a voice sales agent for explaining services and capturing leads. · ☁️ hosted · 🤖 agents · 🛠️ workflow

### 🎨 Design systems and UI prototyping

- [getdesign.md](https://getdesign.md/) - Browsable collection of DESIGN.md files inspired by public websites, giving coding agents markdown-readable design tokens, components, layout rules, responsive behavior, and visual guardrails. · 🔓 open-source · 💻 coding · 🎨 design · 🤖 agents
- [designmd.sh](https://designmd.sh/) - Public DESIGN.md registry by VoltAgent with one-command CLI install and a leaderboard of trending and most-installed design systems for coding and design agents. · ☁️ hosted · 💻 coding · 🎨 design · 🤖 agents
- [Superdesign](https://www.superdesign.dev/ide-extension) - Open-source design agent for IDEs that generates product mockups, UI components, and wireframes from prompts, with fork-and-iterate workflows for Cursor, Windsurf, Claude Code, and VS Code. · 🔓 open-source · 💻 coding · 🎨 design · 🤖 agents

### 📚 Developer documentation and knowledge platforms

- [Mintlify](https://www.mintlify.com/) - AI-native documentation and knowledge platform for developer docs, help centers, API references, AI assistants, llms.txt, MCP, and self-updating content workflows. · ☁️ hosted · 🤖 agents · 🛠️ workflow · 📚 docs
- [Beever Atlas](https://github.com/Beever-AI/beever-atlas) - Open-source team knowledge base that turns Slack, Discord, Microsoft Teams, and Mattermost conversations into cited wiki pages, graph memory, QA, and MCP tools. · 🔓 open-source · 🏠 self-hosted · 🤖 agents · 📚 docs · 📚 rag · 🧠 memory · 🕸️ graph

### 🌍 Localization and translation

- [General Translation](https://generaltranslation.com/) - Developer-focused AI localization platform with i18n libraries, contextual translation APIs, CI/CD translation deployment, and the Locadex repo agent. · ☁️ hosted · 🔌 api · 💻 coding · 🤖 agents · 🛠️ workflow · 🌍 localization
- [Lingo.dev](https://lingo.dev/) - Localization engineering platform for stateful translation APIs, glossaries, quality gates, CLI workflows, GitHub Actions, and MCP-assisted localization. · 🔓 open-source · ☁️ hosted · 🔌 api · 💻 coding · 🛠️ workflow · 🌍 localization

### 👥 Team agents and collaborative tools

- [OpenClaw](https://github.com/openclaw/openclaw) - Open-source personal AI agent platform with multi-channel inboxes, routing, tools, and collaborative workflow surfaces across chat platforms. · 🔓 open-source · 🤖 agents · 💬 chat
- [Harness AI](https://harness.io/products/ai-code-assistant) - Commercial platform and coding agent focused on automating the full software lifecycle. · ☁️ hosted · 💻 coding · 🤖 agents · 🛠️ workflow
- [Hermes Agent](https://hermes-agent.ai/) - Long-lived open-source agent system from Nous Research focused on persistent memory, reusable skills, tool workflows, and multi-channel operation. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🤖 agents · 🧠 memory · 🛠️ workflow
- [Factory](https://factory.ai/) - Agent-native software development platform built around Factory Droid across IDEs, CLI, Slack, project backlogs, and CI/CD. · ☁️ hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [Dust](https://github.com/dust-tt/dust) - Open-source platform for building custom workplace AI agents grounded in company tools, knowledge, and workflows. · 🔓 open-source · ☁️ hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [Routa](https://github.com/phodal/routa) - Open-source workspace-first multi-agent coordination platform for software delivery with shared specs, Kanban orchestration, traces, evidence, review gates, and MCP/ACP/A2A support. · 🔓 open-source · 🏠 self-hosted · 💻 local · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [Multica](https://multica.ai/) - Open-source project management platform for human and coding-agent teams, with task queues, reusable skills, runtime monitoring, and hosted or self-hosted deployment. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [Paperclip](https://paperclip.inc/) - Management layer for AI-agent companies with org charts, budgets, governance, heartbeats, audit trails, and agent-agnostic runtimes. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [HumanLayer](https://github.com/humanlayer/humanlayer) - Approval and collaboration layer for teams using coding agents in real production workflows. · 🔓 open-source · ☁️ hosted · 🤖 agents · 👥 team
- [Vellum](https://www.vellum.ai/) - Enterprise agent control plane for building, testing, and monitoring AI agents. · ☁️ hosted · 🤖 agents · 🧪 observability
- [Agentforce](https://www.salesforce.com/agentforce/) - Salesforce’s low-code platform for building autonomous business agents. · ☁️ hosted · 🤖 agents · 🛠️ workflow
- [Slackbot](https://slack.com/features/slackbot) - Slack's AI work agent for searching workspace context, orchestrating connected apps and agents, and helping teams act inside Slack. · ☁️ hosted · 🤖 agents · 👥 team · 💬 chat · 🛠️ workflow
- [Relevance AI](https://relevanceai.com/) - Enterprise AI workforce platform for building, operating, and governing role-specific agents across GTM and operations workflows. · ☁️ hosted · 🤖 agents · 👥 team · 🛠️ workflow
- [Kore.ai](https://kore.ai/) - Enterprise conversational AI platform for scaling thousands of agents. · ☁️ hosted · 🤖 agents · 🛠️ workflow
- [SubwAI](https://subw.ai/) - AI-native grant infrastructure for technology companies, covering funding discovery, application writing, submission, and compliance. · ☁️ hosted · 🛠️ workflow
- [Devin](https://cognition.ai/) - Autonomous software agent product aimed at longer-running engineering work. · ☁️ hosted · 💻 coding · 🤖 agents

### 📅 Productivity, meeting, and voice assistants

- [TimeOS](https://timeos.ai/) - AI productivity hub for automating meeting prep, note-taking, and cross-platform follow-ups. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Lindy](https://www.lindy.ai/) - Work assistant for inbox management, meeting prep, follow-ups, scheduling, and cross-app task execution. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Jamie](https://meetjamie.ai/) - Bot-free meeting assistant that records locally and generates professional summaries. · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow
- [Granola](https://granola.so/) - Meeting notepad that combines AI transcription with manual notes for structured documentation. · ☁️ hosted · 🛠️ workflow
- [Otter.ai](https://otter.ai/) - Real-time transcription and collaborative note-taking platform for teams and students. · ☁️ hosted · 🛠️ workflow
- [Aqua Voice](https://aquavoice.com/) - Voice dictation assistant that turns natural speech into polished text, prompts, and messages across apps with strong support for coding workflows. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding
- [Wispr Flow](https://wisprflow.ai/) - Cross-app voice dictation tool that rewrites speech into clean, structured text for writing, messaging, and development work. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding
- [Superwhisper](https://superwhisper.com/) - Voice-to-text assistant with offline support, app-aware modes, and fast dictation for coding, notes, and messages. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding

### 🧠 Personal knowledge and memory agents

- [Me.bot](https://me.bot/) - Personal AI memory system that ingests notes, voice, and thoughts to act as a second brain. · ☁️ hosted · 🧠 memory · 👥 companion
- [Khoj](https://github.com/khoj-ai/khoj) - Open-source self-hostable AI second brain for answers over personal docs and the web, custom agents, scheduled automations, and research workflows. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🧠 memory · 📚 rag · 🤖 agents · 🔎 search
- [OpenHuman](https://github.com/tinyhumansai/openhuman) - Open-source personal AI assistant for local-first memory, voice, search, and connected workflows, with optional custom models and managed backend features. · 🔓 open-source · 💻 local · 🧠 memory · 🤖 agents · 💬 chat
- [Saner.ai](https://saner.ai/) - ADHD-friendly workspace that unifies notes and tasks with proactive AI planning and recall. · ☁️ hosted · 🧠 memory · 🛠️ workflow
- [Vellum Assistant](https://github.com/vellum-ai/vellum-assistant) - Open-source personal assistant with structured memory, personality files, proactive check-ins, and macOS, Telegram, and Slack interfaces. · 🔓 open-source · 💻 local · 🧠 memory · 🤖 agents · 💬 chat
- [Second Me](https://github.com/mindverse/Second-Me) - Open-source local AI-self system for training a personal memory model and sharing controlled context as a digital identity. · 🔓 open-source · 🏠 self-hosted · 🧠 memory · 🤖 agents
- [Kin AI](https://mykin.ai/) - Personal agent focused on deep, persistent understanding to provide long-term coaching and insights. · ☁️ hosted · 🧠 memory · 👥 companion

## ⚙️ Orchestration and logic layer

### 🔀 Model routing and gateways

- [OpenRouter](https://openrouter.ai/) - Unified API layer for routing requests across many model providers. · ☁️ hosted · 🔌 api · 🧠 routing
- [Anannas](https://anannas.ai/) - Unified AI API gateway providing access to hundreds of models via a single endpoint. · ☁️ hosted · 🔌 api · 🧠 routing
- [Kilo Gateway](https://kilo.ai/gateway) - OpenAI-compatible gateway with BYOK, routing, usage tracking, and provider abstraction. · ☁️ hosted · 🔌 api · 🧠 routing
- [APIPark](https://apipark.com/) - Open-source AI gateway and API management layer for multi-model deployments. · 🔓 open-source · 🏠 self-hosted · ☁️ hosted · 🔌 api · 🧠 routing
- [LiteLLM](https://litellm.ai/) - Universal I/O library to call any LLM provider using the OpenAI format. · 🔓 open-source · 🔌 api · 🧠 routing
- [Portkey](https://portkey.ai/) - AI gateway and observability suite for managing prompts, caching, and retries. · ☁️ hosted · 🔌 api · 🧠 routing · 🧪 observability

### 🔌 Protocols and interoperability

- [Model Context Protocol (MCP)](https://docs.anthropic.com/en/docs/mcp) - Open protocol for connecting models and agents to tools, resources, and external context in a standardized way. · 🔓 open-source · 🔌 api · 🤖 agents · 🧩 protocol
- [Agent2Agent Protocol (A2A)](https://a2aproject.github.io/A2A/latest/specification/) - Open standard for agent-to-agent communication, capability discovery, task handoffs, and asynchronous collaboration. · 🔓 open-source · 🤖 agents · 🧩 protocol
- [AG-UI](https://docs.ag-ui.com/) - Open event-based protocol for connecting agent backends to user-facing applications with streaming state and interaction primitives. · 🔓 open-source · 🤖 agents · 🧩 protocol · 💬 chat

### 🤖 Agent frameworks

- [LangChain](https://www.langchain.com/) - Framework for building LLM apps, tool-using systems, and agent workflows. · 🔓 open-source · 🧩 framework · 🤖 agents · 📚 rag
- [LlamaIndex](https://www.llamaindex.ai/) - Framework for document-heavy AI apps, retrieval flows, and agent systems. · 🔓 open-source · 🧩 framework · 🤖 agents · 📚 rag
- [AutoGen](https://microsoft.github.io/autogen/) - Microsoft framework for multi-agent systems and tool-enabled AI workflows. · 🔓 open-source · 🧩 framework · 🤖 agents
- [CrewAI](https://crewai.com/) - Framework for role-based multi-agent systems and collaborative AI execution. · 🔓 open-source · ☁️ hosted · 🧩 framework · 🤖 agents
- [LangGraph](https://www.langchain.com/langgraph) - Framework for building robust, stateful multi-agent workflows with cycles. · 🔓 open-source · 🧩 framework · 🤖 agents
- [OpenAI Agents SDK](https://openai.github.io/openai-agents-python/) - Lightweight open-source SDK for multi-agent workflows with tools, handoffs, guardrails, sessions, tracing, realtime agents, and sandbox agents. · 🔓 open-source · 🧩 framework · 🤖 agents · 🛡️ guardrails
- [Google Agent Development Kit](https://google.github.io/adk-docs/) - Open-source code-first framework for building, evaluating, and deploying agents across Python, TypeScript, Go, and Java. · 🔓 open-source · 🧩 framework · 🤖 agents
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Open framework for production-grade Python and .NET agents with graph workflows, observability, durability, and human-in-the-loop patterns. · 🔓 open-source · 🧩 framework · 🤖 agents · 🛠️ workflow
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript framework for production AI apps and agents with workflows, memory, RAG, model routing, MCP servers, evals, and observability. · 🔓 open-source · 🧩 framework · 🤖 agents · 📚 rag · 🧪 observability
- [Agno](https://github.com/agno-agi/agno) - Agent platform SDK and control plane for running agents as production services with storage, memory, tracing, scheduling, RBAC, and chat interfaces. · 🔓 open-source · 🧩 framework · 🤖 agents · 🛠️ workflow
- [elizaOS](https://github.com/elizaOS/eliza) - Open-source framework for autonomous chat and social agents with plugins, multi-agent orchestration, RAG, and Discord, Telegram, and Farcaster connectors. · 🔓 open-source · 🧩 framework · 🤖 agents · 💬 chat · 📚 rag
- [VoltAgent](https://github.com/VoltAgent/voltagent) - TypeScript agent engineering platform with memory, RAG, guardrails, MCP, voice, workflows, evals, and observability. · 🔓 open-source · ☁️ hosted · 🧩 framework · 🤖 agents · 🧪 observability
- [Antigravity](https://google.com/antigravity) - Google’s platform for building agentic apps that interact natively with OS and Workspace. · ☁️ hosted · 🧩 framework · 🤖 agents
- [browser-use](https://github.com/browser-use/browser-use) - Python library for making websites accessible to AI agents using Playwright and natural language. · 🔓 open-source · 🧩 framework · 🤖 agents
- [browser-harness](https://github.com/browser-use/browser-harness) - Lightweight, self-healing browser automation harness built directly on CDP for AI agents. · 🔓 open-source · 🧩 framework · 🤖 agents
- [HyperFrames](https://github.com/heygen-com/hyperframes) - HeyGen's open-source HTML-to-video rendering framework with first-class support for AI agents creating programmatic video compositions. · 🔓 open-source · 🧩 framework · 🤖 agents · 🎬 video
- [OpenHarness](https://github.com/HKUDS/OpenHarness) - Open-source agent framework from HKUDS providing tool-use, skills, memory, and multi-agent coordination primitives. · 🔓 open-source · 🧩 framework · 🤖 agents · 🧠 memory
- [OpenSpace](https://github.com/HKUDS/OpenSpace) - Open-source self-evolving skill system with an MCP interface that lets agents learn, repair, and share skills to cut tokens and raise task success. · 🔓 open-source · 🧩 framework · 🤖 agents · 🧠 memory
- [autoresearch](https://github.com/karpathy/autoresearch) - Andrej Karpathy's autonomous ML research harness where agents iteratively modify training code, run short experiments, and evaluate results. · 🔓 open-source · 🧩 framework · 🤖 agents · 🧪 research · 🏋️ training
- [Griptape](https://www.griptape.ai/) - Python framework for building modular and security-first AI agents and pipelines. · 🔓 open-source · 🧩 framework · 🤖 agents
- [Haystack](https://haystack.deepset.ai/) - Orchestration framework for building customizable RAG pipelines and agent systems. · 🔓 open-source · 🧩 framework · 🤖 agents
- [PydanticAI](https://ai.pydantic.dev/) - Python agent framework focused on validation, structure, and typed outputs. · 🔓 open-source · 🧩 framework · 🤖 agents
- [BMAD](https://github.com/bmad-code-org/BMAD-METHOD) - Breakthrough Method for Agile AI-Driven Development—an open framework for multi-agent software engineering. · 🔓 open-source · 🧩 framework · 🤖 agents · 📐 prompts

### 🧩 Workflow and automation

- [n8n](https://n8n.io/) - Workflow automation platform with strong AI, API, and developer integration support. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow · 🤖 agents
- [Vibe Kanban](https://vibekanban.com/) - Visual orchestration layer for managing parallel AI agents using Kanban boards and Git worktrees. · 🔓 open-source · 🤖 agents · 🛠️ workflow
- [Routa](https://github.com/phodal/routa) - Board-based multi-agent software-delivery workspace where lane specialists refine specs, implement scoped changes, collect evidence, and enforce review gates. · 🔓 open-source · 🏠 self-hosted · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Hermes Agent Kanban](https://hermes-agent.nousresearch.com/docs/user-guide/features/kanban) - Built-in Hermes multi-agent board with task-scoped worker tools, orchestrator skills, dependency links, heartbeats, structured handoff metadata, and a local dashboard. · 🔓 open-source · 🏠 self-hosted · 🤖 agents · 🛠️ workflow
- [Multica](https://multica.ai/) - Managed-agent project platform for assigning issues to coding agents, tracking progress on boards, routing work through squads, and compounding reusable skills. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [Schaltwerk](https://github.com/2mawi2/schaltwerk) - Desktop application for running and reviewing parallel terminal agents in a spec-driven flow. · 🔓 open-source · 🏠 self-hosted · 🤖 agents · 🛠️ workflow
- [Emdash](https://www.emdash.sh/) - Open-source agentic development environment for running many CLI coding agents in parallel across isolated Git worktrees, issue trackers, and remote SSH projects. · 🔓 open-source · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Crystal](https://github.com/stravu/crystal) - Open-source desktop app for running multiple Claude Code and Codex sessions in parallel Git worktrees, testing approaches, and reviewing diffs before merge. · 🔓 open-source · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Superset](https://superset.sh/) - Source-available desktop code editor for orchestrating CLI coding agents in parallel with worktree isolation, built-in terminals, diff review, and IDE handoff. · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Agentastic](https://www.agentastic.dev/) - Mac-native IDE for running terminal-based coding agents in isolated worktrees with built-in diff review and merge workflows. · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
- [Zapier Central](https://zapier.com/central) - Marketplace for automation agents that connect to thousands of business applications. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Gumloop](https://www.gumloop.com/) - AI-native automation builder for creating agents and workflows that use MCP tools, app integrations, and reusable flow steps. · ☁️ hosted · 🛠️ workflow · 🤖 agents · 🧩 protocol
- [Apify Store](https://apify.com/store) - Marketplace for web scraping and automation agents that execute in the browser. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Twin.so](https://twin.so/) - Platform for building no-code browser agents that automate legacy UIs. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Dify](https://dify.ai/) - Platform for prompt apps, RAG workflows, internal tools, and agent systems. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow · 🤖 agents · 📚 rag
- [Flowise](https://flowiseai.com/) - Visual builder for LLM apps, retrieval pipelines, and agentic flows. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow · 🤖 agents · 📚 rag
- [Conductor](https://cndctr.dev/) - Orchestration layer for autonomous Claude Code workflows tied to issues and pull requests. · ☁️ hosted · 🤖 agents · 🛠️ workflow · 💻 coding

### 📐 Prompt, spec, and context engineering

- [Context7](https://context7.com/) - Up-to-date docs and code examples injected directly into coding assistants. · ☁️ hosted · 📚 rag · 💻 coding · 📝 text
- [Spec Kit](https://github.github.com/spec-kit/) - Specification-driven development toolkit for AI-assisted software work. · 🔓 open-source · 💻 coding · 📐 specs
- [SpecStore](https://specstore.ai/) - A repository for storing and sharing AI specifications and prompts. · ☁️ hosted · 📐 specs · 📚 rag
- [OpenSpec](https://openspec.dev/) - Spec-driven development tooling for AI coding and agent workflows. · 🔓 open-source · 💻 coding · 📐 specs
- [Chiron](https://github.com/EdwinjJ1/chiron-prompt) - Open-source repo-aware prompt enhancer for terminal coding agents, with Gemini CLI and Codex-style Ctrl+E prompt refinement workflows. · 🔓 open-source · 💻 local · 💻 coding · 📐 prompts
- [Claude Super Prompt System](https://claude.ai/super-prompt) - Advanced prompt engineering framework for maximizing reasoning capabilities. · 📐 prompts · 📝 text · 🤖 agents
- [Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) - Claude Code skills pack for academic research workflows spanning paper discovery, literature review, writing, peer review, revision, and finalization. · 💻 coding · 📐 prompts · 🧪 research · 🤖 agents
- [Superpowers](https://github.com/obra/superpowers) - Agentic skills framework and software development methodology for coding agents, centered on spec-first design, TDD, and subagent-driven execution. · 🔓 open-source · 🤖 agents · 💻 coding · 📐 specs · 📐 prompts
- [Agency](https://github.com/msitarzewski/agency-agents) - Open-source pack of specialized agent personas and prompt workflows spanning engineering, design, product, growth, and operations, with installers for Claude Code and other coding assistants. · 🔓 open-source · 🤖 agents · 📐 prompts · 💻 coding
- [Impeccable](https://impeccable.style/) - Design-fluency skill for AI coding harnesses with design commands, project design context, anti-pattern detection, and optional CLI and Chrome extension workflows. · 🔓 open-source · 💻 coding · 📐 prompts · 🤖 agents
- [UI UX Pro Max Skill](https://ui-ux-pro-max-skill.nextlevelbuilder.io/) - Design-intelligence skill for AI coding assistants that provides UI/UX patterns, design systems, palettes, fonts, and framework-specific guidance. · 🔓 open-source · 💻 coding · 📐 prompts · 🤖 agents
- [Taste Skill](https://www.tasteskill.dev/) - Collection of frontend design skills that steer AI coding agents toward polished layouts, motion, spacing, and visual quality. · 🔓 open-source · 💻 coding · 📐 prompts · 🤖 agents
- [Layers](https://layers.jamiemill.com/) - Open-source AI skills pack that guides product designers and coding agents through seven layers of product design, from observed behavior and domain modeling to strategy, interaction flow, and surface audits. · 🔓 open-source · 💻 coding · 📐 prompts · 🎨 design · 🤖 agents
- [Huashu Design](https://github.com/alchaincyf/huashu-design) - Agent-agnostic design skill for generating high-fidelity HTML prototypes, slide decks, motion graphics, infographics, design variations, and critique workflows. · 💻 coding · 📐 prompts · 🎨 design
- [TypeUI](https://www.typeui.sh/) - Open-source CLI and registry of design skill files for applying consistent design systems across Claude Code, Codex, Cursor, Google Stitch, and other AI coding tools. · 🔓 open-source · 💻 coding · 📐 prompts · 🎨 design
- [Open Design](https://github.com/nexu-io/open-design) - Open-source local design workspace that turns coding-agent CLIs into a Claude Design-style artifact engine with skills, DESIGN.md systems, live previews, and BYOK routing. · 🔓 open-source · 💻 local · 💻 coding · 📐 prompts · 🎨 design · 🤖 agents
- [Awesome DESIGN.md](https://github.com/VoltAgent/awesome-design-md) - Curated collection of DESIGN.md files inspired by popular brand design systems for guiding AI coding agents toward matching UI. · 🔓 open-source · 💻 coding · 📐 prompts · 🎨 design
- [Refero Styles](https://styles.refero.design/) - Searchable library of extracted design references with colors, typography, spacing, components, and DESIGN.md files for coding agents. · ☁️ hosted · 💻 coding · 📐 prompts · 🎨 design
- [LandingHero Design Library](https://www.landinghero.ai/library) - Prompt-ready collection of UI components and themes for Claude Code, Cursor, Antigravity, and other AI coding tools. · ☁️ hosted · 💻 coding · 📐 prompts · 🎨 design
- [Transitions.dev](https://transitions.dev/) - Copy-paste collection of essential web app transitions for animation, layout changes, menus, modals, panels, and page movement. · 💻 coding · 🎨 design

### 🧪 Evaluation and observability

- [LangSmith](https://www.langchain.com/langsmith) - Unified platform for debugging, testing, and monitoring LLM applications. · ☁️ hosted · 🧪 observability · 🧩 framework
- [Langfuse](https://langfuse.com/) - Open-source observability and analytics platform for tracing and evaluation. · 🔓 open-source · ☁️ hosted · 🧪 observability
- [Latitude](https://latitude.so/) - Open-source agent observability and prompt-evaluation platform for turning production traces, feedback, and failures into fixes. · 🔓 open-source · ☁️ hosted · 🧪 observability · 📐 prompts · 🤖 agents
- [Helicone](https://helicone.ai/) - Open-source observability platform for logging LLM requests, costs, and latency. · 🔓 open-source · ☁️ hosted · 🧪 observability
- [AgentOps](https://agentops.ai/) - Specialized observability and monitoring for AI agents and multi-step reasoning. · ☁️ hosted · 🤖 agents · 🧪 observability
- [Braintrust](https://braintrustdata.com/) - Enterprise stack for building AI products with a focus on automated evaluations. · ☁️ hosted · 🧪 observability · 🧪 research
- [Tracer](https://github.com/Abil-Shrestha/tracer) - CLI-first issue tracker and context layer specifically designed for AI agents. · 🔓 open-source · 🤖 agents · 🧪 observability · 💻 coding
- [Future AGI](https://github.com/future-agi/future-agi) - Open-source platform to simulate, evaluate, trace, guardrail, route, and optimize LLM and AI agent apps in one feedback loop, so agents don't just get monitored, they self-improve. Self-hostable. Apache-2.0. · 🔓 open-source · ☁️ hosted · 🧪 observability

### 🛡️ Safety, guardrails, and governance

- [OpenAI Guardrails](https://openai.github.io/openai-guardrails-python/) - Safety framework for validating LLM inputs and outputs with configurable checks, evals, and production-ready enforcement. · 🔓 open-source · 🛡️ guardrails · 🤖 agents
- [NVIDIA NeMo Guardrails](https://docs.nvidia.com/nemo-guardrails/index.html) - Open-source toolkit for programmable conversational guardrails, policy control, and safety flows around LLM applications. · 🔓 open-source · 🛡️ guardrails · 🤖 agents
- [Guardrails AI](https://guardrailsai.com/docs/) - Reliability framework for structured output validation and runtime input or output risk checks across LLM apps. · 🔓 open-source · 🛡️ guardrails · 📝 text

### 🛤️ Agentic methodologies and conventions

- [12-Factor Agents](https://github.com/humanlayer/12-factor-agents) - Open-source methodology for building production-grade LLM-powered software around owned prompts, explicit context, structured tool calls, control flow, and resumable execution. · 🔓 open-source · 📝 methodology · 🤖 agents · 🛠️ workflow
- [Git Shit Done (GSD)](https://github.com/fredharper/git-shit-done) - A philosophy and set of GitOps conventions focused on high-velocity agentic engineering. · 📝 convention · 🤖 agents · 💻 coding
- [Vibe Coding](https://vibecoding.com/) - A paradigm shift toward orchestrating, planning, and reviewing agents rather than manual typing. · 📝 methodology · 🤖 agents · 💻 coding
- [Spec-Driven Development](https://github.github.com/spec-kit/) - Methodology where executable specifications drive agent work from intent, guardrails, and phased plans instead of one-shot prompts. · 📝 methodology · 🤖 agents · 💻 coding · 📐 specs
- [PRD Breakdown & Execute](https://github.com/nurettincoban/ai-prd-workflow) - A structured workflow for breaking high-level requirements into atomic agent tasks. · 📝 methodology · 🤖 agents · 🛠️ workflow
- [Shape Up](https://shapeup.cc/) - Basecamp’s product development method for shaping work into bounded cycles and meaningful slices, useful for agent task scoping. · 📝 methodology · 🤖 agents · 🛠️ workflow
- [Eat the Frog](https://asana.com/resources/eat-the-frog) - Priority-setting method for tackling the hardest or highest-impact task first, which maps well to sequencing agent work. · 📝 methodology · 🤖 agents · 🛠️ workflow

## 🧠 Machine learning and model layer

### 🧪 AI labs and model creators

- [OpenAI](https://openai.com/) - Frontier AI lab behind the GPT family and unified reasoning/multimodal systems. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video · 🧪 lab
- [Anthropic](https://www.anthropic.com/) - AI lab behind Claude with a focus on high-reasoning and agentic workflows. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🤖 agents · 🧪 lab
- [Google DeepMind](https://deepmind.google/) - Google’s flagship AI lab behind Gemini and multimodal reasoning research. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎧 audio · 🎬 video · 🧪 lab
- [Meta AI](https://ai.meta.com/) - Creators of the Llama open-weight model family and creative media research. · 🪶 open-weights · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🧪 lab
- [Mistral AI](https://mistral.ai/) - Leading European AI lab offering both hosted APIs and open-weight models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding · 🧪 lab
- [xAI](https://x.ai/) - AI lab focused on large-scale reasoning and deep ecosystem integration. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🧪 lab
- [DeepSeek](https://deepseek.com/) - Disruptive lab known for high-performance reasoning and coding models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding · 🧪 lab
- [Cohere](https://cohere.com/) - Enterprise-focused lab specializing in text, embeddings, and retrieval. · ☁️ hosted · 🔌 api · 📝 text · 🧬 embeddings · 📚 rag · 🧪 lab
- [MiniMax](https://www.minimax.io/) - Multimodal lab spanning text, audio, video, music, and autonomous agents. · ☁️ hosted · 🔌 api · 📝 text · 🎧 audio · 🎬 video · 🎼 music · 🧪 lab
- [Zhipu AI](https://www.zhipuai.cn/) - Leading lab known for the GLM family and multimodal media generation. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🎬 video · 🧪 lab
- [Moonshot AI](https://www.moonshot.ai/) - Lab specializing in long-context processing and large-scale reasoning models. · ☁️ hosted · 🔌 api · 📝 text · 🧪 lab
- [01.ai](https://www.01.ai/) - AI lab focused on high-performance model families and global scaling. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🧪 lab
- [Baichuan Intelligence](https://www.baichuan-ai.com/) - Creators of high-performance open-source and proprietary language models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🧪 lab
- [StepFun](https://www.stepfun.com/) - AI lab focused on efficient reasoning models and agentic swarms. · ☁️ hosted · 🔌 api · 📝 text · 🧪 lab
- [Aleph Alpha](https://aleph-alpha.com/) - European lab focused on sovereign AI for highly regulated industries. · ☁️ hosted · 🔌 api · 📝 text · 🧪 lab
- [Silo AI](https://silo.ai/) - Large European lab (acquired by AMD) focused on custom enterprise AI solutions. · ☁️ hosted · 🧪 lab · 🛠️ custom
- [DeepL](https://www.deepl.com/) - Specialized AI lab focused on world-leading translation and language processing. · ☁️ hosted · 🔌 api · 📝 text · 🧪 lab
- [Adept](https://www.adept.ai/) - Lab focused on action-oriented models and autonomous software workflows. · ☁️ hosted · 🤖 agents · 🧪 lab
- [Inflection AI](https://inflection.ai/) - AI lab focused on high-EQ conversational systems and personal assistants. · ☁️ hosted · 💬 chat · 🧪 lab

### 🔌 Model APIs and inference providers

- [DeepInfra](https://deepinfra.com/) - Inference platform for language, embeddings, image, video, and speech. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎬 video · 🎧 audio
- [Together AI](https://www.together.ai/) - AI-native cloud for serving, fine-tuning, and evaluating open models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🖼️ image · 🎬 video · 🎧 audio
- [Fireworks AI](https://fireworks.ai/) - Fast inference platform for open-source models and production AI workloads. · ☁️ hosted · 🔌 api · 🔓 open-source tooling · 📝 text · 🎧 audio
- [Deepgram](https://deepgram.com/) - Voice AI platform for speech-to-text, text-to-speech, and real-time voice-agent orchestration through one API stack. · ☁️ hosted · 🏠 self-hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [AssemblyAI](https://www.assemblyai.com/) - Speech AI platform for streaming transcription, speech understanding, and voice-agent applications. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [Soniox](https://soniox.com/) - Speech AI platform for real-time multilingual transcription, translation, speaker detection, and voice-agent workloads. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [Avalon API](https://aquavoice.com/avalon-api) - Aqua’s OpenAI-compatible speech API tuned for developer dictation, coding terms, and human-computer interaction. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [Replicate](https://replicate.com/) - Execution platform covering a broad range of open and custom models. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎬 video · 🎧 audio
- [fal](https://fal.ai/) - Media infrastructure for image, video, audio, and custom model serving. · ☁️ hosted · 🔌 api · 🖼️ image · 🎬 video · 🎧 audio
- [Cartesia](https://cartesia.ai/) - Low-latency voice AI platform focused on expressive streaming text-to-speech and conversational voice interfaces. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [PlayAI](https://docs.play.ai/) - Voice platform for text-to-speech, AI voice agents, and document-to-podcast generation. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice · 🤖 agents
- [Ollama](https://ollama.com/) - Local model runtime that now also provides access to cloud models through the same CLI, API, and desktop apps. · 💻 local · 🏠 self-hosted · ☁️ hosted · 🪶 open-weights · 🔌 api · 📝 text · 💻 coding
- [Runware](https://runware.ai/) - API platform for image, video, audio, text, and 3D generation. · ☁️ hosted · 🔌 api · 🖼️ image · 🎬 video · 🎧 audio · 📝 text
- [WaveSpeedAI](https://wavespeed.ai/) - Unified inference platform for image, video, and speech models with a large model catalog and one developer-facing API. · ☁️ hosted · 🔌 api · 🖼️ image · 🎬 video · 🎧 audio
- [SiliconFlow](https://siliconflow.cn/) - Unified AI cloud for fast, cost-efficient deployment of open-source models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🎬 video
- [Gcore](https://gcore.com/) - Global edge network provider for low-latency enterprise AI workloads. · ☁️ hosted · 🔌 api · 🧱 infra
- [NVIDIA NIM](https://www.nvidia.com/en-us/ai-data-science/generative-ai/nim/) - Optimized inference microservices for deploying generative AI on NVIDIA GPUs. · ☁️ hosted · 🔌 api · 🧱 infra
- [NVIDIA Build](https://build.nvidia.com/) - Developer catalog and free playground API for NVIDIA-hosted NIM models across text, vision, speech, embeddings, and specialized domains, with self-host paths for production. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎧 audio · 🧬 embeddings
- [Groq](https://groq.com/) - Ultra-fast LPU inference platform for language models with sub-second latency. · ☁️ hosted · 🔌 api · 📝 text · 🧱 infra
- [Cerebras](https://cerebras.ai/) - Wafer-scale AI inference cloud delivering industry-leading performance. · ☁️ hosted · 🔌 api · 🧱 infra · 📝 text
- [SambaNova](https://sambanova.ai/) - Full-stack AI platform and cloud for fast inference of open models. · ☁️ hosted · 🔌 api · 🧱 infra · 📝 text

### 🏋️ Fine-tuning and post-training

- [TRL](https://huggingface.co/docs/trl/en/index) - Hugging Face library for supervised fine-tuning, preference optimization, reward modeling, and RL-style post-training. · 🔓 open-source · 🏋️ training · 📝 text
- [PEFT](https://huggingface.co/docs/peft/index) - Parameter-efficient fine-tuning library for LoRA, AdaLoRA, IA3, and other adapter-based adaptation methods. · 🔓 open-source · 🏋️ training · 🪶 open-weights
- [Unsloth](https://docs.unsloth.ai/) - Open-source stack for faster local fine-tuning and reinforcement learning with significantly lower VRAM requirements. · 🔓 open-source · 🏋️ training · 🪶 open-weights

### 🎨 Media and creative labs

- [Black Forest Labs](https://blackforestlabs.ai/) - Media lab best known for the FLUX family of high-fidelity image models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🖼️ image · 🧪 lab
- [Midjourney](https://www.midjourney.com/) - Community-funded research lab building frontier image and video models with a strong creator ecosystem. · ☁️ hosted · 🖼️ image · 🎬 video · 🧪 lab
- [Sora](https://openai.com/sora/) - OpenAI’s video generation app and model family; Sora 2 is current while Sora 1 is sunset in the US. · ☁️ hosted · 🎬 video · 🎧 audio
- [Veo](https://deepmind.google/models/veo/) - Google DeepMind’s flagship video generation model family with native audio, cinematic controls, editing tools, and Flow integration. · ☁️ hosted · 🎬 video · 🎧 audio · 🧪 lab
- [Stability AI](https://stability.ai/) - Generative lab behind the Stable Diffusion and Stable Video families, with a focus on open-weight image and media ecosystems. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🖼️ image · 🎬 video · 🧪 lab
- [Stable Video Diffusion](https://stability.ai/stable-video) - Stability’s video model family based on Stable Diffusion; the hosted API was deprecated in July 2025 but self-hosting remains supported. · 🏠 self-hosted · 🎬 video
- [Runway](https://runwayml.com/) - Creative lab focused on professional-grade video generation and VFX tools. · ☁️ hosted · 🔌 api · 🎬 video · 🧪 lab
- [ArtCraft](https://github.com/storytold/artcraft) - Open-source IDE for interactive AI image and video creation with compositing, scene blocking, character posing, and multi-provider generation workflows. · 🔓 open-source · 💻 local · 🖼️ image · 🎬 video · 🎨 design
- [Leonardo AI](https://leonardo.ai/ai-video-generator) - Creator-focused visual platform with text-to-video, image-to-video, and controlled animation workflows. · ☁️ hosted · 🔌 api · 🖼️ image · 🎬 video
- [Kling AI](https://kling.ai/) - Kuaishou’s (KwaiVGI) flagship video platform known for high-speed, physics-aware cinematic generation. · ☁️ hosted · 🔌 api · 🎬 video · 🧪 lab
- [PixVerse](https://pixverse.ai/) - AI video platform and developer stack built around proprietary video models, editing tools, and real-time world-model research. · ☁️ hosted · 🔌 api · 🎬 video
- [Seedance](https://seed.bytedance.com/en/seedance2_0) - ByteDance’s multimodal video generation model with text, image, audio, and video inputs plus strong motion control and cinematic output. · ☁️ hosted · 🔌 api · 🎬 video · 🎧 audio · 🧪 lab
- [Wan](https://wan.video/) - Alibaba’s open video model family spanning text-to-video, image-to-video, and speech-to-video generation. · 🔓 open-source · 🪶 open-weights · 🎬 video · 🎧 audio
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - Tencent’s open video foundation model ecosystem for text-, image-, avatar-, and custom video generation. · 🔓 open-source · 🪶 open-weights · 🎬 video
- [ViMax](https://github.com/HKUDS/ViMax) - Open-source agentic video generation system that decomposes production into director, screenwriter, producer, and generator roles. · 🔓 open-source · 🎬 video · 🤖 agents · 🧪 research
- [Hailuo AI](https://hailuoai.video/) - MiniMax’s video creation product family focused on cinematic motion, director controls, and agentic video workflows. · ☁️ hosted · 🔌 api · 🎬 video
- [Luma AI](https://lumalabs.ai/) - Creative lab focused on fast video generation and 3D scene reconstruction. · ☁️ hosted · 🔌 api · 🎬 video · 🖼️ image · 🧪 lab
- [Meta Movie Gen](https://ai.meta.com/research/movie-gen/) - Meta’s research family of media foundation models for video and audio generation; currently in limited partner access, not publicly released. · 🧪 research · 🎬 video · 🎧 audio · 🧪 lab
- [ElevenLabs](https://elevenlabs.io/) - Leading lab for hyper-realistic voice, music, and multimodal audio systems. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice · 🎼 music · 🧪 lab
- [Supertonic](https://github.com/supertone-inc/supertonic) - Open-source on-device multilingual text-to-speech engine running natively through ONNX across desktop, mobile, web, and server runtimes. · 🔓 open-source · 💻 local · 🎧 audio · 🗣️ voice
- [Suno](https://suno.com/) - Creative lab specializing in high-fidelity, full-track music generation. · ☁️ hosted · 🎼 music · 🎧 audio · 🧪 lab
- [Udio](https://udio.com/) - Media lab focused on professional-grade music creation and remixing. · ☁️ hosted · 🎼 music · 🎧 audio · 🧪 lab
- [Hume AI](https://hume.ai/) - Specialized lab focused on empathetic voice agents and emotional intelligence. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice · 🧪 lab

### 🧬 Embeddings and rerankers

- [Voyage AI](https://www.voyageai.com/) - Retrieval-focused provider known for high-accuracy embedding models. · ☁️ hosted · 🔌 api · 🧬 embeddings · 📚 rag
- [Cohere Rerank](https://cohere.com/rerank) - Industry-leading reranker for boosting the accuracy of vector search results. · ☁️ hosted · 🔌 api · 📚 rag
- [Jina AI](https://jina.ai/) - Search and retrieval provider offering embeddings, rerankers, and reader tools. · ☁️ hosted · 🔌 api · 🧬 embeddings · 📚 rag · 🔎 search

## 🗃️ Data layer

### 🧠 Memory systems

- [Mem0](https://mem0.ai/) - Memory layer for AI apps and agents that need persistent user or workflow context. · ☁️ hosted · 🧠 memory · 🤖 agents
- [Honcho](https://honcho.dev/) - Memory server for stateful agents using dialectic reasoning to build user models. · ☁️ hosted · 🧠 memory · 🤖 agents
- [MemoryOS](https://github.com/BAI-LAB/MemoryOS) - Hierarchical memory management system providing short, mid, and long-term storage for agents. · 🔓 open-source · 🧠 memory · 🤖 agents
- [cognee](https://cognee.ai/) - Open-source AI memory engine using knowledge graphs for persistent context. · 🔓 open-source · 🧠 memory · 🤖 agents
- [MemPalace](https://github.com/mempalace/mempalace) - Open-source persistent memory system for building long-context agents. · 🔓 open-source · 🧠 memory · 🤖 agents
- [OpenViking](https://github.com/volcengine/OpenViking) - Open-source context database that organizes agent memories, resources, and skills through a filesystem paradigm. · 🔓 open-source · 🏠 self-hosted · 🧠 memory · 🤖 agents
- [Basic Memory](https://github.com/basicmachines-co/basic-memory) - Open-source, local-first memory system for AI assistants using MCP. · 🔓 open-source · 💻 local · 🧠 memory
- [OpenMemory](https://mem0.ai/openmemory) - Persistent MCP memory layer for coding agents with project-scoped recall and memory management. · 🔓 open-source · 💻 local · 🧠 memory · 🤖 agents
- [agentmemory](https://github.com/rohitg00/agentmemory) - Open-source persistent memory server for coding agents with MCP tools, auto-hooks, hybrid search, knowledge graphs, benchmarks, and integrations for Claude Code, Codex, Cursor, Gemini CLI, and OpenCode. · 🔓 open-source · 💻 local · 🧠 memory · 🤖 agents · 📚 rag · 🕸️ graph
- [Engram](https://github.com/Gentleman-Programming/engram) - A local-first, agent-agnostic memory layer for AI assistants that uses SQLite + FTS5 for high-performance persistent context, featuring a topic-based upsert system and a TUI for memory management. · 🔓 open-source · 🏠 self-hosted · 🧠 memory · 🤖 agents
- [QMD (Query Markup Documents)](https://github.com/tobi/qmd) - Local CLI search engine and MCP server for personal knowledge bases and notes. · 🔓 open-source · 💻 local · 🧠 memory · 🔎 search
- [Memgraph](https://memgraph.com/) - In-memory graph database used for GraphRAG and multi-hop reasoning. · 🔓 open-source · 🏠 self-hosted · 🧠 memory · 🕸️ graph
- [Graphiti](https://github.com/getzep/graphiti) - Temporal context graph engine for AI agents that tracks evolving facts, provenance, and hybrid retrieval. · 🔓 open-source · 🏠 self-hosted · 🧠 memory · 🕸️ graph
- [Motorhead](https://github.com/getmetal/motorhead) - Memory server middleware for handling chat history and summarization. · 🔓 open-source · 🏠 self-hosted · 🧠 memory
- [Zep](https://www.getzep.com/) - Context and memory platform for conversational systems and agents. · ☁️ hosted · 🧠 memory · 🤖 agents
- [Letta](https://www.letta.com/) - Stateful agent platform centered around long-lived memory management. · ☁️ hosted · 🧠 memory · 🤖 agents
- [Supermemory](https://supermemory.ai/) - Context infrastructure for AI agents with connected knowledge sources. · ☁️ hosted · 🧠 memory · 🤖 agents · 📚 rag
- [HydraDB](https://hydradb.com/) - Context infrastructure layer for agents with persistent and queryable memory. · ☁️ hosted · 🧠 memory · 🤖 agents

### 🗂️ Vector databases

- [Pinecone](https://www.pinecone.io/) - Managed serverless vector database for retrieval and memory-heavy products. · ☁️ hosted · 🗂️ vector-db · 📚 rag
- [Zilliz Cloud](https://zilliz.com/) - Managed Milvus built for massive-scale vector search and high-throughput. · ☁️ hosted · 🗂️ vector-db · 📚 rag
- [Weaviate](https://weaviate.io/) - AI-native database for vector search, hybrid retrieval, and knowledge apps. · ☁️ hosted · 🏠 self-hosted · 🔓 open-source · 🗂️ vector-db · 📚 rag
- [Qdrant](https://qdrant.tech/) - Vector database for semantic search with cloud and self-hosted options. · ☁️ hosted · 🏠 self-hosted · 🔓 open-source · 🗂️ vector-db · 📚 rag
- [Milvus](https://milvus.io/) - High-scale vector database for large-scale retrieval and search systems. · 🔓 open-source · 🏠 self-hosted · 🗂️ vector-db · 📚 rag
- [Chroma](https://www.trychroma.com/) - Simple vector storage and search layer aimed at AI application development. · 🔓 open-source · 🏠 self-hosted · 🗂️ vector-db · 📚 rag

### 📚 Retrieval, web search, and RAG tooling

- [Smithery](https://smithery.ai/) - Marketplace for MCP servers to extend agents with external tools and data. · ☁️ hosted · 🔌 api · 🛠️ workflow
- [Tavily](https://tavily.com/) - Search engine built for AI agents and RAG with structured context. · ☁️ hosted · 🔌 api · 🔎 search · 📚 rag
- [Exa](https://exa.ai/) - Neural search engine that uses embeddings to find semantic context. · ☁️ hosted · 🔌 api · 🔎 search · 📚 rag
- [Brave Search API](https://brave.com/search/api/) - Independent web search API for agents, chatbots, and RAG apps backed by Brave’s own search index. · ☁️ hosted · 🔌 api · 🔎 search · 📚 rag
- [SerpApi](https://serpapi.com/) - Search API platform for accessing Google, Bing, Yandex, and other SERPs in structured JSON. · ☁️ hosted · 🔌 api · 🔎 search
- [Serper](https://serper.dev/) - Low-cost Google Search API designed specifically for AI agents. · ☁️ hosted · 🔌 api · 🔎 search
- [Google Programmable Search Engine](https://developers.google.com/custom-search/v1/overview) - Google-backed programmable search service for retrieving web and image results through a configurable JSON API. · ☁️ hosted · 🔌 api · 🔎 search
- [Mojeek Web Search API](https://www.mojeek.com/services/search/web-search-api/) - Independent web search API exposing Mojeek’s own index for embedded search, AI apps, and custom ranking workflows. · ☁️ hosted · 🔌 api · 🔎 search
- [SearXNG](https://docs.searxng.org/) - Free and self-hostable metasearch engine that aggregates results from many search services without tracking users. · 🔓 open-source · 🏠 self-hosted · 🔎 search
- [YaCy](https://yacy.net/) - Open-source decentralized search engine you can run locally or for an organization. · 🔓 open-source · 🏠 self-hosted · 🔎 search
- [Semble](https://github.com/MinishLab/semble) - Open-source code search library, CLI, and MCP server that gives coding agents token-efficient semantic and lexical repository search. · 🔓 open-source · 💻 local · 💻 coding · 🔎 search · 📚 rag · 🤖 agents
- [CodeGraph](https://github.com/colbymchenry/codegraph) - Open-source local code knowledge graph that pre-indexes symbol relationships, call graphs, and code structure for Claude Code, Codex, Cursor, OpenCode, and Hermes Agent. · 🔓 open-source · 💻 local · 💻 coding · 🔎 search · 📚 rag · 🕸️ graph · 🤖 agents
- [GitNexus](https://github.com/abhigyanpatwari/GitNexus) - Source-available code intelligence engine that indexes repositories into local knowledge graphs for MCP-powered agent context, hybrid search, impact analysis, code wiki generation, and web-based repo exploration. · 💻 local · 🏠 self-hosted · 💻 coding · 🔎 search · 📚 rag · 🕸️ graph · 🤖 agents
- [LightRAG](https://github.com/HKUDS/LightRAG) - Open-source graph-enhanced RAG framework with optional multimodal document support via RAG-Anything. · 🔓 open-source · 🏠 self-hosted · 📚 rag · 🕸️ graph
- [Firecrawl](https://www.firecrawl.dev/) - Web scraping service that returns LLM-ready markdown from any URL. · ☁️ hosted · 🔌 api · 📄 parsing
- [Jina Reader](https://r.jina.ai/) - Simple API to convert any web URL into clean markdown for LLMs. · ☁️ hosted · 🔌 api · 📄 parsing · 🔎 search

### 🏷️ Data labeling and evaluation

- [Scale AI](https://scale.com/) - Data platform for AI providing high-quality training data, RLHF, and evaluation. · ☁️ hosted · 🛠️ labeling · 🧪 research
- [Labelbox](https://labelbox.com/) - Data-centric AI platform for labeling, orchestrating, and evaluating training data. · ☁️ hosted · 🛠️ labeling
- [Snorkel AI](https://snorkel.ai/) - Programmatic data labeling platform focused on high-scale enterprise AI development. · ☁️ hosted · 🛠️ labeling

### 🕸️ Knowledge graphs and structured context

- [Morph Data](https://morph-data.io/) - Platform for building AI data apps and connecting agents to databases. · ☁️ hosted · 🤖 agents · 🗃️ data
- [Understand Anything](https://github.com/Lum1104/Understand-Anything) - Open-source coding-assistant plugin that turns codebases, docs, and knowledge bases into interactive knowledge graphs with search, explanations, guided tours, and impact analysis. · 🔓 open-source · 💻 local · 💻 coding · 🤖 agents · 🕸️ graph · 📚 rag
- [Graphify](https://github.com/safishamsi/graphify) - Coding-assistant skill that turns folders of code, docs, images, and video into queryable knowledge graphs with AST parsing, semantic extraction, and local Whisper transcription. · 🔓 open-source · 💻 local · 🕸️ graph · 📚 rag · 💻 coding

### 📄 Document parsing and ingestion

- [Amazon Textract](https://aws.amazon.com/textract/) - AWS document OCR service for extracting text, handwriting, tables, forms, and structured fields from scanned documents. · ☁️ hosted · 🔌 api · 📄 parsing
- [Azure Document Intelligence](https://azure.microsoft.com/en-us/products/ai-foundry/tools/document-intelligence) - Enterprise document AI service for OCR, tables, key-value pairs, forms, and custom extraction workflows. · ☁️ hosted · 🔌 api · 📄 parsing
- [Chunkr](https://docs.chunkr.ai/) - Document parsing API for PDFs and spreadsheets with OCR, tables, bounding boxes, and RAG-ready chunks. · ☁️ hosted · 🏠 self-hosted · 🔌 api · 📄 parsing · 📚 rag
- [DeepSeek-OCR](https://github.com/deepseek-ai/DeepSeek-OCR) - Open-source OCR model for converting images and PDFs into markdown or plain text with vLLM support. · 🔓 open-source · 🏠 self-hosted · 📄 parsing
- [Docling](https://www.docling.ai/) - Open-source document parser for PDFs, Office files, and images with OCR, tables, formulas, and reading order. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [EasyOCR](https://github.com/JaidedAI/EasyOCR) - Lightweight OCR library with broad multilingual support and simple Python integration. · 🔓 open-source · 🏠 self-hosted · 📄 parsing
- [Google Document AI](https://cloud.google.com/document-ai/docs/process-documents-ocr) - Google Cloud document OCR service with layout parsing, math OCR, and structured extraction for PDFs and forms. · ☁️ hosted · 🔌 api · 📄 parsing
- [GLM-OCR](https://github.com/zai-org/GLM-OCR) - Open-source compact OCR model for complex document understanding with support for vLLM, SGLang, and Ollama deployment. · 🔓 open-source · 🏠 self-hosted · 📄 parsing
- [LlamaParse](https://cloud.llamaindex.ai/parse) - Agentic PDF parser designed for complex tables and multi-column layouts. · ☁️ hosted · 🔌 api · 📄 parsing · 📚 rag
- [Marker](https://github.com/datalab-to/marker) - Open-source PDF-to-Markdown and JSON converter with OCR and table extraction for document-heavy RAG pipelines. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [MinerU](https://github.com/opendatalab/MinerU) - Document parsing engine for PDFs and Office docs with OCR, table reconstruction, formulas, and Markdown or JSON output. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [Mistral OCR](https://docs.mistral.ai/capabilities/document_ai/basic_ocr/) - OCR API for extracting structured markdown, tables, and layout-aware content from PDFs and images. · ☁️ hosted · 🔌 api · 📄 parsing · 📚 rag
- [NVIDIA Nemotron Parse](https://docs.api.nvidia.com/nim/reference/nvidia-nemotron-parse) - Document parsing model that extracts formatted text, bounding boxes, and semantic classes from document images. · ☁️ hosted · 🔌 api · 📄 parsing
- [OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) - CLI tool that adds an OCR text layer to scanned PDFs to make them searchable and easier to ingest. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [olmOCR](https://github.com/allenai/olmocr) - Open-source toolkit for turning scanned PDFs and image-based documents into clean markdown or plain text for LLM pipelines. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) - Open-source OCR and document parsing toolkit for PDFs and images with broad multilingual support. · 🔓 open-source · 🏠 self-hosted · 📄 parsing · 📚 rag
- [Tesseract](https://github.com/tesseract-ocr/tesseract) - Widely used open-source OCR engine and library for turning scanned images into machine-readable text. · 🔓 open-source · 🏠 self-hosted · 📄 parsing
- [Unstructured](https://unstructured.io/) - Enterprise-grade ETL for processing almost any file type for RAG. · 🔓 open-source · ☁️ hosted · 📄 parsing · 📚 rag

## 🧱 Infrastructure and compute layer

### ☁️ GPU cloud and compute

- [AWS AI](https://aws.amazon.com/ai/) - Comprehensive AI cloud including Amazon Bedrock (API-first) and SageMaker (platform). · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [Azure AI](https://azure.microsoft.com/en-us/solutions/ai) - Microsoft’s enterprise AI cloud featuring Azure OpenAI Service and custom ML tools. · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [Google Vertex AI](https://cloud.google.com/vertex-ai) - Unified AI platform for building, deploying, and scaling models with Google Cloud. · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [IBM watsonx](https://www.ibm.com/watsonx) - Enterprise AI and data platform focused on governance, scale, and proprietary models. · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [Runpod](https://www.runpod.io/) - GPU cloud for pods, serverless inference, and AI deployment. · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [GMI Cloud](https://gmicloud.ai/) - GPU-specialized cloud provider focused on NVIDIA hardware. · ☁️ hosted · 🧱 gpu-cloud
- [NVIDIA DGX Cloud](https://www.nvidia.com/en-us/data-center/dgx-cloud/) - Fully managed, multi-node AI training-as-a-service platform. · ☁️ hosted · 🧱 gpu-cloud
- [Vast.ai](https://vast.ai/) - GPU marketplace known for flexible and lower-cost rented compute. · ☁️ hosted · 🧱 gpu-cloud
- [Lambda](https://lambda.ai/) - GPU cloud and infrastructure for training and inference workloads. · ☁️ hosted · 🧱 gpu-cloud
- [DigitalOcean Paperspace](https://www.paperspace.com/) - Cloud GPU platform focused on ease of use for developers and ML teams. · ☁️ hosted · 🧱 gpu-cloud
- [Genesis Cloud](https://www.genesiscloud.com/) - European GPU cloud provider for AI training and inference. · ☁️ hosted · 🧱 gpu-cloud
- [Chutes](https://chutes.ai/) - Serverless AI compute platform for open-source model inference. · ☁️ hosted · 🧱 gpu-cloud · 🔌 api
- [CoreWeave](https://www.coreweave.com/) - Large-scale AI cloud for enterprise GPU training and inference. · ☁️ hosted · 🧱 gpu-cloud
- [Nebius](https://nebius.com/) - AI-native cloud built around large-scale GPU workloads. · ☁️ hosted · 🧱 gpu-cloud

### 🏠 Self-hosted runtimes

- [Ollama](https://ollama.com/) - Runtime for running open models locally on laptops and servers. · 💻 local · 🏠 self-hosted · 🪶 open-weights · 📝 text · 💻 coding
- [LocalAI](https://localai.io/) - Self-hosted inference layer that exposes OpenAI-style APIs locally. · 🏠 self-hosted · 🔓 open-source · 🪶 open-weights · 🔌 api
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - Core inference stack for running models on consumer hardware. · 🔓 open-source · 🏠 self-hosted · 💻 local · 🪶 open-weights
- [Mojo](https://www.modular.com/mojo) - High-performance language for AI infrastructure and fast local inference. · 🔓 open-source · 🏠 self-hosted · 🧱 infra

### 💻 Local AI apps

- [LM Studio](https://lmstudio.ai/) - Desktop app for running local models with OpenAI-compatible endpoints. · 💻 local · 🏠 self-hosted · 🪶 open-weights
- [Jan](https://jan.ai/) - Local-first desktop AI assistant with bring-your-own-model workflows. · 💻 local · 🏠 self-hosted · 🔓 open-source · 🪶 open-weights · 💬 chat

### 🚀 Model serving and inference engines

- [vLLM](https://vllm.ai/) - High-throughput model serving engine for production inference. · 🔓 open-source · 🏠 self-hosted · 🧱 infra · 🔌 api
- [SGLang](https://sgl-project.github.io/) - Fast serving and execution runtime for LLM inference workloads. · 🔓 open-source · 🏠 self-hosted · 🧱 infra

### 🌐 Self-hosted AI interfaces

- [Open WebUI](https://github.com/open-webui/open-webui) - Self-hosted chat interface for Ollama and OpenAI backends. · 🔓 open-source · 🏠 self-hosted · 💬 chat
- [AnythingLLM](https://anythingllm.com/) - All-in-one workspace for document chat, RAG, and remote backends. · ☁️ hosted · 🏠 self-hosted · 💬 chat · 📚 rag · 🧠 memory
- [Onyx](https://onyx.app/) - Open-source AI workspace for internal chat, enterprise search, agents, and connected knowledge across self-hosted or cloud deployments. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 💬 chat · 🔎 search · 📚 rag · 🤖 agents

## 📏 Benchmarks and evaluation suites

### 💬 Assistant and agent benchmarks

- [MT-Bench](https://arxiv.org/abs/2306.05685) - Multi-turn benchmark for evaluating chat assistants on instruction following, reasoning, and conversational quality. · 🧪 benchmark · 💬 chat · 📝 text
- [GAIA](https://arxiv.org/abs/2311.12983) - Real-world benchmark for general AI assistants that need reasoning, tool use, multimodality, and web browsing. · 🧪 benchmark · 💬 chat · 🤖 agents · 🔎 search
- [WebArena](https://webarena.dev/) - Realistic benchmark for autonomous web agents acting across self-hostable websites. · 🧪 benchmark · 🤖 agents · 🛠️ workflow
- [OSWorld](https://os-world.github.io/) - Computer-use benchmark for agents operating across desktop and web apps in real environments. · 🧪 benchmark · 🤖 agents · 🛠️ workflow
- [SWE-bench Verified](https://www.swebench.com/verified.html) - Human-validated benchmark for repository-level software issue resolution by coding agents. · 🧪 benchmark · 💻 coding · 🤖 agents
- [BFCL](https://gorilla.cs.berkeley.edu/leaderboard.html) - Berkeley Function Calling Leaderboard for measuring tool and function-calling accuracy in real-world settings. · 🧪 benchmark · 🤖 agents · 🧩 framework

### 🧠 Model and multimodal benchmarks

- [MMLU-Pro](https://arxiv.org/abs/2406.01574) - Harder multi-domain reasoning benchmark spanning 14 subjects with stronger distractors and cleaner questions. · 🧪 benchmark · 📝 text
- [GPQA](https://arxiv.org/abs/2311.12022) - Graduate-level, Google-proof science QA benchmark for biology, physics, and chemistry. · 🧪 benchmark · 📝 text · 🧪 research
- [MATH](https://arxiv.org/abs/2103.03874) - Competition-maths benchmark for step-by-step mathematical reasoning. · 🧪 benchmark · 📝 text
- [MMMU](https://mmmu-benchmark.github.io/) - Expert-level multimodal reasoning benchmark across six disciplines and 30 subjects. · 🧪 benchmark · 🖼️ image · 📝 text
- [GenEval](https://arxiv.org/abs/2310.11513) - Object-focused benchmark for compositional text-to-image generation. · 🧪 benchmark · 🖼️ image
- [Design Arena](https://www.designarena.ai/leaderboard) - Community-driven leaderboard for evaluating AI design capabilities through blind pairwise comparisons across code, image, video, audio, and UI categories. · 🧪 benchmark · 🖼️ image · 🎬 video · 🎧 audio · 💻 coding
- [VBench](https://arxiv.org/abs/2311.17982) - Comprehensive benchmark suite for video generation quality, consistency, and prompt faithfulness. · 🧪 benchmark · 🎬 video
- [SUPERB](https://arxiv.org/abs/2105.01051) - Broad speech benchmark spanning recognition, speaker, semantic, and paralinguistic tasks. · 🧪 benchmark · 🎧 audio · 🗣️ voice

### 🗃️ Retrieval, document, and context benchmarks

- [LongBench](https://github.com/THUDM/LongBench) - Long-context benchmark covering QA, summarisation, few-shot learning, synthetic tasks, and code completion. · 🧪 benchmark · 🧠 memory · 📚 rag
- [MTEB](https://github.com/embeddings-benchmark/mteb) - Standard benchmark suite for text embeddings across retrieval, reranking, classification, clustering, and more. · 🧪 benchmark · 🧬 embeddings · 📚 rag
- [BEIR](https://arxiv.org/abs/2104.08663) - Heterogeneous zero-shot retrieval benchmark widely used for IR and RAG evaluation. · 🧪 benchmark · 🔎 search · 📚 rag
- [ANN-Benchmarks](https://ann-benchmarks.com/) - Standard benchmark for approximate nearest-neighbour search used to compare vector indexes and vector databases. · 🧪 benchmark · 🗂️ vector-db
- [DocVQA](https://www.docvqa.org/) - Established benchmark for document visual question answering and layout-aware document understanding. · 🧪 benchmark · 📄 parsing · 🖼️ image
- [OmniDocBench](https://github.com/opendatalab/OmniDocBench) - Open benchmark for evaluating document parsing, OCR, tables, formulas, and layout detection on diverse real-world PDFs. · 🔓 open-source · 🧪 benchmark · 📄 parsing

### 🧱 System and infrastructure benchmarks

- [MLPerf Inference](https://mlcommons.org/benchmarks/inference-datacenter/) - Industry benchmark for system throughput and latency on deployed inference workloads. · 🧪 benchmark · 🧱 infra
- [MLPerf Training](https://mlcommons.org/benchmarks/training/) - Industry benchmark for time-to-train systems to a target quality threshold. · 🧪 benchmark · 🧱 infra

## 🧭 AI providers and model families

This section maps labs and providers to their main model families. It is intentionally family-oriented: fast-moving providers often rotate exact API aliases, while the family names are the stable way to understand the ecosystem.

### 🧮 Model marketplaces, routers, and inference catalogs

- [Fireworks AI model library](https://app.fireworks.ai/models) - Serverless, dedicated, and fine-tuning platform for open and open-weight models; current recommended families include Kimi K2/K2.6, DeepSeek V3.2, MiniMax M2.5, GLM 4.7/5, Qwen3, Qwen2.5-Coder, GPT-OSS, Llama 3.x, Qwen2.5-VL, Qwen3-VL, DeepSeek-OCR, FLUX, and Stable Diffusion. · ☁️ hosted · 🔌 api · 🪶 open-weights · 💻 coding · 🖼️ image · 📄 parsing
- [Together AI serverless models](https://docs.together.ai/docs/serverless/models) - Broad open-model catalog for chat, image, vision, video, audio, embeddings, reranking, and moderation; notable hosted families include DeepSeek V4, Qwen3.x, Kimi K2.6, GLM-5/5.1, GPT-OSS, Llama, Gemma, MiniMax, Liquid, and many fine-tunable open models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🏋️ training · 🧬 embeddings
- [DeepInfra model catalog](https://deepinfra.com/) - Pay-as-you-go inference provider for 100+ models, including DeepSeek V4 Pro/Flash, NVIDIA Nemotron, Kimi K2.6, Xiaomi MiMo V2.5/V2.5-Pro, Qwen, Llama, Gemma, embeddings, speech, image, and vision-language models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🖼️ image · 🎧 audio
- [OpenRouter providers](https://openrouter.ai/providers/) - Multi-provider routing marketplace spanning official labs, clouds, inference specialists, and BYOK routes; covers OpenAI, Anthropic, Google, xAI, DeepSeek, Qwen/Alibaba, Moonshot, MiniMax, Z.ai, Mistral, Groq, Together, Fireworks, Cerebras, SambaNova, DeepInfra, Bedrock, Vertex, Azure, SiliconFlow, Chutes, Cloudflare, and many smaller providers. · ☁️ hosted · 🔌 api · 🧠 routing · 🪶 open-weights
- [GroqCloud models](https://console.groq.com/docs/models) - LPU inference catalog focused on high-speed open models and Groq Compound systems; common families include GPT-OSS, Llama, Qwen, Llama Guard/Prompt Guard, Orpheus voice, Whisper-style STT, and selected preview models. · ☁️ hosted · 🔌 api · 🧱 infra · 📝 text · 🎧 audio
- [Cerebras Inference model catalog](https://inference-docs.cerebras.ai/models/overview) - Wafer-scale inference endpoints for ultra-fast open-model serving; public and preview catalog includes GPT-OSS, Llama, Qwen3, and GLM, with additional families available through dedicated endpoints. · ☁️ hosted · 🔌 api · 🧱 infra · 🪶 open-weights
- [SambaNova model catalog](https://docs.sambanova.ai/) - SambaCloud inference for open models such as Llama, DeepSeek, Qwen/QwQ, and multimodal Llama releases, with a model-list API for environment-specific availability. · ☁️ hosted · 🔌 api · 🧱 infra · 🪶 open-weights
- [SiliconFlow model marketplace](https://siliconflow.cn/) - China-focused inference cloud and model marketplace for Qwen, DeepSeek, GLM, Kimi, Baichuan, InternLM, MiniCPM, embedding/reranker, video, and speech models. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🎬 video
- [Chutes model API](https://chutes.ai/) - Serverless open-model inference network commonly used for fast access to recent open releases, including Qwen, DeepSeek, Llama, GLM, Kimi, MiniMax, image/video, and community model variants. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🧱 infra
- [Novita AI model API](https://novita.ai/) - Inference platform for text, image, video, and audio generation with large open-model coverage, including Llama, Qwen, DeepSeek, Flux, Stable Diffusion, and media-generation families. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🖼️ image · 🎬 video
- [Baseten model library](https://www.baseten.co/library/) - Managed deployment platform for open and custom models, often used for dedicated production serving of Llama, Qwen, DeepSeek, Whisper, Stable Diffusion/FLUX, embeddings, rerankers, and fine-tuned private models. · ☁️ hosted · 🔌 api · 🧱 infra · 🪶 open-weights
- [Cursor models](https://docs.cursor.com/models/) - Coding IDE model access surface rather than a standalone model lab; supports frontier coding models from OpenAI, Anthropic, Google, DeepSeek, xAI, and Cursor’s own Auto/Composer-style routing, with Max Mode for larger context on selected models. · ☁️ hosted · 💻 coding · 🤖 agents · 🧠 routing
- [DeepSeek API models](https://api-docs.deepseek.com/api/list-models) - Official DeepSeek endpoint and model-list API for DeepSeek-owned chat/reasoning models; use this when you want first-party DeepSeek rather than third-party hosted DeepSeek weights. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding

### 🧪 Frontier labs and hosted model families

- [OpenAI models](https://developers.openai.com/api/docs/models) - GPT-5.x frontier models for reasoning, coding, agents, and multimodal work; specialized families include GPT Codex, GPT Image, GPT Realtime, GPT Audio, Sora, embeddings, moderation, computer-use, and the open-weight gpt-oss line. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video · 🪶 open-weights
- [Anthropic Claude models](https://platform.claude.com/docs/en/about-claude/models/overview) - Claude Opus, Sonnet, and Haiku families for high-reasoning, coding, agentic, long-context, and vision-enabled text workflows, with availability across Anthropic API, Bedrock, Vertex AI, and Microsoft Foundry. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🤖 agents
- [Google Gemini models](https://ai.google.dev/gemini-api/docs/models) - Gemini frontier family spanning Pro, Flash, Flash-Lite, Live, TTS, Deep Research, computer-use, image generation/editing, video generation, music, embeddings, and long-context multimodal understanding. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video · 🎼 music
- [Google Gemma](https://ai.google.dev/gemma/docs) - Open-weight family derived from Gemini research, including Gemma 3, Gemma 3n, CodeGemma, PaliGemma, ShieldGemma, MedGemma, EmbeddingGemma, FunctionGemma, T5Gemma, VaultGemma, and interpretability tooling such as Gemma Scope. · 🪶 open-weights · 💻 local · 📝 text · 🖼️ image · 🎧 audio · 🧬 embeddings
- [xAI Grok models](https://docs.x.ai/developers/models) - Grok chat, Grok Build for coding, Grok Imagine for image/video, and Grok Voice for real-time speech workflows with optional web and X search grounding. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video
- [Mistral AI models](https://docs.mistral.ai/models/overview) - Mistral Large, Medium, Small, Magistral, Ministral, Pixtral, Codestral, Devstral, Voxtral, OCR, embeddings, and moderation families across open-weight and premier hosted deployments. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding · 🖼️ image · 🎧 audio
- [Meta Llama](https://ai.meta.com/llama/get-started/) - Open-weight Llama family including Llama 4 Scout and Maverick, Llama 3.x, Code Llama, Llama Guard, and Prompt Guard; one of the largest downstream fine-tuning bases. · 🪶 open-weights · 💻 local · 📝 text · 🖼️ image · 🛡️ guardrails
- [DeepSeek](https://www.deepseek.com/en/transparency/) - DeepSeek-V4, V3.x, R1, R1-Zero, and R1 distillation families focused on open-weight reasoning, coding, and agentic tool use. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding
- [Alibaba Qwen](https://qwen.ai/) - Qwen family covering Qwen3, Qwen3-Coder, Qwen3-VL, Qwen3-Omni, Qwen-Image, Qwen TTS/ASR, QwQ reasoning, embeddings, rerankers, and DashScope-hosted proprietary variants. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video
- [Xiaomi MiMo](https://huggingface.co/XiaomiMiMo) - MiMo model family spanning MiMo-7B reasoning, MiMo-VL, MiMo-Audio, MiMo-Embodied, MiMo-V2-Flash, MiMo-V2.5, and MiMo-V2.5-Pro for long-context, multimodal, and agentic workflows. · 🪶 open-weights · 💻 local · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🎬 video
- [Z.ai GLM](https://docs.z.ai/guides/llm/glm-4.5) - GLM family from Zhipu/Z.ai, including GLM-4.5, GLM-4.5-Air, X, AirX, and Flash variants for agentic reasoning, coding, tool use, and long-context workflows. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 💻 coding · 🤖 agents
- [Moonshot AI Kimi](https://www.moonshot.ai/) - Kimi family for long-context chat, reasoning, coding, audio, vision-language, and agentic workflows, including Kimi K-series and Moonlight releases. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🖼️ image · 🎧 audio
- [MiniMax models](https://platform.minimax.io/docs/release-notes/models) - MiniMax M-series language models plus Hailuo video, Speech, Music, and image models for agents, coding, voice, video, and entertainment products. · ☁️ hosted · 🔌 api · 📝 text · 💻 coding · 🎧 audio · 🎬 video · 🎼 music
- [ByteDance Seed](https://seed.bytedance.com/en/models) - Seed model family behind Doubao, including Seed language models, Seedance video, Seedream image, Seed-ASR, and multimodal agent releases. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎧 audio · 🎬 video
- [Amazon Nova](https://docs.aws.amazon.com/nova/) - Amazon model family on Bedrock, including Nova Premier, Pro, Lite, Micro, Sonic, Canvas, Reel, Nova multimodal embeddings, and Nova 2.x upgrades. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎧 audio · 🎬 video · 🧬 embeddings
- [Cohere models](https://docs.cohere.com/v2/docs/models) - Enterprise language, retrieval, and search family including Command A, Command R/R+, Command Vision, Command Translate, Embed, and Rerank. · ☁️ hosted · 🔌 api · 📝 text · 🧬 embeddings · 📚 rag
- [AI21 Jamba](https://docs.ai21.com/docs/jamba-foundation-models) - Jamba family built around hybrid Mamba-Transformer architecture, including Jamba Large, Jamba2 Mini, and smaller enterprise-oriented variants. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text
- [Microsoft Phi](https://azure.microsoft.com/en-us/products/phi/) - Small language and multimodal model family including Phi-4, Phi-4-mini, Phi-4-multimodal, and reasoning-focused Phi variants available through Foundry and Hugging Face. · ☁️ hosted · 🪶 open-weights · 💻 local · 📝 text · 🖼️ image · 🎧 audio
- [NVIDIA Nemotron](https://build.nvidia.com/) - NVIDIA open and NIM-served model family for agentic reasoning, chat, reward modeling, content safety, voice, OCR/document parsing, and GPU-optimized deployment. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🧱 infra · 🛡️ guardrails
- [IBM Granite](https://research.ibm.com/blog/granite-4-1-ai-foundation-models) - Enterprise open model family for language, code, vision, speech, embeddings, time series, and Granite Guardian safety models on watsonx and open platforms. · ☁️ hosted · 🪶 open-weights · 📝 text · 💻 coding · 🖼️ image · 🎧 audio · 🛡️ guardrails

### 🪶 Open-weight lineages, forks, and derivatives

- [Qwen3](https://github.com/QwenLM/Qwen3) - Base open-weight Qwen lineage with dense and MoE models; Qwen3 builds on Qwen2.5, QwQ, Qwen2.5-Coder, and Qwen2.5-Math training recipes for hybrid thinking and agentic tool use. · 🪶 open-weights · 📝 text · 💻 coding · 🤖 agents
- [Qwen3-Coder](https://qwenlm.github.io/blog/qwen3-coder/) - Qwen coding lineage optimized for repository-scale coding, browser-use, tool-use, and agentic workflows; Qwen Code is a fork/adaptation of Gemini CLI for Qwen-Coder models. · 🪶 open-weights · 💻 coding · 🤖 agents
- [Qwen3-VL](https://github.com/QwenLM/Qwen3-VL) - Qwen vision-language lineage with dense and MoE Instruct/Thinking variants for OCR, visual reasoning, GUI agents, video understanding, and long-context multimodal work. · 🪶 open-weights · 🖼️ image · 🎬 video · 🤖 agents
- [DeepSeek-R1](https://huggingface.co/deepseek-ai/DeepSeek-R1) - Reasoning lineage where the full R1 model is DeepSeek-native, while the R1-Distill checkpoints are smaller Qwen/Llama-based models fine-tuned from R1-generated reasoning data. · 🪶 open-weights · 📝 text · 💻 coding
- [DeepSeek-R1-Distill-Qwen](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Qwen-32B) - Qwen-descended DeepSeek distillation branch based on Qwen2.5/Qwen2.5-Math checkpoints, commonly seen in 1.5B, 7B, 14B, and 32B sizes. · 🪶 open-weights · 📝 text · 💻 coding
- [DeepSeek-R1-Distill-Llama](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-70B) - Llama-descended DeepSeek distillation branch based on Llama checkpoints, typically used when people want R1-style reasoning behavior on Llama-compatible runtimes. · 🪶 open-weights · 📝 text · 💻 coding
- [Llama derivatives](https://huggingface.co/meta-llama/models) - Broad ecosystem of Llama-based fine-tunes, quantizations, instruction models, coding variants, safety models, and domain-specific forks; descendants often inherit Llama architecture but differ heavily in data, alignment, and license. · 🪶 open-weights · 💻 local · 📝 text
- [Mistral derivatives](https://huggingface.co/mistralai) - Mistral 7B, Mixtral, Mistral Nemo, Codestral, Devstral, and Pixtral have large downstream fine-tune ecosystems, especially for local chat, coding, and low-latency agents. · 🪶 open-weights · 💻 local · 📝 text · 💻 coding
- [Gemma derivatives](https://ai.google.dev/gemma/docs/get_started) - Gemma ecosystem includes official task branches such as PaliGemma, ShieldGemma, MedGemma, T5Gemma, EmbeddingGemma, and many community fine-tunes hosted on Kaggle and Hugging Face. · 🪶 open-weights · 💻 local · 📝 text · 🖼️ image
- [MiMo derivatives](https://huggingface.co/XiaomiMiMo/MiMo-V2.5) - Xiaomi MiMo releases expose base, instruct, RL, audio, VL, embodied, Flash, and V2.5 branches; community variants are mostly quantizations and deployment ports rather than separate base-model forks. · 🪶 open-weights · 💻 local · 📝 text · 🖼️ image · 🎧 audio
- [Nous Hermes](https://huggingface.co/NousResearch) - Popular family of open instruction fine-tunes historically built on Llama, Mistral, Mixtral, and Qwen backbones for general chat, tool use, and agent workflows. · 🪶 open-weights · 💻 local · 📝 text · 🤖 agents
- [Dolphin](https://huggingface.co/cognitivecomputations) - Community instruction and coding fine-tune family that commonly targets Llama, Mistral, Mixtral, and Qwen base models. · 🪶 open-weights · 💻 local · 📝 text · 💻 coding
- [Unsloth model zoo](https://huggingface.co/unsloth) - Fine-tuned and quantized variants of Qwen, Llama, Gemma, Mistral, DeepSeek, and other open models optimized for local training and inference. · 🪶 open-weights · 💻 local · 🏋️ training
- [GGUF and llama.cpp ecosystem](https://github.com/ggml-org/llama.cpp) - Quantized local-running descendants of major open-weight families; GGUF files are deployment formats, not new base models. · 🔓 open-source · 💻 local · 🪶 open-weights

### 🌏 Regional, sovereign, and enterprise model families

- [Baidu ERNIE](https://huggingface.co/baidu) - ERNIE and Wenxin model family spanning hosted chat, reasoning, multimodal understanding, and open ERNIE 4.5 variants on Hugging Face. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🖼️ image
- [Tencent Hunyuan](https://hunyuan.tencent.com/) - Hunyuan family covering large language models, HunyuanVideo, image generation, 3D generation, OCR, translation, and cloud-hosted enterprise APIs. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🖼️ image · 🎬 video · 🧊 3d
- [Huawei Pangu](https://support.huaweicloud.com/intl/en-us/productdesc-pangulm/) - Huawei Cloud model family for industry, government, scientific, weather, vision, and enterprise AI workloads, with openPangu variants in the broader ecosystem. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🧪 research
- [01.ai Yi](https://www.01.ai/) - Yi model family for open-weight and hosted multilingual language models, long-context chat, and enterprise applications. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text
- [Baichuan](https://www.baichuan-ai.com/) - Baichuan language model family for Chinese and multilingual chat, reasoning, enterprise deployment, and open-weight releases. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text
- [StepFun Step](https://www.stepfun.com/) - Step model family for multimodal chat, reasoning, image/video understanding, and Chinese-market AI applications. · ☁️ hosted · 🔌 api · 📝 text · 🖼️ image · 🎬 video
- [Aleph Alpha Pharia](https://aleph-alpha.com/) - European sovereign AI family focused on transparent, regulated, and enterprise deployments. · ☁️ hosted · 🔌 api · 📝 text · 🧪 lab
- [Sarvam AI](https://www.sarvam.ai/) - India-focused model family for Indic language text, speech, translation, and government/enterprise workflows. · ☁️ hosted · 🔌 api · 🪶 open-weights · 📝 text · 🎧 audio
- [Naver HyperCLOVA X](https://clova.ai/en/) - Korean-focused model family for enterprise language, search, writing, and productivity workflows. · ☁️ hosted · 🔌 api · 📝 text
- [Upstage Solar](https://www.upstage.ai/) - Korean enterprise model family for small language models, document AI, OCR, and retrieval-heavy workloads. · ☁️ hosted · 🔌 api · 📝 text · 📄 parsing
- [LG EXAONE](https://www.lgresearch.ai/) - LG AI Research model family for language, multimodal reasoning, materials, chemistry, and enterprise research workflows. · ☁️ hosted · 🪶 open-weights · 📝 text · 🧪 research
- [TII Falcon](https://falconllm.tii.ae/) - Abu Dhabi Technology Innovation Institute open model family including Falcon language models and multimodal/research variants. · 🪶 open-weights · 💻 local · 📝 text
- [Jais](https://www.core42.ai/jais) - Arabic-English model family from Core42/Inception focused on Arabic language, enterprise, and regional deployment. · ☁️ hosted · 🪶 open-weights · 📝 text
- [AI2 OLMo](https://allenai.org/olmo) - Fully open language model family from the Allen Institute for AI with open weights, data, training code, and evaluation artifacts. · 🔓 open-source · 🪶 open-weights · 📝 text · 🧪 research
- [Databricks DBRX](https://www.databricks.com/blog/introducing-dbrx-new-state-art-open-llm) - Open MoE model family from Databricks for enterprise data, SQL, coding, and retrieval workflows. · 🪶 open-weights · 📝 text · 💻 coding · 🗃️ data
- [Snowflake Arctic](https://www.snowflake.com/en/data-cloud/arctic/) - Enterprise open model family optimized for SQL, coding, and data-cloud workloads. · 🪶 open-weights · 📝 text · 💻 coding · 🗃️ data

### 🎛️ Specialized model families

- [Black Forest Labs FLUX](https://blackforestlabs.ai/) - Image generation family including FLUX.1 and newer hosted/open variants used across creative tools and inference platforms. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🖼️ image
- [Stability AI Stable Diffusion](https://stability.ai/) - Stable Diffusion, Stable Image, Stable Audio, Stable Video, and 3D/image editing model families with a large downstream ecosystem. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🖼️ image · 🎧 audio · 🎬 video
- [Runway Gen](https://runwayml.com/) - Gen video model family for professional video generation, editing, inpainting, motion, and VFX-style workflows. · ☁️ hosted · 🔌 api · 🎬 video
- [Midjourney](https://www.midjourney.com/) - Proprietary image and video model family focused on high-quality creative generation through Discord and web workflows. · ☁️ hosted · 🖼️ image · 🎬 video
- [Kling AI](https://kling.ai/) - Kuaishou/Kwai video model family for cinematic text-to-video, image-to-video, and editing workflows. · ☁️ hosted · 🔌 api · 🎬 video
- [PixVerse](https://pixverse.ai/) - Video model family for text-to-video, image-to-video, effects, editing, and developer-accessible generation. · ☁️ hosted · 🔌 api · 🎬 video
- [ElevenLabs](https://elevenlabs.io/) - Voice, speech-to-text, text-to-speech, dubbing, sound effects, and music model family for real-time and production audio. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice · 🎼 music
- [Cartesia Sonic](https://cartesia.ai/) - Low-latency voice model family for streaming TTS and conversational voice agents. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [Deepgram Nova](https://deepgram.com/) - Speech recognition, speech understanding, TTS, and voice-agent model family for realtime and batch audio applications. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice
- [AssemblyAI Universal](https://www.assemblyai.com/) - Speech-to-text and speech intelligence model family for transcription, speaker labels, summarization, and audio understanding. · ☁️ hosted · 🔌 api · 🎧 audio
- [Suno](https://suno.com/) - Music generation model family for full-song creation, vocals, lyrics, and remix workflows. · ☁️ hosted · 🎼 music · 🎧 audio
- [Udio](https://udio.com/) - Music model family for song generation, remixing, extension, and creator workflows. · ☁️ hosted · 🎼 music · 🎧 audio
- [Voyage AI](https://www.voyageai.com/) - Embedding and reranking model family focused on retrieval, multilingual search, code retrieval, and legal/finance domains. · ☁️ hosted · 🔌 api · 🧬 embeddings · 📚 rag
- [Jina AI embeddings and rerankers](https://jina.ai/) - Open and hosted model family for embeddings, rerankers, late-interaction retrieval, readers, and multimodal search. · ☁️ hosted · 🔌 api · 🪶 open-weights · 🧬 embeddings · 📚 rag
