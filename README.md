# Turkish Art Blob

Source for **[gokhanturhan.com/turkish-art-blob](https://gokhanturhan.com/turkish-art-blob/)** — a living sculpture and real-world installation proposal for a talking, flesh-like AI organism that discusses Turkish and global contemporary art in English and Turkish.

## Layout

- `site/index.html` — English page (`/turkish-art-blob/`)
- `site/tr/index.html` — Turkish page (`/turkish-art-blob/tr/`)
- `site/css/`, `site/js/`, `site/img/` — shared styles, interactive WebGL blob bundle, and installation scene mock-ups

## Publishing

Pushes to `main` touching `site/**` (or manual runs of **Publish to gokhan-memex** via `workflow_dispatch`) run `.github/workflows/publish.yml`. The workflow syncs `site/` into `public/turkish-art-blob/` on `avalidurl/gokhan-memex` (`main`), which Cloudflare Pages builds and deploys automatically to `https://gokhanturhan.com/turkish-art-blob/`.

---

© Gökhan Turhan. All rights reserved.
