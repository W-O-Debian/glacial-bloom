# Changelog

All notable changes to Glacial Bloom will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0] — 2026-09-11

### Added

- **PDF Export styling** — Obsidian's "Export to PDF" now produces beautiful theme-colored PDFs with proper page margins, preserved callouts, and signature highlights.
- **Custom syntax highlighting** — code blocks now use palette-tuned colors.
- **Graph view color preset** — the graph view now matches the theme palette instead of using Obsidian's defaults.

### Removed

- **Warm Toggle** — removed the built-in warm color temperature shift. Eye comfort is better handled at the system level (macOS Night Shift, Windows Night Light, f.lux).

## [1.1.1] — 2026-09-10


### Removed

- **Warm Toggle** — removed the built-in warm color temperature shift. Eye comfort is better handled at the system level (macOS Night Shift, Windows Night Light, f.lux) where users can control it globally across all apps. The theme should focus on being a good theme, not on duplicating OS-level features.

## [1.1.0] — 2026-09-10

### Added


- **True Focus Mode** — hides everything except the note workspace (ribbon, sidebars, tabs, status bar, view header). More aggressive than Minimal's built-in focus mode. Toggle via Style Settings → Advanced → "True focus mode", or per-note using the `true-focus-mode` cssclass. A subtle "Esc to exit focus mode" hint appears in the bottom-right corner.
- **PDF Export styling** — `@media print` rules that force background colors to print, hide UI chrome, set proper page margins (2cm), prevent orphaned headings, and preserve callouts, code blocks, highlights, and tables. Obsidian's "Export to PDF" now produces beautiful theme-colored PDFs.
- **Custom syntax highlighting** — palette-tuned code colors: keywords in cyan, strings in frosted emerald, comments in slate, numbers in amber, functions in icy lavender, tags in red.
- **Graph view color preset** — graph nodes, lines, tags, attachments, and unresolved links now match the Glacial Bloom palette instead of Obsidian's defaults.

### Changed

- Updated header comment to document the new v1.1.0 features.

## [1.0.0] — 2026-09-05

### Added

- Initial release of Glacial Bloom — a recolour of Minimal v9.0.2 for Obsidian.
- Deep glacial blue-black backgrounds (`#0a1218`, `#13202b`, `#1c2e3d`) for dark mode — reduces OLED eye strain vs. pure black.
- Ice-white text (`#e0f2fe`) for softer contrast vs. pure black-on-white.
- Crystalline cyan accent (`#22d3ee`) for links and interactive elements.
- Signature warm red bloom (`#dc2626` at 35% opacity) for text highlights — the palette's namesake.
- **Glacial Mist** light variant — pale icy backgrounds with deep blue-black text, darker cyan accent for contrast on bright surfaces. Warm red bloom preserved.
- Extended palette harmonised with the glacial aesthetic (frosted emerald, icy lavender, dusty rose, etc.).
- Explicit scheme classes `.minimal-glacial-bloom-dark` and `.minimal-glacial-bloom-light` for parity with Minimal's other named schemes.
- Demo vault showcasing headings, callouts, tables, code blocks, task lists, and Dataview examples.
- Real Obsidian screenshots for light/dark editor and reading modes.

### Inherited from Minimal v9.0.2

- Full feature set: focus mode, cards, image grid, table helpers, tab styles, callouts, embeds, heading dividers, tag styles.
- Plugin compatibility: Calendar, Charts, Dataview, Git, Kanban, Style Settings, Zoom, and more.
- Complete Style Settings YAML surface for granular customization.
- 14 preset color schemes (Dracula, Gruvbox, Nord, Solarized, Catppuccin, etc.) remain selectable.

### Credits

- Original Minimal theme by [@kepano](https://twitter.com/kepano) — [github.com/kepano/obsidian-minimal](https://github.com/kepano/obsidian-minimal)
- Glacial Bloom palette and recolour by [Ward Skaiker](https://github.com/W-O-Debian)
