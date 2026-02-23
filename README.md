# LiaBakes SG 🧁

Interactive bakery website for [@liabakes_sg](https://instagram.com/liabakes_sg) — a home baker in Singapore.

Built with **Astro** + **Three.js** (vanilla). Deployed to **GitHub Pages**.

## Features

- 3D interactive hero scene with floating cupcakes, cookies & donuts
- Click/tap the main cupcake to spin it
- Mouse/touch parallax on the 3D scene
- Stitch-inspired blue/pink/lavender color palette
- Scroll animations, responsive layout
- Instagram & WhatsApp order CTAs

## Setup

```bash
npm install
npm run dev      # localhost:4321
npm run build    # outputs to ./dist
```

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source** → select **GitHub Actions**
3. The workflow in `.github/workflows/deploy.yml` handles the rest
4. Update `site` in `astro.config.mjs` to your actual GitHub Pages URL

## Customization

- **Colors**: Edit CSS variables in `:root` in `index.astro`
- **Menu items**: Edit the menu cards HTML section
- **About text**: Edit the about section
- **WhatsApp link**: Replace `https://wa.me/` with `https://wa.me/65XXXXXXXX`
- **Photos**: Replace the emoji placeholders in the about visual with actual `<img>` tags
