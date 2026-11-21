# editarium-site

Landing page for Editarium (editarium.io): editing studio for streamers.
Static site, no build step: `index.html`, `favicon.svg`, `img/`.

- Brand: direction B "in/out points" (cobalt `#1C33E0`, yellow `#FFDD00`, night `#0A0F2E`, Archivo + JetBrains Mono).
- Copy is in Portuguese (it is what visitors read); code and comments in English.
- Contact form: set `FORM_ENDPOINT` in `index.html` (Formspree, Web3Forms...). Empty = preview mode, only shows the summary.
- Local preview: `python3 -m http.server 8080` and open http://localhost:8080
- Deploy: any static host (Cloudflare Pages, Vercel, GitHub Pages) pointing at the repo root.
