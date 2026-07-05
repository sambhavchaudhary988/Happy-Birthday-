# Happy Birthday Card 🎂❤️

An interactive birthday card: gift reveal → photo slideshow → typewriter letter → confetti/balloons/fireworks celebration.

## Files

- `index.html` — page structure
- `style.css` — all styling and animations
- `script.js` — all interactivity (open `script.js` and edit the `CONFIG` block at the top to personalize)
- `images/photo1.jpg` … `photo6.jpg` — the slideshow photos
- `music/birthday.mp3` *(optional, not included)* — drop a file here to enable background music; the mute/unmute button appears automatically once it detects a working audio file, and stays hidden if there isn't one

## Personalizing

Open `script.js` and edit the `CONFIG` object near the top:

```js
const CONFIG = {
  recipientBadge: "❤️ FOR MY CUTE AUNTY ❤️",
  senderName: "Sambhav chaudhary",
  photos: [ ... ],
  letterMessage: `...`,
  music: { src: "music/birthday.mp3", volume: 0.4 }
};
```

To swap photos, replace the files in `images/` (keep the same filenames) or update the `image` paths in the `photos` array.

## Publishing with GitHub Pages

1. Create a new repository and push these files (keep the folder structure — `index.html` at the repo root, `images/` alongside it).
2. In the repo, go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to "Deploy from a branch", pick your default branch (e.g. `main`) and folder `/ (root)`.
4. Save. GitHub will give you a URL like `https://yourusername.github.io/repo-name/` within a minute or two — that's the link you can share.

## Notes

- The gift-box GIF is embedded via Tenor's public embed script — no file needed, but it does require internet access to load.
- Everything else works fully offline once hosted (or even opened directly from a folder in a browser).
