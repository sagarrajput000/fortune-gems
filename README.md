# fortune-gems

Free-to-play demo portal for the **Fortune Garuda 1000** Unity WebGL game.

The site is a single page ([`index.html`](index.html)) that loads the game full-screen and plays it with simulated demo credits.

- No real-money wagering; outcomes and credits are simulated.
- The game is embedded from the original public host — no game files are copied into this repo.

## Run locally

Open `index.html` in any browser, or serve the folder:

```bash
npx serve .
```

## Usage notes

- The game URL can be overridden with a query parameter: `index.html?game=<other-build-url>`.
- First load downloads the Unity WebGL build (~20–40s); it is cached by the browser afterward.
- If the upstream host rotates/deletes a build, the frame goes blank — use the Reload button or the `?game=` override.
