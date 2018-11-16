# Building style guides with kss-node

This software is a Node.js implementation of [Knyle Style Sheets](https://github.com/kneath/kss) (KSS), "a documentation syntax for CSS" that's intended to have syntax readable by humans *and* machines. Hence, the kss-node software can be used to create a "living style guide".

1. Write human-readable documentation using "KSS syntax" comments. Can be added to CSS, Sass, LESS, or any other CSS Preprocessor files.
2. Have the `kss` tool automatically build a style guide from your stylesheets.

Here's an example KSS comment:
```css
/*
Button

Your standard button suitable for clicking.

:hover   - Highlights when hovering.
.shiny   - Do not press this big, shiny, red button.

Markup: button.html

Style guide: components.button
*/
.button {
  /* … */
}
.button.shiny {
  /* … */
}
```

**For more information on how to write KSS comments, see the [KSS spec](https://github.com/kss-node/kss/blob/spec/SPEC.md).**