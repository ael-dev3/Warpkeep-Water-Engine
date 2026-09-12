# Working on Warpkeep Water Engine

Read [README.md](README.md) first. This repository is a planned extraction point,
not an implemented engine. Current user instructions take precedence over older
plans; describe the checked-in implementation and observed results accurately.

Before adding a package, inspect the game's current 0.4 Greater Realm renderer
and its actual callers. Keep game authority, world cells and gameplay routes in
the game. Define a reusable rendering boundary only when integration or another
real consumer makes it useful. Preserve the separate G001 rendering path.

Judge water in its complete scene: shoreline readability, camera distance,
loading, quality fallback, reduced motion, context restoration and disposal.
Record desktop, emulated mobile and physical-device evidence separately. Added
reflections, geometry or animation need a visible benefit and measured cost;
neither a screenshot nor a draw-call count establishes mobile performance.

Preserve source attribution and inspect the terms of any imported code or media.
The [Apache 2.0 software license](LICENSE) does not relicense material from the
mixed-license [asset archive](https://github.com/ael-dev3/Warpkeep-Assets).

For documentation, verify linked source paths and claims. Once implementation
exists, document its actual install/build/test commands and exercise a real game
integration, resource cleanup and fallback behavior. Do not invent commands,
publish an empty package, or describe an unmeasured prototype as production-ready.

Commit and push each completed development change after proportionate review and
verification. Before handing off, publish all durable work authored for the task,
including unfinished source with its actual limitations. Do not wait for an
engine release or game deployment to back up development.

Fetch the verified owning remote and resolve the current authorized branch.
Stage exact reviewed paths, scan the entire outgoing commit range for secrets,
push the full reviewed SHA without force, and verify the live remote ref.
Preserve unrelated edits, private data and active generated families; exclude
caches, dependencies and disposable builds. If publication fails, retain the
work, record the exact failure, and retry when it clears. Do not recreate a
merged or deleted branch or redirect unfinished work into main automatically.

Update the README when the repository gains a real implementation or release.
Source publication and a working Warpkeep deployment are separate outcomes.
