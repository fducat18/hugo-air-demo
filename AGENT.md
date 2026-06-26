# AGENT.md — hugo-air-demo

This repository is the public demo site for the `hugo-air` theme.
It consumes `hugo-air` as a Git submodule at `themes/air`.

## Component model

- **Demo content** (`content/`): showcases theme features across locales.
- **Demo configuration** (`hugo.yaml`): demo menus, params, multilingual setup.
- **Theme dependency** (`themes/air`): source of layout/style/shortcode behavior.
- **Deployment workflow** (`.github/workflows/hugo.yml`): builds and deploys demo to GitHub Pages.

## Ownership and boundaries

- This repo owns demonstration content and demo configuration.
- Theme feature behavior is owned by `hugo-air`.
- Theme updates are consumed by submodule pointer bumps, not by copying theme internals.

## Standard workflow

1. Update `hugo-air` when behavior/fixes belong to the reusable theme.
2. Bump `themes/air` pointer in this repo to consume that theme commit.
3. Keep demo links/base URLs aligned with current repository owner and Pages URL.

## Provider-agnostic agent contract

Any AI agent working in this repository should use capability-first instructions, not provider-specific assumptions.

Required capabilities:

- Read/search files
- Edit files safely
- Run build/deploy verification commands
- Explain configuration and migration changes clearly

## Repository policy

- Public demo repository.
- Maintainer can edit directly.
- Community contributions are welcome for demo/documentation improvements.
