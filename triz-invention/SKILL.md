---
name: triz-invention
description: Apply TRIZ-inspired contradiction analysis to technical inventions and product or process tradeoffs. Use when improving one property worsens another, or one component needs conflicting properties under different conditions. Produces explicit problem models, alternative mechanisms, and validation plans without claiming engineering performance or novelty from an idea alone.
---

# TRIZ-inspired invention

Investigate the conflict preventing a technical system from improving. This is an independent adaptation of public TRIZ material associated with Genrich Altshuller's tradition. It uses selected problem models and invention heuristics, not a claim to reproduce the complete TRIZ methodology or a certified analysis.

## Describe the real system

Identify the useful function, the interacting components, operating conditions, and the unwanted effect. Include the surrounding system when it materially affects the problem. Preserve the user's outcome and hard requirements. Establish units, loads, dimensions, and other parameters from supplied data or clearly marked assumptions.

Separate a physical limit from a limitation of the current architecture. If the causal mechanism is unknown, propose a diagnostic observation or test rather than disguising uncertainty with technical terminology.

## Model the contradiction

For an engineering contradiction, state the proposed change, the property it improves, and the different property it worsens. Describe the mechanism connecting them. A generic wish for higher quality at lower cost is not yet a useful technical model.

For a physical contradiction, identify a single parameter or property that has opposing justified requirements. Specify where, when, or under which operating conditions each requirement applies. Do not manufacture a contradiction if one of the supposed requirements can simply be removed.

Use the model that best exposes a path forward. Multiple formulations may be useful, but do not force every design problem through both forms.

## Explore mechanisms that change the conflict

For a physical contradiction, investigate whether the requirements can be satisfied at different times, locations, conditions, or system levels. For an engineering contradiction, use relevant invention heuristics such as segmentation, changing local properties, advance preparation, or adjustable configuration. Explain the proposed mechanism rather than listing principle names.

If using a published contradiction matrix, consult the actual version and document the parameter mapping. Do not invent a matrix lookup, principle number, or claim that the matrix prescribed an idea. A heuristic used directly should be described as a heuristic.

Consider the useful function in an idealized form: how might it be supplied with fewer added burdens? Inventory existing material, space, time, energy, information, and surrounding resources that could help. Resource reuse is a design direction, not permission to ignore conservation laws or physical constraints.

## Develop and challenge candidates

Produce distinct candidate mechanisms where the problem warrants alternatives. For each, explain what changes, how it could satisfy the conflicting requirements, what remains unresolved, and any new failure mode. Keep ordinary optimization available when it is sufficient; invention is not always the best next step.

Compare the candidates with the actual requirements and operating envelope. Check consequences that materially affect the design, such as reach, stability, pinch points, maintenance, or tolerance sensitivity. Do not substitute a generic safety checklist for analysis of the mechanism.

## Specify the proof needed

Choose a calculation, simulation, or prototype that can test the claimed improvement and the protected property together. State conditions and proposed acceptance targets. Keep targets, estimates, and measured results distinct. An appearance model or keyframed animation does not establish mechanical or autonomous performance.

Deliver the contradiction, candidate mechanisms, reasoning, and next verification step at the requested depth. Do not claim patent novelty, manufacturability, certified safety, or achieved performance without corresponding evidence. Preparing concepts does not authorize fabrication or external testing.

### Original example

A cart may need a narrow footprint in an aisle and a wider support base during a reach. A changeable stance is one candidate to investigate. It also introduces transitions, floor-space demands, and possible pinch points; its appearance in a render would not demonstrate stable loaded operation.

## Sources

Public sources reviewed 30 October 2026. No affiliation or endorsement is implied.

- [MATRIZ: Engineering contradiction](https://wiki.matriz.org/docs/triz/problem-solving-tools-5890/contradictions/engineering-contradiction-5995/) — conflicting effects on different parameters.
- [MATRIZ: Physical contradiction](https://wiki.matriz.org/docs/triz/problem-solving-tools-5890/contradictions/physical-contradiction-6056/) — opposing requirements for one parameter.
- [MATRIZ: Inventive principles](https://wiki.matriz.org/docs/triz/problem-solving-tools-5890/contradictions/inventive-principles-6023/) — generalized solution heuristics.
- [Technical Innovation Center: Ideality](https://triz.org/ideality/) — useful function and use of existing resources.
