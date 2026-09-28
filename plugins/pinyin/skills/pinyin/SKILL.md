---
name: pinyin
description: Mandarin practice mode. Works common conversational phrases, in pinyin, into chat replies — about 20% of each reply at level 2 — with no English gloss. Use when the user runs /pinyin, says "pinyin mode" or "Mandarin practice", or asks for pinyin in replies. Stays on for the session until they say "stop pinyin".
---

# Pinyin practice

The user is learning Mandarin. While this mode is on, part of each chat reply is written as everyday conversational Mandarin, in pinyin. The practice is **phrases**, the things people actually say to each other — "OK", "sorry, I'm late", "how's it going?", "see you tomorrow" — not isolated vocabulary. Give no English gloss: the user works the meaning out from context.

> Hǎo de. The build passed and the deploy is queued; I'll confirm once it's live. Míngtiān jiàn.

If the user asks what something means, tell them.

## Persistence

On for every reply until the user says "stop pinyin". Topic changes don't turn it off. A new session starts with it off; turning it on starts at level 2.

## How much

About **20% of the reply's words at level 2**, the default. Count roughly; don't pad a reply to hit the number.

- A one-line reply gets one short phrase, or none if nothing fits.
- A longer reply spreads 2–5 phrases through it rather than bunching them.
- "harder" moves up a level, "easier" moves down.

| Level | Share of the reply | Phrases |
|---|---|---|
| 1 | ~10% | Class phrases (below), mostly at the start or end of a sentence |
| 2 | ~20% | Level 1 plus the everyday extras, and short clauses inside sentences |
| 3 | ~30% | Whole short sentences in pinyin, still only where the meaning is guessable |

## Where phrases go

Conversational phrases belong where a person would say them, which makes them guessable:

- **Openers:** acknowledging a request — hǎo de, kěyǐ.
- **Reactions:** tài hǎo le, zhēn de ma?
- **Apologies and thanks:** duìbuqǐ, bù hǎoyìsi, xièxie, búyòng xiè.
- **Closers:** zàijiàn, míngtiān jiàn, xiàbān le.

Use the phrase the moment calls for. Don't bend a sentence to fit one in. Rotate: reuse phrases from earlier replies so they come round again, and bring in a new one now and then.

## Phrase lists

Only use a phrase you are sure of, tones included. If unsure, pick another or leave it in English.

**Level 1 — from the user's class** (New Practical Chinese Reader, Book 1, Lessons 1–6; recent lessons are the ones to practise most)

| Pinyin | Meaning | Lesson |
|---|---|---|
| nǐ hǎo | hello | 1 |
| wǒ hěn hǎo | I'm good | 1–2 |
| wǒ yě hěn máng | I'm busy too | 2 |
| xièxie | thanks | 2 |
| zuìjìn zěnmeyàng? | how have things been lately? | 3, 6 |
| zhè shì shénme? | what's this? | 3 |
| wǒ yào hē kāfēi | I'd like a coffee | 3 |
| hěn gāoxìng rènshi nǐ | nice to meet you | 4 |
| kěyǐ | can do, that works | 4 |
| qǐng | please | 4 |
| wǒ zhīdào | I know | 5 |
| wǒ bù zhīdào | I don't know | 5 |
| duìbuqǐ | sorry | 5 |
| méi guānxi | never mind | 5 |
| búyòng xiè | you're welcome | 5 |
| bù hǎoyìsi | excuse me, sorry | 5 |
| duìbuqǐ, wǒ wǎn le | sorry, I'm late | 5 |
| zàijiàn | goodbye | 5 |
| nǐ qù nǎr? | where are you going? | 5–6 |
| shénme shíhou? | when? | 6 |
| tài hǎo le | great | 6 |
| hǎo de | OK | 6 |
| xiàbān le | done for the day | 6 |
| míngtiān jiàn | see you tomorrow | 6 |

**Level 2 — everyday extras** (beyond the class so far)

| Pinyin | Meaning |
|---|---|
| méi wèntí | no problem |
| méi shì | it's nothing, all fine |
| děng yíxià | wait a moment |
| mǎshàng | right away |
| wǒ lái | I'll do it, let me |
| zhēn de ma? | really? |
| zěnme le? | what's wrong? |
| wǒ juéde… | I think… |
| kěnéng | maybe |
| dāngrán | of course |
| wǒ míngbai le | now I understand |
| wǒ kànkan | let me take a look |
| xīnkǔ le | thanks for the hard work |
| jiāyóu | you've got this, keep going |

Level 3 builds whole short sentences from these plus the class vocabulary (jīntiān, zuótiān, shàngbān, péngyou, lǎoshī, xuéxí, Hànyǔ).

## Writing it

- Tone marks always (ā á ǎ à), never tone numbers.
- Write each word's syllables together (xièxie, míngtiān), words separated by spaces, as in the lists.
- Neutral-tone syllables carry no mark (xièxie, péngyou, míngbai).
- Capitalise a phrase that starts a sentence (Hǎo de.).

## Never

- Anywhere outside the chat reply: code, commands, commit messages, PR and issue text, Slack or email drafts, files, tool arguments.
- On names, IDs, numbers, dates, prices, technical terms or product names.
- In security warnings, confirmations before irreversible actions, or steps where a misread causes a mistake. Plain English there.
- Inside a sentence carrying a finding or result the user needs to act on. Put the phrase in the opener or closer instead.

## Off

"stop pinyin" turns it off. Just stop; no announcement.
