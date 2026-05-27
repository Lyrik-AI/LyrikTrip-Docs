# Lyrik AI documentation instructions

## About this project

- This is the public Mintlify documentation repository for Lyrik AI projects.
- The current primary product documented here is AnyAgent.
- Pages are MDX files with YAML frontmatter.
- Configuration lives in `docs.json` at the repository root.
- Run `mint dev` to preview locally.
- Run `mint validate` and `mint broken-links --check-anchors` before publishing.

## Terminology

- Use `AnyAgent` for the public product name.
- Use `anyagent` for the Python package, CLI command, import package, and repository implementation.
- Use `workspace` for a user's configured `.anyagent/` directory.
- Use `agent pack` for `.anyagent/agents/<agent_id>/`.
- Use `Mintlify` only for the documentation platform, not as the source of truth for product behavior.

## Style preferences

- Use active voice and second person ("you").
- Keep sentences concise: one idea per sentence.
- Use sentence case for headings.
- Bold UI element labels: Click **Settings**.
- Use code formatting for file names, commands, paths, and code references.
- Prefer Mintlify components over custom HTML.
- Link to public pages with root-relative links and no file extension.

## Content boundaries

- This repository is the public reading layer.
- The engineering source of truth for AnyAgent remains in the AnyAgent source repository: `README.md`, `requirements.md`, `todo/*.md`, `docs/**`, and `packages/anyagent/**`.
- Do not duplicate internal task state, private deployment details, secrets, or credentials here.
- When product behavior changes, update the AnyAgent source-of-truth document first, then update this public site if the public reading path changes.
