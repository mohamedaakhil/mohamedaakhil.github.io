**#Github Pages Deployment**
# mohamedaakhil.github.io


A static website automatically deployed to **GitHub Pages** via **GitHub Actions** — triggers only when `index.html` changes.

🌐 **Live site:** `https://mohamedaakhil.github.io`

## Stack

HTML · GitHub Actions · GitHub Pages

## How it works

Any push to `main` that modifies `index.html` triggers the workflow in `.github/workflows/deploy.yml`, which builds and deploys the site to GitHub Pages automatically.

## Setup

1. Clone this repo
2. Go to **Settings → Pages → Source** → set to **GitHub Actions**
3. Push a change to `index.html` — the site deploys itself
