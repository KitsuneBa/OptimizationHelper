# Optimization Helper

A comprehensive Unity editor window that inspects your VRChat avatars and Animator Controllers, calculates an accurate performance score, and provides one-click tools to reduce VRAM usage, clean materials, and locate heavy components.

---

## What It Does

Optimization Helper analyzes avatar hierarchies, components, meshes, textures, and animators directly in the Unity Editor. It flags performance bottlenecks, calculates exact GPU VRAM consumption, and provides utilities to optimize assets while preserving visual fidelity.

### Key Features

- **Performance Score & Grade:** Evaluates avatar components and Animator Controllers into a clear performance grade, with independent scoring for meshes and controllers.
- **PC, Mobile & Suggested Thresholds:** Compares polygons, skinned meshes, material slots, PhysBones, contacts, constraints, lights, and particles against standard VRChat limits and recommended creator targets.
- **Deep Controller Diagnostics:** Scans Animator Controllers for layers, states, sub-state machines, transitions, AnyState transitions, conditions, and Write Defaults consistency, with a sortable per-layer table to locate slow FX layers.
- **Texture & Material Optimization:** Batch-compress textures, configure crunch compression, strip unused serialized material properties, and adjust shadow casting and distance fade on lilToon and Poiyomi shaders.
- **Hierarchy Component Finder:** Search avatar hierarchies by component type (PhysBones, colliders, constraints, renderers, contacts) and sort by polygon or material count.
- **Exact Mesh & Texture VRAM Footprint:** Calculates GPU memory consumption in megabytes (MB) for every mesh and texture on the avatar.
- **One-Click Material Backup:** Automatically duplicates materials before bulk adjustments to prevent accidental data loss.

---

## Documentation

Full documentation and usage walkthroughs are available at:  
[Optimization Helper Documentation](https://kitsuneba.github.io/docs/optimization-helper/)

---

## Installation via VCC or ALCOM

Add the repository listing directly to your package manager:  
https://kitsuneba.github.io/KitsuneBaTools/

Or add it manually:
1. Open **VRChat Creator Companion (VCC)** or **ALCOM**.
2. Go to **Settings -> Packages -> Add Repository**.
3. Paste the listing URL:
   ```text
   https://kitsuneba.github.io/KitsuneBaTools/index.json
   ```
4. Click **Add**.

---

## License

See [LICENSE.md](LICENSE.md) for terms of use.
