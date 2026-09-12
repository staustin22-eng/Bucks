# Bucks

Will Robins' Scoring Method, on the dot. Three checks a hole, 54 fairways-and-greens
points, one goal: break 90.

Installable PWA — works fully offline once loaded, stores every round on the device.

## Put it online (GitHub Pages, ~5 minutes, no git required)

1. Go to **github.com/new**. Name the repository `bucks`. Set it to **Public**
   (free GitHub Pages needs public). Click **Create repository**.
2. On the empty repo page click **uploading an existing file**.
3. Drag in the *contents* of this folder — all seven files, not the folder itself:
   `index.html`, `manifest.webmanifest`, `sw.js`, `icon-180.png`, `icon-192.png`,
   `icon-512.png`, `icon-maskable-512.png`. Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, set
   Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**. Save.
5. Wait about a minute, then open `https://YOUR-USERNAME.github.io/bucks/`

## Install it on the phone

Open that URL in **Safari** on the iPhone → Share → **Add to Home Screen**.
It launches full screen with no browser chrome, and works with no signal.

## Updating it later

Edit `index.html` in the repo, and bump `VERSION` in `sw.js` (`bucks-v1` → `bucks-v2`)
so installed phones pick up the new version instead of serving the cached one.

## Your data

Rounds live in the phone's local storage for this web address only — nothing is sent
anywhere, and there is no account. Export from **Trends → Export CSV** (one row per
shot) before clearing site data or switching phones.
