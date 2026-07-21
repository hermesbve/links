# f2p Links

A minimal dark‑theme Linktree‑style page for **f2p**.

Built as a Jekyll site for GitHub Pages. All content and links are driven from `_config.yml`; no editing of `index.html` needed.

## Structure

```
├── _config.yml     ← all content: title, social links, section links
├── index.html      ← Liquid template (reads _config.yml)
├── logo.png        ← round avatar
├── qr-code.svg     ← QR code (desktop bottom‑right)
└── README.md
```

## Updating links

Edit `_config.yml` — add/remove entries under `social:` or `sections:`. Commit and push; GitHub Pages rebuilds automatically.

## Local dev

```bash
bundle exec jekyll serve
```
