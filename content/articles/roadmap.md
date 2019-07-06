---
title: "Roadmap"
date: 1970-01-01T12:00:00-06:00
description: This article serves as a roadmap for the Black & Light 2 theme.
---

Since the Black & Light 2 theme powers my own [website](https://nickolaskraus.org), I am constantly making improvements.

The following is a list of improvements that I am working on.

## Iterate over social links instead of hardcoding them

This is a simple change that should allow social links to be added more easily.

One would simply need to add an item to the `config.toml` and the link would be created on the homepage.

**Example**

```toml
[params.social]
  instagram = "https://www.instagram.com/nickolashkraus"
```

## Address 'Page's .RSSLink is deprecated and will be removed in a future release.'

This will address the following error:

```bash
WARN 2019/07/06 16:55:25 Page's .RSSLink is deprecated and will be removed in a future release. Use the Output Format's link, e.g. something like:
    {{ with .OutputFormats.Get "RSS"  }}{{ .RelPermalink  }}{{ end  }}.
```

## Look into adding the ability for sup, sub, and kbd elements

Currently, Black & Light 2 does not support `<sup>`, `<sub>`, or `<kbd>`, elements.

**Example**

```
H<sub>2</sub>O
```

H<sub>2</sub>O

```
X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>
```

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

```
Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.
```

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.
