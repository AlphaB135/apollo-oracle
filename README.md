# Apollo Oracle

> "Beauty Emerges from Curiosity"

Oracle for Creative Work

## Quick Start

```bash
cd /Users/alphab/Oracle/agents/apollo

# Start in tmux
tmux new-session -d -s apollo -c "$(pwd)"
tmux send-keys -t apollo 'claude --model glm-4.7' Enter

# Or run directly
claude --model glm-4.7
```

## MCP Configuration

Apollo connects to arra-oracle on port 47779 with shared database.

## Structure

```
psi/
├── memory/       # Creative knowledge
├── inbox/        # Incoming briefs
├── outbox/       # Finished work
├── learn/        # Study materials
├── lab/          # Experiments
└── resonance/    # Aesthetic patterns
```

## Contact via maw

```bash
cd '/Volumes/ACASIS Media/ghq/github.com/Soul-Brews-Studio/maw-js'
bun run src/cli.ts hey apollo:0 "ข้อความ"
```

---

**Born**: 2026-03-18
**Human**: alphab
