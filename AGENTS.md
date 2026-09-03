# Agent Instructions

This file is guidance for AI coding agents (Claude, etc.) working in this repo. It's the ArkanSec public website — a static site (Bootstrap 3.3.7 + custom CSS) hosted on GitHub Pages at www.arkansec.com (see `CNAME`).

## Git workflow

- **Always work on a feature branch and open a merge/pull request.** Never commit directly to `main` — MRs are required for this project (branch protection / review process expects it).
- Branch naming follows `<type>/<short-description>`, e.g. `event/arkansec-...`, `policy/...`, `docs/...`. Match that convention for new branches.
- Keep commit messages plain — summary line, optional body. **Do not add AI/Claude attribution trailers** (e.g. `Co-Authored-By: Claude ...`, `Claude-Session: ...`) to commit messages in this repo.

## Structure

- `index.html` — homepage.
- `policies.html` — policy pages (e.g. vendor/sponsor policy), same header/footer/theme as the homepage.
- `assets/css/style.css` — shared styles (black/red theme, `agencyfbregular` font).
- `assets/fonts/`, `assets/img/` — font and image assets.

New pages should reuse the existing header/footer markup and styling conventions rather than introducing a new look.
