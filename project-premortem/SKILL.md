---
name: project-premortem
description: Apply Gary Klein-inspired premortem analysis to a concrete project or decision before commitment. Use to surface plausible failure mechanisms, challenge fragile assumptions, and revise a plan. Produces prioritized risks, warning signs, and proposed responses while distinguishing imagined failure from observed events.
---

# Project premortem

Examine a plan by imagining that it has failed, then investigating plausible reasons. This is an independent application of Gary Klein's public premortem method. The prioritization, response planning, and examples below are original working adaptations.

## Establish a plan worth examining

Identify the intended outcome, proposed approach, horizon, and material constraints. Use the actual plan and known dependencies. If the plan is still vague, make the working version and its assumptions explicit before criticizing it. Do not replace the user's objective simply because achieving it is uncertain.

Define a concrete failure outcome relevant to the decision. Distinguish complete failure from delay, partial delivery, disappointing adoption, or an unacceptable side effect. One scenario may be sufficient; add another only when it reveals a materially different vulnerability.

## Generate explanations before defending the plan

Invite people to imagine they are looking back after the specified failure and explain how it happened. When facilitating an actual team, collect individual contributions before letting a group discussion settle on an explanation. Make it useful to voice a doubt rather than reward defense of the plan.

For an assistant-only review, generate plausible scenarios and label them as desk analysis. Do not invent participants, attributed objections, meeting outcomes, or independent agreement. An imagined failure is a thinking device, not a report that failure has occurred.

Make each proposed cause a mechanism tied to the plan. Ask what dependency breaks, how that affects another step, and why existing protections would not prevent the outcome. Replace a generic concern such as poor execution with a specific chain that could be investigated. Include an uncomfortable alternative explanation when it is relevant, such as lack of demand despite a functioning product.

## Separate evidence from possibility

For each consequential failure mechanism, identify known evidence, the assumption being challenged, and what would reveal whether the concern is real. Merge duplicates without hiding distinct causes. A risk can affect several outcomes; do not count each consequence as a separate independent cause.

Prioritize using consequence, plausibility, ability to detect the problem in time, and ability to change the plan. Keep catastrophic possibilities distinct from likely inconveniences. Do not assign invented probabilities or multiply arbitrary scores into a claim of precision. Explain why a concern deserves attention.

## Change the plan where it matters

For the most consequential concerns, propose a preventive change, a targeted test, a contingency, or explicit acceptance. Connect the response to the failure mechanism. A response that merely asks everyone to be careful is unlikely to resolve a fragile dependency.

Identify an observable warning sign and the decision it would trigger. Name an owner or deadline only if supplied or clearly proposed for agreement. Check whether a mitigation creates a new dependency, cost, or failure mode. Reassess the plan after these changes rather than leaving the original recommendation untouched.

## Deliver a usable review

Return the imagined failure scenario, the consequential mechanisms, and recommended changes at a depth proportionate to the task. A compact table can connect each mechanism to evidence, warning sign, and response. State what remains uncertain and which next test would most improve the decision.

Do not present the review as proof that the plan will fail or that the revised plan is safe. Preparing the analysis does not authorize changing a live project, assigning work to others, or contacting stakeholders.

### Original example

For a store pilot, an imagined failure might be that staff stop offering the cart. One possible mechanism is that repeated resets interrupt their other duties. Check actual recovery behaviour and staff workload before treating that explanation as established; a reset demonstration alone would not answer the question.

## Sources

Public sources reviewed 30 October 2026. This skill is not affiliated with or endorsed by Gary Klein.

- [Gary Klein: Premortem](https://www.gary-klein.com/premortem) — the method's core failure-imagination exercise.
- [McKinsey interview with Gary Klein and Daniel Kahneman](https://www.mckinsey.com/capabilities/strategy-and-corporate-finance/our-insights/strategic-decisions-when-can-you-trust-your-gut) — Klein's explanation of using prospective failure to surface doubts.
