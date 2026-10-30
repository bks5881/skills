---
name: first-principles-thinking
description: Analyze a problem by separating established facts, constraints, assumptions, and conventions, then rebuild possible solutions from the required outcome and underlying mechanisms. Use for first-principles requests, inherited design choices, unexplained costs, or claims that an approach is unavoidable. Produces inspectable reasoning and testable alternatives without treating speculation as fundamental truth.
---

# First-principles thinking

Identify what the problem actually requires, what is known, and which parts of the current solution are choices. Rebuild from that foundation when it could change the decision. This is an original practical synthesis, with philosophical and scientific context linked below; it is not a standardized or certified method attributed to one modern author.

## Define the outcome without prescribing the mechanism

State the result the user wants, who benefits, and the criteria that matter. Separate the desired function from the current implementation. Preserve explicit user requirements and preferences. Question an assumption without silently replacing the user's goal with an easier one.

Identify the decision the analysis should inform. Use existing context and evidence first. Ask for a missing detail only when it materially changes the reasoning; otherwise state a working assumption and continue.

## Establish the status of important claims

Distinguish the following where they affect the decision:

- Established facts or measurements, with sources and applicable conditions.
- Physical or logical principles, including the model and limits under which they apply.
- Requirements, commitments, and constraints that apply to this assignment.
- Preferences or value judgments about which outcome is desirable.
- Assumptions, estimates, and conventions that could be investigated or changed.

A requirement is not a law of nature, but it can still be binding for the task. A preference is not proved by physics, but it can still determine the right design. Do not promote an intuition, popular claim, or convenient simplification into an unquestionable premise.

For a consequential claim, ask what supports it, how it could be checked, and what changes if it is false. Verify domain-specific or time-sensitive claims with appropriate sources. Missing evidence should remain visible rather than being filled with confident invention.

## Decompose only as far as the decision needs

Break the outcome into necessary functions, causal steps, or resource requirements. Identify dependencies and bottlenecks. Ask why a component, step, or cost exists and which function would be lost if it were removed. Repeatedly asking why is useful only when the answers become better supported or expose a meaningful choice.

Use a calculation or simple model when it clarifies the issue. State units, inputs, assumptions, and operating conditions. Distinguish a theoretical lower bound from an achievable design and from a delivered cost. For example, raw material cost alone omits fabrication, yield losses, assembly, support, and other relevant burdens.

Keep interactions between parts visible. A component-level improvement can worsen overall performance. Stop decomposing when further detail is unlikely to change the choice; avoid turning an ordinary reversible decision into an attempt to derive an entire discipline.

## Rebuild alternatives from the necessary functions

Explore materially different ways to satisfy the outcome using the established constraints and available resources. Change the arrangement, sequence, mechanism, or allocation of work when relevant. Explain how each alternative delivers the required function and which assumption it challenges.

Include the current approach as a baseline when useful. Existing expertise, precedent, and analogous cases are evidence to examine; first-principles reasoning does not require discarding them or rebuilding a proven tool from scratch. A conventional solution may remain preferable after analysis.

Separate deductions that follow from the premises from hypotheses requiring empirical tests. Human adoption, organizational responses, and market demand generally need observation; they cannot be established merely by a plausible chain of reasoning.

## Challenge the conclusion and choose a test

Check whether the recommendation depends on a fragile input or omitted constraint. Vary uncertain inputs enough to see whether the preferred option changes. Seek a counterexample or competing explanation that could overturn a consequential claim.

Recommend a proportionate calculation, observation, prototype, or experiment for the remaining uncertainty. Define what result would change the decision. Keep proposed targets, simulated behaviour, and measured performance distinct.

Deliver the answer at the requested depth: the outcome, the decisive premises, the important assumption challenged, the alternative or recommendation, and the next verification step. Do not equate an elegant explanation with a proven solution or claim novelty from reasoning alone. Analysis does not authorize external commitments or live changes.

### Original example

Suppose a cart is said to need a larger battery because it needs a longer operating time. First establish the duty cycle, energy demand, reserve requirement, and charging opportunities. A larger battery, reduced demand, or changed charging arrangement could each meet the goal under different conditions. Without those inputs, calling one option unavoidable would be premature.

## Sources and provenance

Public sources reviewed 30 October 2026. These provide context, not an endorsement of this skill or a claim that either author prescribed the workflow above.

- [Aristotle: Topics, Book I, translated by W. A. Pickard-Cambridge](https://classics.mit.edu/Aristotle/topics.1.i.html) — distinguishes reasoning from primary premises from reasoning based on accepted opinions.
- [Richard Feynman: Cargo Cult Science, Caltech (1974)](https://calteches.library.caltech.edu/51/2/CargoCult.htm) — examines intellectual honesty, alternative explanations, and evidence that could undermine a conclusion.
