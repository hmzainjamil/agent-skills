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
| **Skill** | Reusable capability module for Claude Code |
| **Auto-Activate** | Intent-based keyword trigger system |
| **SKILL.md** | Standard skill definition format |
| **Index** | index.json manifest for skill discovery |
| **Deactivate** | Automatic skill unloading after task |
| **Compose** | Chain skills for complex workflows |
| **Test** | Skill unit testing framework |
| **Publish** | Share skills to community registry |

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
- **Founders**: ship skill features 10x faster
- **Freelancers**: deliver claude work with AI precision

---

## Features

- Agent automation
- Skill automation
- Claude automation
- Library automation
- Tool automation
- Automation automation

---

## Installation

```bash
git clone https://github.com/hmzainjamil/agent-skills.git
cd agent-skills
```

---

## Usage

```bash
# Activate skill in Claude Code
claude --skill agent-skills "your task here"

# Quick workflow
claude "agent automation task"

# Get help
claude "what can agent-skills do?"
```

---

## Configuration

| Variable | Description | Default |
|---|---|---|
| `API_KEY` | Primary API key | Required |
| `MODEL` | AI model to use | claude-3-5-sonnet |
| `DEBUG` | Enable verbose debug | false |
| `MAX_TOKENS` | Max token budget | 8192 |
| `TIMEOUT` | Request timeout (sec) | 30 |
| `LOG_LEVEL` | Logging verbosity | info |

---

## Architecture

```
agent-skills/
├── README.md           # Documentation
├── SKILL.md            # Claude Code skill definition
├── scripts/            # Automation scripts
├── templates/          # Output templates
├── examples/           # Usage examples
└── docs/               # Extended documentation
```

---

## Examples

### Basic

```bash
# Simple task
claude --skill agent-skills "agent task"

# Verbose
claude --skill agent-skills --verbose "detailed skill task"
```

### Advanced Pipeline

```bash
# Chain skills
claude --skill agent-skills "step 1" | claude --skill summarize

# Batch run
for item in $(cat list.txt); do
  claude --skill agent-skills "process $item"
done
```

---

## Troubleshooting

| Issue | Cause | Fix |
|---|---|---|
| Auth fails | Invalid API key | Re-export key in shell profile |
| Timeout | Network or large payload | Increase TIMEOUT value |
| Empty output | Prompt too vague | Add more context |
| Rate limit | Too many requests | Add delay between calls |
| Model error | Unsupported version | Update MODEL variable |
| Import error | Missing dependency | Run pip install -r requirements.txt |

---

## Comparison

| Feature | This Skill | Alt A | Alt B |
|---|---|---|---|
| Claude Code native | ✅ | ❌ | ✅ |
| Auto-activation | ✅ | ✅ | ❌ |
| Free to use | ✅ | ❌ | ✅ |
| Production ready | ✅ | ✅ | ❌ |
| Active maintenance | ✅ | ❌ | ❌ |

---

## Changelog

| Version | Changes |
|---|---|
| v2.0 | Claude 4 support, auto-activation |
| v1.5 | Added keyword triggers |
| v1.0 | Initial release |

---

## Contributing

1. Fork → feature branch → commit → PR
2. Follow conventional commits: `feat:`, `fix:`, `docs:`
3. Add tests for new features

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=hmzainjamil/agent-skills&type=Date)](https://star-history.com/#hmzainjamil/agent-skills&Date)

---

## 📜 License

MIT — free to use, modify, distribute.

---

Made with ❤️ by [@hmzainjamil](https://github.com/hmzainjamil)
