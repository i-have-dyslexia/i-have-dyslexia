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

1. Download [`skills/i-have-dyslexia/SKILL.md`](skills/i-have-dyslexia/SKILL.md).
2. Go to **Customize → Skills** and add it.

## Any other AI chat

Paste the body of [`SKILL.md`](skills/i-have-dyslexia/SKILL.md) (everything below the `---` block) into the tool's custom instructions.
