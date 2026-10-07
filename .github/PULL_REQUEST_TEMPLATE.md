## What does this change?

<!-- One or two sentences. Say whether it touches mods, packs, scripts or docs. -->

## Why?

<!-- Link the issue if there is one. -->

## Scope

- [ ] `mods/` (Fabric mods - Gradle subprojects)
- [ ] `packs/` (datapacks / resource packs)
- [ ] `scripts/` (tooling)
- [ ] `examples/`
- [ ] docs only

## Checks

- [ ] `./gradlew buildAll` passes
- [ ] `./gradlew lint` passes
- [ ] If `packs/` was touched: the pack was **loaded in-game** and verified
      (CI's Mecha lint only checks command syntax, it never loads the pack)
- [ ] No new dependencies unless they are necessary, and each one is explained
- [ ] No obfuscation, hidden network calls, or behavior not described above

## Notes for reviewers

<!-- Anything risky, anything deliberately left out, anything that needs a
     second pair of eyes. -->
