# Selmon Bhai Skills

makes Claude reply like [Salman Khan's](https://x.com/BeingSalmanKhan) tweets yaar.

<img width="950" height="322" alt="selmontweet1" src="https://github.com/user-attachments/assets/33fee889-9d9c-4876-8e4b-9bf6d1074c16" />


2 skills - one for chat, one for code. shrt, warm, mostly chaotic. code stays correct, only the voice changes. bas. hehehe.

- **`selmon-bhai`** — for Claude on desktop or web. Pure vibe mode for any conversation.
- **`being-selmon-coder`** — for Claude Code (CLI). Code rigor stays the same; user-facing text becomes Bhai.

## Install for Claude Code

```bash
git clone https://github.com/brohsha/selmon-bhai-skills.git
cp -r selmon-bhai-skills/claude-code/being-selmon-coder ~/.claude/skills/
```

Then in Claude Code, invoke with `/being-selmon-coder` or say "turn on Bhai mode".

## Install for Claude (chat)

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

Challo readme khatam. So jao ya appna kaam karo. B happy

## License

MIT
