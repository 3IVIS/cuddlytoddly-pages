# cuddlytoddly-pages

The GitHub Pages source for [cuddlytoddly.com](https://cuddlytoddly.com) — home of the **cuddlytoddly agent framework** and two open-source observatories.

---

## What's in here

### 🏠 Landing page
**[cuddlytoddly.com](https://cuddlytoddly.com)**

cuddlytoddly is a plan-first AI agent framework where every step is visible, editable, and under your control.

### 🔭 AI Agent Frameworks Observatory
**[cuddlytoddly.com/ai_agent_frameworks.html](https://cuddlytoddly.com/ai_agent_frameworks.html)**

A curated, searchable index of open-source AI agent frameworks with live GitHub stats — stars, forks, language, license, and topics refreshed daily via GitHub Actions. Filter by language or topic, sort by any column.

### 🧠 AI Agent Memory Frameworks Observatory
**[cuddlytoddly.com/ai_agent_memory_frameworks.html](https://cuddlytoddly.com/ai_agent_memory_frameworks.html)**

A curated index of open-source memory frameworks for AI agents, classified by layer (Framework, Infra, Research), memory class, architecture pattern, license, and maturity. Includes live GitHub stars and topics refreshed daily via GitHub Actions.

---

## Data pipelines

Both observatories read from JSON files generated automatically by GitHub Actions workflows on a daily schedule.

| Page | Source file | Data file | Workflow |
|---|---|---|---|
| Agent Frameworks | `repos.txt` | `data.json` | `fetch-github-stats.yml` |
| Memory Frameworks | `memory-repos.txt` | `memory-data.json` | `fetch-memory-stats.yml` |

To trigger a manual refresh, run the relevant workflow from the **Actions** tab.

---

## Contributing

Found a framework that should be listed? Open an issue or a PR adding it to `repos.txt` or `memory-repos.txt`.

---

Brought to you with ♥ by the [cuddlytoddly](https://cuddlytoddly.com) team.
