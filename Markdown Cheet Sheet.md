# Markdown Cheat Sheet

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Headings](#headings)
- [Emphasis](#emphasis)
- [Lists](#lists)
  - [Unordered](#unordered)
  - [Ordered](#ordered)
  - [Nested](#nested)
- [Links](#links)
- [Images](#images)
- [Blockquotes](#blockquotes)
- [Code](#code)
  - [Inline](#inline)
  - [Block](#block)
- [Horizontal Rule](#horizontal-rule)
- [Tables](#tables)
- [Task Lists](#task-lists)
- [Escaping](#escaping)

## Headings

```markdown
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

## Emphasis

```markdown
*italic* or _italic_
**bold** or __bold__
~~strikethrough~~
`inline code`
```

## Lists

### Unordered:
```markdown
- Item
* Item
+ Item
```

### Ordered:
```markdown
1. First
2. Second
3. Third
```

### Nested:
```markdown
- Item 1
  - Subitem 1.1
  - Subitem 1.2
```

## Links

```markdown
[Link text](https://example.com)
[Link with title](https://example.com "Title")
<https://example.com>
```

## Images

```markdown
![Alt text](image-url)
![Alt text](image-url "Title")
```

## Blockquotes

```markdown
> This is a blockquote.
> 
> > Nested blockquote.
```

## Code

### Inline:
`code`

### Block:
```language
Your code here
```

## Horizontal Rule

```markdown
---
***
___
```

## Tables

```markdown
| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 3   | Cell 4   |
```

## Task Lists

```markdown
- [x] Done
- [ ] Not done
```

## Escaping

To display Markdown characters literally, prefix with a backslash:
```markdown
\*literal asterisk\*  => *literal asterisk*
\`backtick\`         => `backtick`
```

---

Notes:
- GitHub-style anchor links are lowercase with spaces converted to hyphens and most punctuation removed (e.g., "Table of Contents" → `#table-of-contents`). If you need anchors tailored for another renderer, I can adjust them.
- I can also add a collapsed TOC, more examples, or printable PDF export if you'd like.
