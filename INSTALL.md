# Install

## Claude Code

```sh
claude plugin marketplace add i-have-dyslexia/i-have-dyslexia
claude plugin install i-have-dyslexia@i-have-dyslexia
```

Restart Claude Code, then:

- `/i-have-dyslexia` redraws the last answer as visuals.
- `/i-have-dyslexia <topic>` explains a topic visually.
- `/i-have-dyslexia on` turns it on for the whole session. Say **"stop dyslexia mode"** to turn it off.

## Claude app (claude.ai)

1. [Download the zip](https://github.com/i-have-dyslexia/i-have-dyslexia/releases/latest/download/i-have-dyslexia-claude-app.zip).
2. In Claude, go to **Settings → Capabilities → Skills** and upload it.

There are no slash commands in the app. Say these instead:

- "redraw that" or "explain that visually" redraws the last answer.
- "explain <topic> with pictures" explains a topic visually.
- "dyslexia mode" turns it on for the chat. Say **"stop dyslexia mode"** to turn it off.

## Any other AI chat

Paste the body of [`SKILL.md`](skills/i-have-dyslexia/SKILL.md) (everything below the `---` block) into the tool's custom instructions.
