# Warpkeep Water Engine

A planned home for reusable water-rendering work from
[Warpkeep](https://warpkeep.com/), a persistent strategy game about
a personal keep and a shared world worth returning to.

**Status: repository placeholder.** There is no engine implementation, installable
package, demo or test suite here yet. Start with this overview and the
[contributor guide](AGENTS.md). Project-authored software is covered by the
[Apache 2.0 license](LICENSE).

## Current water work

Warpkeep's water is currently implemented inside the game. Its 0.4 renderer
builds water geometry from public world cells and uses a standard material with
restrained color and opacity animation. Its quality and performance must be
judged in the actual Greater Realm scene. It does not import a package from
this repository. The implementation source is maintained in the private game
workspace; this public placeholder documents its role and direction.

The preserved Genesis 001 renderer has a separate water layer. That older
implementation and the current 0.4 path have different callers;
neither establishes that a standalone engine has been extracted or released.

## Direction

The 0.4 Verdant Citadel direction calls for water that gives the landscape
movement, depth and a clear shoreline while leaving journeys and resource
destinations easy to read. Phone responsiveness, stable visual quality and
graceful fallback matter alongside appearance.

A future extraction should follow demonstrated reuse: define a small rendering
interface, preserve source attribution, include an integrated example, and
measure the complete scene before promising performance. The game repository
remains the source of truth for implementation and release readiness.

## Related repositories

- [Warpkeep](https://warpkeep.com/) — the playable Alpha; 0.4 remains in development.
- [Warpkeep Live](https://github.com/ael-dev3/Warpkeep-Live) — published frontend
  assets and licensing records. Development source and creative archives remain
  private; their assets retain their own terms. This repository's software license
  does not cover them.
