---
title: "Black & Light 2"
date: 2018-10-14T12:00:00-06:00
layout: about.html
---

# Black & Light 2
A beautifully simple, high contrast, text-oriented theme for Hugo. Black & Light 2 is hyper-performant, JavaScript-free, and fully open-source!

## Features

* Loads in a single request (with web-fonts disabled)
* 100/100 on [Google PageSpeed Tools](https://developers.google.com/speed/) and 100/100 on mobile (with web-fonts disabled)
* No JavaScript (unless using Google Analytics).
* Styles are pure CSS and are inlined in `<head>`.

## Installation

```bash
git submodule add git@github.com:nickolashkraus/black-and-light-2.git themes/black-and-light-2
```

## Configuration
Copy the [`config.toml`](https://github.com/nickolashkraus/black-and-light-2/blob/master/exampleSite/config.toml) from the `exampleSite` directory of this theme to the root directory of your Hugo site.

### Changing the favicon
Black & Light 2 comes with a default favicon (`favicon.png`). To use your own favicon, simply create `favicon.png` in the `static` directory of your Hugo website. When running `hugo`, the favicon located at `static/favicon.png` will overwrite the favicon located at `themes/black-and-light-2/static/favicon.png`.

### The About section
Instead of creating `about.html` with standard HTML, a simple layout is applied to the content contained in `about.md`. To change the **About** section, simply modify this file.

## Acknowledgments
This is a clean fork of David Hamp-Gonsalves's [Black & Light](https://github.com/davidhampgonsalves/hugo-black-and-light-theme).

## License
This theme is released under MIT License. For more information, the full license can be found [here](https://github.com/nickolashkraus/black-and-light-2/blob/master/LICENSE).
