# VS Code Personal Settings

A curated `settings.json` for Visual Studio Code focused on **consistency, clarity, and speed** across development workflows.

This repository exists as a **portable, versioned source of truth** for editor behavior, formatting, typography, Git usage, and visual ergonomics.

---

## Purpose

These settings are designed to:

- Enforce **automatic formatting and linting**
- Reduce friction through **sensible defaults**
- Improve **readability and focus** for long coding sessions
- Keep behavior **predictable across machines**
- Disable telemetry and unnecessary interruptions

This is not a theme pack. It is an **opinionated working configuration**.

---

## Key Characteristics

### Formatting & Code Style
- Format on save using **Prettier**
- Consistent tab size and word wrapping
- Automatic import updates on file move
- ESLint runs on save

### Editing Experience
- Linked editing enabled
- Whitespace always visible
- Rich IntelliSense suggestions everywhere
- Parameter hints always on
- Preview tabs disabled for stability

### Fonts & Readability
- Monospaced developer-first font stack
- Font ligatures enabled
- Increased line height and letter spacing
- Large token limits for heavy files

### Terminal
- JetBrains Mono for terminal
- Increased scrollback
- Consistent font sizing and spacing
- Terminal opens in file directory

### Git & GitHub
- Auto-fetch enabled
- Force push allowed (intentional)
- Always push branch for PRs

### UI & Ergonomics
- One Monokai color theme
- Material Icon Theme
- Activity bar at the bottom
- Centered editor layout
- Startup editor disabled

### Comments & Annotations
Enhanced comment visibility using **Better Comments**:
- TODO
- FIXME
- NOTE
- BUG
- IMPORTANT

Each tag is color-coded and visually emphasized.

### Privacy
- Telemetry disabled
- Crash reporting disabled

---

## Usage

1. Copy the contents of `settings.json`
2. Paste into your local VS Code `settings.json`
3. Reload VS Code

This configuration is safe to adapt, fork, or extend.

---

## Philosophy

- Fewer decisions while coding
- Editor should **disappear**, not demand attention
- Settings should serve **long-term consistency**, not novelty

Use what helps. Remove what doesn’t.
