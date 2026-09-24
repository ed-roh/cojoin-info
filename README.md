# cojoin-info

Static site for Cojoin, served at https://cojoin.io (Vercel; GitHub Pages mirror at https://ed-roh.github.io/cojoin-info/)

- `index.html` — landing page (support link, privacy link)
- `invite/index.html` — where invite links land when the app isn't installed
- `PRIVACY.md` → `privacy.html` (regenerate with `node -e` + marked after editing the markdown; served at /privacy)
- `.well-known/apple-app-site-association` — Universal Links for /invite on iOS
- `vercel.json` — clean URLs, the AASA content type

Publish: create the repo `ed-roh/cojoin-info` on GitHub, push `main`, then
Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
