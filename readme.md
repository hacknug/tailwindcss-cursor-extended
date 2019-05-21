# Tailwind CSS Cursor Extended Plugin

**Deprecated due to Tailwind CSS supporting `cursor` as of v1.0.0.**

This plugin adds all of the missing cursor utilities to Tailwind CSS.

## Installation

Add this plugin to your project:

```bash
# Install using npm
npm install --save-dev tailwindcss-cursor-extended

# Install using yarn
yarn add -D tailwindcss-cursor-extended
```

## Usage

```js
require('tailwindcss-cursor-extended')(['responsive'])
```

```css
.cursor-none { cursor: none; }
.cursor-context-menu { cursor: context-menu; }
.cursor-help { cursor: help; }
.cursor-progress { cursor: progress; }
.cursor-cell { cursor: cell; }
.cursor-crosshair { cursor: crosshair; }
.cursor-text { cursor: text; }
.cursor-vertical-text { cursor: vertical-text; }
.cursor-alias { cursor: alias; }
.cursor-copy { cursor: copy; }
.cursor-no-drop { cursor: no-drop; }
.cursor-all-scroll { cursor: all-scroll; }
.cursor-col-resize { cursor: col-resize; }
.cursor-row-resize { cursor: row-resize; }
.cursor-n-resize { cursor: n-resize; }
.cursor-e-resize { cursor: e-resize; }
.cursor-s-resize { cursor: s-resize; }
.cursor-w-resize { cursor: w-resize; }
.cursor-ne-resize { cursor: ne-resize; }
.cursor-nw-resize { cursor: nw-resize; }
.cursor-se-resize { cursor: se-resize; }
.cursor-sw-resize { cursor: sw-resize; }
.cursor-ew-resize { cursor: ew-resize; }
.cursor-ns-resize { cursor: ns-resize; }
.cursor-nesw-resize { cursor: nesw-resize; }
.cursor-nwse-resize { cursor: nwse-resize; }
.cursor-zoom-in { cursor: zoom-in; }
.cursor-zoom-out { cursor: zoom-out; }
.cursor-grab { cursor: grab; }
.cursor-grabbing { cursor: grabbing; }
```
