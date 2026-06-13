---
title: 'Session 5: Validating Review Questions and Testing the Modular Review Arc'
authors: [courtney, daniela, rowan, chad]
date: 2026-05-19
downloads:
  - file: session-5-slides.pdf
    title: Session 5 Slides
---

| Date and time    | May 19, 2026 \- 60 minutes                                                                           |
| :--------------- | :--------------------------------------------------------------------------------------------------- |
| **Format**       | Virtual (Zoom)                                                                                       |
| **Hosts**        | Continuous Science Foundation × PREreview                                                            |
| **Facilitators** | Courtney Babott, Daniela Saderi, Rowan Cockett, and Chad Sansing                                     |
| **Theme**        | Running live reviews through the modular peer review system                                          |
| **Slides**       | [Session 5 Slides](./session-5-slides.pdf)                                                          |

## Overview

Session 5 shifted from design to hands-on testing. Instead of discussing hypotheticals, participants reviewed real preregistrations, datasets, and visualizations using the modular peer review framework. The goal was to pressure test the system:

- Are review functions and criteria useful?
- Do questions generate meaningful trust signals?
- Does the modular review arc work for different research objects?

This live review was the first practical trial, revealing both where the framework succeeds and where it needs refinement.

## System Map Update

The session opened with a review of the latest version of the Modular Review System Map. One of the most significant changes from Session 4 was the removal of outcomes from the framework.

Following extensive discussion in the previous session, participants concluded that outcomes risked reintroducing the kinds of binary decisions modular review was intended to move beyond. Rather than producing pass/fail decisions, the purpose of modular review appeared to be to generate trust signals that could accompany an object and support future interpretation, reuse, and decision-making. As a result, the review arc was simplified to:

**Object → Function → Criteria → Signal → Capture**

The group also incorporated the radar-chart concept proposed during Session 4. Instead of reducing review into a single score, signals could potentially be represented as a multidimensional trust profile, preserving nuance across dimensions such as robustness, reproducibility, clarity, usefulness, risk, care, compliance, and maturity.

Participants were reminded that the primary objective of Session 5 was to determine whether the review questions actually generated useful trust signals.

:::{figure #fig-session5-system-map} ./images/session-5-system-map.png
The updated DRAFT v2 system map, simplified to the Object → Function → Criteria → Signal → Capture arc, with a radar chart representing trust signals as a multidimensional profile rather than a single score.
:::

## The Live Review Exercise

Participants returned to their three object-based subgroups:

- Preregistration
- Dataset
- Figures and Visualizations

Each group received a live research object and a structured review worksheet. The worksheet walked participants through the modular review arc, asking them to:

1. Identify the lifecycle stage and object.
2. Define the purpose of the review.
3. Test review criteria and questions
4. Assess resulting trust signals.
5. Consider what should be captured and preserved with the object.

The exercise intentionally emphasized learning through use. Rather than debating the framework in the abstract, participants were asked to experience what it felt like to review a modular object using the proposed system.

## Visualization Group

The visualization group reviewed a figure, code, and data from a published article.

Key highlights:

- Review purpose often depends on who requests it; many figure reviews are for iteration and feedback, not just evaluation.
- Essential questions: Is the figure accurate, understandable on its own, context-rich, data-rich, and accessible?
- Editorial and accessibility issues were common and could often be addressed with automated checks.
- The figure often requires the context of the full article they sit within.
- Strongest trust signals were clarity, reproducibility, and care, especially where code and communication effort were evident.
- Improvements are needed for standalone clarity and interpretability.

## Dataset Group

The dataset group reviewed a user survey dataset and raised several key issues:

- Datasets often span multiple lifecycle stages and typically require context from related materials (protocols, code, instruments).
- Modular objects are rarely reviewed in isolation.
- Important review motivations: accurate representation, transparency, soundness, and especially reuse and clarity, which may deserve their own functions.
- Functions, criteria, and signals should be explicitly mapped for structure and consistency.
- _Key review questions:_ metadata quality, file formats, completeness, and handling missing data—all supporting robustness, reproducibility, and usefulness.
- _Debate_: scoring signals numerically risks metric-driven behavior; focus should be on issue severity, with reviewer confidence noted.
- Trust signals depend on reviewer expertise and accountability, raising governance questions around reputation and conflict of interest.

## Preregistration Group

The group reviewed an open preregistration and focused on the ambiguity of review functions.

Key points:

- Preregistration covers both conceive and plan stages, but distinctions between soundness, accurate representation, and refinement were unclear and often overlapped.
- Review often blends evaluation (Is the study sound enough to proceed?) with development (How can it be improved?).
- _Review criteria included:_ compliance with standards, study design, ethics, resource awareness, value of null results, and feasibility.
- Null results were emphasized as valuable, reframing questions to focus on whether the research question justifies resource investment.
- Feasibility was proposed as a new signal: does the study seem realistically doable?
- The group did not complete signal mapping due to time, and overall found that review functions need more clarity before consistent application is possible.

## Emerging Themes

Several themes emerged consistently across all three groups.

### Functions, Criteria, and Signals May Need Explicit Mapping

The review functions should map to specific criteria and signal types. Rather than asking reviewers to start from a blank page, future versions of the framework may provide recommended criteria based on the selected object and review purpose.

### Signals Should Preserve Nuance

Trust signals are preferred for feedback on scientific objects, preserving nuance and multidimensionality. Radar charts visualize this complexity, but numerical scores risk oversimplifying rich judgments.

### Review Functions Need Greater Clarity

The greatest challenge was clarifying the purpose of review functions. Categories like soundness, accurate representation, and refinement often overlap, especially when evaluation and improvement occur together. Refining these definitions is essential for effective adoption and consistent use.

### New Concepts Continue to Emerge

The exercise surfaced several concepts to include in the functions and signals.

- Reuse as a distinct review function
- Clarity as a review function
- Feasibility as a signal
- Reviewer confidence as a companion signal
- Explicit mappings between functions, criteria, and signals
