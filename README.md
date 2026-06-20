# theerasan.github.io — Personal Profile Website

Personal portfolio site for **Ta Theerasan Tonthongkam** — Staff Software Developer & Engineering Lead.

Single self-contained `index.html` (all fonts, images, and runtime inlined) — no build step, no dependencies.

## Deploy to GitHub Pages

1. Create a **public** repo named exactly **`theerasan.github.io`**.
2. Upload **`index.html`**, the **`assets/`** folder, and **`.nojekyll`** (keep the folder structure).
3. Go to **Settings → Pages** → Source = **Deploy from a branch** → Branch = **main** → folder = **/ (root)** → **Save**.
4. Live at **https://theerasan.github.io** in ~1 minute.

## Social share preview

`assets/og-image.png` is the 1200×630 link-preview thumbnail. The meta tags in `index.html` already
point to `https://theerasan.github.io/assets/og-image.png`, so the rich preview works once the repo is live.
Test it at https://www.opengraph.xyz or LinkedIn's Post Inspector.

## Files

```
index.html            # the entire website, self-contained
assets/og-image.png   # social share thumbnail (1200×630)
.nojekyll             # tells GitHub Pages to skip Jekyll processing
README.md             # this file
```

## Custom domain (optional, later)

To use a domain like `theerasan.dev`: add a `CNAME` file containing the domain, point your DNS at GitHub,
then update the absolute URLs in the `index.html` meta tags from `theerasan.github.io` to the new domain.
