# Practice workspace

Build one familiar multipass renderer first in D3D11, then in D3D12. Keep the scene
simple: a mesh, HDR target, compute postprocess, and tone mapping. Add culling later.

- [D3D11 workspace](01-d3d11/README.md): days 1–7.
- [D3D12 workspace](02-d3d12/README.md): days 8–42.
- shared/: add small utilities only after both backends make the need clear.

## Build scaffold

The root CMakeLists.txt discovers each backend once it has its own CMakeLists.txt.
There are initially no executable targets or downloaded dependencies. Implementing
the first starter is Day 1 work, with API calls kept visible for learning.

Use Windows, a C++ compiler, CMake, and Windows SDK headers/libraries. For example,
from a Visual Studio developer shell, after adding a backend target:

```powershell
cmake -S . -B build
cmake --build build --config Debug
```

Add shader compilation rules explicitly with the backend. Document the chosen HLSL
compiler and shader model; do not assume D3D11 and D3D12 use identical shader profiles.

## Evidence of completion

Correct image, relevant validation reviewed, explainable bindings and lifetimes,
and a capture summary when appropriate. Performance claims also require measurements.