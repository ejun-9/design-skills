# design-skills

Claude Skills I use in my own design work, written as a product designer for other designers.

| Skill | What it does |
|---|---|
| [ux-codesigner](skills/ux-codesigner) | A design partner for rough ideas and screen reviews. Maps flows and edge cases, and reviews screens as one connected workflow. |
| [ai-trust-audit](skills/ai-trust-audit) | Seven checks for whether users can trust an AI feature enough to act on its output. |
| [design-challenge-practice](skills/design-challenge-practice) | Practice whiteboard challenges and take-homes for senior product design interviews, tailored to the company. |

Related: [ds-specs](https://github.com/ejun-9/ds-specs) (a design system an LLM can follow, with two-way Figma sync) and [figma-comments-mcp](https://github.com/ejun-9/figma-comments-mcp) (lets Claude read Figma comments).

## Install

Claude Code, all three skills:

```bash
git clone https://github.com/ejun-9/design-skills.git
cp -r design-skills/skills/* ~/.claude/skills/
```

One skill only:

```bash
cp -r design-skills/skills/ai-trust-audit ~/.claude/skills/
```

Claude.ai: zip a skill's folder and upload it under Settings → Capabilities → Skills.

Skills load on their own when a request matches their description. You can also call one by name, for example "use ai-trust-audit on this flow."

The Figma parts of ux-codesigner and ai-trust-audit need the [Figma MCP server](https://help.figma.com/hc/en-us/articles/32132100833559). Without it, share screenshots instead.

## About

I'm [Eun Ji Jung](https://eunji.design), a product designer. I spent four years at Komodo Health designing data and AI tools for clinical analysts.

## License

MIT
