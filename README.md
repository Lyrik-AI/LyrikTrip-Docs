# Lyrik AI docs

This repository contains the public Mintlify documentation for Lyrik AI projects.
The current primary product is AnyAgent.

## Structure

- `docs.json` configures the Mintlify site.
- `index.mdx` and `quickstart.mdx` are the main public entry points.
- `concepts/`, `guides/`, and `reference/` contain AnyAgent documentation pages.
- Static assets live in `logo/` and `favicon.svg`.

## Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Preview locally:

```bash
mint dev
```

Validate before publishing:

```bash
mint validate
mint broken-links --check-anchors
```

## Publishing

Connect this repository to Mintlify:

- Organization: `Loap`
- Repository: `Lyrik-AI/LyrikTrip-Docs`
- Branch: `main`
- Docs directory: repository root

Mintlify deploys automatically after changes are pushed to the connected branch.

## Source of truth

This repository is the public reading layer. AnyAgent engineering truth remains in the AnyAgent source repository:

- `README.md`
- `requirements.md`
- `todo/*.md`
- `docs/**`
- `packages/anyagent/**`

Update the source repository first when behavior, configuration, contracts, or operational semantics change.
