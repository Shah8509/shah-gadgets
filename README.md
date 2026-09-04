# Shah Gadgets — Store Website

Cinematic, dark-themed front-end for the Shah Gadgets brand (homepage + featured product page), built with plain HTML/CSS/JS and GSAP for scroll animations.

## Run locally
Just open `index.html` in any browser — no build step, no dependencies to install.

## Deploy free with GitHub Pages
1. Create a new repo on GitHub (e.g. `shah-gadgets`).
2. Upload `index.html` (and this `README.md`) to the repo — either drag-and-drop on the GitHub website, or:
   ```
   git init
   git add .
   git commit -m "Shah Gadgets store site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/shah-gadgets.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Branch: main → / (root) → Save**.
4. After a minute, your site is live at:
   `https://<your-username>.github.io/shah-gadgets/`

## Customize
All colors, fonts, and spacing are defined once at the top of the `<style>` block inside `index.html`, under `:root { ... }` — change a value there and it updates everywhere on the site.

## Note
This is a static front-end mockup, not a connected Shopify store — it has no real backend, payments, or inventory. To sell for real, either wire this design into a Shopify theme (Liquid) or add a checkout provider on top of it.
