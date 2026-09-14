# Mint Fantasy 3D Portfolio

## Pages
- `index.html` — main portfolio / game-lobby style page
- `ar.html` — dedicated AR camera page (opened by START AR CAMERA)

## Assets
- `assets/mint-profile.png` — profile image supplied by Mint
- `assets/tracker.png` — marker image
- `assets/tracker.patt` — marker pattern used by AR.js

## Epona model source
The website loads the Epona GLB from the URL supplied in the assignment:
https://sibsansuk.github.io/epona.glb

The same model is used on the portfolio page and AR page. The animation is not created by this HTML; it is embedded in the GLB when the model contains animation clips. The web viewer/AR runtime plays those embedded clips.

## Useful references
- AR.js marker-based AR documentation: https://ar-js-org.github.io/AR.js-Docs/marker-based/
- Three.js GLTFLoader: https://threejs.org/docs/#examples/en/loaders/GLTFLoader
- A-Frame: https://aframe.io/

## Important
Camera access normally requires HTTPS or localhost. GitHub Pages is suitable for deployment.
