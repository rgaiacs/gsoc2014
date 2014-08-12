---
layout: default
---

One of the widely ways to write mathematics is using (La)TeX. Unfortunately it
require the frequently use of some special characters like `\`, `{`, `}`, `_`,
`^` that aren't easy accessible at virtual keyboards. To try improve your typing
speed you can use one virtual keyboard special design for (La)TeX.

This virtual keyboard is an
[open source project](https://github.com/r-gaia-cs/gsoc2014)
that started as one of
[Google Summer of Code 2014 project](https://www.google-melange.com/gsoc/proposal/public/google/gsoc2014/r_gaia_cs/5629499534213120).
Right now it is **only** available for
[Firefox OS](https://www.mozilla.org/firefox/os/)
and you can install it from 
[Marketplace](https://marketplace.firefox.com/app/latex-keyboard).

## Features

- Styled letters are available as alternate keys.

<img class='hamachi' src="animation/styled-letters.gif">

- Many symbols are available as alternate keys, e.g. the ∏ is available as the
  alternate of ∑.
- Smart dots, i.e., pressing three dots results in `\dots`.

<img class='hamachi' src="animation/dots.gif">

- Auto capitalization, i.e., if the text before the cursor is `. ` the
  capitalization is automatically enabled.

<img class='hamachi' src="animation/auto-capitalization.gif">

- Press the return key will trigger a heuristic that change the cursor position
  inside or outside command/environment option/argument and if there isn't
  position to jump insert a new line.

<img class='hamachi' src="animation/jumps.gif">

- Subscript and superscript behave different if the character behind the cursor
  is a empty space or not. If the character behind the cursor is a empty space
  the keyboard will insert ``{}`` otherwise not.

<img class='hamachi' src="animation/script-continue.gif">
<img class='hamachi' src="animation/script-new.gif">

- If the cursor is immediately after a (La)TeX commands the backspace key will
  remove this (La)TeX commands.

<img class='hamachi' src="animation/backspace.gif">
