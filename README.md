# Cedars-Sinai Newsletters

Websites for the Cedars-Sinai Head and Neck Cancer Program and Thyroid Cancer
Program newsletters, plus a self-hosted flipbook prototype — an Issuu-style
magazine experience with no subscription and no per-reader Box access needed.

## Contents

- `index.html` — **Final page:** one Harvard-style summary index of all 21
  issues from both programs, newest first, with the HN Gestalt 2026 flipbook
  built in (two-page spread on desktop, page curl on phones). This is the
  page GitHub Pages serves at the repo root.
- `head-and-neck/index.html` — Head and Neck Cancer Program site (11 issues,
  HN Gestalt 2017–2026). Live:
  https://muse.ai/s/cedars-sinai-head-and-neck-cancer-xqxt6txlxjxhnc66/203dY2ipJWDBfVEgxGIDS3M2PQgL6GWMeXSDvrz9IYY
- `thyroid/index.html` — Thyroid Cancer Program site (10 issues, Thyroid
  Catalyst 2018–2024, Thyroid Compass 2025–2026, Thyroid Insight 2017). Live:
  https://muse.ai/s/cedars-sinai-thyroid-cancer-program-xaxg6txlxi3pnjg/Pz_dwRxJsYBh1HVQd_fGXDpDsTeTW2dXG-9qe5fE_Es
- `flipbook-prototype/hn-gestalt-2026.html` — Flipbook prototype for one issue
  (HN Gestalt 2026, Vol 12 Issue 1, Fall 2026). Live:
  https://muse.ai/s/hn-gestalt-2026-flipbook-prototype-df6txxlxexjorxb/5ZcVylpc70JPX1Pey6-FueNtd8QxRQB7HzK0PSvC9xo
- `issues.md` — Manifest of all 21 newsletter PDFs and where they live.

## Source PDFs

All 21 newsletter PDFs (75.2 MB total) live in the shared Box folder:
https://app.box.com/s/bibsh7cemjgon50kcif6y9yehz6emvu4

## How the flipbook works

Open-source, self-hosted: the PDF pages are rendered to images and flipped
with a 3D page-curl (StPageFlip-style). Two-page spread on desktop,
single-page curl on phones, with thumbnails, fullscreen, and a closer-reading
view. $0, no Issuu subscription, no ads, full Cedars branding, and it works
on work laptops that block Box.

## Status (Nov 24, 2026)

Final page built: the root `index.html` is the unified summary page with all
21 issues. HN Gestalt 2026 opens in the built-in flipbook; the other 20
issues link to their PDFs in the Box folder (they convert to flipbooks the
same way as their page images are rendered).
