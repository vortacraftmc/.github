# Contributing

Thanks for wanting to help. This is the default guide for all vortacraftmc repositories.
A repository may add its own `CONTRIBUTING.md`, which then takes priority. For the main
monorepo see
[`vortacraftmc/core`](https://github.com/vortacraftmc/core/blob/main/CONTRIBUTING.md).

## Before you start

- Search existing issues and pull requests first.
- For larger changes, open an issue to discuss the idea before writing code.
- Read the repository's `README` and `NOTICE`, if present, for build and layout details.

## Making a change

1. Fork the repository and create a branch from `main`.
2. Keep the change focused - one topic per pull request.
3. Run the repository's build and lint checks (for `core`: `./gradlew buildAll` and
   `./gradlew lint`). Gradle passing does not validate a datapack; load the pack in-game to
   check it.
4. Open a pull request and fill in the template, saying whether it touches mods, packs, or
   both.

## Ground rules

- Do not add obfuscated code, hidden network calls or behavior that the pull request does
  not describe.
- Avoid new dependencies unless they are necessary.
- Keep function, tag and scoreboard names namespaced so they cannot collide with other packs.
- Do not remove or alter existing copyright, license or origin notices (including
  attribution to the original source, Runtoolkit).
- Report security problems privately - see [SECURITY](SECURITY.md).

## Licensing

Unless a repository says otherwise, your contribution is licensed under that repository's
`LICENSE`. Only submit work you have the right to contribute.

## Conduct

Everyone taking part is expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
