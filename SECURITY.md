# Security

## Reporting a problem

Please don't open a public issue. Use **Report a vulnerability** on the repo's Security tab, which only the maintainers can see. Say what's affected, how to reproduce it, and what someone could do with it.

We'll reply within a week, and keep you posted while it's fixed. Once a fix is out we're happy to credit you, unless you'd rather not be.

## What's supported

Everything here is pre-release, so only the latest release gets fixes.

## In scope

Things like:

- Installing or updating a mod in a way the user didn't agree to, like getting around the Hub's signature or hash checks
- A mod's zip writing files outside its own folder
- Another user or program on the PC driving Wraith, or the Wraith app, without permission
- The Hub: getting into someone else's account, publishing as someone else, or seeing data you shouldn't
- Memory safety bugs reachable from files, schemas, scripts or the network

## Not in scope

- **What mods can do.** Plugins run native code inside the game with the same rights as the game. That's what they're for, so only install mods you trust. Report a harmful mod on its page on the [Hub](https://hub.wraith.io) instead, and it'll be pulled.
- **Anti-cheat.** Wraith doesn't hide from it, on purpose, so a game spotting Wraith isn't a bug. See [Anti-cheat](https://docs.wraith.io/about/anticheat/).
- Problems in a game itself, or in the third-party libraries we use. Report those upstream, though tell us if Wraith makes one worse.
