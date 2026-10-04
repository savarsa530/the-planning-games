# The Planning Games

A 10-minute screen-share warm-up for each morning of PI planning (Oct 13–15).
Three games (Estimation Showdown, Sort It, Confidence Bets), a scoreboard, and host notes.

It's one self-contained `index.html` — no build step, no dependencies beyond Google Fonts.
Scores are saved only in the host's browser (localStorage); nothing is sent anywhere.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `planning-games`).
2. Upload `index.html`, `.nojekyll`, and this README to the root of the `main` branch
   (on github.com: **Add file → Upload files**).
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to
   **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute or two the site is live at
   `https://<your-username>.github.io/planning-games/`.

## Run locally

Just double-click `index.html`, or run `python3 -m http.server` in this folder and open http://localhost:8000.
