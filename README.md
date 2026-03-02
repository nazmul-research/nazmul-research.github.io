# nazmul-research.github.io (Redirect Repo)

This repository exists to keep the GitHub Pages URL (`https://mdnazmulislam0087.github.io/`) active and redirect visitors to the production portfolio CMS app hosted on Vercel.

## Redirect target

- **Source (GitHub Pages):** `https://mdnazmulislam0087.github.io/`
- **Destination (Vercel app):** `https://nazmul-portfolio-blond.vercel.app/`

## How redirect is implemented

The redirect is handled by `index.html` using:

1. `<meta http-equiv="refresh" ...>` for immediate browser redirect
2. JavaScript fallback: `window.location.replace(...)`
3. A manual clickable link in case redirect is blocked

## Why this setup is used

GitHub Pages cannot run the full Next.js + Prisma + API backend stack required by the CMS.

So:
- Runtime app lives on **Vercel**
- GitHub Pages URL remains as a stable public entrypoint and redirects to Vercel

## Update redirect target

If your Vercel URL changes, update `index.html` target URL and push:

```bash
git add index.html
git commit -m "chore: update redirect target"
git push
```

## Related repos

- **Main app/CMS repo:** `https://github.com/nazmul-research/nazmul-portfolio`
- **This redirect repo:** `https://github.com/nazmul-research/nazmul-research.github.io`
