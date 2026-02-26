# Meyer For Hire Consulting Marketplace

AI agents and skills for code quality, refactoring, and engineering excellence.

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add Meyer-For-Hire/m4h-marketplace
```

Or from the command line:

```bash
claude plugin marketplace add Meyer-For-Hire/m4h-marketplace
```

## Available Plugins

### agents4hire

**Description:** Specialized AI agents for code quality, refactoring, and engineering excellence

**Install:**
```
/plugin install agents4hire@m4h-marketplace
```

**What you get:**
- `well-factored-code-auditor` skill — systematic codebase factoring audit with graded scorecard
- Grading rubric across seven principles (Clarity, SRP, DRY, YAGNI, Testability, Test Adequacy, Consistency)
- Scorecard template for consistent, structured output
- Integration with [Superpowers](https://github.com/obra/superpowers) for structured planning workflows

**Repository:** https://github.com/Meyer-For-Hire/agents4hire

## Marketplace Structure

```
m4h-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # Plugin catalog
└── README.md                  # This file
```

## License

Marketplace metadata: MIT License

Individual plugins: See respective plugin licenses
