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

Mandarin practice. While it's on, Claude swaps a few common words in each reply for their pinyin, with no English gloss, so you read them in context:

> The biggest wèntí is the release date.

- Say "pinyin mode" to turn it on, or run `/pinyin:pinyin` (`/pinyin` if you installed with the skills CLI). Say "stop pinyin" to turn it off.
- It starts with everyday basics. Say "harder" or "easier" to change the level.
- Ask what a word means and Claude tells you.
- It never puts pinyin in code, commands, commits, files, names, numbers or warnings.
