Save this as `README.md` in the repo:

```markdown
# confetti.ndd.js

Tiny vanilla-JS canvas confetti rain. One 2.6KB file, zero dependencies, one function.

**Live demo + copy-paste snippet:** https://nodrama.au/confetti-js/

## Use it

1. Add a canvas anywhere in your body:

```html
<canvas id="fx"></canvas>
```

2. Include the file:

```html
<script src="confetti.ndd.js"></script>
```

3. Fire on good news:

```js
Celebrate.fire()
```

That's the entire API. One call, 150 pieces, rain from the top of the page.

## Details

- Single `requestAnimationFrame` loop that stops once the pieces land
- Canvas is `pointer-events: none` — it never blocks a click
- Strips, dots and ribbons with sway, spread across shuffled lanes
- No build step, no framework, runs in any modern browser

## Licence

MIT — use it on client sites, products and side projects. No attribution required.

Made by [No Drama Digital](https://nodrama.au/) — websites without the drama.
```

Kept it short on purpose — devs bounce off long READMEs, and the demo page carries the rest.
