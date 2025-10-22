# Release Notes — v1.0
**Date:** October 22, 2025  
**Tag:** v1.0

##  Features
- **README**: added project concept and rationale.
- **Zine**: created `zine/` and `zine/intro.md` (includes the phrase “time machine”).
- **Licensing & Policy**: added `LICENSE` (MIT/Apache-2.0) and `CODE_OF_CONDUCT.md`.

##  Improvements
- **.gitignore**: ignores OS/build artifacts; explained patterns in README.
- **Branch model**: created `author/idea-sprint` (drafting) and `editor/review` (polish/review); documented usage in README.
- **Issues & PR workflow**: opened “Layout”, “Content”, “Polish (cleanup)” and completed focused PRs from `feat/<topic>` branches (each PR references and closes its issue).

##  Fixes
- Resolved merge conflict in `zine/intro.md` created intentionally (edited same lines on two branches); final text merges both intents.
- Removed tracked `.DS_Store` and ensured it’s ignored going forward.

##  References
- Issues: Layout, Content, Polish (cleanup) — closed via `Fixes #…` in PRs.
- Tags: `v0.1` (lightweight), `v1.0` (annotated with message).

##  Summary
v1.0 establishes a clean repo structure, clear commit history (≥6 atomic commits; ≥3 with “why” bodies), a documented branch/review process, and release tagging suitable for future iterations.
