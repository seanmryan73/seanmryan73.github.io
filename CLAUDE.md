# BagPipes-Site — Claude Context

Static portfolio site hosted at seanmryan73.github.io. Lists all published BagPipes apps. Also provides the public website URL, privacy policy, and terms of service required for TikTok API registration. Plain HTML/CSS, no build step, no JavaScript.

## Shared reference notes

@c:\_repos\Obsidian\Notes\Claude\Reference\Author-Version-Standards.md

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

When the session ends or the user says to wrap up, update the project context note:
`c:\_repos\Obsidian\Notes\Claude\Projects\BagPipes-Site Claude Context.md`

Update these sections:
- **Current constraints** — add any new rules or patterns discovered
- **Fix history** — add bugs fixed (one line each: date · symptom · cause · fix)
- **Next actions** — replace with the current list
- **Apps currently listed** — keep in sync with index.html
- **frontmatter `version:`** — set to today's date (YYYY.MM.DD)
