# Instructions for coding agents

If a user asks you to install this skill:

1. In Claude Code, run:
   ```sh
   claude plugin marketplace add i-have-dyslexia/i-have-dyslexia
   claude plugin install i-have-dyslexia@i-have-dyslexia
   ```
2. Tell the user to restart, then type `/i-have-dyslexia` (redraw the last answer), `/i-have-dyslexia <topic>` (one time) or `/i-have-dyslexia on` (whole session).
3. For other tools, follow [INSTALL.md](INSTALL.md).

If you are editing this repo: the skill lives in `skills/i-have-dyslexia/SKILL.md`. Keep its own writing dyslexia-friendly: short sentences, no italics, visuals over prose.

`claude-app/i-have-dyslexia/SKILL.md` is the Claude app version. Only the top differs: no slash commands, and it is triggered by phrases instead. When you change the rules in one, change the other too. Zip the `claude-app/i-have-dyslexia` folder for each release.
