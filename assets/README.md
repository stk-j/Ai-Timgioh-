# Optional images

The game works without any images. To use your own, put them in this folder and set the paths in `CONFIG.images` at the top of `index.html`:

```js
images: {
  head:       'assets/tim-head.png',   // DVD logo, webcam, clips, ID card (square, transparent PNG is best)
  logo:       'assets/logo.png',       // small square logo top-left
  buttonIcon: 'assets/button.png',     // round picture inside the MONTE MAN YES button
  cardBack:   'assets/card-back.png',  // back of the booster cards (portrait, about 59:86)
  stageBg:    'assets/bg.jpg',         // calm background of the play area
},
```

- Always use **relative** paths (no leading `/`), so the game works on IONOS, GitHub Pages and locally.
- If a file is missing, the game logs a warning in the console and falls back to the drawing.
- Only use pictures you have the rights to, such as images Tim has shared or approved for the fan site.
