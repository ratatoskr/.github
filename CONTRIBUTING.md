# Contributing

Thanks for wanting to help. This covers every Ratatoskr repo. Each one's README says how to build and test it.

## Before you start

- **Bugs:** open an issue with what you did, what you expected and what happened. Logs help. For Wraith, say which game and how you started it.
- **Small fixes:** send a pull request.
- **Anything bigger,** like a new feature or a change to an API: open an issue first, so we can agree on it before you spend the time.
- **Security problems:** don't open an issue. See [SECURITY.md](SECURITY.md).

## The CLA

By opening a pull request, you agree to the [Contributor License Agreement](https://docs.wraith.io/about/cla/). It keeps your copyright with you, and lets the project offer [commercial licenses](https://docs.wraith.io/about/commercial/) alongside the open source one. Please read it before sending code.

## What we won't take

- Anything that hides from, disables or gets around anti-cheat, or is made for cheating in online games. See [Anti-cheat](https://docs.wraith.io/about/anticheat/).
- Code you didn't write and can't license to us, or that comes under a license that doesn't fit the project's.

## Pull requests

- Keep each one to one change, with tests for what it adds or fixes.
- Run the tests, and `zig fmt` for Zig code. CI runs them too.
- Match the code around you. Comments are short and plain, and only where the code needs explaining.
- Don't hand-edit generated files. The build has a step that writes each one, named in its header.

### Zig repos

- Use the exact Zig version in the repo's `build.zig.zon`, under `minimum_zig_version`. Zig changes a lot between dev builds.
- Code builds for x64 and x86, and Salamander for Linux and macOS too. Don't assume 64-bit.
- Platform calls go through the platform layer, like `tuft_sys` or a `win/` folder, never straight from shared code.

## Questions

Open an issue on the repo. Be kind. Everyone here is doing this in their free time.
