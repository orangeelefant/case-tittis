# AGENTS.md

Instructions for automation agents (Claude Code, Codex) working in this repository.

## Repository

- **Name:** `orangeelefant/case-tittis`
- **Purpose:** Public case study of Tittis Städ (https://tittisstad.se), written by Webraketen
- **Contents:** Markdown only. The site's source code lives in a separate private repository.

## Rules

- Push directly to `main`. One logical change per commit.
- Keep every existing outbound link to client and partner sites, with the same URL and anchor text.
- Never commit secrets, private contact details, internal prices or internal file paths.
- `README.md` is the source of truth. The other docs must not contradict it.
- Add a line under `## [Unreleased]` in `CHANGELOG.md` with every change.
