---
name: professional-development-lifecycle
description: |
  Use when an education or professional-development team needs to connect what educators should learn, how learning should be assessed, how grading/reporting should express student learning, and how to evaluate whether the PD changed practice or student outcomes. Trigger phrases include “design PD,” “PD essentials,” “formative assessment,” “grading policy,” “standards-based report card,” “evaluate professional development,” “measure training impact,” “implementation fidelity,” “student outcomes from teacher learning,” or “专业发展核心实践/专业发展评估”. Route practice-design questions to the education-practice module and impact/effectiveness questions to the PD-evaluation module. Do not use as a substitute for current legal advice, psychometric validation, privacy compliance, or causal-inference expertise.
metadata:
  merged-from: [pd-essential-education, professional-development-evaluation]
  merge-model: layered-umbrella-with-internal-modules
  source-books: [Guskey & Jung 2013, Guskey 2000]
  module-count: 2
---

# Professional Development Lifecycle

## Purpose

This skill connects two questions that are often handled separately:

1. **Practice design:** What should educators and students learn, how should evidence guide instruction, and how should grades/reports communicate it?
2. **PD evaluation:** Did the professional-development effort build that practice, receive organizational support, get used, and contribute to student outcomes?

Use the smallest module set that answers the request. Load both only when the task crosses from designing the educational practice into evaluating the PD that develops it.

## Lifecycle map

```text
Learning goals and standards
        ↓
Assessment, formative response, grading, and reporting practice
        ↓
Professional-development design and implementation
        ↓
PD evaluation: reactions → learning → organizational support → use → student outcomes
        ↓
Evidence-based redesign and next PD cycle
```

## Routing

| User intent | Load first | Add the other module when |
|---|---|---|
| Clarify standards, assessment purpose, formative feedback, common assessments, grading, reporting, family communication, accommodation/modification | `references/modules/education-practice-essentials.md` | The user also asks whether a PD program successfully taught or changed that practice |
| Design or evaluate PD, implementation, organizational support, teacher use, student outcomes, continuation/scale/stop decisions | `references/modules/professional-development-evaluation.md` | The evaluation depends on defining the educational practice or evidence that PD is intended to change |
| Design a PD program that teaches better assessment/grading/reporting and evaluate whether it worked | Load both modules in order: education practice → PD evaluation | Always |

## Integrated execution

1. **Define the target practice.** State what educators should do, what students should learn and be able to do, what evidence represents it, and what grades/reports should mean.
2. **Design the PD around the target.** Specify participants, learning experiences, practice opportunities, organizational supports, coaching/follow-up, and intended student/organizational results.
3. **Plan evaluation before launch.** Name stakeholders, decisions, baselines, indicators, timing, sources, owners, and boundaries. Use the five PD-evaluation levels when impact is in scope.
4. **Run the practice and feedback loops.** Use formative evidence to correct and enrich learning; use common assessment/team analysis when collaborative improvement is needed.
5. **Evaluate implementation and impact.** Assess participant learning, organizational support, quality/amount of use, and aligned student outcomes. Do not treat satisfaction or a new report-card format as proof.
6. **Redesign and repeat.** Produce a decision-ready report with evidence, limitations, unintended effects, and continue/expand/modify/stop recommendations; feed findings into the next practice and PD cycle.

## Required boundaries

- Do not begin with a workshop, survey, gradebook, or report-card template before clarifying the learning target and decision.
- Do not treat attendance, satisfaction, a formative quiz, a new grading scale, or a positive score trend as proof of PD effectiveness.
- Do not confuse accommodation (access support) with modification (changed target); current local policy and qualified specialists control legal decisions.
- Do not claim PD caused student outcomes without appropriate timing, comparison/baseline, implementation evidence, and consideration of alternatives.
- Escalate current legal, psychometric, privacy, accessibility, equity, and causal-inference questions to the relevant specialist method.

## Internal modules

- [Education practice essentials](./references/modules/education-practice-essentials.md)
- [Professional-development evaluation](./references/modules/professional-development-evaluation.md)

## Example routing

- “How do we teach common formative assessment and use the results?” → education-practice module.
- “Did our teacher training change classroom practice?” → PD-evaluation module.
- “Design PD that improves formative assessment, then specify how we will know it worked.” → both, in lifecycle order.

## Audit note

This umbrella preserves the original source-grounded modules and narrows their overlap through explicit routing. The original installed packages remain available as rollback copies; the umbrella is the recommended discoverable entry for cross-lifecycle requests.
