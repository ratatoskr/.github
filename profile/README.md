# Ratatoskr

Tools for modding Windows games, made in [Zig](https://ziglang.org).

- **[Wraith](https://github.com/ratatoskr/wraith)** is a mod loader. It runs inside the game with an overlay, mod manager, tweaks and a workbench for digging into how the game works. Mods are written in C#, Zig, JavaScript or Lua.
- **[Tuft](https://github.com/ratatoskr/tuft)** is the toolkit under Wraith: hooks, memory scans, assembly, DLL injection, and Dear ImGui drawn in the game for D3D, OpenGL and Vulkan.
- **[Salamander](https://github.com/ratatoskr/salamander)** gives Zig, C, C3, JavaScript and Lua typed interfaces to each other. Write an API once in a `.sal` schema, and plugins, scripts and native code all call each other through it.

Everything's pre-release, so expect things to change.

## Links

- [wraith.io](https://wraith.io) to get Wraith
- [docs.wraith.io](https://docs.wraith.io) for guides and the API
- [hub.wraith.io](https://hub.wraith.io) for mods
- [salamander.io](https://salamander.io) for Salamander

## Anti-cheat

Wraith is for single-player games, offline play and games that welcome mods. It doesn't hide from anti-cheat, and we won't help anyone get past it. See [Anti-cheat](https://docs.wraith.io/about/anticheat/).

## Helping out

Issues and pull requests are welcome. See [CONTRIBUTING.md](https://github.com/ratatoskr/.github/blob/main/CONTRIBUTING.md), and [SECURITY.md](https://github.com/ratatoskr/.github/blob/main/SECURITY.md) for anything security related.

<p align="center"><sub>Made with ♥ by <a href="https://github.com/asgardkat">Asgard</a></sub></p>
