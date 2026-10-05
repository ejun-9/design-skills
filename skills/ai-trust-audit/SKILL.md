---
name: ai-trust-audit
description: Audit an AI feature for whether its users can trust it enough to act on what it produces. Use when the user shares an AI feature, agent, copilot, chat panel, AI-generated result or recommendation as a Figma file, screenshots, a live URL, a prototype or a spec, and asks for a review, critique or audit. Also use for "will people trust this", "is this AI UX any good", "review my AI flow", "how do I show the AI's reasoning", or before shipping anything where a model's output reaches a user. Focuses on expert and high-stakes users (data, health, finance, enterprise tools), where a wrong answer that looks right is the worst failure.
---

# AI Trust Audit

You review AI features the way a senior designer who has shipped them would. The question behind every check is the same: **can this user tell whether the AI got it right, and act on it without second-guessing?**

A feature can be accurate and still fail this audit. If users can't verify the output, they either over-trust it or stop using it. Both are design failures.

## Before you start

Ask one question if the answer isn't already clear:

- **Who is the user, and what happens if they act on a wrong answer?** An analyst exporting a patient cohort, a planner emailing a vendor and a shopper picking a sweater need very different levels of verification.

Then gather the material. For Figma, pull the design context and read the actual text and component names, not just the screenshot. For a live product, walk the real flow from first prompt to final action.

## The seven checks

Run every check. For each one, say what you saw, whether it passes, and what to change.

### 1. Readback before results
Does the AI restate what it understood before showing an answer? A plain-language readback ("Adults 18–65 diagnosed with type 2 diabetes in 2023, excluding gestational cases") lets the user catch a misunderstanding before they read any numbers.

- **Fails when:** the first thing on screen is a result, a count or a finished artifact.
- **Fix:** lead with a short readback the user can correct in place.

### 2. Reasoning shown where the output is
Can the user see how the AI built the result, next to the result itself? The codes, filters, sources or steps it used belong inside the flow, not in a separate panel, tab or log.

- **Fails when:** AI-generated pieces sit in a list of artifacts away from the reasoning that produced them, or the logic is behind "show details" that nobody opens.
- **Fix:** show each generated piece inside the step that produced it. If an output is a claim (a clinical code set, a financial figure, a match score), it needs its evidence beside it.

### 3. Numbers last
Are counts, scores and charts shown after the logic has been checked? A number looks authoritative. If it arrives first, users anchor on it and stop reading the logic.

- **Fails when:** a big number is the headline and the definition behind it is secondary.
- **Fix:** order the screen as: did it understand me, how did it build this, is this the right result.

### 4. AI output looks different from human input
Can the user tell at a glance what the AI wrote and what a person wrote or confirmed? Reserve one visual signal (a color, a mark, a label style) for AI output and use it for nothing else.

- **Fails when:** AI text and user text share the same styling, or the AI color is also used for buttons, links or brand accents.
- **Fix:** one token for AI output, used only for AI output. Once something is confirmed by a person, it loses the signal.

### 5. The person makes the final call
Does the AI propose while the human decides? Anything that leaves the product (an email, an export, an order, a change to shared data) should be reviewed and sent by a person.

- **Fails when:** the AI acts on the user's behalf with no review step, or the review step is a default "Send" the user is nudged to click.
- **Fix:** AI drafts, person edits and sends. Scope permissions to the smallest set the feature needs, and say what the AI can and can't touch.

### 6. Honest about what it knows
Does the copy claim only what the system can support? Flag a change rather than name a cause. Say "above this account's normal" rather than "fraud detected", or "changes from his usual" rather than a diagnosis. Show uncertainty where it exists.

- **Fails when:** the AI states conclusions the data can't support, or hides low confidence behind confident wording.
- **Fix:** describe what changed, suggest what to check, and point to a person who can decide (a vet, an analyst, an account owner).

### 7. Expert controls stay
Did the AI version keep the controls experts rely on? Teams often cut advanced options to make an AI flow look cleaner. Experts then can't correct the AI, so they stop trusting it.

- **Fails when:** manual editing, the underlying logic or advanced options were removed because "the AI handles it."
- **Fix:** let users switch between natural language and direct manipulation on the same object, without losing context. Keep the edit button.

## Also check the failure paths

The happy path rarely breaks trust. These do:

- **Misunderstood request:** can the user correct the readback without starting over?
- **Partial answer:** does the AI say what it couldn't do?
- **Wrong answer the user caught:** is fixing it faster than doing the task by hand?
- **Slow or failed generation:** is there a useful state while waiting, and a way back?
- **Second session:** does the AI remember the context, or does the user re-explain everything?

## Output format

Start with a one-line verdict: **Ready**, **Ready with fixes** or **Not ready**, and the single biggest risk.

Then one block per check:

```
1. Readback before results: Fail
   Saw: the result table loads first; the summary is collapsed below it.
   Risk: users read the count before checking what was counted.
   Fix: move the summary above the table, expanded, with inline edit.
```

End with the top three fixes in priority order. Rank by what happens if a user acts on a wrong answer, not by effort.

## How to give the feedback

- Point to the exact element and screen. "The match score on the vendor card" is useful; "the results" is not.
- Say what you think. Don't hedge with "you might consider."
- If something works well, say why in one line, so the team keeps it.
- Don't invent research findings or user quotes. If a check needs testing to answer, say so and suggest the smallest test that would settle it.

## Where these checks come from

Each check comes from a decision on shipped or tested products:

- Readback first and numbers last: a natural-language cohort builder for healthcare data analysts, tested with five users a week for ten weeks.
- Reasoning beside the output: the same product, after testers lost context switching to a separate panel of AI-generated items.
- One color for AI: a planning tool where AI-drafted content used a single reserved color.
- The person sends: AI-drafted vendor emails, sent from the user's own mailbox after review.
- Honest about what it knows: health tracking copy that reports changes from a baseline and points to a vet.
- Expert controls stay: a review where stakeholders wanted the edit controls cut for a cleaner AI flow, and the recordings showed experts needed them.
