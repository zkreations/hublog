---
title: "Markdown Style Guide"
description: "A comprehensive demonstration of standard Markdown elements supported by Hublog."
tags: ["markdown", "style-guide", "demo"]
---

This document provides a complete demonstration of standard Markdown formatting elements to verify typography, spacing, and responsive behavior.

## Headings

The theme establishes a clear typographic hierarchy across heading levels:

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

## Paragraphs & Typography

Good typography creates an effortless reading experience. Comfortable line lengths, adequate line height, and proportionate margins ensure long passages remain legible across varying screen dimensions.

Typography is not merely about selecting letters; it is about organizing content so that readers can absorb ideas without friction. When interfaces minimize extraneous visual decoration, the words themselves carry the voice of the author.

## Blockquotes

Quotations provide emphasis and editorial context:

> Good design is as little design as possible. Less, but better, because it concentrates on the essential aspects, and the products are not burdened with non-essentials.
> 
> — Dieter Rams

Nested blockquotes are also supported:

> Primary thought.
>> Secondary supporting note within the blockquote.

## Lists

### Unordered List

- Semantic HTML architecture
- Pure CSS design tokens
- Zero JavaScript requirement
  - No client-side hydration
  - Instant page delivery

### Ordered List

1. Define design tokens in `:root`
2. Structure base templates with semantic landmarks
3. Assemble content views and pagination
4. Process assets with Hugo Pipes

### Task List

- [x] Accessible WCAG AA color contrast
- [x] Responsive layout without horizontal overflow
- [ ] Add your first article

## Code Blocks & Syntax

Inline code snippets like `hugo server` or `config.toml` stand out cleanly.

Block code with syntax highlighting:

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello from Hugo!")
}
```

Configuration example:

```toml
[pagination]
  pagerSize = 5

[params]
  show_reading_time = true
```

## Tables

Tables remain contained and provide horizontal scrolling on narrower viewports:

| Feature | Hublog | Typical Blog Theme | Notes |
|---|---|---|---|
| JavaScript Dependencies | 0 KB | 50–200 KB | Completely script-free |
| CSS Framework | None (Vanilla) | Tailwind or Bootstrap | Pure custom properties |
| Build Requirement | Hugo Standard | Hugo Extended + npm | Runs on vanilla Hugo |
| Accessibility Standard | WCAG AA | Variable | Built-in focus & skip link |

## Emphasis & Links

You can use **bold text** for strong emphasis, *italic text* for subtle distinction, or ***both combined***. Links like [Hugo Documentation](https://gohugo.io) are distinctly styled with visible underline cues.

## Horizontal Rule

A divider provides a visual break between disparate sections:

---

End of the Markdown style guide demonstration.
