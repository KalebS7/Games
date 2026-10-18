# Games (offline Android app)
Minesweeper, Solitaire and Connect 4. Fully offline.

Repo files: `www/index.html`, `package.json`, `capacitor.config.json`,
`make-icons.py`, `.github/workflows/build-apk.yml`, `README.md`,
plus **your own `debug.keystore`** (required) and optional `icon.png`.

1. Add `debug.keystore` (and optionally `icon.png`) to the repo root.
2. GitHub > Actions > "Build APK" > Run workflow.
3. When it turns green, open the run and download the **Games-APK** artifact.
4. Unzip it and install `app-debug.apk`.
