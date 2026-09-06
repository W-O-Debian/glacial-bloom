---
created: 2026-09-05
type: demo
tags: [glacial-glacier, demo, embeds]
---

# Embeds and Links

How Glacial Bloom handles internal links, external links, and transclusions.

## Internal links

Internal links use the cyan accent color (`#22d3ee`). Hovered links darken to `#67e8f9`.

- [[Welcome]] — basic internal link
- [[Typography|Typography demo]] — internal link with custom display text
- [[Tables#Basic table]] — link to a specific heading
- [[Code#Code blocks]] — link to another heading

## External links

External links use the same cyan accent. By default, Obsidian appends an external-link icon.

- [Obsidian](https://obsidian.md) — the official Obsidian website
- [Minimal Theme](https://github.com/kepano/obsidian-minimal) — the base theme by @kepano
- [Minimal Theme Settings](https://github.com/kepano/obsidian-minimal-settings) — companion plugin
- [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) — for granular customization

## Unresolved links

Unresolved links (links to notes that don't exist yet) appear with reduced opacity and a dashed underline. This makes them easy to spot without being distracting.

- [[This note does not exist yet]] — unresolved link
- [[Another missing note]] — another unresolved link

## Embeds (transclusions)

Embeds let you include the content of one note inside another. Glacial Bloom inherits Minimal's embed styling.

### Embed a full note

![[Typography]]

### Embed a specific section

![[Tables#Basic table]]

### Embed a specific block

![[Code#Code blocks]]

## Strict embeds

Add the `embed-strict` class to a note (or enable it globally) to make embeds appear seamlessly in the flow of text — no border, no title, no padding. The embedded content reads as part of the host note.

## Embed underline

Add the `embed-underline` class to underline embedded text with a subtle dotted line. Useful for distinguishing embedded content from the host note without using borders.

## Backlinks

Backlinks appear in the right sidebar (or at the bottom of the note in reading mode, depending on your settings). They use the muted text color and show a snippet of context around the linking text.

This note has backlinks from:
- [[Welcome]] — the demo vault overview

## Outgoing links

The outgoing links panel shows all notes this note links to. For this note, that includes:

- [[Welcome]]
- [[Typography]]
- [[Tables]]
- [[Code]]

---

*You've reached the end of the demo vault. Try toggling between light and dark mode to see how Glacial Bloom and Glacial Mist handle each element differently.*
