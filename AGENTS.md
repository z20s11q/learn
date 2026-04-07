# AGENTS.md

## Cursor Cloud specific instructions

This is a documentation-only repository containing Chinese-language Markdown reading notes. There is no application code, no build system, and no runtime dependencies.

### Repository structure

- `README.md` — Project readme (title only)
- `内在动机_自主掌控人生的力量.md` — Notes on *"Why We Do What We Do"* by Edward L. Deci
- `成功_动机与目标.md` — Notes on *"Succeed: How We Can Reach Our Goals"* by Heidi Grant Halvorson
- `情商系列书籍核心要点大纲.md` — Outline of Daniel Goleman's *Emotional Intelligence* series

### Lint

Run `markdownlint '*.md'` to lint all Markdown files. The files currently have style warnings (e.g. `MD022`, `MD032`, `MD036`) which are non-blocking.

### Preview / Render

- Use `pandoc <file>.md -o <file>.html --standalone` to render any Markdown file to HTML.
- Use `python3 -m http.server 8080` to serve the workspace and preview rendered HTML in a browser.

### Notes

- No package manager lockfiles or dependency files exist; the update script is a no-op (`true`).
- All content is in Chinese (Simplified). Pandoc handles CJK characters correctly out of the box.
