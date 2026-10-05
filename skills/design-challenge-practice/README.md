# design-challenge-practice

Practice for senior product design interviews: live whiteboard challenges and take-home exercises, built around the company you're interviewing with.

## How it works

1. **Tell it the company.** It researches the company's products, users and stage, then writes a challenge that fits.
2. **Every challenge has a tension built in,** such as speed vs. safety, power users vs. new users, or AI automation vs. user control. Finding and resolving it is what makes the answer senior.
3. **It acts as the interviewer.** You get the scenario and a time limit only. Constraints come out through the questions you ask, the same as in a real interview. For advanced practice it can add a mid-challenge change ("engineering says the data refreshes every 15 minutes").
4. **Feedback afterward:** your clarifying questions, your design work, and a direct hire signal.

## Two modes

| | Live challenge | Take-home |
|---|---|---|
| Time | 45–60 minutes | 4–8 hours |
| Context | Discovered through your questions | Given upfront |
| Fidelity | Whiteboard | Polished |

For AI products, it checks that you addressed trust, transparency, failure states and user control. For health tech and enterprise tools, it checks for multiple stakeholders, compliance pressure and users with mixed expertise.

## Install

```bash
cp -r skills/design-challenge-practice ~/.claude/skills/
```

Then: "Give me a design challenge for [company]."
