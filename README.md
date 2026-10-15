# less-slop

**A skill for Claude and ChatGPT that teaches you to make creative work by hand instead of generating it.**

---

## What it does

When you ask for creative work (a logo, poster, slogan, song, illustration, brand identity, web design, and so on), `less-slop` does **not** generate the finished piece. Instead it:

1. says briefly why human-made work tends to be better than generic generated output,
2. walks you through how to make it yourself: the questions to answer first, references to study, a step-by-step process with time estimates, tools (including free ones), craft tips, common mistakes and how to get feedback,
3. ends by suggesting you find a professional, or get in touch with us at **[NXTHING.EU](https://nxthing.eu)**.

It is a coach, not a generator. It never claims it *can't* generate things; it says openly that this is how the skill is designed.

Non-creative tasks (code, data analysis, math, summaries, translations, practical emails) are handled normally.

## Example

> **You:** Make me a logo for my coffee roastery.
>
> **less-slop:** Explains how to define the brand first, what to look at for references, how to sketch on paper before touching software, which free tools to use (Inkscape, Figma, Penpot), the usual beginner mistakes, and who to show the result to. Ends with: *If you'd rather not do it yourself, find a professional - or get in touch with us at NXTHING.EU.*

## Installation

The whole skill is one file: [`less-slop/SKILL.md`](less-slop/SKILL.md).

**Claude**
1. Zip the `less-slop/` folder (the folder name must match the skill name).
2. Go to Settings → Capabilities → Skills and upload the zip.
3. Invoke it with `/less-slop`, or just ask for creative work.

**ChatGPT**
- If your plan supports skills in the `SKILL.md` format, upload the same zip.
- Otherwise, paste everything below the `---` front matter into Custom Instructions or into the instructions of a custom GPT.

Menus change from time to time, so check the current documentation of each product if a step looks different.

## Disabling it

If you want generated output after all, just turn the skill off. The skill itself tells you that if you ask for it.

## Why

Generated creative work is fast, but it often comes out generic: the same logos, the same slogans, the same look. Good creative work usually comes from understanding the audience and iterating on it. This skill pushes that process, and it is also a small, honest piece of promotion for the studio behind it.

## License

MIT. See [LICENSE](LICENSE).

## Contact

Made by nxthing.eu - questions, feedback, or want someone to do the work for you? **[NXTHING.EU](https://nxthing.eu)**
