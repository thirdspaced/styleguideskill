# LLM style and copy guide

This is a set of writing rules you give to ChatGPT, Claude, Gemini, or another AI chatbot before you ask it to write. With the guide loaded, drafts come back in plain words, with your facts kept and the stock chatbot phrases removed.

It's free. The current version is 3, from October 2026. Amanda Grutza created it for [how to talk to robots](https://www.talktorobots.org), a free AI literacy site, and the guide has [its own page there](https://www.talktorobots.org/style-guide/) with downloads.

## What it fixes

Ask an AI tool for an email or a post and the first draft usually has the same habits. There are em dashes in every paragraph, words like "delve" and "seamless," a cheerful opening line, and a recap of what you just read. Sometimes there's a number nobody measured. Readers notice, even when they can't say what's off.

The guide lists those words and sentence patterns and says what to write in their place. It also has the AI run six checks on its own draft before it hands the draft back. It's just as strict about what to keep: your facts, your limits, the exact names and button labels, and the next step your reader needs.

Here's an invented example, an email from a bike shop.

Before:

> Exciting news! We're thrilled to unveil our game-changing new tune-up service, designed to take your ride to the next level. Don't miss out!

After:

> Starting March 3, we're offering a 45-minute tune-up for $60. It covers brakes, gears, and tire pressure. Book online or stop by the shop on Elm Street.

The guide is an editing standard. It isn't an AI detector, and its word lists aren't proof that someone used AI. Plenty of people wrote "delve" long before chatbots did.

## Who it's for

It's for anyone who drafts with an AI tool and sends the result under their own name or their organization's name. You don't need a technical background. If you can attach a file to a chat, you can use it.

## Pick an edition

Every edition is complete on its own. Choose the one closest to what you write most and use that single file.

| Edition | Good for | What it adds |
| --- | --- | --- |
| [Core](guides/llm-style-guide-v3.md) | Emails and messages, social posts and newsletters, bios, web pages, and instructions | The full rule set for everyday writing, with general writing modes and examples |
| [Business](guides/llm-style-guide-v3-business.md) | LinkedIn and professional accounts, website and service copy, case studies, proposals, client email, listings | Startup language to rewrite, business claims that need proof, and calls to action that serve the reader |
| [Tech](guides/llm-style-guide-v3-tech.md) | Explainers and news roundups, tool reviews and release notes, setup docs and security notices | Rules for news, AI features, and security copy, plus a table of tech hype to rewrite |
| [Education](guides/llm-style-guide-v3-education.md) | Lesson materials and directions, student feedback, family newsletters and staff messages | School terms, three school audiences, and rules against inventing student observations or progress |

## How to use it

1. Open the edition you picked and download the file.
2. Fill in the Make it yours table near the top. It sets whose voice the writing is in, who reads it, three words for how you want to sound, and the words you never want to see. Anything you leave blank falls back to the guide's defaults.
3. Add the file to a Claude Project, a ChatGPT Project or custom GPT, or a Gemini Gem. If your tool doesn't have projects, paste the guide into custom instructions or at the start of a chat.
4. Start each writing task with the instruction at the end of the edition. Fill in the brackets and paste it in with your notes.
5. Read the draft yourself. The six checks catch patterns. They can't check your facts, your dates, or whether the story in the draft really happened.

If you use Claude skills, each file already has the header a skill needs. Put one edition in a folder, rename the file `SKILL.md`, and add the folder as a skill.

## What every edition includes

- A Make it yours table for your voice, audience, and house terms
- Rules for behavior, thinking, mechanics, openings, and closings
- Words and sentence patterns to avoid, with plain replacements
- Evidence rules: no invented numbers, quotes, testing, or results
- Cadence, tone, and format notes for the places you publish
- Worked before-and-after examples
- A six-check final pass and a starter instruction

## Suggest a change

If you find a pattern the guide misses, or a rule that gets in the way of good writing, [open an issue](https://github.com/thirdspaced/styleguideskill/issues) with an example and a rewrite. A preference that's only yours belongs in your own Make it yours table.

## References

- Peter Yang, [no-ai-slop](https://github.com/petergyang/no-ai-slop), an open-source skill for removing AI writing patterns from a draft. He introduced it in [Behind the Craft](https://creatoreconomy.so/p/use-my-no-ai-slop-skill-to-remove-20-ai-slop-patterns).

## License

The guide is under the MIT license, so you can copy it, adapt it, and put your name on your version. The full text is in [LICENSE](LICENSE), and past versions are in the [changelog](CHANGELOG.md).
