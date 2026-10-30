---
name: calibrated-forecasting
description: Structure and review probabilistic forecasts using reference classes, explicit evidence, updates, and outcome tracking inspired by Philip Tetlock and forecasting research. Use when estimating whether a defined event will happen by a deadline or improving a forecast record. Does not treat a plausible narrative or an untested probability as demonstrated forecasting skill.
---

# Calibrated forecasting

Make predictions that can be inspected, updated, and checked. This is an independent application of public work by Philip Tetlock and colleagues. Calibration is a property assessed over a collection of resolved forecasts; the skill's name does not claim that any newly generated estimate is already calibrated.

## Define a resolvable question

Specify the event, deadline, scope, and source or rule that will determine the outcome. Clarify ambiguous terms when they could change resolution. Preserve the user's actual question. If it cannot be resolved directly, propose a useful measurable subquestion and explain the limitation rather than silently substituting it.

Keep a forecast about what will happen distinct from a recommendation about what to do. An action can be worthwhile despite a low chance of success, or unwise despite a likely favorable outcome, depending on the consequences and alternatives.

## Build an evidence-based estimate

Look for a relevant reference class: comparable cases with known outcomes and a defensible denominator. Explain why those cases are comparable, which cases were excluded, and how their context differs. Do not manufacture a base rate or treat missing information as a 50 percent probability.

Use specific evidence to consider how the present case departs from that starting point. Check at least one plausible alternative explanation when it could alter the estimate. Distinguish current reporting, historical data, the user's assumptions, and the forecaster's judgment. Verify time-sensitive facts with current sources.

When decomposing a question, state dependencies. Do not multiply event probabilities as if the events were independent unless that assumption is justified. Use formal Bayesian updating only when the needed inputs can be defended; do not decorate a subjective adjustment with invented likelihood ratios.

Report a probability at a precision warranted by the evidence, with the main reasons and material uncertainty. If the evidence is too weak to estimate usefully, say so and identify the most valuable missing information. A qualitative assessment is preferable to an arbitrary percentage presented as measurement.

## Make updates inspectable

Record the question, estimate, timestamp, evidence cutoff, rationale, and what information would move the estimate. When new evidence arrives, explain why the probability changes or remains similar. Distinguish a substantive update from a wording or resolution-rule change. Preserve earlier estimates rather than rewriting the record after the result is known.

Do not create a monitoring or notification process unless requested. Provide update triggers as part of the forecast; they are not authorization to run scheduled checks.

## Evaluate after resolution

Apply the agreed resolution rule and retain unresolved or void cases transparently. For a binary event, one useful scoring convention is the squared error `(p - y)^2`, where `p` is the predicted probability from 0 to 1 and `y` is 1 if the event occurred and 0 otherwise; lower is better. State the convention and evaluate comparable forecasts consistently.

Across enough resolved cases, compare predicted probabilities with observed frequencies, note sample sizes, and compare against a simple baseline. Avoid judging probability quality from one surprising outcome. Account for differing horizons and multiple updates rather than treating every update as an independent event.

Deliver the forecast or review the user requested, with a compact evidence trail. Do not claim a track record, accuracy improvement, or validated model without actual records.

### Original example

Will a robot-cart pilot succeed is too ambiguous to score. A possible revision is whether a specified store will renew its pilot by an agreed date under stated terms. That question is resolvable, but any estimated renewal probability still needs evidence.

## Sources

Public sources reviewed 30 October 2026. No affiliation or endorsement is implied.

- [Philip Tetlock: Superforecasting master class](https://www.edge.org/event/a-short-course-in-superforecasting%E2%80%94philip-tetlock-an-edge-master-class) — explicit probabilities, defined questions, and forecasting practice.
- [Tetlock: Master class, Class II](https://www.edge.org/conversation/philip_tetlock-edge-master-class-2015-a-short-course-in-superforecasting-class-ii) — reference classes and updating.
- [Mellers and colleagues (2014)](https://escholarship.org/uc/item/4rg4n9vr) — primary research on training, collaboration, and forecast evaluation.
