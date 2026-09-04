# Scenewright — $10

Paste a chapter. Lock faces. Export Grok Imagine prompts.

**Price:** $10 one-time via PayPal.

## Live site (GitHub Pages)

https://serialchiller09-boop.github.io/scenewright/

- Demo app: https://serialchiller09-boop.github.io/scenewright/
- Sell page: https://serialchiller09-boop.github.io/scenewright/sell.html

**Pages source:** if the site 404s after merge, set **Settings → Pages → Source: GitHub Actions** (not “Deploy from a branch”). Workflow: `.github/workflows/pages.yml` (upload-pages-artifact + deploy-pages). Leave that file as-is unless the deploy pattern changes.

## Buy

[PayPal — $10](https://py.pl/VzHU7QkjihOOJv6slVmG9A)

## How to use

1. Open the live site (or `index.html` locally).
2. Paste a chapter (or hit **Load sample**).
3. Extract scenes, lock character / location plates, then compile.
4. Use **Export prompt pack** → **Copy entire pack** or **Download .txt**.
5. Paste lock plates into Grok Imagine first, then scene prompts in order.

## Sample pack

Clear Beech Street sample: [`packs/beech-street-imagine-pack.txt`](packs/beech-street-imagine-pack.txt) (see [`packs/README.md`](packs/README.md) and [`sell/README.md`](sell/README.md)).

## Repo layout

| Path | Purpose |
|------|---------|
| `sell.html` | $10 sales landing |
| `sell/README.md` | Sell notes + sample pack pointer |
| `index.html` | Compiler demo |
| `packs/` | Sample prompt pack |
| `.github/workflows/pages.yml` | Static site → GitHub Pages |

No server required. Payment is PayPal only—there is no custom checkout backend.
