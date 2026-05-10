# Anish Hand

A font based on Anish's handwriting, made with Claude.

**Live:** http://anish.thite.site/anishhand/

## What's here

- `index.html` — single-page live editor (handwriting font embedded as base64 in `@font-face`). Type, change size, save as PNG, or download the .ttf.
- `AnishHand-Regular.ttf` — the font file. Drop into your OS or `@font-face` it directly.

## Glyph set

`a–z`  `A–Z`  `0–9`  `! ?`  `, .`  `$ #`  `; :`

Other characters won't render.

## Use the font in your own page

```html
<style>
  @font-face {
    font-family: "AnishHand";
    src: url("AnishHand-Regular.ttf") format("truetype");
  }
  .hand { font-family: "AnishHand", cursive; }
</style>

<p class="hand">hello!</p>
```

## Hosting

Served via GitHub Pages from `main` branch root. Push to deploy.
