## Intro

These two files provide a mouse style for web pages, `default.cur` by default, which can be switched to `pointer.cur` when placed on top of a hyperlink

## Usage

A simple method to use in `styles.css`

```css
* {
  cursor:url(https://cdn.jsdelivr.net/gh/kpl0111/tool/mouse/default.cur),auto!important;
}

/* define two different styles */
.cursor-default {
  cursor: url(https://cdn.jsdelivr.net/gh/kpl0111/tool/mouse/default.cur), auto!important;
}

.cursor-pointer {
  cursor: url(https://cdn.jsdelivr.net/gh/kpl0111/tool/mouse/pointer.cur), auto!important;
}

/* Assign the default mouse style to a */
a {
  cursor: url(https://cdn.jsdelivr.net/gh/kpl0111/tool/mouse/default.cur), auto!important;
}

/* Change the mouse style to the pointer style when the mouse hovers over a */
a:hover {
  cursor: url(https://cdn.jsdelivr.net/gh/kpl0111/tool/mouse/pointer.cur), auto!important;
}
```
