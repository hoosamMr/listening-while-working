# listening-while-working

A Claude skill that teaches a subject through deep, professional, code-free lectures designed to be **listened to while working**, for example with the app's read-aloud feature, without needing to look at the screen.

You choose the subject and the explanation language. Claude delivers one substantial, self-contained part at a time (roughly 900–1,400 words), builds from accessible foundations into advanced connected ideas, and ends each part with a spoken recap. Say "continue" to get the next part.

## Example prompts

- `listening while working: how neural networks learn, explain in Hebrew`
- `listening while working: the basics of TCP/IP, in English, beginner level`
- `continue`

The explanation language must be stated explicitly for each new lesson. The skill asks if it is missing.

## Install

### Claude app (claude.ai / desktop)

1. Download `listening-while-working.zip` from the [Releases](../../releases) page.
2. Open **Customize > Skills**, upload the ZIP, and turn the skill on.

The ZIP must contain the `listening-while-working/` folder at its top level, with `SKILL.md` inside it. The ZIP attached to a release is built this way. GitHub's automatic "Download ZIP" is not, because its top-level folder is named differently.

### Claude Code

Clone the repository into your personal skills folder:

```bash
git clone https://github.com/hoosamMr/listening-while-working ~/.claude/skills/listening-while-working
```

### Team and Enterprise

After uploading, use **Share** or **Publish to org** on the skill under **Customize > Skills**.

## What is in this repository

- `SKILL.md`: the skill itself (instructions and metadata)
- `agents/openai.yaml`: metadata for other agent platforms
- `assets/icon.svg`: icon

## License

MIT. See [LICENSE](LICENSE).

---
