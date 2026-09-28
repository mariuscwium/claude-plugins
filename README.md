# claude-plugins

Claude Code plugins by Marius Wium.

## Install

In Claude Code:

```
/plugin marketplace add mariuscwium/claude-plugins
/plugin install pinyin@mariuscwium
```

Or with the [skills CLI](https://skills.sh), which also works for other agents:

```
npx skills add mariuscwium/claude-plugins
```

## Plugins

### pinyin

Mandarin practice. While it's on, Claude works common conversational phrases, in pinyin, into each reply, with no English gloss, so you read them in context:

> Hǎo de. The build passed and the deploy is queued; I'll confirm once it's live. Míngtiān jiàn.

- Say "pinyin mode" to turn it on, or run `/pinyin:pinyin` (`/pinyin` if you installed with the skills CLI). Say "stop pinyin" to turn it off.
- It starts at level 2, about 20% of each reply: phrases from New Practical Chinese Reader Book 1, Lessons 1–6, plus everyday extras. Say "harder" or "easier" to move between levels (about 10%, 20% and 30%).
- Ask what a phrase means and Claude tells you.
- It never puts pinyin in code, commands, commits, files, names, numbers or warnings.
