# Six-week schedule

30–60 minutes per day; days are relative, not calendar deadlines.

Resources use the keys in [RESOURCES.md](RESOURCES.md). Each daily note contains its exercise and optional stretch.

## Week 1 — D3D11 translation

Milestone: Explain a validated multipass D3D11 frame.

Resources: DX11, Compare.

| Day | Topic |
| --- | --- |
| 01 | [API map and starter](notes/week-01/day-01.md) |
| 02 | [Pipeline and validation](notes/week-01/day-02.md) |
| 03 | [GLSL to HLSL](notes/week-01/day-03.md) |
| 04 | [Textures and views](notes/week-01/day-04.md) |
| 05 | [HDR and tone mapping](notes/week-01/day-05.md) |
| 06 | [Compute and hazards](notes/week-01/day-06.md) |
| 07 | [Week 1 review](notes/week-01/day-07.md) |

## Week 2 — D3D12 execution

Milestone: Prove command allocator and resource reuse is safe.

Resources: Raw, Reference, PIX.

| Day | Topic |
| --- | --- |
| 08 | [Raw D3D12 and object model](notes/week-02/day-08.md) |
| 09 | [Lists and allocators](notes/week-02/day-09.md) |
| 10 | [Swap chain and presentation](notes/week-02/day-10.md) |
| 11 | [Fences and timelines](notes/week-02/day-11.md) |
| 12 | [Frames in flight](notes/week-02/day-12.md) |
| 13 | [PIX capture](notes/week-02/day-13.md) |
| 14 | [Week 2 review](notes/week-02/day-14.md) |

## Week 3 — Memory and binding

Milestone: Distinguish resource, descriptor, and memory lifetimes.

Resources: 3DGEP, Descriptors, Reference.

| Day | Topic |
| --- | --- |
| 15 | [Heaps and mesh uploads](notes/week-03/day-15.md) |
| 16 | [Texture footprints](notes/week-03/day-16.md) |
| 17 | [Per-frame constants](notes/week-03/day-17.md) |
| 18 | [Root signatures](notes/week-03/day-18.md) |
| 19 | [Materials and descriptors](notes/week-03/day-19.md) |
| 20 | [RTV and DSV descriptors](notes/week-03/day-20.md) |
| 21 | [Week 3 review](notes/week-03/day-21.md) |

## Week 4 — Synchronization

Milestone: Justify every dependency, barrier, and wait.

Resources: Barriers, Enhanced, 3DGEP.

| Day | Topic |
| --- | --- |
| 22 | [Dependency table](notes/week-04/day-22.md) |
| 23 | [Legacy transitions](notes/week-04/day-23.md) |
| 24 | [UAV ordering](notes/week-04/day-24.md) |
| 25 | [Compute mip generation](notes/week-04/day-25.md) |
| 26 | [Enhanced barriers](notes/week-04/day-26.md) |
| 27 | [Cross-queue handoff](notes/week-04/day-27.md) |
| 28 | [Week 4 review](notes/week-04/day-28.md) |

## Week 5 — Renderer systems

Milestone: Build reliable ownership and allocation systems.

Resources: Samples, Reference.

| Day | Topic |
| --- | --- |
| 29 | [Deferred destruction](notes/week-05/day-29.md) |
| 30 | [Upload allocation](notes/week-05/day-30.md) |
| 31 | [Descriptor retirement](notes/week-05/day-31.md) |
| 32 | [MiniEngine comparison](notes/week-05/day-32.md) |
| 33 | [PSOs and shader compilation](notes/week-05/day-33.md) |
| 34 | [Robustness](notes/week-05/day-34.md) |
| 35 | [Week 5 review](notes/week-05/day-35.md) |

## Week 6 — GPU-driven rendering and profiling

Milestone: Support performance decisions with measurements.

Resources: Samples, PIX, Reference.

| Day | Topic |
| --- | --- |
| 36 | [ExecuteIndirect](notes/week-06/day-36.md) |
| 37 | [Compute culling](notes/week-06/day-37.md) |
| 38 | [PIX measurement](notes/week-06/day-38.md) |
| 39 | [Parallel recording](notes/week-06/day-39.md) |
| 40 | [Async compute](notes/week-06/day-40.md) |
| 41 | [Transient aliasing](notes/week-06/day-41.md) |
| 42 | [Final review](notes/week-06/day-42.md) |
