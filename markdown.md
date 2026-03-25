# Markdown Cheat Sheet

This file shows Markdown syntax as literal text, so the examples do not break while you read them.

## Headings

| Syntax | Meaning |
|---|---|
| ``# Heading`` | H1 |
| ``## Heading`` | H2 |
| ``### Heading`` | H3 |
| ``#### Heading`` | H4 |
| ``##### Heading`` | H5 |
| ``###### Heading`` | H6 |

## Alternate Heading Syntax

| Syntax | Meaning |
|---|---|
| ``Heading Level 1``<br>``===============`` | H1 |
| ``Heading Level 2``<br>``---------------`` | H2 |

## Text Styles

| Syntax | Meaning |
|---|---|
| ``**Bold text**`` | Bold |
| ``__Bold text__`` | Bold |
| ``*Italic text*`` | Italic |
| ``_Italic text_`` | Italic |
| ``***Bold italic text***`` | Bold + Italic |
| ``___Bold italic text___`` | Bold + Italic |
| ``~~Strikethrough~~`` | Strikethrough |

## Inline Elements

| Syntax | Meaning |
|---|---|
| `` `inline code` `` | Inline code |
| ``[OpenAI](https://openai.com)`` | Link |
| ``<https://openai.com>`` | Automatic link |
| ``![Alt text](image.png)`` | Image |
| ``[Link](https://example.com "Title")`` | Link with title |

## Blockquotes

| Syntax | Meaning |
|---|---|
| ``> This is a blockquote`` | Blockquote |
| ``>> This is nested`` | Nested blockquote |

## Lists

### Unordered List

```text
- Item one
- Item two
* Item three
+ Item four
```

### Ordered List

```text
1. First item
2. Second item
3. Third item
```

### Task List

```text
- [ ] Pending task
- [x] Completed task
```

## Code Blocks

### Basic Code Block

````text
```text
Code block here
```
````

### Code Block With Language

````text
```python
print("Hello, Markdown!")
```
````

## Horizontal Rules

```text
---
***
___
```

## Escaping Characters

| Syntax | Meaning |
|---|---|
| ``\* Not italic \*`` | Show special characters without formatting |
| ``\# Not a heading`` | Prevent heading formatting |
| ``\[Not a link\]`` | Prevent link formatting |

## Tables

### Basic Table

````text
| Name | Age | City |
|---|---|---|
| Ali | 22 | Delhi |
| Sara | 25 | Paris |
````

### Table Alignment

````text
| Left | Center | Right |
|:---|:---:|---:|
| A | B | C |
````

## Footnotes

```text
Footnote example[^1]

[^1]: This is the footnote
```

## Definition List

```text
Term
: Definition
```

Note: definition lists are supported in some Markdown flavors, not all.

## HTML Inside Markdown

| Syntax | Meaning |
|---|---|
| ``<mark>Highlight</mark>`` | Highlight using HTML |
| ``<sub>Subscript</sub>`` | Subscript using HTML |
| ``<sup>Superscript</sup>`` | Superscript using HTML |

## Quick Practice Example

````text
# My Notes

## Today

- Learn headings
- Learn lists
- Learn links

> Markdown is easy once the syntax is visible.

Visit [OpenAI](https://openai.com)
````
