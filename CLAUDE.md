# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile repository** (`thejackarnold/thejackarnold`). The sole file that matters is `README.md` — GitHub renders it as the public profile page for the account. There is no application code, build system, or test suite.

## Development Workflow

Editing the profile is a direct Markdown edit-commit-push cycle:

```bash
# Edit the profile
# Then commit and push to main
git add README.md
git commit -m "Update profile"
git push origin main
```

Changes go live on the GitHub profile immediately after pushing to `main`.

## Conventions

- The `README.md` uses standard GitHub Flavored Markdown (GFM).
- GitHub profile READMEs support HTML, GFM badges (shields.io), and embedded images.
- Keep the file readable as raw Markdown — it is the only deliverable.
