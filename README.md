# Awesome-Personal-AI-Agents

# Top Personal AI Agents Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Self-Improving Memory, Autonomous Task Execution & Persistent User Modeling*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Personal AI Agents**. These tools act on your behalf across apps, browsers, and messaging platforms — building a persistent model of who you are, remembering past interactions, and executing multi-step tasks without being tethered to a single IDE or chat window.

**Examples** include Hermes Agent, Lindy, MultiOn, Personal AI, Limitless (formerly Rewind), Dify, and OpenAcme (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, persistent memory, and autonomous execution — ideal for users who want an AI that actually knows them without handing their entire digital life to a cloud provider.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Lindy](https://www.lindy.ai/)**  
  **The inbox-and-calendar AI assistant that runs your work life from iMessage or SMS.** Drafts emails, schedules meetings, takes notes, and handles follow-ups with **100+ integrations** including Gmail, Outlook, Google Calendar, Slack, and Notion . **Plus at $49.99/month** (2 inboxes, standard usage), **Pro at $99.99/month** (3x usage, computer use, model selection), **Max at $199.99/month** (7x usage, 5 inboxes) . **Enterprise adds HIPAA BAA, SSO/SCIM, audit logs, and custom company context** . **Security posture**: enterprise-grade encryption, approvals built in, **data never sold or used to train models** . **Best for professionals wanting a polished, zero-maintenance assistant** reachable from their phone.

- **[MultiOn](https://www.multion.ai/)**  
  **The autonomous browser agent platform** for building agents that navigate websites, fill forms, and complete web tasks. **Local mode** lets the server-hosted agent interact with your installed Chrome browser extension — keeping session data on your machine . **Session-based architecture** with automatic browse or step-by-step control, speed modes (standard for complex tasks, fast for simpler ones), and proxy support for bot protection bypass . **Best for developers building web automation agents** with programmatic control over browsing sessions.

- **[Personal AI](https://www.personal.ai/)**  
  **The memory-first personal AI platform built on patented memory technology.** **SOC 2 and HIPAA certified**, GDPR compliant, with TLS 1.2+ in transit and AES256 at rest . **Seven US patents** covering memory data based on user input, memory retrieval and text generation, memory response generation, memory retention and recall, memory data structures, and capturing/retrieving personalized memory data in context . **"Stateless AI is transactional. Stateful AI builds relationships"** — the platform synthesizes lived experiences rather than just processing documents . **Best for users wanting a privacy-certified, memory-native assistant** with enterprise-grade security.

- **[Limitless AI (formerly Rewind AI)](https://www.limitless.ai/)**  
  **The wearable-enabled personal AI assistant system** that captures, recalls, and acts on information from everyday conversations. **The Pendant** wearable records spoken conversations and logs them securely; the cloud service transforms audio into **automatic summaries, to-do lists, reminders, and searchable lifelogs** . **Speaker recognition, automatic tagging/bookmarking, and calendar/task tool integration** for follow-ups . **The Rewind Mac app is shutting down following Meta's acquisition of Limitless** — the product direction has shifted toward wearable capture . **Best for users wanting continuous memory augmentation** of their conversations and daily activities.

## Open-Source GitHub Projects

- **[Hermes Agent](https://github.com/NousResearch/hermes-agent)**  
  **The leading open-source self-improving personal AI agent** — MIT licensed, built by Nous Research (the lab behind the Hermes model series) . **24 million+ downloads and several thousand open-source contributors**; accounts for an estimated **2.5% of the world's token consumption** . **$90M Series B at a $1.5B valuation** backed by Nvidia, Samsung, and Y Combinator . **The only agent with a built-in closed learning loop** — it creates skills from experience, improves them during use, nudges itself to persist knowledge, and builds a **deepening model of who you are across sessions** . **Memory system** with agent-curated memory, periodic nudges, FTS5 cross-session recall with LLM summarization, and Honcho dialectic user modeling . **Runs anywhere** — 7 terminal backends (local, Docker, SSH, Daytona, Singularity, Modal, Vercel Sandbox) with serverless persistence on Daytona/Modal costing nearly nothing when idle . **Lives where you do** — 20+ messaging platforms including Telegram, Discord, Slack, WhatsApp, Signal, Matrix, Mattermost, Email, SMS, and Home Assistant . **60+ built-in tools**, MCP integration, scheduled automations via cron, Bot Mode for specialist teams, voice mode, and a credential vault that signs into sites without exposing passwords . **Best for users wanting a genuinely self-hosted, self-improving agent** that works across their messaging apps and gets smarter the longer it runs.

- **[Dify](https://github.com/langgenius/dify)**  
  **The most-starred open-source LLM application development platform** — 158,000+ GitHub stars . **Visual workflow builder for agents and LLM apps** with RAG pipelines, knowledge-base management, and plugin marketplace . **Self-hostable via Docker Compose** with five application types (Chatbot, Agent, Text Generator, Chatflow, Workflow) . **Best for teams wanting a visual platform** to build and deploy personal agents with retrieval over private data.

- **[OpenAcme](https://github.com/sandydasari/openacme)**  
  **Role-specialized agents that self-organize** — MIT licensed, TypeScript. **Agents with distinct roles coordinate autonomously** rather than operating as a single monolithic assistant . **Best for users experimenting with multi-agent personal setups** where different agents handle different life domains.

- **[Hivekeep](https://github.com/MarlBurroW/hivekeep)**  
  **Self-hosted team of persistent personal agents** — MIT licensed, TypeScript. **Multiple agents with persistent state working together** for a single user . **Best for users wanting a self-hosted agent team** rather than a single assistant.

### Additional Strong Open-Source Options

- **Atomic Agent** — Local-first CLI agent for open-weight models. 3,230 GitHub stars, MIT licensed .
- **Agent Teams** — Desktop app running coding-agent teams across CLIs. 2,254 stars, AGPL-3.0 .
- **SwarmClaw** — Self-hosted runtime for multi-agent CLI work. 689 stars, MIT licensed .
- **OpenHermit** — Deploys agent fleets as long-running services. 87 stars, MIT licensed .
- **5dive** — Run a company of named agents on your own server. 68 stars, MIT licensed .

**Frameworks for building custom systems**: Combine **Hermes Agent** for a self-hosted, self-improving personal agent with persistent memory and 20+ messaging integrations, **Dify** for visual agent building with RAG over private data, **MultiOn** for browser automation tasks, and **Personal AI** or **Limitless** if you prefer managed memory services — to build a personal AI stack tailored to your privacy requirements, task scope, and tolerance for operational overhead.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Personal AI agents differ significantly in memory architecture, execution scope, and data ownership. **Hermes Agent is the leading open-source option** with a built-in learning loop, 24M+ downloads, and $90M in backing — but it requires running your own infrastructure (VPS, Docker, or serverless) and managing credentials . **Lindy drafts messages for approval** rather than sending autonomously . **MultiOn's local mode** keeps session data on your machine via a browser extension . **Personal AI holds SOC 2 and HIPAA certifications** with patented memory technology . **Rewind's Mac app is shutting down** following Meta's acquisition of Limitless — the product direction has shifted to wearable capture . **Self-hosted agents accumulate personal context over time** — losing that memory store or exposing its credentials has real privacy consequences.
- Self-hosted open-source solutions require proper backup of memory databases, credential vault security, and monitoring of agent actions across connected platforms.

---

**Made for individuals building personal AI agents that know them, remember them, and act for them.**
Let's make personal AI agents more open, self-hosted, and genuinely personal.
