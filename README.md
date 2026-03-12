# superpowers-plus-marketplace

Claude Code plugin marketplace for [superpowers-plus](https://github.com/bordenet/superpowers-plus) — extended skills for wiki editing, issue tracking, security audits, and more.

Built on [obra/superpowers](https://github.com/obra/superpowers) by Jesse Vincent.

## Installation

Add this marketplace to Claude Code:

```bash
/plugin marketplace add bordenet/superpowers-plus-marketplace
```

## Available Plugins

### superpowers (Prerequisite)

**Description:** Core skills library by Jesse Vincent — TDD, debugging, collaboration patterns, and proven techniques.

**Install:**
```bash
/plugin install superpowers@superpowers-plus-marketplace
```

**What you get:**
- 20+ battle-tested skills
- `/brainstorm`, `/write-plan`, `/execute-plan` commands
- Skills-search tool for discovery
- SessionStart context injection

**Repository:** https://github.com/obra/superpowers

---

### superpowers-plus

**Description:** Extended domain skills for wiki editing, issue tracking, security audits, TypeScript patterns, and AI text quality.

**Install:**
```bash
/plugin install superpowers-plus@superpowers-plus-marketplace
```

**What you get:**
- 40 additional skills across 9 domains
- Wiki: editing, authoring, verification, secret audit
- Issue Tracking: Linear, GitHub, Jira, ADO adapters
- Security: secret-detection, public-repo-ip-audit
- TypeScript: strict mode, complexity refactoring, Vitest patterns
- Writing: AI slop detection, professional language audit

**Repository:** https://github.com/bordenet/superpowers-plus

---

## Quick Start

Install both plugins:

```bash
/plugin marketplace add bordenet/superpowers-plus-marketplace
/plugin install superpowers@superpowers-plus-marketplace
/plugin install superpowers-plus@superpowers-plus-marketplace
```

Restart Claude Code, then ask:
- "what skills do I have" — lists all available skills
- "help me write a wiki page" — triggers wiki-authoring skill
- "check this code for secrets" — triggers secret-detection skill

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
- **obra/superpowers:** https://github.com/obra/superpowers

## License

Marketplace metadata: MIT License

Individual plugins retain their own licenses.

