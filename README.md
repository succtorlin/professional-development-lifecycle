# Professional Development Lifecycle

![Skill status](https://img.shields.io/badge/status-validated-2ea44f)
![Source books](https://img.shields.io/badge/source_books-2-6f42c1)
![License](https://img.shields.io/badge/license-MIT-blue)

Design professional learning that changes educator practice—and prove whether it changed student learning.

`professional-development-lifecycle` is a reusable AI skill for connecting two decisions that are often separated:

1. **What should educators learn and do?**
2. **How will we know the learning worked?**

It combines an education-practice module with a professional-development evaluation module, then routes each request to the smallest useful set of guidance.

## The lifecycle

```text
Learning goals & standards
          ↓
Assessment, feedback, grading & reporting
          ↓
Professional learning design & implementation
          ↓
Evaluation: reaction → learning → organization → use → student outcomes
          ↓
Evidence-based redesign
```

The result is a practical loop rather than a one-time workshop: align the goal, design the learning, support transfer, collect evidence, and improve the next cycle.

## What it can do

| Need | The skill helps you… |
| --- | --- |
| Practice design | Clarify standards, essential questions, formative assessment, grading, and reporting decisions. |
| PD design | Turn a learner or system need into outcomes, learning experiences, transfer supports, and evidence. |
| PD evaluation | Build a five-level evidence plan: participant reaction, learning, organizational support, use, and student outcomes. |
| Full lifecycle | Connect teacher learning to classroom implementation and student-facing results without overclaiming causality. |

## Included modules

- [`SKILL.md`](SKILL.md) — routing, lifecycle workflow, quality checks, and boundaries.
- [`education-practice-essentials.md`](references/modules/education-practice-essentials.md) — standards, assessment, grading, reporting, and instructional coherence.
- [`professional-development-evaluation.md`](references/modules/professional-development-evaluation.md) — evaluation questions, evidence sources, implementation fidelity, and decision rules.

## Install

Copy the folder into the skills directory used by your assistant:

```bash
cp -R professional-development-lifecycle ~/.codex/skills/
```

For a manual setup, place this repository at `professional-development-lifecycle` inside your assistant's skills directory and keep the relative `references/modules/` paths intact.

## Example prompts

Try prompts such as:

```text
Design a six-month PD cycle for improving formative assessment and define evidence at every level.

Audit this grading initiative: identify the essential questions, implementation risks, and evaluation measures.

Create a launch-and-follow-up plan that connects teacher learning to student outcomes without confusing correlation with causation.
```

## Design principles

- Start with the problem of practice, not the event calendar.
- Make intended educator behavior observable.
- Treat transfer conditions—time, leadership, tools, collaboration—as part of the intervention.
- Use multiple evidence sources and distinguish implementation from impact.
- Prefer decision-ready evidence over impressive but unused data.
- Protect privacy and avoid attributing student results to PD without a credible design.

## Why this exists

PD teams commonly have strong workshop plans but weak transfer evidence, while evaluation teams often measure attendance and satisfaction without tracing changes in practice. This skill makes the connection explicit so a plan can answer both **“what changes?”** and **“what evidence would convince us?”**

## Contributing

Suggestions are welcome. Open an issue or pull request with:

- a concrete education or PD use case;
- the evidence or decision the skill should support;
- proposed wording that preserves the skill's boundaries and avoids unsupported causal claims.

## Sources

The synthesis is based on the companion source work used to create the two modules: *Answers to Essential Questions About Standards, Assessments, Grading, and Reporting* and *Evaluating Professional Development*.

## License

MIT — see [`LICENSE`](LICENSE).
