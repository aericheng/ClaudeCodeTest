# ClaudeCodeTest

A collection of self-contained browser mini-apps. Each app is a single HTML file — no build step, no dependencies, no package manager required.

## Apps

| File | Description |
|------|-------------|
| `calendar.html` | 行事曆 — A calendar app with event management and task status tracking. Supports browser notifications and persists data via localStorage. |
| `tictactoe.html` | Tic Tac Toe — A two-player tic-tac-toe game with win detection. |

## Usage

Open any `.html` file directly in a browser:

```
# Windows
start calendar.html
start tictactoe.html
```

Or double-click the file in File Explorer.

## Architecture

- Single-file apps: HTML + CSS + JS all in one `.html` file
- No external libraries or CDN dependencies
- Persistence via `localStorage` (no backend needed)

## Development

Edit any `.html` file in a text editor and refresh the browser to see changes.
