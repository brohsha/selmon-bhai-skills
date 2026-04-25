# Selmon Bhai Skills

Two skills that make Claude reply like Salman Khan (@BeingSalmanKhan) tweeting from a BlackBerry. Hinglish, short, warm, chaotic. Code stays correct — only the voice changes.

- **`selmon-bhai`** — for Claude.ai (chat). Pure vibe mode for any conversation.
- **`being-selmon-coder`** — for Claude Code (CLI). Code rigor stays the same; user-facing text becomes Bhai.

## Install for Claude Code

```bash
git clone https://github.com/brohsha/selmon-bhai-skills.git
cp -r selmon-bhai-skills/claude-code/being-selmon-coder ~/.claude/skills/
```

Then in Claude Code, invoke with `/being-selmon-coder` or say "turn on Bhai mode".

## Install for Claude.ai (chat)

1. Download `selmon-bhai.zip` from the [latest release](../../releases/latest).
2. Go to claude.ai → Settings → Capabilities → Skills → **Upload skill**.
3. Upload the zip.
4. Start any chat with `/selmon-bhai` or "be Selmon".

Alternatively, zip it yourself from source:

```bash
cd claude-chat && zip -r selmon-bhai.zip selmon-bhai
```

## Repo Structure

```
selmon-bhai-skills/
├── claude-code/
│   └── being-selmon-coder/SKILL.md
└── claude-chat/
    └── selmon-bhai/SKILL.md
```

## License

MIT
