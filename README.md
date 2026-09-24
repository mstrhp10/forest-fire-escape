# Forest Fire Escape Learning Package

Static HTML learning package for Grade VIII English.

## Project structure

- `index.html` — home screen
- `homescreen.png` — home screen artwork
- `learning/simple-past.html` — Simple Past Tense learning module
- `game/forest-fire-escape.html` — Forest Fire Escape game
- `game/assets/images/` — game image assets
- `game/assets/audio/` — game audio assets

## Run locally

Open `index.html` in a browser. For best compatibility, use a local HTTP server or GitHub Pages.

## Publish with GitHub Pages

1. Create a GitHub repository (for example, `forest-fire-escape`).
2. Upload the **contents** of this package to the repository's root. Make sure `index.html`, `homescreen.png`, `learning/`, and `game/` are at the root level.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for the deployment to finish. GitHub will show the published site URL in the Pages section.

## Note about the lesson video

The learning module refers to `learning/yesterday-at-school.mp4`, but that video is not included in this package. The HTML includes a fallback scene, so the module can still be used; add the video file to the `learning/` folder if you want that video to play.
