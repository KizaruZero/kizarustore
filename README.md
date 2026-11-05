# KIZARU STORE

Static neobrutalism promo website for digital subscription products
(Netflix, Spotify, ChatGPT, Canva, CapCut, and more — 13 products in 4 groups).

- **Site:** `index.html` — single self-contained static page
  (GSAP loaded from CDN). No backend, no build step.
- **Style:** neobrutalism from
  [nextbytehackaton-fixit](https://github.com/KizaruZero/nextbytehackaton-fixit)
  (`#FFFDF6` background, `#111111` ink, `#4D61FC`, `#FFDE59`, `#FF3D3D`,
  `#3DFFA2`; Space Grotesk + Space Mono; sharp corners, 3px borders,
  hard shadows, grid background).
- **Best Seller section** at the top (below the hero): CapCut, Canva,
  GetContact, Netflix — extra-large cards with ★ BEST SELLER badges and
  rank #1–#4. The four also appear in their normal categories below.
- **Order flow (WA-first, no on-site checkout):** products are reseller-sourced,
  so prices and stock change often. Every card shows visible variant option
  buttons (all variants listed, first one selected by default — no hidden
  dropdown); the buyer picks a variant, then taps "Tanya Stok & Harga", which
  opens WhatsApp with a prefilled message containing ONLY the chosen variant
  and its listed price, asking if it's still in stock and what the latest
  price is. Payment is agreed in the WhatsApp chat. No QRIS / payment upload
  on the site (the old checkout modal was removed 2026-11-05).
- **Order/chat WhatsApp:** 082223816953 (`wa.me/6282223816953`).
  KIZARU STORE has no WhatsApp catalog — do not link any `wa.me/c/...` URL.

## Deploy

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / `/ (root)`.
Or serve `index.html` from any static host.
