# 地底巨獸 Burrow Titan — playable demo

Single-file build. Source lives in the private repo `beast-titans`.

Play: https://kabulin1994.github.io/beast-titans-play/

`index.html` inlines the whole app, so browsers cache it aggressively. The page
checks `version.json` on load and reloads itself once when the deployed build id
differs, so a new deploy reaches players without a manual hard refresh.

Rebuild with `npm run build:single` in the source repo, then copy
`dist-single/beast-titans.html` here as `index.html` and `dist-single/version.json` alongside it.
