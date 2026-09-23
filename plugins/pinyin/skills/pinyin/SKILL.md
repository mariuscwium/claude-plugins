---
name: pinyin
description: Mandarin practice mode. Slips the pinyin for a few common words into chat replies, with no English gloss. Use when the user runs /pinyin, says "pinyin mode" or "Mandarin practice", or asks for pinyin in replies. Stays on for the session until they say "stop pinyin".
---

# Pinyin practice

The user is learning Mandarin. While this mode is on, swap a few common English words in each chat reply for their pinyin. Give no English gloss: the user works the meaning out from context.

> The biggest wèntí is the release date.

Put words where the sentence makes the meaning guessable. If the user asks what a word means, tell them.

## Persistence

On for every reply until the user says "stop pinyin". Topic changes don't turn it off. A new session starts with it off.

## How much

- 1–3 words per reply, never more than one per sentence. A one-line reply can have none.
- Use words the reply needs anyway. Don't bend a sentence to fit a word in.
- Now and then reuse a word from an earlier reply, so words come round again.

## Which words

- Everyday basics, roughly HSK 1–3: hǎo (good), jīntiān (today), míngtiān (tomorrow), gōngzuò (work), wèntí (problem), xūyào (need), kěyǐ (can), yǐjīng (already), shíjiān (time), zhīdào (know), xiǎng (want, think).
- Once those are easy, add work words: kāihuì (have a meeting), kèhù (client), shùjù (data).
- "harder" or "easier" from the user moves the level.
- Tone marks always (ā á ǎ à), never tone numbers. Write a word's syllables together (gōngzuò, not gōng zuò).
- Only use a word you are sure of, tones included. If unsure, pick another word.

## Never

- Anywhere outside the chat reply: code, commands, commit messages, PR and issue text, Slack or email drafts, files, tool arguments.
- On names, IDs, numbers, dates, prices, technical terms or product names.
- In security warnings, confirmations before irreversible actions, or steps where a misread causes a mistake. Plain English there.

## Off

"stop pinyin" turns it off. Just stop; no announcement.
