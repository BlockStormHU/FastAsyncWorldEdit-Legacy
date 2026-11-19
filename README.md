<div align="center">

# ⚡ FastAsyncWorldEdit Legacy

**Fast, asynchronous WorldEdit for Paper 1.8.8 servers.**

[![Latest release](https://img.shields.io/github/v/release/BlockStormHU/mc-fastasyncworldedit-legacy-fork?label=release)](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/releases/latest)
![Paper 1.8.8](https://img.shields.io/badge/Paper-1.8.8-0e7490)
![Java 8+](https://img.shields.io/badge/Java-8%2B-orange?logo=openjdk&logoColor=white)
![WorldEdit 6](https://img.shields.io/badge/requires-WorldEdit%206.1-dc2626)
[![License: GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-blue)](LICENSE)

> BlockStorm's fork of [RefineDevelopment/FastAsyncWorldEdit-Legacy](https://github.com/RefineDevelopment/FastAsyncWorldEdit-Legacy).

</div>

---

FastAsyncWorldEdit (FAWE) is a plugin that sits on top of WorldEdit 6 and runs edits off the main thread, so large
`//set`, `//paste` and brush operations don't freeze the server. This is the legacy codebase, kept for Paper 1.8.8
servers. It is not the modern FAWE and does not support newer Minecraft versions.

This fork has no code changes. BlockStorm keeps it to build and publish ready-to-use jars through GitHub Actions.

## ✨ At a glance

- ⚡ Asynchronous, chunk-based block placement for WorldEdit commands
- 💾 Undo history and clipboard stored on disk, with `//frb` rollback and an inspect tool
- 🚦 Per-group limits (`fawe.limit.<group>`) and a memory guard that cancels oversized edits
- 🛡️ Optional region restrictions for WorldGuard, PlotSquared, PlotMe, Residence, GriefPrevention and ASkyBlock
- 💡 Lighting fixes, including a hook for the Carbon lighting engine
- 🧹 A tick limiter for falling blocks, physics and item spawns

## 📖 Documentation

Everything else is in the [wiki](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki):

- [Installation](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki/Installation)
- [Commands and Permissions](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki/Commands-and-Permissions)
- [Configuration](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki/Configuration)
- [Region Restrictions](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki/Region-Restrictions)
- [Original README](https://github.com/BlockStormHU/mc-fastasyncworldedit-legacy-fork/wiki/Original-README)

---

<div align="center">
<sub>FastAsyncWorldEdit was created by <b>Jesse Boyd</b> (Empire92) and the FAWE contributors · Legacy 1.8 work by <a href="https://github.com/RefineDevelopment">RefineDevelopment</a> and earlier forks · Maintained by <b>BlockStorm</b> · Licensed under the <a href="LICENSE">GNU GPL v3.0</a></sub>
</div>
