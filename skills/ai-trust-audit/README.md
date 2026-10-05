# ai-trust-audit

Reviews an AI feature for one thing: can users tell whether the AI got it right, and act on it without second-guessing?

An accurate feature can still fail. If people can't check the output, they either trust it too much or stop using it.

## The seven checks

1. **Readback before results:** the AI restates what it understood before showing an answer.
2. **Reasoning shown where the output is:** how it got there sits next to the result, not in a separate panel.
3. **Numbers last:** counts and scores appear after the logic is checked, so nobody anchors on them.
4. **AI output looks different:** one visual signal, used only for AI output.
5. **The person makes the final call:** the AI drafts; a person reviews and sends anything that leaves the product.
6. **Honest about what it knows:** it reports changes and suggests what to check, without claiming causes it can't support.
7. **Expert controls stay:** the AI version keeps the manual controls experts use to correct it.

It also walks the failure paths: misunderstood requests, partial answers, wrong answers the user caught, slow generation, and a second session.

## Output

A verdict (Ready, Ready with fixes, Not ready), then each check with what it saw, the risk and the fix, then the top three fixes ranked by what happens if a user acts on a wrong answer.

## Where the checks come from

Each one comes from a decision on a product I designed: a natural-language cohort builder for healthcare data analysts (tested with five users a week for ten weeks), a planning tool with AI-drafted email, and health-tracking copy that reports changes without diagnosing. The case studies are at [eunji.design](https://eunji.design).

## Install

```bash
cp -r skills/ai-trust-audit ~/.claude/skills/
```

Works best on high-stakes, expert tools: data, health, finance and enterprise software.
