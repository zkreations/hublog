---
title: "Embracing System Fonts"
date: 2026-11-06T12:15:00Z
description: "Why modern operating system font stacks provide unmatched performance, crispness, and comfort."
tags: ["css", "typography", "performance"]
---

Web fonts are frequently the largest source of layout shift and network latency on content websites. By turning to modern system typography stacks, themes achieve zero font downloads and zero cumulative layout shift (CLS).

### The Modern System Stack

Modern platforms ship with world-class, extensively tested typefaces designed explicitly for screen readability:

```css
:root {
  --font-body: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
  --font-mono: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;
}
```

### Advantages

1. **Zero Bandwidth:** No external HTTP font requests or font file rendering delays.
2. **Instant Rendering:** Text is available immediately on the first paint without FOIT (Flash of Invisible Text).
3. **Native Familiarity:** The typeface matches the native aesthetic of the reader's operating system.
