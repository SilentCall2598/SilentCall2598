# SilentCall

**Rendering systems · Performance optimization · Minecraft modding**

Independent developer working on open-source projects for Minecraft Forge 1.12.2. My focus is on efficient implementations, compatibility, and measurable improvements backed by profiling and testing.

## Featured projects

### [Focalis](https://github.com/SilentCall2598/Focalis)

An experimental modular graphics and optimization project for Minecraft Forge 1.12.2. Development is focused on shader support, rendering infrastructure, and compatibility with modded environments.

**Status:** Active development. The shader pipeline is still under construction.

### [QuarryOpt](https://github.com/SilentCall2598/QuarryOpt)

A server-side performance patch for Extra Utilities 2 Quantum Quarries. It reduces unnecessary work in item filtering, drop handling, and chunk cleanup without changing quarry speed, yield, or energy use.

In matched Spark profiling runs, `TileQuarry.update` decreased from **6.50% to 3.90% of server-thread time** (roughly a **40% reduction in its measured share** under the tested workload, not a 40% overall server-performance gain).

**Release:** 1.0.1 · [CurseForge](https://www.curseforge.com/minecraft/mc-mods/quarry-opt) · [Modrinth](https://modrinth.com/project/LOK78gSf) · [Source code](https://github.com/SilentCall2598/QuarryOpt)

## Areas of interest

`Java` · `Minecraft Forge` · `OpenGL` · `Gradle` · `Git`

- Graphics programming and rendering pipelines
- Performance profiling and targeted optimization
- Mod compatibility, correctness, and regression testing

## Links

[Focalis community](https://discord.gg/wmJKKvkCMX) · [Focalis issues](https://github.com/SilentCall2598/Focalis/issues) · [QuarryOpt issues](https://github.com/SilentCall2598/QuarryOpt/issues)
