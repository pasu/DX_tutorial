# Resources

Collected for this course on 2026-09-14. Read only the relevant sections each day.
Older tutorials explain concepts; use current Microsoft documentation to check API
contracts, SDK setup, compiler choices, and feature support.

| Key | Resource | Use |
| --- | --- | --- |
| GW | [Jendrik Illner: Learning D3D12](https://www.jendrikillner.com/post/d3d12-learning-plan/) | Original curated learning recommendations (2021) |
| Compare | [A Comparison of Modern Graphics APIs](https://alain.xyz/blog/comparison-of-modern-graphics-apis) | Map concepts across APIs |
| DX11 | [D3D11 documentation](https://learn.microsoft.com/en-us/windows/win32/direct3d11/atoc-dx-graphics-direct3d-11) | Resources, views, pipeline, mapping, shader interfaces |
| DX11 setup | [DirectXTK tutorials](https://github.com/microsoft/DirectXTK/wiki/Getting-Started) | Setup/examples; inspect what helpers abstract |
| Raw | [Raw DirectX 12](https://alain.xyz/blog/raw-directx12) | Compact complete application walkthrough |
| 3DGEP | [Learning DirectX 12](https://www.3dgep.com/learning-directx-12-1/) | Parts 1–2 API, Part 3 framework, Part 4 textures/mips |
| 3DGEP code | [LearningDirectX12 repository](https://github.com/jpvanoosten/LearningDirectX12) | Companion implementation |
| Samples | [Microsoft samples and MiniEngine](https://github.com/microsoft/DirectX-Graphics-Samples) | Small features first, architecture comparison later |
| Descriptors | [Sawicki: Do RTV and DSV descriptors make any sense?](https://asawicki.info/news_1772_secrets_of_direct3d_12_do_rtv_and_dsv_descriptors_make_any_sense) | Descriptor mechanics and lifetime discussion |
| Barriers | [Resource Barriers and State Tracking video](https://www.youtube.com/watch?v=nmB2XMasz2o) | Legacy D3D12 synchronization concepts |
| Enhanced | [Enhanced Barriers specification](https://microsoft.github.io/DirectX-Specs/d3d/D3D12EnhancedBarriers.html) | Synchronization, access, layout, aliasing |
| PIX | [Microsoft PIX video series](https://developer.microsoft.com/en-us/games/articles/2023/12/using-pix-to-optimize-your-pc-builds-and-diagnose-issues/) | GPU captures and timing captures |
| Reference | [D3D12 programming guide](https://learn.microsoft.com/en-us/windows/win32/direct3d12/directx-12-programming-guide) | Authoritative API guidance |
| Video library | [Microsoft DirectX 12 and Graphics Education](https://www.youtube.com/channel/UCiaX2B8XiXR70jaN7NK-FpA) | Selected technical talks |
| Debugging talk | [Optimizing and debugging your DirectX 12 game](https://learn.microsoft.com/en-us/shows/gdc-gdc-2018/10) | Later-stage debugging/performance study; older UI |

## Graphics Programming Weekly provenance

- Raw, Compare, 3DGEP, specs, and Microsoft samples are selected in the GW learning guide.
- The descriptor article appears in [issue 313](https://www.jendrikillner.com/post/graphics-programming-weekly-issue-313/).
- Enhanced barriers were covered in [issue 213](https://www.jendrikillner.com/post/graphics-programming-weekly-issue-213/).
- Daily ordering, exercises, and milestones are customized for this course rather
  than presented as Illner's own curriculum.

For new resources record: URL, author, date read, relevant section, takeaway, and
whether a claim is normative API behavior, vendor advice, or an implementation choice.
Link to original material rather than copying articles into this repository.