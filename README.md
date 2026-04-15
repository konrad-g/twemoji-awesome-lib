# :tada: Twemoji Awesome :beer:

Like [Font Awesome](http://fontawesome.io), but for [Twitter Emoji](http://twitter.github.io/twemoji/).

## Installation

Include the stylesheet in your HTML:

```html
<link rel="stylesheet" href="lib/twemoji-awesome.css">
```

## Usage

Use the `twa` base class plus a `twa-*` class matching the [Emoji Cheat Sheet](http://www.emoji-cheat-sheet.com/) name (replace underscores with hyphens):

```html
<!-- Default size -->
<i class="twa twa-heart"></i>

<!-- Large (1.33x) -->
<i class="twa twa-lg twa-sparkles"></i>

<!-- 2x size -->
<i class="twa twa-2x twa-hatching-chick"></i>
```

| Emoji Cheat Sheet | HTML |
|---|---|
| `:heart:` | `<i class="twa twa-heart"></i>` |
| `:sparkles:` | `<i class="twa twa-lg twa-sparkles"></i>` |
| `:hatching_chick:` | `<i class="twa twa-2x twa-hatching-chick"></i>` |

## Notes

- Class names use `twa-*` (like Font Awesome's `fa-*`).
- Emoji Cheat Sheet names with underscores must use hyphens: `:hatching_chick:` → `twa-hatching-chick`.
- Size modifiers: `twa-lg`, `twa-2x`, `twa-3x`, `twa-4x`, `twa-5x`.
- Emoji are rendered as SVG `background-image` from MaxCDN.
- Code licensed under MIT. Graphics licensed under CC-BY.
