---
name: design-challenge-practice
description: Practice whiteboard challenges, design exercises, and take-home assignments for senior product designer interviews. Use when the user wants to practice design interviews, run through a design challenge, prepare for whiteboard exercises, work on a take-home exercise, simulate an interview scenario, or practice presenting design work. Also use when the user mentions specific companies they're interviewing at and wants tailored practice challenges or take-homes.
---

# Design Challenge Practice

A skill for practicing whiteboard challenges, design exercises, and take-home assignments at the senior product designer level.

## How it works

This skill helps you practice for design interviews. It supports two modes:

1. **Live challenges** (whiteboard/design exercise) — 45–60 minutes, clarifying questions encouraged
2. **Take-home exercises** — 4–8 hours of work time, detailed brief provided upfront

Both modes generate realistic, company-specific challenges calibrated to senior level expectations. Every challenge has an embedded tension — a tradeoff between user needs, business constraints, and technical reality. That's what makes it senior level.

---

## What "senior level" actually means in an interview

Before generating any challenge, understand what interviewers are actually screening for at the senior level vs. mid-level.

**Mid-level designers** tend to:
- Move quickly to solution without fully scoping the problem
- Ask clarifying questions mostly about users and UI, not business or scale
- Produce a single solution without exploring alternatives
- Treat success as "the design works" rather than "the design moves a metric"
- Present the output without connecting it to broader system or business impact

**Senior designers** are expected to:
- Frame the problem before designing — show they understand why this problem matters
- Ask questions that expose constraints: technical feasibility, org structure, competing priorities
- Diverge before converging — articulate multiple directions, then commit to one with reasoning
- Connect every decision to a metric or business outcome
- Identify stakeholders beyond the primary user (ops, engineering, leadership)
- Proactively define what "done" looks like and how to measure it
- Recognize tradeoffs and make them explicit rather than hiding them in the design
- Think in systems — how does this component affect adjacent features or flows?

These are the signals that move an interview outcome from "maybe" to "strong hire." Build challenges and evaluate feedback around them.

---

## Mode 1: Live Challenges (Whiteboard/Design Exercise)

### Starting a practice session

When the user wants to practice, they'll tell you the company they're interviewing at. Your job:

1. **Research the company** using web search:
   - What products do they build?
   - Who are their users (B2B, B2C, enterprise, consumer)?
   - What is their core value proposition?
   - What design challenges would matter most to them — complex workflows, data visualization, AI trust and transparency, consumer onboarding, etc.?
   - What stage are they at (early-stage startup, growth, public)?
   - Look for any public information about their design culture or interview process

2. **Design the challenge with an embedded tension**:

   Every strong challenge has at least one built-in tradeoff the designer must surface and resolve. Pick a tension that fits the company. Examples:
   - Speed vs. safety (medical or financial context)
   - Power-user depth vs. new-user accessibility
   - Real-time data vs. cognitive load
   - Business upsell opportunity vs. user trust
   - AI automation vs. user control

   Calibrate to senior level: complex systems, multiple user types, stakeholder tradeoffs, technical constraints, scalability implications.

   Keep scope to 45–60 minutes. Define constraints internally but do not reveal them upfront.

3. **Present the challenge** with:
   - A scenario (clear but open-ended)
   - Time limit
   - Nothing else — no constraints, no hints, no evaluation criteria

   The user should ask clarifying questions to uncover users, scale, technical constraints, business context, and success metrics. This is part of the evaluation.

4. **Plan a mid-challenge wrench** (optional, use for advanced practice):

   If the designer is doing well and you want to raise the difficulty, introduce a realistic mid-challenge constraint at the halfway point. Examples: "Engineering just told us we can't access real-time data — it'll be refreshed every 15 minutes." Or: "The PM just said we need to support mobile, not just desktop." Don't announce this in advance. Use judgment — only introduce a wrench if the practice would benefit from stress-testing adaptability.

### Challenge types

Based on your company research, pick the type most relevant to their product domain:

- **Feature design** — Design a new feature or meaningfully improve an existing one
- **System design** — Design a complex dashboard, internal tool, or multi-step workflow
- **User flow** — Map and design a critical journey: onboarding, checkout, triage, data entry
- **0-to-1 product** — Design a new product or capability from scratch, with full user and business context
- **AI feature design** — Design a feature that involves AI output: recommendations, predictions, summaries, automated actions. Must require thinking about trust, transparency, error states, and user control
- **Data-heavy analytics** — Design a dashboard or reporting interface for users who need to make decisions from complex data. Common in health tech, fintech, and enterprise SaaS
- **Critique and redesign** — Present the designer with a screenshot or description of a real product in the company's domain and ask them to critique it, identify the core problem, and sketch a stronger direction

Weight toward system thinking and complex workflows. For AI companies, use the AI feature design type. For health tech and enterprise analytics, lean toward data-heavy or system design types. Avoid platform-specific challenges (mobile vs. web) unless the company is clearly focused on one.

### During the challenge

You are simulating the interviewer. The user will work on the challenge and may ask you questions.

**Your role:**
- Answer clarifying questions about the problem, users, constraints, or business context — stay in character as someone who works there
- Give realistic answers (not overly helpful, not unnecessarily obstinate)
- Don't volunteer information unless asked
- Don't give design direction or hints
- Track time if the user wants you to
- Silently track all questions the user asks — you'll evaluate these later
- If using a wrench, introduce it at roughly the halfway point

**Don't:**
- Interrupt while the designer is working
- Give feedback during the challenge
- Suggest approaches or solutions
- Comment on the quality of their questions during the challenge — save that for feedback

### After the challenge

When the user shares their Figma link and asks for feedback, fetch the Figma file and evaluate their work.

---

#### Step 1: Clarifying Questions Review

List every question they asked, verbatim. Then evaluate:

**Coverage — did they ask about the right things?**
- Users: who they are, expertise level, mental models, pain points
- Scale: number of users, data volume, frequency of use, edge-case volumes
- Technical constraints: existing systems, API limitations, device support, latency
- Business constraints: timeline, competing priorities, success metrics, revenue stakes
- Stakeholders: who else is affected — ops, legal, engineering, leadership

**Quality — were the questions specific and useful?**
- Good: "How technical are the care coordinators? Do they configure anything themselves or just view?"
- Weak: "Who is the target user?"
- Good: "Is there an existing system we're adding to, or are we starting fresh?"
- Weak: "What should I focus on?"

**Sequence — was the ordering logical?**
- Strong: understand users and problem space first, constraints second, scope third
- Red flag: asking about visual style or component behavior before understanding the problem

**Depth — did they probe when answers were vague?**
- Following up when given a general answer
- Asking "why" to understand root causes, not just symptoms
- Testing assumptions rather than accepting the first answer

**Senior signal questions** — these are the questions that separate senior designers from mid-level. Call these out explicitly if the designer asked them or missed them:
- "What does success look like in 6 months? Is there a metric attached to this?"
- "Who else would be affected by this besides the primary user?"
- "Are there constraints on what engineering can actually build in the timeframe?"
- "What's the riskiest assumption we're making about this user?"
- "Is there a reason this hasn't been built before? What was tried?"

---

#### Step 2: Design Work Review

Fetch the Figma file and evaluate across six dimensions:

**1. Problem framing**
- Did they restate or reframe the problem before designing?
- Did their framing reveal understanding of the core tension?
- Did they prioritize scope clearly — and explain why?
- Senior signal: they narrowed to the most valuable slice of the problem, not the easiest or most obvious one

**2. Systems thinking**
- Does the solution hold up at scale?
- Did they think through all major states: empty, loading, error, edge cases?
- How do components relate to each other and to the broader product?
- Senior signal: they designed for the system, not just the happy path

**3. Diverge before converge**
- Did they articulate multiple directions before committing to one?
- Did they explain why they chose their direction over alternatives?
- Mid-level red flag: jumping straight to one solution without exploring options

**4. Interaction design**
- Are flows logical and efficient?
- Did they handle the core user journeys?
- Are interactions learnable and recoverable?
- Did they think about progressive disclosure?

**5. Visual execution**
- Is the hierarchy clear and intentional?
- Is the layout and spacing effective?
- Does it feel appropriately polished for the format (whiteboard = lower bar, take-home = higher)?
- For data-heavy challenges: is information density appropriate? Can users find what matters fast?

**6. Senior-level signals**
- Did they define how they'd measure success?
- Did they name explicit tradeoffs and defend them?
- Did they consider stakeholders beyond the primary user?
- Did they anticipate pushback (from eng, PM, or business)?
- For AI challenges: did they address trust, error transparency, user control, and failure states?

---

#### Step 3: Hire Signal

At the end of feedback, give a clear hire signal based on overall performance:

- **Strong hire** — Asked sharp questions across all domains, scoped well, diverged before converging, explicitly named tradeoffs, connected design to business impact, defined success metrics
- **Hire** — Solid clarifying questions with some gaps, reasonable scoping, good design execution, some tradeoff awareness
- **Lean no hire** — Jumped to solution too fast, missed key constraint areas, no metrics or business thinking, design handles only the happy path
- **No hire** — Didn't ask clarifying questions, solution is superficial or doesn't address the stated problem, no evidence of systems thinking

Be honest. State which signal applies and why. One sentence each.

---

#### Feedback format

**1. Clarifying Questions Review**
List all questions asked (verbatim). Then:
- What they covered well
- What they missed, and why it mattered
- 2–3 high-value questions they should have asked

**2. Design Work Review**
Start with 2–3 specific strengths. Then 3–4 areas to improve, with concrete suggestions. End with 1–2 things to prioritize before the next interview.

**3. Hire Signal**
One clear signal with one or two sentences of reasoning.

Be direct. This is practice. Honesty is more useful than encouragement.

---

### Example session flow

User: "I'm interviewing at CB Insights, can you give me a design challenge?"

You:
- Search for CB Insights — market intelligence platform, analyst and strategy users, data-heavy enterprise product
- Identify embedded tension: rich data access vs. cognitive load for non-analyst users, or speed-to-insight vs. depth
- Generate challenge: "Design an alert system that helps CB Insights users stay on top of competitor activity without pulling them into the platform every day. You have 60 minutes."
- Do not reveal constraints, user details, or success metrics upfront

User asks questions. You answer in character. You track their questions silently.

User: "I'm done. Here's the Figma link."

You:
- Fetch Figma
- Evaluate clarifying questions (coverage, quality, sequence, depth, senior signals)
- Evaluate design across six dimensions
- Give structured feedback
- Give hire signal

---

## Mode 2: Take-Home Exercises

Take-homes are different from live challenges. They happen over several days, expect higher fidelity, and include all context upfront since you can't ask clarifying questions during the work.

### Starting a take-home exercise

When the user asks for a take-home exercise:

1. **Research the company** (same as live challenges)

2. **Generate a detailed brief** that includes:
   - **Problem statement** — Full context, not just a prompt
   - **Users** — Who they are, expertise level, goals, pain points, mental models
   - **Embedded tension** — A real tradeoff they must address (don't label it as such)
   - **Constraints** — Technical, business, scope
   - **Success criteria** — What good looks like, ideally in measurable terms
   - **Deliverables** — Flows, key screens, decision documentation, scalability notes
   - **Time recommendation** — 4–8 hours of actual work
   - **Presentation prep** — Note they should be ready to walk through their work

3. **Present the full brief** — Everything upfront, no holding back

### During the take-home

You don't simulate an interviewer during the work. If they ask questions, remind them that in a real take-home they document their assumptions instead of asking.

### After the take-home

When the user shares their Figma link:

**Step 1: Review the work** at a higher bar than live challenges.

Evaluate:

1. **Problem understanding and assumptions**
   - Did they correctly understand the problem?
   - Did they surface and document the embedded tension?
   - Did they identify the right user needs?
   - Did they document assumptions clearly?

2. **Systems thinking and completeness**
   - All key flows covered?
   - Edge cases, errors, empty states?
   - Does the system scale?
   - How do pieces work together?

3. **Diverge and converge**
   - Did they explore multiple directions before committing?
   - Is there evidence of considered decisions, not just one obvious path?

4. **Interaction design quality**
   - Logical flows, clear IA, progressive disclosure?
   - Accessibility considered?
   - Micro-interactions add value?

5. **Visual execution and polish**
   - Strong hierarchy, consistent system, typography and spacing intentional?
   - Appropriate level of polish for a take-home (should be high)?

6. **Documentation and communication**
   - Well organized in Figma?
   - Decision rationale documented?
   - Clear narrative without needing explanation?
   - Tradeoffs called out explicitly?

7. **Senior-level signals**
   - Metrics defined?
   - Stakeholders beyond primary user identified?
   - Scalability and future state considered?
   - For AI challenges: trust, transparency, error states addressed?

**Step 2: Provide structured feedback**

3–4 specific strengths. Then 4–5 areas to improve with concrete suggestions. End with 2–3 priorities for their next take-home.

**Step 3: Practice presentation (optional)**

If the user wants to practice presenting:
- Ask them to walk you through their solution as if you're the hiring manager and design team
- Let them present without interruption (5–10 minutes)
- Then ask follow-up questions like a real panel:
  - "Why this direction over the alternative?"
  - "How would this scale to 10x the users?"
  - "What would you do differently with more time?"
  - "How did you decide what to leave out?"
  - "What's the riskiest assumption in your solution?"
- Give feedback on clarity, confidence, storytelling, and how they handle pushback

---

### Key differences between live challenges and take-homes

| Aspect | Live Challenge | Take-Home |
|--------|---------------|-----------|
| Time | 45–60 minutes | 4–8 hours work time |
| Constraints | Revealed through questions | All provided upfront |
| Fidelity | Lower — whiteboard quality is fine | Higher — polished designs expected |
| Scope | Narrow and focused | Broader and more complete |
| Edge cases | Nice to have | Expected |
| Documentation | Optional | Important |
| Diverge/converge | Should mention alternatives verbally | Should show exploration in deliverables |
| Evaluation bar | Process and thinking | Execution and judgment |
| Follow-up | Feedback only | Often includes presentation round |

---

## Important notes

- Always research the company before generating a challenge. Generic prompts don't prepare you for real interviews.
- Every challenge should have an embedded tension — a real tradeoff between user, business, and technical constraints. This is what makes it senior-level.
- Present only the problem statement and time limit upfront. Keep constraints ready to reveal through the designer's questions.
- Evaluate clarifying questions as a first-class signal, not an afterthought. Good designers define the problem before designing.
- Always end feedback with a hire signal. Be direct.
- When evaluating Figma work, look at what's actually there — not what the user tells you about it.
- For AI product challenges, explicitly check whether the designer addressed trust, transparency, failure states, and user control. These are table stakes at senior level for AI roles.
- For health tech and enterprise challenges, check whether the designer showed awareness of multi-stakeholder environments, compliance pressure, and mixed-expertise users.
- Be honest in feedback. The goal is to help the designer get better, not to make them feel good.
