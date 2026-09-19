# BagPipes-Site — Agent Context

Static portfolio site hosted at seanmryan73.github.io. Lists all published BagPipes apps. Also provides the public website URL, privacy policy, and terms of service required for TikTok API registration. Plain HTML/CSS, no build step, no JavaScript.

> **Agent context — required reading.** Lines beginning with `@` below are absolute file paths (one complete path per line; paths may contain spaces). Claude Code auto-imports them. All other agents (Codex, Copilot, etc.): read every `@` file now, before doing any work.

## Shared reference notes

@c:\_repos\Obsidian\Notes\Claude\Reference\Author-Version-Standards.md
@c:\_repos\Obsidian\Notes\Claude\Reference\Core-Rules.md

## Project context

@c:\_repos\Obsidian\Notes\Claude\Projects\BagPipes-Site Claude Context.md

## Critical constraints

- **No build step** — files are served as-is from GitHub Pages. Do not add npm, webpack, TypeScript, or any bundler.
- **No JavaScript** — portfolio site is plain HTML/CSS only. Do not add JS.
- **Do not delete TikTok verification files** — `tiktokQ6MewTAmWH90sVhOtPO4AgCS6DJKBMjj.txt` must stay at repo root; TikTok may re-verify at any time.
- **Footer must link to Terms and Privacy** — required by TikTok app review guidelines.
- **Shared style.css** — changes affect all three pages (index, privacy, terms). Test all three after any CSS edit.

## Working rules

- Prefer minimal, targeted edits.
- Push to main — GitHub Pages deploys automatically (no CI needed).
- When adding a new app card to index.html, follow the `.app-card` pattern already in the file.

## After this session

Run **`/wrapup`** (`c:\_repos\Obsidian\Notes\Claude\Skills\wrapup\SKILL.md`). It is the procedure; this section only adds to it. This repo's project note: `Projects/BagPipes-Site Claude Context.md`.

Repo-specific additions:

- **Apps currently listed** — keep in sync with index.html
