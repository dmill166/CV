---
title: CV Repo Rules
id: agents-cv
version: 1.0.0
status: active
owner: Dakota Hollmann
maintainer: claude-cowork
created: 2026-06-07
updated: 2026-06-07
scope: repo-local — adds to (and inside this repo, overrides) ~/agents/AGENTS.md
changelog:
  - "1.0.0 (2026-06-07): Initial per-repo AGENTS.md — Phase 2 of the AI-first reorg."
---

# CV — Repo Rules for Agents

This is the public GitHub profile repo (github.com/dmill166): a publish surface for the rendered profile page and the exported resume PDF.

## Layout

| Path | Purpose |
|---|---|
| `README.md` | Rendered GitHub profile page — badges, LinkedIn links, profile image |
| `DHollmann_Resume.pdf` | Exported resume — do not edit directly |
| `images/profile.jpeg` | Profile photo |
| `_config.yml` | GitHub Pages config |

## Conventions

- **This repo is a publish surface only.** Resume content lives in `life-os/01_career/DHollmann_Resume.md`.
- To update the resume: edit the source in `life-os`, run `01_career/scripts/generate_resume_pdf.py` there, then copy the resulting PDF here as `DHollmann_Resume.pdf`.
- Never edit resume content directly in this repo.
- Everything here is public — never place anything sensitive (keys, personal data, drafts) in this repo.
- Profile copy (README.md) may be edited here directly; it has no separate source of truth.
