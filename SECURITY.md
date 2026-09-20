# Security Policy

## Reporting a vulnerability

**Please do not open a public issue, pull request or discussion for a security problem.**

Report it privately instead:

1. Go to the **Security** tab of the affected repository.
2. Choose **Report a vulnerability** (GitHub private vulnerability reporting).

For the main repository that is:
<https://github.com/vortacraftmc/core/security/advisories/new>

If private reporting is not available for a repository, contact a maintainer directly
through GitHub and share details only once a private channel is established.

Please include:

- the affected project, version or commit
- Minecraft version and loader (Fabric) version, if relevant
- clear steps to reproduce, and the impact you observed
- a proof of concept **only if** it can be shared safely in a private report

## What counts as a security issue

This organization ships datapacks and mods that generate and run commands, so the areas we
care about most are:

- **Macro / command injection** - attacker-controlled input reaching function macros or
  dynamically generated commands
- **Namespace isolation** - a pack overwriting, shadowing or hijacking another pack's
  functions, tags or scoreboard data
- **Permission handling** - bypassing permission checks in mods (for example command
  dispatch APIs)
- **Hidden behavior** - undisclosed network calls, obfuscated code or backdoors
- Secrets or credentials committed to a repository

Ordinary bugs, crashes and compatibility problems are not security issues; please use the
normal issue templates for those.

## What to expect

We will try to:

- acknowledge your report within **7 days**
- confirm whether it is a valid issue and share a rough plan
- credit you in the fix or advisory if you want to be credited

These are targets, not guarantees. This is a volunteer-maintained project.

## Supported versions

Security fixes go to the latest release and the `main` branch of each repository.
Archived or frozen packs receive fixes only for significant issues; check the repository's
own policy where one exists.

## Please do not

- test against servers or worlds you do not own or have permission to test
- publicly disclose an issue before a fix or agreed disclosure date
- use anything from these repositories to build griefing tools, cheat clients or exploit kits
