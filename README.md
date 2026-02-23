# LiaBakes SG 🧁

Interactive bakery website with a 3D cupcake hero built with Astro + Three.js.

## Quick Start

```bash
npm install
npm run dev
```

## Adding the 3D Model

The hero section loads a GLTF model from `public/cupcake.glb`. To set it up:

1. Go to [Cutie Cupcake on Sketchfab](https://sketchfab.com/3d-models/cutie-cupcake-5a0a52b6af8e431f80fd2044069474a5) (or any cupcake/cake model you like)
2. Click **Download** → choose **glTF** format
3. Extract the `.glb` file
4. Rename it to `cupcake.glb` and place it in the `public/` folder

The model is auto-scaled and centered, so any reasonably-sized GLTF will work.

**Attribution:** If using the Cutie Cupcake model, credit is already included in the footer. Update the credit link if you use a different model.

## Deploy to GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages → Source → GitHub Actions**
3. The included workflow auto-deploys on push to `main`
4. Update `site` in `astro.config.mjs` to your actual GitHub Pages URL

## Customise

- **About section:** Replace the emoji placeholder with an actual photo
- **Menu items:** Update to match real products
- **WhatsApp:** Change `https://wa.me/` to `https://wa.me/65XXXXXXXX`
- **Instagram:** Already set to @liabakes_sg
- **Colors:** Edit CSS variables in `:root` in `index.astro`
- **3D Model:** Swap `public/cupcake.glb` with any `.glb` file

## Tech Stack

- [Astro](https://astro.build) — static site generator
- [Three.js](https://threejs.org) — 3D rendering (GLTFLoader + OrbitControls)
- GitHub Pages — hosting

## License

Site code is free to use. 3D model has its own license (check Sketchfab).
