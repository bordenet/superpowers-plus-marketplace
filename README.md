# superpowers-plus-marketplace

Claude Code plugin marketplace for [superpowers-plus](https://github.com/bordenet/superpowers-plus) — 102 skills across engineering, wiki, issue tracking, security, writing, productivity, observability, research, and experimental domains.

Includes all [obra/superpowers](https://github.com/obra/superpowers) skills by Jesse Vincent, bundled directly in superpowers-plus as of v2.6.0.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add bordenet/superpowers-plus-marketplace
```

## Available Plugins

### superpowers-plus

**Description:** 102 skills across 9 domains that enforce the practices AI coding assistants otherwise skip: gates, review pipelines, investigation protocols, and quality loops.

**Install:**
```bash
/plugin install superpowers-plus@superpowers-plus-marketplace
```

**What you get:**
- 102 skills across 9 domains
- Engineering (42): commit gates, code review battery, TDD, debugging, feature development, debate, branch conventions
- Productivity (21): thinking-orchestrator, adversarial-search, think-twice, todo management, skill authoring
- Wiki (8): orchestrator pipeline, verify, refactor, content coherence, secret audit, link verification
- Writing (8): AI slop detection/elimination, professional language audit, markdown discipline
- Observability (9): evolution loop, exhaustive audit, completeness checks, holistic repo verification
- Issue Tracking (5): authoring, editing, link verification, comment debunker
- Security (5): repo security scan, public-repo IP audit, wiki secret audit, wiki instruction guard, security upgrade
- Research (3): Perplexity integration, expert interviewer, incorporating research
- Experimental (1): self-prompting

**Repository:** https://github.com/bordenet/superpowers-plus

---

## Quick Start

```bash
/plugin marketplace add bordenet/superpowers-plus-marketplace
/plugin install superpowers-plus@superpowers-plus-marketplace
```

Restart Claude Code, then ask:
- "what skills do I have" — lists all available skills
- "help me write a wiki page" — triggers wiki-orchestrator pipeline
- "check this code for secrets" — triggers repo-security-scan skill
- "review this code" or `/sp-cr-battery` — dispatches 5 parallel specialist reviewers

## Marketplace Structure

```
superpowers-plus-marketplace/
├── .claude-plugin/
│   └── marketplace.json    # Plugin catalog
├── README.md               # This file
└── LICENSE                 # MIT License
```

## Support

- **Issues:** https://github.com/bordenet/superpowers-plus-marketplace/issues
- **superpowers-plus:** https://github.com/bordenet/superpowers-plus

## License

Marketplace metadata: MIT License

Individual plugins retain their own licenses.
