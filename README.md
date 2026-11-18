# satsuki ♡

A one-page interactive night-sky confession, in Japanese. Best opened on a phone.

- `index.html`: the whole page (animations, story, question).
- `song.mp3`: background music. It starts when she taps the first screen, because iPhones block sound before a tap.

## Change names or text

Open `index.html` and edit the `CONFIG` block near the top of the script:

```js
const CONFIG = {
  her: "さつき",
  me:  "アルチョム",
  music: "song.mp3"
};
```

The story lines are in `SCENES`, right below it.

## Put it online (GitHub Pages)

1. Open the repo on GitHub, then go to **Settings → Pages**.
2. Under **Build and deployment**, set Source to **Deploy from a branch**, choose branch `main` and folder `/ (root)`, then click Save.
3. After about a minute the page is live at `https://artyom-black.github.io/satsuki/`.
