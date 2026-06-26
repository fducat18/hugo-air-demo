# Hugo Air Demo Context

This context defines language for the hugo-air demo site and its relationship to the hugo-air theme.

## Language

**Demo Repository**:
The public site used to demonstrate and validate the hugo-air theme behavior.
_Avoid_: production site, customer site

**Theme Repository**:
The `hugo-air` repository that owns reusable templates, styles, and shortcodes.
_Avoid_: demo implementation layer

**Theme Submodule Pointer**:
A pinned commit reference from Demo Repository to Theme Repository.
_Avoid_: copied theme files

**Ownership Migration**:
Systematic update of repository owner references (GitHub org/user URLs and GitHub Pages URLs) after account transfer.
_Avoid_: ad-hoc URL patching

**Pages Base URL**:
Canonical deployed URL prefix used for absolute asset generation in demo builds.
_Avoid_: localhost path in production build

**Hugo Runtime Baseline**:
The agreed Hugo version used across GitHub Actions and hosted deploy targets to avoid behavior drift.
_Avoid_: per-environment Hugo version drift

## Example dialogue

Dev: "Demo CSS is broken after repository transfer."
Domain expert: "Check Ownership Migration and Pages Base URL first."
Dev: "Theme behavior changed too."
Domain expert: "Update Theme Repository, then bump Theme Submodule Pointer in Demo Repository."
