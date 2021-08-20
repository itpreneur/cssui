# CSSUI

CSSUI is a library of interactive components realized in pure HTML and CSS. It includes frequently used components as Accordion, Modal, Tabs and more.

## Installation

Use [npm](https://www.npmjs.com/package/css-ui-test) to install CSSUI in your project:

```bash
npm install cssui-lib
```

## Usage

The library includes:
- `cssui.css`, a global stylesheet which contains the CSS variables used by all components.
- components folder list

Each component folder includes two files: a template file (HTML) and a CSS stylesheet.

You can use template files as partial or copy/paste the code into your project's files according to the language used.

### Components customization

Customize the component layout by simply overriding the global or specific CSS variables.

Global variables are specified in the `cssui.css` file

```css
:root {
  --cssui-animation-rotate: rotate(-180deg);
  --cssui-animation-timing: .25s;
  --cssui-font-family: -apple-system, blinkmacsystemfont, "Segoe UI", roboto, "Helvetica Neue", arial, "Noto Sans", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  --cssui-gray-lighter: #e5e7eb;
  --cssui-gray-light: #d1d5db;
  --cssui-gray-dark: #4b5563;
  --cssui-gray-darkest: #1f2937;
  --cssui-padding: 1rem;
  --cssui-radius: 4px;
}
```

Specific variables belong to each component's stylesheets

```css
[data-dropdown] {
  --dropdown-border-radius: var(--cssui-radius);
  --dropdown-border-color: var(--cssui-gray-light);
  --dropdown-link-background: var(--cssui-gray-lighter);
  --drodpwon-link-color: var(--cssui-gray-darkest);
  --dropdown-panel-background: #fff;
  --dropdown-padding: var(--cssui-padding);
}
```

## Support

[Open an issue ](https://github.com/zetareticoli/cssui/issues) here on Github to share feedback, report bug or ask help.

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



