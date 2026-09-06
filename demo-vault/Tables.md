---
created: 2026-09-05
type: demo
tags: [glacial-glacier, demo, tables]
---

# Tables

How Glacial Bloom handles tabular data.

## Basic table

| Variable | Role | Hex | HSL |
|---|---|---|---|
| `--bg1` | Background | `#0a1218` | 33 47% 96% |
| `--bg2` | Card / Surface | `#13202b` | 36 56% 98% |
| `--bg3` | Popover / Hover | `#1c2e3d` | 32 32% 90% |
| `--tx1` | Foreground | `#e0f2fe` | 9 28% 19% |
| `--ax1` | Accent | `#22d3ee` | 213 90% 45% |
| `--hl2` | Highlight glow | `#dc2626` | 41 54% 50% |

## Wide table

| Name | Type | Status | Created | Modified | Tags | Priority | Owner |
|---|---|---|---|---|---|---|---|
| Project Alpha | Active | In Progress | 2026-01-15 | 2026-09-04 | #work, #priority | High | Ward |
| Project Beta | Active | Review | 2026-02-20 | 2026-09-01 | #work | Medium | Ward |
| Project Gamma | Archived | Completed | 2025-11-10 | 2026-03-15 | #archive | Low | Ward |
| Project Delta | Active | Planning | 2026-08-01 | 2026-09-03 | #work, #planning | High | Ward |
| Project Epsilon | Pending | On Hold | 2026-07-22 | 2026-08-30 | #pending | Low | Ward |

## Table with alignment

| Left aligned | Center aligned | Right aligned |
|:---|:---:|---:|
| Left | Center | Right |
| Longer text on the left | Centered text | Right-aligned |
| Short | C | 1 |

## Table with formatting

| Feature | Status | Notes |
|---|---|---|
| **Bold feature** | ✅ Done | Works as expected |
| *Italic feature* | ⏳ In progress | ETA next week |
| `Code feature` | ❌ Blocked | Waiting on dependency |
| [Linked feature](Welcome) | ✅ Done | See linked note |
| ==Highlighted feature== | ⏳ In progress | Almost done |

## Compact table

| A | B | C | D | E |
|---|---|---|---|---|
| 1 | 2 | 3 | 4 | 5 |
| 6 | 7 | 8 | 9 | 10 |

## Notes on table styling

Glacial Bloom inherits Minimal's table system. With the **Minimal Theme Settings** plugin, you can toggle:

- Row lines (borders between rows)
- Column lines (borders between columns)
- Cell lines (borders around all cells)
- Striped rows (alternating row backgrounds)
- Striped columns (alternating column backgrounds)
- Row numbers (auto-numbered rows)
- Tabular figures (fixed-width numbers)
- Center small tables

Use the helper classes `table-lines`, `row-lines`, `col-lines`, `row-alt`, `col-alt`, `table-numbers`, `table-tabular`, `table-center` per-note to override globally.

---

*Continue to [[Callouts]] for the next demo.*
