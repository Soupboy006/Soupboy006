# Soupboy

**I build and ship Android apps and developer tools by directing AI.**

I don't hand-write the code — I plan the work, direct AI ([OpenCode](https://opencode.ai)), test on real hardware, and ship. No computer science degree, no team.

## Shipped and maintained upstream

Real fixes in the tools I depend on:

- **Turborepo on Android** ([termux-packages#32649](https://github.com/termux/termux-packages/pull/32649)) — made `turbo` build on all four Termux architectures by replacing its ghostty/zig terminal dependency with a pure-Rust fallback.
- **tdl byte-level resume** ([iyear/tdl#1388](https://github.com/iyear/tdl/pull/1388)) — interrupted Telegram downloads now continue where they stopped instead of starting over.
- **termux-packages revbump** ([#32175](https://github.com/termux/termux-packages/pull/32175)) — fixed dependency parsing for packages with version constraints.

## Currently

Building **tgstream** (local Telegram video streaming in Go) and keeping Termux packages buildable on Android.

## How I work

- AI writes the code; I bring the judgment — what to build, what to verify, what to ship.
- Verified on real hardware (Android / Termux), not just in theory.
- Built and fixed in public — ideas, mistakes, and fixes all visible.

## For non-coders

Want to start but think you can't? You're welcome here. Say hi in [welcome](https://github.com/Soupboy006/welcome/issues/1), or fork anything — it's all open source.
