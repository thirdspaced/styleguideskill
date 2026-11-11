# LLM style and copy guide

A free set of writing rules you give to ChatGPT, Claude, Gemini, or any other AI chatbot. Upload it once, and the drafts that come back use plain words, keep your facts, and drop the habits that make people stop reading.

Current version: 3 (October 2026). Created by Amanda Grutza for [how to talk to robots](https://www.talktorobots.org). The guide also has a [page on the site](https://www.talktorobots.org/style-guide/).

## What it's for

Ask an AI tool for a post or an email and the first draft usually shows the same habits: em dashes everywhere, "delve" and "seamless," a cheerful intro, three tidy bullets, a recap of what you just read, and sometimes a number nobody measured. Readers notice, even when they can't say what's off.

The guide tells the model which words and sentence patterns to avoid, what to write instead, and how to run a six-check final pass before it hands the draft back. It's just as strict about what to keep: the facts, the limits, the exact names and button labels, and the next step your reader needs.

**Before**

> AI isn't just a tool. It's your unfair advantage. The people who embrace it today will be the ones leading tomorrow. Let that sink in.

**After the style pass**

> Before adding AI to your week, pick the one task you want to change. Drafting a reply from meeting notes is a specific task. "Be more productive" is too broad to test. Try it for a week and notice how much editing the drafts still need.

It's an editing standard. It isn't an AI detector, and its word lists aren't proof that someone used AI. Plenty of people wrote "delve" long before chatbots did.

## Who can use it

Anyone who uses an AI tool to draft something they'll send under their own name or their organization's name. You don't need to be technical. If you can upload a file to a chat, you can use it.

## Editions

Every edition is complete on its own. Choose the one closest to what you write most and use that single file.

| Edition | Best for | What it adds |
| --- | --- | --- |
| [Core](guides/llm-style-guide-v3.md) | Emails and messages, social posts and newsletters, bios, web pages, and instructions | The full rule set for everyday writing, with general writing modes and examples |
| [Business](guides/llm-style-guide-v3-business.md) | LinkedIn and professional accounts, website and service copy, case studies, proposals, client email, listings | Startup language to rewrite, business claims that need proof, and calls to action that serve the reader |
| [Tech](guides/llm-style-guide-v3-tech.md) | Explainers and news roundups, tool reviews and release notes, setup docs and security notices | Rules for news, AI features, and security copy, plus a tech hype table |
| [Education](guides/llm-style-guide-v3-education.md) | Lesson materials and directions, student feedback, family newsletters and staff messages | School terms, three school audiences, and rules against inventing student observations or progress |

## How to use it

1. **Fill in Make it yours.** The table near the top of each edition sets whose voice it is, who reads it, three words for how you want to sound, and the words you never want to see. Anything you leave blank falls back to the defaults.
2. **Upload it to a project.** Add the file to a Claude Project, a ChatGPT Project or custom GPT, or a Gemini Gem. If your tool doesn't have projects, paste it into custom instructions or at the start of a chat.
3. **Start each task with the instruction.** Every edition ends with a starter instruction. Fill in the brackets and paste it in with your notes.
4. **Read the draft yourself.** The final pass catches patterns. It can't check your facts, your dates, or whether the story in the draft really happened. That part stays with you.

### Use it as a Claude skill

Each file starts with skill frontmatter. Put one edition in a folder, rename it `SKILL.md`, and add the folder as a skill.

## What's in every edition

- A Make it yours table for your voice, audience, and house terms
- Rules for behavior, thinking, mechanics, openings, and closings
- Words and sentence patterns to avoid, with plain replacements
- Evidence rules: no invented numbers, quotes, testing, or results
- Cadence, tone, and format notes for the places you publish
- Worked before-and-after examples
- A six-check final pass and a starter instruction

## Contributing

If you find a pattern the guide misses, or a rule that gets in the way of good writing, [open an issue](https://github.com/thirdspaced/styleguideskill/issues) with an example and a rewrite. A preference that's only yours belongs in your own Make it yours table.

## References

- Peter Yang, [no-ai-slop](https://github.com/petergyang/no-ai-slop): an open-source skill for removing AI writing patterns from a draft. He introduced it in [Behind the Craft](https://creatoreconomy.so/p/use-my-no-ai-slop-skill-to-remove-20-ai-slop-patterns).

## License

MIT. Copy it, adapt it, and put your name on your version. See [LICENSE](LICENSE) and the [changelog](CHANGELOG.md).
