# Cows & Bulls

> *Hey Wordle! who's your daddy?*

A retro-cyberpunk 5-letter word guessing game engineered for crisp 4K clarity across Android & Apple iOS vertical 9:16 portrait phones (up to 4× Super-Retina DPR) as well as 2K–4K desktop monitors. Features 10 attempts, UK English dictionary validation, 3 Oracle Hints, CRT synthwave visuals, procedural 128 BPM melodic retro-trance music, Google/Facebook cloud stat sync, and native 9:16 PNG Story Card sharing for Instagram and mobile apps.

## Deploy to GitHub Pages

1. Create a new public repository on GitHub (e.g. `cows-and-bulls`).
2. Upload `index.html`, `README.md`, and the `assets/` folder (or push with Git).
3. Go to **Settings → Pages**, set **Source** to **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
4. Your live game will be available at `https://<your-username>.github.io/<repo-name>/`.

## Enable Live Google & Facebook Sign-In (Free via Firebase)

1. Go to [Firebase Console](https://console.firebase.google.com/) and create a free project.
2. Add a **Web App** and copy your `apiKey`, `authDomain`, `projectId`, and `appId` into `FIREBASE_CONFIG` inside `index.html`.
3. In Firebase Console → **Authentication → Sign-in method**, enable **Google** and **Facebook** (using your Facebook Developer App ID & Secret).
4. In **Authentication → Settings → Authorized domains**, add `<your-username>.github.io`.
5. In **Firestore Database**, create a database so player stats sync automatically across devices under `cows_bulls_stats/{uid}`.
