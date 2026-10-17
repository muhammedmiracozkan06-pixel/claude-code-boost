# claude-code-boost

A Claude skill that makes Claude do **exactly what you ask** while using **as few tokens as possible**.

Claude, tam istediğini yapsın ve gereksiz uzatmasın diye yazılmış bir skill.

## What it does / 

- Follows instructions literally, no scope creep
- Answer first: no filler, no restating, no unsolicited extras
- Diff-only code edits, minimal tool calls, no repeated content
- Replies in your language
- Your explicit requests ("detailed", "step by step") always override brevity

## Install

**Claude Code (global):**
```bash
git clone https://github.com/muhammedmiracozkan06-pixel/claude-code-boost ~/.claude/skills/claude-code-boost
```

**Claude Code (project only):**
```bash
git clone https://github.com/muhammedmiracozkan06-pixel/claude-code-boost .claude/skills/claude-code-boost
```

**Claude.ai:** Download the repo as ZIP → Settings → Capabilities → Skills → upload.

## Structure

```
claude-code-boost/
├── SKILL.md   # the skill (frontmatter + instructions)
└── README.md
```

