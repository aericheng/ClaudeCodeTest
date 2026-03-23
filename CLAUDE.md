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
- After every meaningful change: commit with a descriptive message and push to `origin master`
- Commit message format: short imperative subject line, then a blank line and a brief body describing what and why

## Code Conventions

- Chinese (Traditional) for all user-facing text (labels, placeholders, status messages)
- English for code (variable names, function names, comments)
- Color palette: `#3b82f6` blue primary, `#e94560` red accent, `#1a1a2e` / `#16213e` dark backgrounds
