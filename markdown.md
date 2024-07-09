# Markdown Style Guide

This style guide is designed to help maintain consistency and clarity in your Markdown documents, taking inspiration from best practices used by GitHub, Google, and other major tech companies.

## Table of Contents
1. [Headings](#headings)
2. [Paragraphs](#paragraphs)
3. [Line Breaks](#line-breaks)
4. [Lists](#lists)
5. [Links](#links)
6. [Images](#images)
7. [Code Blocks](#code-blocks)
8. [Inline Code](#inline-code)
9. [Blockquotes](#blockquotes)
10. [Horizontal Rules](#horizontal-rules)
11. [Tables](#tables)
12. [Emphasis](#emphasis)
13. [Footnotes](#footnotes)
14. [Task Lists](#task-lists)
15. [Miscellaneous](#miscellaneous)

## Headings

- Use `#` for top-level headings, `##` for second-level, and so on.
- Only one top-level heading (`#`) per document.
- Headings should be capitalized consistently. Use title case for headings.

```markdown
# Document Title

## Section Title

### Subsection Title
Paragraphs
Separate paragraphs with a blank line.
Avoid using manual line breaks within paragraphs unless necessary for readability.
markdown
Copy code
This is a paragraph.

This is another paragraph.
```

## Line Breaks

Use two spaces at the end of a line to create a line break within a paragraph.

```markdown
This is a line with a break.  
This is the second line.
```

## Lists

Use hyphens (-) or asterisks (*) for unordered lists, but be consistent within the document.  
Use numbers for ordered lists.  
Indent nested lists with two spaces.  

```markdown
- Item 1
- Item 2
  - Subitem 2.1
  - Subitem 2.2
    - Sub-subitem 2.2.1

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
```

## Links

Use reference-style links for better readability.  
Ensure all URLs are up-to-date and functioning.  

```markdown
This is an [example link][example].

[example]: http://example.com
```

## Images

Use reference-style for images, similar to links.  
Provide descriptive alt text for accessibility.

```markdown
![Alt text][image]

[image]: http://example.com/image.jpg
```

## Code Blocks

Use triple backticks (```) for code blocks.  
Specify the language for syntax highlighting.

```markdown
\```python
def example_function():
    print("Hello, World!")
\```
```

## Inline Code

Use single backticks (`) for inline code.

```markdown
To print a message, use the `print` function.
```

## Blockquotes

Use > for blockquotes.  
For nested blockquotes, use additional > characters.  

```markdown
> This is a blockquote.
> 
> > This is a nested blockquote.
```

## Horizontal Rules

Use three or more hyphens (---), asterisks (***), or underscores (___) on a line by themselves.

```markdown
---

***

___
```

## Tables

Use pipes (|) and hyphens (-) to create tables.  
Align text to the left, right, or center by using colons (:).

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|:--------:|---------:|
| Row 1    | Centered |  Right   |
| Row 2    | Content  |    $10   |
```

## Emphasis

Use asterisks (*) or underscores (_) for emphasis.  
Use double asterisks or underscores for strong emphasis.

```markdown
*italic* _italic_

**bold** __bold__
```

##Footnotes

Use [^1] for footnote references and add the footnote text at the bottom of the document.

```markdown
This is a sentence with a footnote.[^1]

[^1]: This is the footnote.
``

## Task Lists
Use hyphens with square brackets ([ ]) for incomplete tasks and [x] for completed tasks.

```markdown
- [ ] Incomplete task
- [x] Completed task
```

## Miscellaneous

Keep lines under 80 characters when possible.  
Use consistent indentation and spacing throughout the document.
