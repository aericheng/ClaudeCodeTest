# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A collection of self-contained browser mini-apps — each app is a single HTML file with embedded CSS and JavaScript. No build step, no dependencies, no package manager.

## Running the Apps

Open any `.html` file directly in a browser:
```
start tictactoe.html
start calendar.html
```

## Architecture

Each app is a **single-file** HTML/CSS/JS application:
- All styles are in a `<style>` block in `<head>`
- All logic is in a `<script>` block at the end of `<body>`
- Persistence uses `localStorage` (no backend)
- No external libraries or CDN dependencies

## Git & GitHub

- Remote: `https://github.com/aericheng/ClaudeCodeTest`
- Branch: `master`
- **Commit and push frequently** — after every meaningful unit of work (new feature, bug fix, significant edit), always `git add`, `git commit`, and `git push origin master`. Never leave completed work uncommitted.
- Push after each commit so the remote is always up to date and work is never lost.
- Commit message format: short imperative subject line (≤72 chars), blank line, then a brief body describing what changed and why.

## Code Conventions

- Chinese (Traditional) for all user-facing text (labels, placeholders, status messages)
- English for code (variable names, function names, comments)
- Color palette: `#3b82f6` blue primary, `#e94560` red accent, `#1a1a2e` / `#16213e` dark backgrounds
