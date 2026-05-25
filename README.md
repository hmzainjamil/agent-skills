# agent-skills

> **Agent skills library — production skill implementations for Claude Code agents**

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat)
![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-FF6B35?style=flat)
![Stars](https://img.shields.io/github/stars/hmzainjamil/agent-skills?style=flat)
![Last Commit](https://img.shields.io/github/last-commit/hmzainjamil/agent-skills?style=flat)

---

## CONCEPTS

| Concept | Description |
|---|---|
| **Agent** | Core agent capability for agent-skills workflows |
| **Skill** | Core skill capability for agent-skills workflows |
| **Claude** | Core claude capability for agent-skills workflows |
| **Library** | Core library capability for agent-skills workflows |
| **Tool** | Core tool capability for agent-skills workflows |
| **Automation** | Core automation capability for agent-skills workflows |
| **Workflow** | Core workflow capability for agent-skills workflows |
| **Production** | Core production capability for agent-skills workflows |

---

## 🔥 Hot Commands

```bash
# Activate skill
claude --skill agent-skills 'your task'

# Quick workflow
claude 'agent automation task'

# Get capabilities
claude 'what can agent-skills do?'
```

## ■ tip
> Mention **agent** or **skill** in your prompt to auto-activate this skill.

---

## ☠️ STARTUPS / BUSINESSES

- **Agencies**: automate agent workflows for clients at scale
- **Founders**: ship skill features 10x faster with Claude
- **Freelancers**: deliver claude work with AI-assisted precision

---

## Features

- Agent automation and orchestration
- Skill automation and orchestration
- Claude automation and orchestration
- Library automation and orchestration
- Tool automation and orchestration
- Automation automation and orchestration

---

## Installation

```bash
git clone https://github.com/hmzainjamil/agent-skills.git
cd agent-skills
```

---

## Usage

```bash
# In Claude Code
/agent-skills
claude 'agent task here'
```

---

## Configuration

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Primary API key for service access | Required |
| `MODEL` | AI model to use | claude-3-5-sonnet |
| `DEBUG` | Enable verbose debug output | false |
| `MAX_TOKENS` | Max token budget per request | 8192 |
| `TIMEOUT` | Request timeout in seconds | 30 |
| `LOG_LEVEL` | Logging verbosity | info |

---

## Architecture

```
agent-skills/
├── README.md           # This file
├── SKILL.md            # Claude Code skill definition
├── scripts/            # Automation and utility scripts
├── templates/          # Output and prompt templates
├── examples/           # Usage examples and demos
├── tests/              # Unit and integration tests
└── docs/               # Extended documentation
    ├── setup.md        # Setup guide
    ├── api.md          # API reference
    └── faq.md          # Frequently asked questions
```

---

## Examples

### Basic Usage

```bash
# Activate in Claude Code
claude --skill agent-skills "your task here"

# With options
claude --skill agent-skills --verbose "detailed task"
```

### Advanced Workflow

```bash
# Chain with other skills
claude --skill agent-skills "step 1" | claude --skill summarize

# Batch processing
for item in list; do
  claude --skill agent-skills "process $item"
done
```

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Auth fails | Invalid/expired API key | Re-export key in shell profile |
| Timeout error | Network latency or large payload | Increase TIMEOUT value |
| Empty output | Prompt too vague | Add more context to request |
| Rate limit hit | Too many requests | Add delay between calls |
| Model error | Unsupported model version | Update MODEL variable |
| Import error | Missing dependency | Run pip install -r requirements.txt |

---

## Comparison

| Feature | This Skill | Alternative A | Alternative B |
|---|---|---|---|
| Claude Code native | ✅ | ❌ | ✅ |
| Auto-activation | ✅ | ✅ | ❌ |
| Free to use | ✅ | ❌ | ✅ |
| Production ready | ✅ | ✅ | ❌ |
| Active maintenance | ✅ | ❌ | ❌ |

---

## Contributing

1. Fork this repo
2. Create feature branch: `git checkout -b feat/your-feature`
3. Commit changes: `git commit -m 'feat: add feature'`
4. Push: `git push origin feat/your-feature`
5. Open PR

---

## Changelog

| Version | Changes |
|---|---|
| v2.0 | Major refactor, Claude 4 support |
| v1.5 | Added auto-activation keywords |
| v1.0 | Initial release |

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/agent-skills&type=Date)](https://star-history.com/#hmzainjamil/agent-skills&Date)

---

## 📜 License

MIT — free to use, modify, and distribute.

---

Made with ❤️ by [@hmzainjamil](https://github.com/hmzainjamil)
