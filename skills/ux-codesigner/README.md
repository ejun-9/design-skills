# ux-codesigner

A design partner for two jobs: turning a rough idea into a flow you can build, and reviewing screens before they go to engineering.

## What makes it different

Most design-critique skills review one screen at a time. This one reviews the set as a workflow:

- **Flow continuity:** can the user get from each screen to the next, or do they hit a dead end?
- **Stranded value:** wherever the user finds something useful, can they act on it? A discovery screen with no save, contact or shortlist action is a dead end.
- **Competing patterns:** if one screen uses natural-language search and another uses filters, which one is primary, and is the relationship designed?
- **States between screens:** sign-in walls, loading, errors and empty results. If nobody designs them, they get improvised in development.

Two modes on top:

- **MVP:** checks for scope creep, whether the core loop works with only these screens, and stats that can't be backed up yet.
- **"Dig":** goes down to exact click sequences and proposes specific fixes.

## What it does with a rough idea

It asks one clarifying question, then answers in four parts: the concept restated, the core flow, edge cases, and open questions.

**You:** I want users to save their search filters so they don't rebuild them every time.

**It returns:**
- **Concept:** saved, named filters for repeated analysis.
- **Core flow:** build a filter → "Save this filter" near Apply → name it → it appears under Saved Filters → one click restores it next session.
- **Edge cases:** 20+ saved filters, editing a saved filter (overwrite or save as new), a filter that points to deleted data, shared workspaces, mobile.
- **Open questions:** folders? A limit? Shareable with teammates? What happens when the data schema changes?

## Install

```bash
cp -r skills/ux-codesigner ~/.claude/skills/
```

Figma reviews use the Figma MCP server. Without it, paste screenshots.

## Credit

The starting idea came from a LinkedIn post about using Claude as a UX co-designer. I've since lost the link. The workflow review, MVP and dig modes, and the examples are mine, drawn from reviews on my own projects.
