# Cows & Bulls

> *Hey Wordle! who's your daddy?*

A retro-cyberpunk 5-letter word guessing game engineered for crisp 4K clarity across Android & Apple iOS vertical 9:16 portrait phones (up to 4× Super-Retina DPR) as well as 2K–4K desktop monitors. Features 10 attempts, UK English dictionary validation, 3 Oracle Hints, CRT synthwave visuals, procedural 128 BPM melodic retro-trance music, Firebase Google/Facebook cloud stat sync (`cows-and-bulls-stats`), and native 9:16 PNG Story Card sharing for Instagram and mobile apps.

## Deploy to GitHub Pages

1. Replace `index.html` (and `assets/` if not already uploaded) in your GitHub repository.
2. Push to `main`—GitHub Pages will update `https://flybyrhythmz.github.io/<repo-name>/` within ~1 minute.
3. Make sure `flybyrhythmz.github.io` is added under Firebase Console → **Authentication → Settings → Authorized domains** and your Firestore rules allow authenticated users to read/write `cows_bulls_stats/{userId}`.
