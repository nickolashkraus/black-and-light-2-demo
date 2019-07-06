---
title: "Markdown Syntax"
date: 1970-01-01T12:00:00-06:00
description: This article provides a sample of basic Markdown syntax that can be used in Hugo content files with this theme.
---

This article provides a sample of basic Markdown syntax that can be used in Hugo content files with this theme. It also shows how basic HTML elements can be decorated with CSS.

## Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Paragraph

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Blockquotes

The *blockquote* element represents content that is quoted from another source. There are two types of blockquotes available: *left-justified* and *centered*.

### Left-Justified

```
> Much of what separates the great from the very good is deep presence...
```

> Much of what separates the great from the very good is deep presence...

Optionally, you can add a citation using the `cite` or `footer` element:

```
> Much of what separates the great from the very good is deep presence...
> — <cite>Josh Waitzkin [^1]</cite>

[^1]: The above quote is excerpted from Josh Waitzkin's book, *The Art of Learning*
```

> Much of what separates the great from the very good is deep presence...
> — <cite>Josh Waitzkin [^1]</cite>

[^1]: The above quote is excerpted from Josh Waitzkin's book, *The Art of Learning*

### Centered

The centered blockquote is invoked using the `prose` CSS class:

```bash
<blockquote class="prose">
  Much of what separates the great from the very good is deep presence...
</blockquote>
```

<blockquote class="prose">
  Much of what separates the great from the very good is deep presence...
</blockquote>

## Tables

Tables are not part of the core Markdown specification, but Hugo supports supports them out-of-the-box.

```
   Name | Age
--------|------
    Bob | 27
  Alice | 23
```

   Name | Age
--------|------
    Bob | 27
  Alice | 23

#### Inline Markdown within tables

```
| Inline     | Markdown  | In                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~ | `code`     |
```

| Inline     | Markdown  | In                | Table      |
| ---------- | --------- | ----------------- | ---------- |
| *italics*  | **bold**  | ~~strikethrough~~ | `code`     |

## Code Blocks

#### Code block with backticks

``````
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
``````

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

#### Code block with four space indented

```
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>
```
    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### Code block with Hugo's internal highlight shortcode

```
{{</* highlight html */>}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{</* /highlight */>}}
```

{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## List Types

#### Ordered List

```
1. First item
2. Second item
3. Third item
```

1. First item
2. Second item
3. Third item

#### Unordered List

```
* List item
* Another item
* And another item
```

* List item
* Another item
* And another item

## Other Elements: abbr, mark

```
<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.
```

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

```
Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other
small creatures.
```

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
