# GitHub Markdown Guide

## Table of Contents
1. [Headers](#headers)
2. [Emphasis](#emphasis)
3. [Lists](#lists)
4. [Links](#links)
5. [Images](#images)
6. [Code](#code)
7. [Blockquotes](#blockquotes)
8. [Tables](#tables)
9. [Task Lists](#task-lists)
10. [Footnotes](#footnotes)
11. [Mentioning Users](#mentioning-users)
12. [References](#references)

---

## Headers

Headers are created using the `#` symbol followed by a space and the header text. The number of `#` symbols indicates the header level.

```markdown
# H1 Header
## H2 Header
### H3 Header
#### H4 Header
##### H5 Header
###### H6 Header
```

## Emphasis

Emphasis can be added using asterisks `*` or underscores `_`.

- *Italic*: `*italic*` or `_italic_`
- **Bold**: `**bold**` or `__bold__`
- ***Bold and Italic***: `***bold and italic***` or `___bold and italic___`

## Lists

### Unordered Lists

Unordered lists use dashes `-`, plus `+`, or asterisks `*`.

```markdown
- Item 1
- Item 2
  - Subitem 1
  - Subitem 2
```

### Ordered Lists

Ordered lists use numbers followed by periods.

```markdown
1. First item
2. Second item
   1. Subitem 1
   2. Subitem 2
```

## Links

Links are created using square brackets for the text and parentheses for the URL.

```markdown
[GitHub](https://github.com)
```

### Links with Titles

Links can also have titles, which display as a tooltip.

```markdown
[GitHub](https://github.com "Visit GitHub")
```

## Images

Images are similar to links but with an exclamation mark `!` at the beginning.

```markdown
![Alt text](https://example.com/image.jpg)
```

### Images with Titles

```markdown
![Alt text](https://example.com/image.jpg "Image Title")
```

## Code

### Inline Code

Inline code uses backticks `` ` ``.

```markdown
Here is some `inline code`.
```

### Code Blocks

Code blocks use triple backticks `` ``` `` or indentation.

    ```markdown
    function example() {
        console.log("Code block");
    }
    ```

## Blockquotes

Blockquotes use the `>` symbol.

```markdown
> This is a blockquote.
> 
> This is the second line of the same blockquote.
```

## Tables

Tables use pipes `|` and dashes `-`.

```markdown
| Header 1 | Header 2 |
| -------- | -------- |
| Row 1    | Data     |
| Row 2    | Data     |
```

## Task Lists

Task lists use dashes and square brackets.

```markdown
- [x] Task 1
- [ ] Task 2
- [ ] Task 3
```

## Footnotes

Footnotes use square brackets with a caret `^`.

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.
```

## Mentioning Users

You can mention users with an `@` symbol.

```markdown
@username
```

## References

You can use reference-style links for cleaner Markdown.

```markdown
[GitHub][github-link]

[github-link]: https://github.com
```

---

This guide covers the basics of Markdown on GitHub. For more advanced usage and additional features, refer to the [GitHub Flavored Markdown documentation](https://guides.github.com/features/mastering-markdown/).
