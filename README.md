# KIZARU STORE

Static neobrutalism promo website for digital subscription products
(Netflix, Spotify, ChatGPT, Canva, CapCut, and more — 13 products in 4 groups).

- **Site:** `index.html` — single self-contained static page (QRIS image inlined,
  GSAP loaded from CDN). No backend, no build step.
- **Style:** neobrutalism from
  [nextbytehackaton-fixit](https://github.com/KizaruZero/nextbytehackaton-fixit)
  (`#FFFDF6` background, `#111111` ink, `#4D61FC`, `#FFDE59`, `#FF3D3D`,
  `#3DFFA2`; Space Grotesk + Space Mono; sharp corners, 3px borders,
  hard shadows, grid background).
- **Checkout (Opsi A, static):** per-product checkout modal shows the QRIS,
  buyer uploads payment proof, then sends via Web Share API (photo + text to
  WhatsApp on Android) with a `wa.me` text-template fallback on desktop/iPhone.
  Proof lives only in the buyer's browser — nothing is stored server-side.
- **Payment:** QRIS — KIZARU SHOP, NMID `ID1025411992304`
  (original image: `assets/qris.jpg`).
- **Order/chat WhatsApp:** 082223816953 (`wa.me/6282223816953`).

## Deploy

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
Or serve `index.html` from any static host.
