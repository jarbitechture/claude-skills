# Claude Code Skills Arsenal

> **1,253 skills** for [Claude Code](https://claude.com/claude-code) — the largest personal collection of automation, development, reasoning, security, infrastructure, and creative skills for the Claude CLI agent.

```
skills/
├── 910 SaaS & API automations
├── 97  Azure SDK & cloud skills
├── 27  routers & orchestrators
├── 24  Google service integrations
├── 16  agent & multi-agent frameworks
├── 14  Zoho suite integrations
├── 11  reasoning & cognitive tools
├── 8   Hugging Face ML skills
├── 8   Obsidian knowledge management
├── 8   security & vulnerability scanning
├── 7   file format processors
├── 5   deployment targets
└── 100+ development, architecture, research & creative skills
```

---

## What Are Claude Code Skills?

Skills are markdown-based prompt modules that extend Claude Code's capabilities. Drop a skill folder into `~/.claude/skills/` and Claude gains specialized knowledge — from automating Slack workflows to running Semgrep scans to generating podcast audio.

Each skill directory contains:

| File | Purpose |
|------|---------|
| `SKILL.md` | Core instructions, workflows, and trigger conditions |
| `CLAUDE.md` | Optional project-level overrides for Claude Code |
| `references/` | Supporting docs, examples, API schemas |
| `scripts/` | Executable helpers (Python, Node, shell) |

---

## Skill Categories

### SaaS & API Automations (910)

End-to-end integrations via [Composio/Rube MCP](https://composio.dev) — each skill knows the API surface, handles auth flows, and provides ready-to-use workflows.

<details>
<summary>Highlights (click to expand)</summary>

| Skill | What It Does |
|-------|-------------|
| `slack-automation` | Messaging, channels, search, reactions, threads |
| `notion-automation` | Databases, pages, blocks, search, permissions |
| `github-automation` | Issues, PRs, repos, actions, webhooks |
| `salesforce-automation` | CRM records, SOQL, bulk operations |
| `hubspot-automation` | Contacts, deals, pipelines, email sequences |
| `stripe-automation` | Payments, subscriptions, invoices, refunds |
| `shopify-automation` | Products, orders, inventory, fulfillment |
| `airtable-automation` | Bases, tables, records, views, formulas |
| `jira-automation` | Issues, sprints, boards, JQL queries |
| `discord-automation` | Messages, channels, roles, server management |
| `twilio-automation` | SMS, voice, WhatsApp via Telnyx/Twilio |
| `mailchimp-automation` | Campaigns, audiences, templates, analytics |
| `zoho-crm-automation` | Leads, contacts, deals, custom modules |

...and 897 more covering every major SaaS platform.

</details>

### Azure SDK & Cloud (97)

Deep Azure integration skills across languages (Python, Java, .NET, Rust, TypeScript):

- **AI Services** — OpenAI, Vision, Content Safety, Document Intelligence, Translation, Speech, Agents
- **Data** — Cosmos DB, Storage Blobs/Queues/Files, Data Tables, Data Lake
- **Messaging** — Event Hubs, Event Grid, Service Bus, Web PubSub
- **Security** — Key Vault (keys, secrets, certificates), Identity
- **Monitoring** — OpenTelemetry exporters, Monitor Query, Ingestion
- **Management** — API Center, API Management, Bot Service, Fabric, Playwright Testing

### Reasoning & Cognitive Tools (11)

Advanced thinking frameworks that enhance Claude's problem-solving:

| Skill | Approach |
|-------|----------|
| `think` | Non-linear reasoning + mental models + literate programming |
| `reason` | Structured step-by-step logical analysis |
| `dialectical` | Thesis-antithesis-synthesis reasoning |
| `critique` | Systematic evaluation and counterargument generation |
| `hierarchical-reasoning` | Multi-level decomposition for complex problems |
| `thought-based-reasoning` | Chain-of-thought with explicit reasoning traces |
| `constraints` | Constraint satisfaction for bounded optimization |
| `textbook-grounding` | Academic source-based verification |
| `grounding-router` | Routes to the right grounding strategy |

### Routers & Orchestrators (27)

Meta-skills that route to the right specialist based on task context:

```
meta-router          → Master router across all categories
├── agents-router    → Agent framework selection
├── analysis-router  → Data/code analysis dispatch
├── build-router     → Build system selection
├── cli-router       → CLI tool selection
├── commands-router  → Command pattern matching
├── context-router   → Context strategy selection
├── data-router      → Data pipeline routing
├── development-router → Dev workflow dispatch
├── documentation-router → Doc format/tool selection
├── infrastructure-router → IaC/cloud routing
├── reasoning-router → Thinking strategy selection
├── research-router  → Research method dispatch
├── skills-router    → Skill discovery & suggestion
├── think-router     → Cognitive approach selection
└── tools-router     → Tool selection optimization
```

### Security & Vulnerability Scanning (8)

| Skill | Capability |
|-------|-----------|
| `vulnerability-scanning/semgrep` | SAST with custom rules and autofix |
| `vulnerability-scanning/codeql` | Deep semantic code analysis |
| `vulnerability-scanning/variant-analysis` | Finding vulnerability variants across codebases |
| `vulnerability-scanning/insecure-defaults` | Detecting insecure default configurations |
| `security-threat-model` | STRIDE-based threat modeling from code |
| `security-best-practices` | OWASP Top 10, secure coding patterns |
| `security-ownership-map` | Asset ownership and responsibility mapping |
| `osgrep` | OS-level security grep patterns |

### Agent & Multi-Agent Frameworks (16)

| Skill | Framework |
|-------|----------|
| `multi-agent-patterns` | Architecture patterns for multi-agent systems |
| `multi-agent-coordination` | Inter-agent communication protocols |
| `agents-v2-py` | Python Agent SDK v2 |
| `agent-framework-azure-ai-py` | Azure AI Agent Service |
| `agent-evaluation` | Agent quality assessment methodologies |
| `agent-prompt-evolution` | Iterative prompt improvement for agents |
| `agent-observability` | Monitoring and debugging agent systems |
| `maker-framework` | MAKER — consensus-voting multi-agent reasoning |
| `m365-agents-dotnet` / `m365-agents-py` | Microsoft 365 Agents SDK |
| `hosted-agents-v2-py` | Cloud-hosted agent deployment |
| `copilot-sdk` | Microsoft Copilot SDK integration |

### Development & Code Quality (20+)

| Skill | Purpose |
|-------|---------|
| `software-architecture` | System design and architecture guidance |
| `architecture-decision-records` | ADR creation (Michael Nygard template) |
| `code-refactor` / `refactor` | Structured refactoring workflows |
| `test-generation` | Test infrastructure setup (Vitest, xUnit, pytest) |
| `test-driven-development` | TDD red-green-refactor cycle |
| `property-based-testing` | PBT patterns (Trail of Bits) |
| `testing-strategy` | Test pyramid and coverage planning |
| `ci-cd-optimization` | Pipeline performance tuning |
| `dependency-health` | Dependency audit and update strategies |
| `technical-debt-management` | Tech debt tracking and prioritization |
| `baseline-quality-assessment` | Codebase health scoring |
| `database-optimizer` | SQL optimization (PostgreSQL, MySQL, SQLite, SQL Server) |
| `api-design` | REST/GraphQL API design patterns |

### Infrastructure & DevOps (10+)

| Skill | Scope |
|-------|-------|
| `iac-terraform` | Terraform/OpenTofu modules, testing, CI/CD |
| `k8s-troubleshooter` | Kubernetes incident response & diagnostics |
| `observability-instrumentation` | Logs, metrics, traces (OpenTelemetry, Prometheus, slog) |
| `cloudflare-deploy` | Cloudflare Workers/Pages deployment |
| `vercel-deploy` | Vercel project deployment |
| `netlify-deploy` | Netlify site deployment |
| `render-deploy` | Render service deployment |

### AI & ML Tools (15+)

| Skill | Capability |
|-------|-----------|
| `hugging-face-model-trainer` | Fine-tuning models on HF |
| `hugging-face-evaluation` | Model benchmarking and eval |
| `hugging-face-datasets` | Dataset creation and management |
| `hugging-face-tool-builder` | Building HF Spaces/tools |
| `hugging-face-trackio` | Experiment tracking |
| `dspy` / `dspy-code` | Stanford's DSPy framework for LM programming |
| `prompt-engineering` | Production prompt design and optimization |
| `context-engineering` | Context window optimization for agents |
| `gpt-researcher` | Autonomous web research agent |
| `fabric` | 242+ Fabric CLI patterns for content processing |

### Obsidian Knowledge Management (8)

| Skill | Function |
|-------|---------|
| `obsidian` | Core Obsidian vault workflows |
| `obsidian-markdown` | Advanced markdown formatting |
| `obsidian-batch` | Bulk operations across vaults |
| `obsidian-data-importer` | External data → Obsidian notes |
| `obsidian-developer` | Plugin and theme development |
| `obsidian-devtools` | Developer tooling for Obsidian |
| `obsidian-bases` | Database-like views in Obsidian |
| `obsidian-process` | Process documentation in vaults |

### Creative & Media (10+)

| Skill | Output |
|-------|--------|
| `suno-song` | Suno V5 song generation prompts |
| `podcast-generation` | AI podcast audio via Azure OpenAI Realtime |
| `imagegen` | Image generation/editing via OpenAI API |
| `video-downloader` | YouTube/platform video downloads |
| `youtube-transcript` | Video transcript extraction |
| `canvas-design` | Visual design on canvas |
| `algorithmic-art` | Generative art patterns |
| `speech` | Text-to-speech workflows |
| `transcribe` | Audio-to-text transcription |

### File Format Processors (7)

Handle documents natively within Claude Code:

`pdf` · `docx` · `pptx` · `xlsx` · `csv-analysis` · `spreadsheet` · `json-canvas`

### Notion Workflows (5)

| Skill | Use Case |
|-------|---------|
| `notion-automation` | Core Notion API operations |
| `notion-knowledge-capture` | Automated knowledge base building |
| `notion-meeting-intelligence` | Meeting notes → structured Notion pages |
| `notion-research-documentation` | Research → organized Notion docs |
| `notion-spec-to-implementation` | Notion specs → code implementation |

### Google Integrations (24)

Full coverage: `gmail` · `google-drive` · `google-calendar` · `google-maps` · `google-search-console` · `google-classroom` · `google-admin` · `google-docs` · `google-sheets` · `google-slides` · `google-tasks` · `google-meet` · `google-photos` · `google-bigquery` · `google-analytics` · `google-ads` · `google-cloud-vision` · and more.

---

## Installation

### Single Skill

```bash
# Copy one skill into your Claude Code skills directory
cp -r skills/slack-automation ~/.claude/skills/
```

### All Skills

```bash
# Clone and symlink the entire collection
git clone https://github.com/jarbitechture/claude-skills.git ~/claude-skills
ln -s ~/claude-skills/skills/* ~/.claude/skills/
```

### Cherry-Pick by Category

```bash
# Example: install all security skills
for skill in vulnerability-scanning security-threat-model security-best-practices security-ownership-map osgrep; do
  cp -r skills/$skill ~/.claude/skills/
done
```

---

## How Skills Work

```
User: "Send a message to #general in Slack saying deployment is done"

Claude Code:
  1. Matches intent → loads slack-automation skill
  2. Skill provides: API surface, auth flow, tool schemas
  3. Claude executes: RUBE_SEARCH_TOOLS → find send_message → call it
  4. Result: Message sent to #general ✓
```

Skills trigger automatically based on context, or can be invoked explicitly via `/skill-name` in Claude Code.

---

## Stats

| Metric | Count |
|--------|-------|
| Total skills | 1,253 |
| Total files | 5,053 |
| Skills with reference docs | 187 |
| Skills with CLAUDE.md | 31 |
| Lines of instruction | 1.16M |

---

## Sources & Attribution

Skills sourced, adapted, and extended from open-source contributors:

| Source | Skills |
|--------|--------|
| [antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill) | Terraform/OpenTofu |
| [trailofbits/skills](https://github.com/trailofbits/skills) | Security scanning, PBT |
| [ahmedasmar/devops-claude-skills](https://github.com/ahmedasmar/devops-claude-skills) | DevOps, K8s |
| [andronics/claude-plugin-adr](https://github.com/andronics/claude-plugin-adr) | Architecture Decision Records |
| [levnikolaevich/claude-code-skills](https://github.com/levnikolaevich/claude-code-skills) | Development tools |
| [QuestForTech-Investments/claude-code-skills](https://github.com/QuestForTech-Investments/claude-code-skills) | Automation skills |
| [Composio](https://composio.dev) | SaaS integration toolkits |
| Community & custom | Reasoning, orchestration, creative |

---

## License

This is a personal collection. Individual skills may carry their own licenses from upstream sources. Check each skill's directory for attribution details.
