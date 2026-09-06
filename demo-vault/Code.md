---
created: 2026-09-05
type: demo
tags: [glacial-glacier, demo, code]
---

# Code

How Glacial Bloom handles inline code and code blocks.

## Inline code

Inline code uses a pale slate color (`#a8b8ce`) against a glacial surface background (`#1c2e3d`). The border is subtle, so code reads as part of the paragraph without breaking flow.

Use `var(--accent)` to reference CSS variables. Use `npm install` for commands. Use `Cmd + E` for shortcuts.

## Code blocks

```python
# Python with syntax highlighting
def fibonacci(n: int) -> list[int]:
    """Generate the first n Fibonacci numbers."""
    if n <= 0:
        return []
    if n == 1:
        return [0]
    
    sequence = [0, 1]
    for i in range(2, n):
        sequence.append(sequence[-1] + sequence[-2])
    
    return sequence

# Example usage
numbers = fibonacci(10)
print(f"First 10 Fibonacci numbers: {numbers}")
```

```javascript
// JavaScript with syntax highlighting
const debounce = (fn, delay) => {
  let timeoutId;
  return (...args) => {
    clearTimeout(timeoutId);
    timeoutId = setTimeout(() => fn(...args), delay);
  };
};

// Usage
const handleInput = debounce((value) => {
  console.log('Searching for:', value);
}, 300);
```

```bash
#!/bin/bash
# Shell script example
set -euo pipefail

VAULT_DIR="${1:-.}"
THEME_DIR="$VAULT_DIR/.obsidian/themes/Glacial Bloom"

if [ -d "$THEME_DIR" ]; then
    echo "Theme already installed."
    exit 0
fi

mkdir -p "$THEME_DIR"
cp manifest.json theme.css "$THEME_DIR/"
echo "Glacial Bloom installed successfully."
```

```css
/* CSS with syntax highlighting */
:root {
  --glacial-bg: #0a1218;
  --ice-white-text: #e0f2fe;
  --cyan-accent: #22d3ee;
  --gold-glow: #dc2626;
}

.callout {
  background: var(--glacial-bg);
  color: var(--ice-white-text);
  border-left: 3px solid var(--cyan-accent);
}
```

```json
{
  "name": "Glacial Bloom",
  "version": "1.0.0",
  "minAppVersion": "1.13.0",
  "author": "Ward Skaiker (recolour) · @kepano (Minimal base)",
  "authorUrl": "https://github.com/W-O-Debian"
}
```

## Plain code block (no language)

```
This is a plain code block with no syntax highlighting.
Useful for ASCII art, diagrams, or generic preformatted text.
   ┌─────────────┐
   │  Glacial Bloom │
   └─────────────┘
```

## Inline code in lists

- Use `npm install` to install dependencies
- Run `npm run dev` to start the dev server
- Deploy with `npm run build && npm run deploy`

## Code with formatting around it

Here's a paragraph with `inline code` followed by **bold**, then a code block:

```python
print("Hello, Glacial Bloom!")
```

And here's the paragraph after the code block.

---

*Continue to [[Quotes and Highlights]] for the next demo.*
