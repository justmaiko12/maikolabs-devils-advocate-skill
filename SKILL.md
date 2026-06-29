---
name: devils-advocate
description: Use when someone asks for devil's advocate, a roast, pressure-test, stress-test, brutal second opinion, business idea validation, "convene the council", or says "/roast". Runs a five-perspective adversarial council, then returns one GO / RESHAPE / KILL verdict with the cheapest 48-hour test.
argument-hint: "[the idea, product, offer, content angle, strategy, or plan to pressure-test]"
---

# Devil's Advocate

Use this skill before the user sinks time, money, reputation, or emotional energy into a weak idea. The goal is not cruelty or contrarian theater. The goal is to expose the load-bearing assumptions, sharpen the idea, and force a real decision.

`/roast` is the high-intensity version of this workflow. It should be blunt, specific, and useful.

## Step 1: Get The Brief

If the user's request already contains the idea, start there. Ask only for missing context that materially changes the evaluation. Keep it to one batch of 3-4 questions max:

1. The idea in one or two sentences: what it is and what it does.
2. Who it is for and how it makes money: buyer, price, model, or desired payoff.
3. The user's edge: skills, audience, distribution, assets, data, relationships, or credibility.
4. Constraints: budget, timeline, risk tolerance, and how fast they need first proof or first dollar.

If the user says "just run it" or has already provided enough, proceed without more questions.

Write the brief into one short paragraph. Use that exact brief for every council perspective so each one evaluates the same thing.

## Step 2: Convene The Council

If this environment exposes subagent or multi-agent tools, run all five council members in parallel. If it does not, run the five perspectives yourself as separate labeled analyses before judging.

Each council member must return:

- One-line stance.
- 3-5 sharpest points.
- The single most important thing the user must hear.
- A 1-10 score on that persona's dimension, where 1 means walk away and 10 means no-brainer.

### 1. The Contrarian: Red Team

Assume this idea fails. Find the fatal flaws, the fastest way it dies, and the load-bearing assumptions that are probably wrong. Be ruthless and specific. No hedging. Attack the weakest points.

### 2. The Expansionist: Bull Case

Make the strongest possible case for the idea. Find the biggest upside, the 10x version, adjacent opportunities, and unlock points the user is not seeing. Be specific about where the real leverage or money could be.

### 3. The Logician: First Principles

Use no outside research. Reason from fundamentals: does the mechanism make sense, do the incentives line up, is the logic sound, does the math work in theory, and what has to be true for this to function?

### 4. The Researcher: Evidence

Use web search when market, competitor, pricing, demand, legal, platform, or current factual claims matter. Bring real-world evidence: competitors, demand signals, comparable pricing, existing behavior, and what reality says for or against the idea. Cite sources. If web access is unavailable, say the evidence pass is limited.

### 5. The Buyer: Voice Of Customer

Role-play the exact target customer in first person. React honestly. Would you pay for this? What is the real objection? What would make you choose a competitor or do nothing? What price feels right, and what would make you say yes now?

## Step 3: Judge

After all five perspectives are complete, act as the Judge. Weigh the findings and synthesize one decisive verdict. Do not average the scores. Name the real tension between the personas and resolve it.

Add the economics lens yourself:

- Rough pricing or value capture.
- Realistic time-to-first-dollar or first proof.
- Whether the user can ship the test quickly given their edge and constraints.
- What would make the idea obviously wrong within 48 hours.

Output the verdict in this exact shape:

```markdown
## THE VERDICT: GO / RESHAPE / KILL
Confidence: [low / medium / high]

**The call in one line:** [the decision, plainly]

**Why:** [2-3 sentences resolving the council's tension]

**Biggest risk:** [the single thing most likely to kill it]
**Biggest upside:** [the strongest reason to do it]

**Money read:** [rough price, time-to-first-dollar, can they ship fast]

**The cheapest 48-hour test:** [the smallest, fastest thing they can do to validate the riskiest assumption before building anything]

**If RESHAPE:** [the specific pivot that fixes the fatal flaw while keeping the upside]
```

Then list the five council scores in one line:

```text
Contrarian X/10 | Expansionist X/10 | Logician X/10 | Researcher X/10 | Buyer X/10
```

## Rules

- Make an actual call: GO, RESHAPE, or KILL. "It depends" is not a verdict.
- Do not be mean for entertainment. Be direct because directness reduces wasted time.
- If the idea is vague, judge the most plausible version and state the assumption.
- The 48-hour test is the most important output. It must be cheaper than building the product.
- Keep the final answer skimmable. The council provides depth; the Judge makes the decision.
