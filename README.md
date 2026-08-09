# Paul Rudland — Portfolio

A single-page portfolio site (`index.html`) plus the photo `paul.jpg`. No build step. `package.json` just tells Railway how to serve it.

## Files
- `index.html` — the whole site
- `paul.jpg` — hero portrait
- `package.json` — start command for Railway (`serve`)
- `.gitignore` — keeps `node_modules` out of the repo

## Run it on your own machine (optional)
```bash
npm install
npm start
```
Then open the address it prints (usually http://localhost:3000).

## Deploy on Railway
1. Go to https://railway.app and sign in with GitHub.
2. **New Project → Deploy from GitHub repo**.
3. Pick this repo. Railway installs `serve` and runs `npm start` automatically.
4. Open **Settings → Networking → Generate Domain** to get your live URL.

Every push to `main` after that redeploys on its own.
