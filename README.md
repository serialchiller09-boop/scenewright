# Scenewright — $10

Paste a chapter. Lock faces. Export Grok Imagine prompts.

**Price:** $10 one-time via PayPal.

## Live site (GitHub Pages)

https://serialchiller09-boop.github.io/scenewright/

- Demo app: https://serialchiller09-boop.github.io/scenewright/
- Sell page: https://serialchiller09-boop.github.io/scenewright/sell.html

**Jeff:** after this workflow merges, enable Pages if needed — **Settings → Pages → Source: GitHub Actions**. The workflow is `.github/workflows/pages.yml` (upload-pages-artifact + deploy-pages).

## Buy

[PayPal — $10](https://py.pl/VzHU7QkjihOOJv6slVmG9A)

## How to use

1. Open the live site (or `index.html` locally).
2. Paste a chapter (or hit **Load sample**).
3. Extract scenes, lock character / location plates, then compile.
4. Use **Export prompt pack** → **Copy entire pack** or **Download .txt**.
5. Paste lock plates into Grok Imagine first, then scene prompts in order.

## Repo layout

| Path | Purpose |
|------|---------|
| `sell.html` | $10 sales landing |
| `index.html` | Compiler demo |
| `packs/` | Sample prompt pack |
| `.github/workflows/pages.yml` | Static site → GitHub Pages |

No server required. Payment is PayPal only—there is no custom checkout backend.
