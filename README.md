# cojoin-info

Static site for Cojoin, served at https://cojoin.io (Vercel; GitHub Pages mirror at https://ed-roh.github.io/cojoin-info/)

- `index.html` — landing page (support link, privacy link). While the app is in beta it shows TestFlight install steps with inline QR codes (TestFlight on the App Store, then the public beta link `https://testflight.apple.com/join/4XRWQ3Am`). Once the App Store listing is live, replace the `.beta` section with a single App Store button.
- `invite/index.html` — where invite links land when the app isn't installed
- `PRIVACY.md` → `privacy.html` (regenerate with `node -e` + marked after editing the markdown; served at /privacy)
- `.well-known/apple-app-site-association` — Universal Links for /invite on iOS
- `vercel.json` — clean URLs, the AASA content type

Publish: create the repo `ed-roh/cojoin-info` on GitHub, push `main`, then
Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
