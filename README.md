# DirectX 11 → 12: engineering learning journal

A six-week, 42-day course for an experienced OpenGL/WebGL rendering engineer.
Repository: [pasu/DX_tutorial](https://github.com/pasu/DX_tutorial).
Budget: **30–60 minutes per day**. The goal is a working foundation and a small
renderer with explainable bindings, synchronization, ownership, and measurements.

## Start here

- [42-day schedule](SCHEDULE.md)
- [Verified resource links and reading guidance](RESOURCES.md)
- [Progress tracker](PROGRESS.md)
- [Day 01](notes/week-01/day-01.md)
- [Practice workspace](practice/README.md)
- [Daily workflow and remote setup](CONTRIBUTING.md)
- [Technical conclusions](conclusions/README.md)
- [Course roadmap image](assets/course-roadmap.png)

## Daily loop

Recall → read/watch → implement → discuss → record evidence.

For 30 minutes: 5 recall + 10 reading + 10 practice + 5 notes/discussion.
For 60 minutes: 5 recall + 15 reading + 30 practice + 10 notes/discussion.
Some implementation labs need several sessions. Use the weekly review day to
catch up, then move the schedule forward rather than exceeding the time budget.

Open today's note, state your available time, and bring the current question to
our discussion. Afterwards record the conclusion in your own words, its evidence,
and its limits. A planned exercise is never evidence that it was completed.

## Repository layout

```text
notes/week-01/ … week-06/  Daily exercises and discussion notes
conclusions/              Cross-cutting decisions and validated understanding
practice/01-d3d11/         D3D11 renderer workspace
practice/02-d3d12/         D3D12 renderer workspace
practice/shared/          Small genuinely shared utilities
captures/                 Capture summaries; large binary captures stay local
templates/                Reusable daily, conclusion, and capture templates
assets/                   Course roadmap
```

This initial repository contains planning and project scaffolding, not a completed
renderer. Practice code will be added as part of learning. No exercise is marked done.
The existing [Apache 2.0 license](LICENSE) is preserved.
Keep imported sample code's upstream license and attribution. This repository does
not assign a new license to third-party material.
