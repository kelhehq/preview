# Kelhe

The website for **[kelhe.com](https://kelhe.com)** — a risk layer for autonomous agents.

Kelhe is building a **risk scoring engine**: a middleware that AI agents call right
before they execute an action. The engine scores the action and returns a decision —
**proceed**, **hold for human approval**, or **deny** — so agents can act in the real
world without acting recklessly.

## Stack

A plain static site — no build step, no framework. Just:

```
index.html          # the landing page
styles.css          # dark "infra" theme
CNAME               # custom domain for GitHub Pages
kelhe-fox-*.svg     # brand marks (inlined where they need color)
kelhe-fox-logo.png  # social / link-preview (Open Graph) image
```

## Run locally

Open `index.html` directly, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

Push to the default branch and enable **Settings → Pages → Deploy from branch**
(root). The `CNAME` file wires up `kelhe.com` once the DNS is pointed at GitHub Pages.

## Contact

[team@kelhe.com](mailto:team@kelhe.com)
