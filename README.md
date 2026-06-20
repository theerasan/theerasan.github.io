# Theerasan.dev — Personal Profile Website

Personal portfolio site for **Ta Theerasan Tonthongkam** — Staff Software Developer & Engineering Lead.

Single self-contained `index.html` (all fonts, images, and runtime inlined) — no build step, no dependencies.

## Deploy to GitHub Pages

1. Create a public repo named `<your-username>.github.io` (for a root site).
2. Upload **`index.html`**, the **`assets/`** folder, **`.nojekyll`**, and (optionally) `CNAME`.
3. Go to **Settings → Pages**, set Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**, Save.
4. Site goes live at `https://<your-username>.github.io` in ~1 minute.

## Social share preview (Open Graph)

`assets/og-image.png` is the 1200×630 link-preview thumbnail.

The meta tags in `index.html` reference it at an absolute URL (`https://theerasan.dev/assets/og-image.png`).
**Update that base URL** to your live address (e.g. `https://<your-username>.github.io`) so the preview resolves
when the link is shared on LinkedIn, X, Slack, etc. Test with https://www.opengraph.xyz once live.

## Custom domain

To use `theerasan.dev`: add a `CNAME` file containing `theerasan.dev`, then configure your DNS
(per GitHub's instructions in Settings → Pages → Custom domain). The meta tags already match this domain.

## Files

```
index.html            # the entire website, self-contained
assets/og-image.png   # social share thumbnail (1200×630)
.nojekyll             # tells GitHub Pages to skip Jekyll processing
README.md             # this file
```
