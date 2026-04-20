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
- [Goose](https://goose-docs.ai/) - Open-source local AI agent with desktop, CLI, and API interfaces for code, automation, MCP workflows, and subagents. · 🔓 open-source · 💻 local · 💻 coding · 🤖 agents · 🛠️ workflow
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
- [What The Diff](https://whatthediff.ai/) - AI-powered pull request assistant focused on diff summaries, change explanations, and review support in GitHub or GitLab. · ☁️ hosted · 💻 coding · 🧾 code-review

### 🛠️ App builders and product tools

- [v0](https://v0.app/) - Prompt-based product and UI builder for components, apps, and front-end flows. · ☁️ hosted · 💻 coding · 🤖 agents
- [Bolt](https://bolt.new/) - Browser-based AI builder for creating full-stack apps and quick prototypes. · ☁️ hosted · 💻 coding · 🤖 agents
- [Lovable](https://lovable.dev/) - Prompt-to-app builder for generating product prototypes and web applications. · ☁️ hosted · 💻 coding · 🤖 agents
- [Replit Agent](https://replit.com/ai) - Agentic browser development environment for building and deploying apps from prompts. · ☁️ hosted · 💻 coding · 🤖 agents

### 👥 Team agents and collaborative tools

- [OpenClaw](https://github.com/openclaw/openclaw) - Open-source personal AI agent platform with multi-channel inboxes, routing, tools, and collaborative workflow surfaces across chat platforms. · 🔓 open-source · 🤖 agents · 💬 chat
- [Harness AI](https://harness.io/products/ai-code-assistant) - Commercial platform and coding agent focused on automating the full software lifecycle. · ☁️ hosted · 💻 coding · 🤖 agents · 🛠️ workflow
- [Hermes Agent](https://hermes-agent.ai/) - Long-lived agent system from Nous Research focused on memory and tool workflows. · ☁️ hosted · 🤖 agents · 🧠 memory
- [Factory](https://factory.ai/) - Agent-native software development platform built around Factory Droid across IDEs, CLI, Slack, project backlogs, and CI/CD. · ☁️ hosted · 💻 coding · 🤖 agents · 👥 team · 🛠️ workflow
- [HumanLayer](https://github.com/humanlayer/humanlayer) - Approval and collaboration layer for teams using coding agents in real production workflows. · 🔓 open-source · ☁️ hosted · 🤖 agents · 👥 team
- [Vellum](https://www.vellum.ai/) - Enterprise agent control plane for building, testing, and monitoring AI agents. · ☁️ hosted · 🤖 agents · 🧪 observability
- [Agentforce](https://www.salesforce.com/agentforce/) - Salesforce’s low-code platform for building autonomous business agents. · ☁️ hosted · 🤖 agents · 🛠️ workflow
- [Kore.ai](https://kore.ai/) - Enterprise conversational AI platform for scaling thousands of agents. · ☁️ hosted · 🤖 agents · 🛠️ workflow
- [Devin](https://cognition.ai/) - Autonomous software agent product aimed at longer-running engineering work. · ☁️ hosted · 💻 coding · 🤖 agents

### 📅 Productivity, meeting, and voice assistants

- [TimeOS](https://timeos.ai/) - AI productivity hub for automating meeting prep, note-taking, and cross-platform follow-ups. · ☁️ hosted · 🛠️ workflow · 🤖 agents
- [Jamie](https://meetjamie.ai/) - Bot-free meeting assistant that records locally and generates professional summaries. · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow
- [Granola](https://granola.so/) - Meeting notepad that combines AI transcription with manual notes for structured documentation. · ☁️ hosted · 🛠️ workflow
- [Otter.ai](https://otter.ai/) - Real-time transcription and collaborative note-taking platform for teams and students. · ☁️ hosted · 🛠️ workflow
- [Aqua Voice](https://aquavoice.com/) - Voice dictation assistant that turns natural speech into polished text, prompts, and messages across apps with strong support for coding workflows. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding
- [Wispr Flow](https://wisprflow.ai/) - Cross-app voice dictation tool that rewrites speech into clean, structured text for writing, messaging, and development work. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding
- [Superwhisper](https://superwhisper.com/) - Voice-to-text assistant with offline support, app-aware modes, and fast dictation for coding, notes, and messages. · 💻 local · 🛠️ workflow · 🗣️ voice · 💻 coding

### 🧠 Personal knowledge and memory agents

- [Me.bot](https://me.bot/) - Personal AI memory system that ingests notes, voice, and thoughts to act as a second brain. · ☁️ hosted · 🧠 memory · 👥 companion
- [Saner.ai](https://saner.ai/) - ADHD-friendly workspace that unifies notes and tasks with proactive AI planning and recall. · ☁️ hosted · 🧠 memory · 🛠️ workflow
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
- [Antigravity](https://google.com/antigravity) - Google’s platform for building agentic apps that interact natively with OS and Workspace. · ☁️ hosted · 🧩 framework · 🤖 agents
- [browser-use](https://github.com/browser-use/browser-use) - Python library for making websites accessible to AI agents using Playwright and natural language. · 🔓 open-source · 🧩 framework · 🤖 agents
- [browser-harness](https://github.com/browser-use/browser-harness) - Lightweight, self-healing browser automation harness built directly on CDP for AI agents. · 🔓 open-source · 🧩 framework · 🤖 agents
- [OpenHarness](https://github.com/zhijiewong/openharness) - Open-source framework for building agent tool-calling loops and skill governance. · 🔓 open-source · 🧩 framework · 🤖 agents
- [Griptape](https://www.griptape.ai/) - Python framework for building modular and security-first AI agents and pipelines. · 🔓 open-source · 🧩 framework · 🤖 agents
- [Haystack](https://haystack.deepset.ai/) - Orchestration framework for building customizable RAG pipelines and agent systems. · 🔓 open-source · 🧩 framework · 🤖 agents
- [PydanticAI](https://ai.pydantic.dev/) - Python agent framework focused on validation, structure, and typed outputs. · 🔓 open-source · 🧩 framework · 🤖 agents
- [BMAD](https://github.com/bmad-code-org/BMAD-METHOD) - Breakthrough Method for Agile AI-Driven Development—an open framework for multi-agent software engineering. · 🔓 open-source · 🧩 framework · 🤖 agents · 📐 prompts

### 🧩 Workflow and automation

- [n8n](https://n8n.io/) - Workflow automation platform with strong AI, API, and developer integration support. · 🔓 open-source · ☁️ hosted · 🏠 self-hosted · 🛠️ workflow · 🤖 agents
- [Vibe Kanban](https://vibekanban.com/) - Visual orchestration layer for managing parallel AI agents using Kanban boards and Git worktrees. · 🔓 open-source · 🤖 agents · 🛠️ workflow
- [Schaltwerk](https://github.com/2mawi2/schaltwerk) - Desktop application for running and reviewing parallel terminal agents in a spec-driven flow. · 🔓 open-source · 🏠 self-hosted · 🤖 agents · 🛠️ workflow
- [Zapier Central](https://zapier.com/central) - Marketplace for automation agents that connect to thousands of business applications. · ☁️ hosted · 🛠️ workflow · 🤖 agents
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
- [Claude Super Prompt System](https://claude.ai/super-prompt) - Advanced prompt engineering framework for maximizing reasoning capabilities. · 📐 prompts · 📝 text · 🤖 agents
- [Superpowers](https://github.com/obra/superpowers) - Agentic skills framework and software development methodology for coding agents, centered on spec-first design, TDD, and subagent-driven execution. · 🔓 open-source · 🤖 agents · 💻 coding · 📐 specs · 📐 prompts

### 🧪 Evaluation and observability

- [LangSmith](https://www.langchain.com/langsmith) - Unified platform for debugging, testing, and monitoring LLM applications. · ☁️ hosted · 🧪 observability · 🧩 framework
- [Langfuse](https://langfuse.com/) - Open-source observability and analytics platform for tracing and evaluation. · 🔓 open-source · ☁️ hosted · 🧪 observability
- [Helicone](https://helicone.ai/) - Open-source observability platform for logging LLM requests, costs, and latency. · 🔓 open-source · ☁️ hosted · 🧪 observability
- [AgentOps](https://agentops.ai/) - Specialized observability and monitoring for AI agents and multi-step reasoning. · ☁️ hosted · 🤖 agents · 🧪 observability
- [Braintrust](https://braintrustdata.com/) - Enterprise stack for building AI products with a focus on automated evaluations. · ☁️ hosted · 🧪 observability · 🧪 research
- [Tracer](https://github.com/Abil-Shrestha/tracer) - CLI-first issue tracker and context layer specifically designed for AI agents. · 🔓 open-source · 🤖 agents · 🧪 observability · 💻 coding

### 🛡️ Safety, guardrails, and governance

- [OpenAI Guardrails](https://openai.github.io/openai-guardrails-python/) - Safety framework for validating LLM inputs and outputs with configurable checks, evals, and production-ready enforcement. · 🔓 open-source · 🛡️ guardrails · 🤖 agents
- [NVIDIA NeMo Guardrails](https://docs.nvidia.com/nemo-guardrails/index.html) - Open-source toolkit for programmable conversational guardrails, policy control, and safety flows around LLM applications. · 🔓 open-source · 🛡️ guardrails · 🤖 agents
- [Guardrails AI](https://guardrailsai.com/docs/) - Reliability framework for structured output validation and runtime input or output risk checks across LLM apps. · 🔓 open-source · 🛡️ guardrails · 📝 text

### 🛤️ Agentic methodologies and conventions

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
- [Leonardo AI](https://leonardo.ai/ai-video-generator) - Creator-focused visual platform with text-to-video, image-to-video, and controlled animation workflows. · ☁️ hosted · 🔌 api · 🖼️ image · 🎬 video
- [Kling AI](https://kling.ai/) - Kuaishou’s (KwaiVGI) flagship video platform known for high-speed, physics-aware cinematic generation. · ☁️ hosted · 🔌 api · 🎬 video · 🧪 lab
- [PixVerse](https://pixverse.ai/) - AI video platform and developer stack built around proprietary video models, editing tools, and real-time world-model research. · ☁️ hosted · 🔌 api · 🎬 video
- [Seedance](https://seed.bytedance.com/en/seedance2_0) - ByteDance’s multimodal video generation model with text, image, audio, and video inputs plus strong motion control and cinematic output. · ☁️ hosted · 🔌 api · 🎬 video · 🎧 audio · 🧪 lab
- [Wan](https://wan.video/) - Alibaba’s open video model family spanning text-to-video, image-to-video, and speech-to-video generation. · 🔓 open-source · 🪶 open-weights · 🎬 video · 🎧 audio
- [HunyuanVideo](https://github.com/Tencent-Hunyuan/HunyuanVideo) - Tencent’s open video foundation model ecosystem for text-, image-, avatar-, and custom video generation. · 🔓 open-source · 🪶 open-weights · 🎬 video
- [Hailuo AI](https://hailuoai.video/) - MiniMax’s video creation product family focused on cinematic motion, director controls, and agentic video workflows. · ☁️ hosted · 🔌 api · 🎬 video
- [Luma AI](https://lumalabs.ai/) - Creative lab focused on fast video generation and 3D scene reconstruction. · ☁️ hosted · 🔌 api · 🎬 video · 🖼️ image · 🧪 lab
- [Meta Movie Gen](https://ai.meta.com/research/movie-gen/) - Meta’s research family of media foundation models for video and audio generation; currently in limited partner access, not publicly released. · 🧪 research · 🎬 video · 🎧 audio · 🧪 lab
- [ElevenLabs](https://elevenlabs.io/) - Leading lab for hyper-realistic voice, music, and multimodal audio systems. · ☁️ hosted · 🔌 api · 🎧 audio · 🗣️ voice · 🎼 music · 🧪 lab
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
- [LightRAG](https://github.com/HKUDS/LightRAG) - Open-source graph-enhanced RAG framework with optional multimodal document support via RAG-Anything. · 🔓 open-source · 🏠 self-hosted · 📚 rag · 🕸️ graph
- [Firecrawl](https://www.firecrawl.dev/) - Web scraping service that returns LLM-ready markdown from any URL. · ☁️ hosted · 🔌 api · 📄 parsing
- [Jina Reader](https://r.jina.ai/) - Simple API to convert any web URL into clean markdown for LLMs. · ☁️ hosted · 🔌 api · 📄 parsing · 🔎 search

### 🏷️ Data labeling and evaluation

- [Scale AI](https://scale.com/) - Data platform for AI providing high-quality training data, RLHF, and evaluation. · ☁️ hosted · 🛠️ labeling · 🧪 research
- [Labelbox](https://labelbox.com/) - Data-centric AI platform for labeling, orchestrating, and evaluating training data. · ☁️ hosted · 🛠️ labeling
- [Snorkel AI](https://snorkel.ai/) - Programmatic data labeling platform focused on high-scale enterprise AI development. · ☁️ hosted · 🛠️ labeling

### 🕸️ Knowledge graphs and structured context

- [Morph Data](https://morph-data.io/) - Platform for building AI data apps and connecting agents to databases. · ☁️ hosted · 🤖 agents · 🗃️ data

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
