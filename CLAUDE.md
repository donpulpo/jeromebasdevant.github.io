# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Personal website for Jérôme Basdevant's AI leadership advisory practice, hosted on GitHub Pages at `jeromebasdevant.com`.

## Architecture

Single-page static site with no build step, no JavaScript, and no dependencies beyond Google Fonts and one image:

- `index.html` — the entire site: markup + inline `<style>` block
- `assets/jerome-basdevant_lg_2000px_01a.jpg` — hero photo
- `content/Website Copy v2.md` — canonical source for all website copy
- `Brief.md` — design brief and technical constraints
- `CNAME` — custom domain config for GitHub Pages

## Development

No build, lint, or test commands. To preview locally:

```
python3 -m http.server 8000
```

Deployment happens automatically via GitHub Pages when changes are pushed to `main`.

## Design Conventions

- **Fonts**: DM Serif Display (headings) and Inter (body/UI) via Google Fonts
- **Color palette**: CSS custom properties in `:root` — warm sand `--sand: #E8DED1`, charcoal `--charcoal: #2C2C2C`, blue-grey accent `--accent: #6B7B8D`
- **Layout**: `.container` at `max-width: 720px` for text sections, `.container--wide` at `880px` for hero/tiers; responsive at 700px and 480px breakpoints
- **All CSS is inline** in the `<head>` `<style>` block — no external stylesheets
- **No dark mode** — the warm palette is the identity per the brief

## Content Notes

- The name has an accent: **Jérôme Basdevant** — use the correct spelling with `é`
- Copy tone is deliberately direct — do not soften phrases like "what to kill" or "AI theatre"
- CTA email is `jerome@tresllum.com`
- The three engagement tiers (Diagnostic / Strategy / Embedded) are styled as distinct cards
