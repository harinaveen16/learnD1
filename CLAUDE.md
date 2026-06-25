# CLAUDE.md

Guidance for AI assistants (and humans) working in this repository.

## What this repository is

This is a personal Git/GitHub learning sandbox (`learnD1`), not a production
application. There is no build system, package manager, test suite, or CI.
Contents are practice artifacts from learning Git workflows and basic Python.

## Structure

```
.
├── Git/
│   └── Github_cmd_purpose   # Markdown cheat sheet of git/GitHub commands
├── Git2.1/
│   └── main.py              # Trivial demo script (prompts for name, prints length)
├── version.txt              # Free-text notes / demo content
└── version2.txt             # Free-text notes / demo content
```

- `Git/Github_cmd_purpose` is a reference doc (git command → purpose table). Treat
  it as documentation to keep accurate, not executable code.
- `Git2.1/main.py` is a standalone script with no dependencies:
  ```bash
  python3 Git2.1/main.py
  ```
- `version.txt` / `version2.txt` are scratch text files used to practice commits;
  they have no semantic meaning beyond their literal content.

## Conventions

- No formal naming/versioning scheme is enforced — file and folder names (e.g.
  `Git2.1`) reflect ad-hoc versioning from past practice sessions, not a pattern
  to replicate.
- There are no tests, linters, or formatters configured. Don't introduce a build
  toolchain or dependency manager unless explicitly asked.
- Keep changes minimal and additive, consistent with the repo's purpose as a
  learning log — don't refactor or "clean up" prior practice artifacts unless
  asked.

## Working here

- Since there's no build/test pipeline, there's nothing to run to "verify"
  changes beyond executing `main.py` directly if it's modified.
- When asked to add new practice content, follow the existing pattern of small,
  self-contained files/folders rather than introducing a project framework.
