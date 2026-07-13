---
layout: post
title: "Hello, world"
description: "First post — testing the layout, typography, and code blocks."
---

This is a placeholder post so you can see what the layout looks like. Delete it
whenever you're ready to write something real.

Paragraphs get a readable line length and generous line height. **Bold** and
*italic* work as expected, as do [links](https://example.com) and inline
`code spans`.

## Code blocks

Syntax highlighting is handled by Rouge, which GitHub Pages runs natively:

```python
def reading_time(text: str, wpm: int = 200) -> int:
    """Estimate reading time in minutes."""
    words = len(text.split())
    return max(1, words // wpm)

print(reading_time("some very long post" * 500))
```

## Images

Drop images anywhere in the repo (e.g. an `assets/images/` folder) and
reference them with standard Markdown:

```markdown
![Alt text](/assets/images/example.png)
```

## Quotes and lists

> A blockquote, for when someone else said it better.

- Lists work
- Like you'd expect
- Nothing fancy

That's the whole layout. No chrome, just text.
