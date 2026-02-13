---
title: Running a test of the blog posting system on through Github Actions
date: 2026-02-14
author: Joel Flanagan
summary: This is a quick test to see if everything is working correctly.
tags:
  - testing
  - GitHub Actions
---

# Getting Started

I want to test all of the markdown features.

## Headings

### Heading Level 3
#### Heading Level 4
##### Heading Level 5
###### Heading Level 6

## Text Formatting

- **Bold text**: `**This is bold text**` → **This is bold text**
- *Italic text*: `*This is italic text*` → *This is italic text*
- ~~Strikethrough~~: `~~This is strikethrough~~` → ~~This is strikethrough~~
- ***Bold and Italic***: `***This is bold and italic text***` → ***This is bold and italic text***

## Links

- [This is an inline link](https://example.com)
- [This is a link with a title attribute](https://example.com "Example Domain")
- This is an automatic link: <https://www.example.com>

---

## Images

![Markdown Logo](https://markdown-here.com/img/icon256.png "Markdown Logo")
![From assets](/assets/test.png "image from assets")

---
## Lists

### Unordered List
- Item 1
  - Sub-item 1.1
  - Sub-item 1.2
- Item 2

### Ordered List
1. First item
1. Second item
   1. Sub-item 2.1
   1. Sub-item 2.2

---
## Blockquotes

> “Markdown is a lightweight markup language with plain-text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.”  
> — [Wikipedia](https://en.wikipedia.org/wiki/Markdown)

---
## Code

- Inline code: `console.log("Hello, Markdown!");`

### Code Block

```javascript
// This is a JavaScript code block 
function greet(name) { 
  console.log(Hello, ${name}!); 
}

greet("World");
```

---

## Tables

Markdown also supports basic tables:

| Syntax      | Description |
|-------------|-------------|
| Header      | Title here  |
| Row 1       | Content     |
| Row 2       | More content|

---

## Horizontal Rules

You can create horizontal rules using three or more dashes, asterisks, or underscores:

---

***

___

---

## HTML in Markdown

You can also mix in raw HTML for greater customization. For example:
<div style="background-color: lightblue; padding: 1em;"> <strong>This is a custom HTML block.</strong> </div>

---

## Special Characters

Escape special Markdown characters using a backslash (`\`):
- Use `\*` to write an asterisk: \*
- Use `\#` to write a pound sign: \#
- Use `\|` to write a vertical bar: \|

---

## Task Lists

You can create task lists like this:

- [x] Write example post
- [x] Test Markdown rendering
- [ ] Fix bugs
- [ ] Share with the community

---

## Footnotes

You can even add footnotes<span class="footnote ms-1 me-1"><sup class="footnote__counter" tabindex="0">1</sup></span>.

<span class="footnote ms-1 me-1"><sup class="footnote__counter" tabindex="0">1</sup></span>: This is a footnote example.

---

## Math (Plugins?)

Inline math example: $E = mc^2$  
Block math example:
$$
\int_{a}^{b} x^2 dx = \frac{b^3}{3} - \frac{a^3}{3}
$$

---

## Callouts

If the Markdown parser supports custom containers using `:::`, you can also create callouts:

::: tip
This is a **tip** callout. You can use it to share helpful advice.
:::

::: danger
This is a **danger** callout. Be cautious!
:::
