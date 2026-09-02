# Pac-Man Clone

A simple, playable Pac-Man clone built with vanilla HTML5 canvas and JavaScript — no dependencies, no build step.

## Play it

Open `index.html` in any browser.

- **Move**: Arrow keys or WASD
- **Pause**: P
- Eat all the dots to win. Power pellets (large dots) let you eat ghosts for a short time. Avoid ghosts otherwise — you have 3 lives.

## Files

- `index.html` — the entire game (markup, styling, and logic in one file)

## Push this to a new GitHub repo

1. Create a new empty repository on GitHub (no README/license, so it's truly empty) — e.g. `pacman-clone`.
2. In this folder, run:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: Pac-Man clone"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   git push -u origin main
   ```

3. Optional — enable GitHub Pages so it's playable online:
   - Go to your repo's **Settings → Pages**
   - Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`
   - Your game will be live at `https://<your-username>.github.io/<your-repo-name>/`
