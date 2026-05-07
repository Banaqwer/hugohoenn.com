# hugohoenn.com

Personal portfolio website built as a case study for the **Hurst Cyclic Trading System**.
Tailored for the Publicis Sapient Software Engineer Intern application.

## Structure

```
website/
├── index.html        Single-page portfolio
├── css/styles.css    All styling (no framework, hand-written)
├── js/main.js        Mobile menu + reveal-on-scroll
└── README.md         This file
```

No build step. No dependencies. Open `index.html` in a browser to preview, or
deploy the folder directly to any static host.

## Local preview

From this folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000

## Deploying to hugohoenn.com

Any of the following will work — pick what feels easiest:

1. **GitHub Pages** — push the contents of `website/` to a repo, enable Pages on the
   `main` branch, point your domain `hugohoenn.com` at GitHub's IPs in your DNS.
2. **Netlify / Vercel / Cloudflare Pages** — drag-and-drop the `website/` folder; add
   `hugohoenn.com` as a custom domain in the dashboard.
3. **Render** — already used by the trading project; create a new Static Site, point it
   at this folder, attach the domain.

## Things to update before sharing

- [ ] Replace the placeholder GitHub / LinkedIn `href="#"` links in `index.html`
      with your real profile URLs.
- [ ] Confirm the email `hugo@hugohoenn.com` resolves, or replace with your actual address.
- [ ] (Optional) Add a small headshot — easiest place is inside the hero, next to `h1`.
- [ ] (Optional) Add a `favicon.ico` to the website root.
