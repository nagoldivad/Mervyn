# Mervyn.css

**A Small CSS Framework for Reading**

Mervyn.css is a lightweight CSS framework specifically designed for text-heavy content such as eBooks, articles, and blogs. Its purpose is to enhance the readability of digital text by mimicking the elegance and functionality of a printed page.

## Features

- **Optimized Typography**: Carefully tuned for long-form reading, inspired by best practices in typography.
- **Responsive Design**: Scales beautifully across all devices.
- **Dark Mode Support**: Automatically adapts to the user’s system preferences for light or dark mode.
- **Lightweight**: Small enough to embed directly in your HTML.
- **Accessibility**: Respects user browser settings for font scaling and accessibility.


---

## Live Demo

Explore an example of Mervyn.css in action: [Mervyn.css Example](https://www.nagoldivad.com/stuff/mervyn-example.html)


---

## Installation

### Embedding Directly in HTML

Copy and paste the following `<style>` block into your HTML:

```html
:root{--color-bg:#ffffff;--color-fg:#444444;--color-selection:#b3d4fc;--color-link:#FF4136;--color-link-hover:#b40a01;--color-hr:#cccccc;--font-family-sans-serif:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Oxygen,Ubuntu,Cantarell,"Helvetica Neue",Arial,sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";--font-family-monospace:SFMono-Regular,Menlo,Monaco,Consolas,"Liberation Mono","Courier New",monospace;--font-size-base:1.125rem;--font-size-medium:1.1875rem;--font-size-large:1.375rem;--font-size-full:1.5rem;--col-width:40.625rem;--col-width-large:60rem;--line-height:1.5;--hyphenation:auto}html{-webkit-text-size-adjust:100%}body{background-color:var(--color-bg);color:var(--color-fg);font-family:var(--font-family-sans-serif);font-size:var(--font-size-base);max-width:var(--col-width);margin:1.25rem auto;padding:0 .625rem;line-height:var(--line-height);text-align:justify;overflow-wrap:break-word;word-wrap:break-word;-ms-word-break:break-all;word-break:break-word;-ms-hyphens:var(--hyphenation);-moz-hyphens:var(--hyphenation);-webkit-hyphens:var(--hyphenation);hyphens:var(--hyphenation)}h1{font-size:2.5rem}h2{font-size:2rem}h3{font-size:1.75rem}h4{font-size:1.5rem}h5{font-size:1.25rem}h1,h2,h3,h4,h5{line-height:1.25;margin:1em 0 .67em 0}img{max-width:100%;height:auto}img[alt]:not([src]){font-style:normal}blockquote p{hanging-punctuation:first}p{margin-top:0;margin-bottom:0;text-wrap:pretty;overflow-wrap:break-word}p+p{text-indent:1em}a{color:var(--color-link);text-decoration:none;transition:color .3s ease-in-out}a:hover{color:var(--color-link-hover);text-decoration:underline}::selection{background:var(--color-selection);text-shadow:none}hr{display:block;height:1px;border:0;border-top:1px solid var(--color-hr);margin:1em 0;padding:0}@media (min-width:768px){body{font-size:var(--font-size-medium);padding:0}}@media (min-width:992px){body{font-size:var(--font-size-large)}}@media (min-width:1200px){body{font-size:var(--font-size-full);max-width:var(--col-width-large)}}@media (prefers-color-scheme:dark){:root{--color-bg:#121212;--color-fg:#e0e0e0;--color-link:#bb86fc;--color-link-hover:#3700b3;--color-hr:#333333}}
```

### Using an External File

Save the `mervyn.min.css` file and include it in your HTML with:
```html
<link rel="stylesheet" href="path/to/mervyn.min.css">
```


---

## Development

For contributors or advanced users, you can clone the project and use tools like [PostCSS](https://postcss.org/) with `cssnano` for custom builds and optimizations.


---

## License

Mervyn.css is licensed under the [WTFPL License](http://www.wtfpl.net/). Use it as you like!


---

## Changelog

- **Version 1.0.0** (January 2024): Initial release with optimized typography, responsive design, and dark mode support.
- **Version 0.3** (April 2020): Early release, using scss

