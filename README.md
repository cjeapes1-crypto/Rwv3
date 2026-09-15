# Rusty Warfare — GitHub Pages 3D Edition

This build is designed for **100% GitHub Pages hosting**. It uses no Node server and no external JavaScript libraries/CDNs.

## Included
- Your supplied Rusty Warfare map image
- Your supplied home-screen image
- Your supplied login image
- Your supplied create-account/server image
- Buttons positioned over the supplied UI artwork
- Dependency-free WebGL 3D island prototype
- WASD movement + mouse/touch-look
- Map overlay
- Inventory with stable slot selection
- **Pickup/selection bug protection:** adding/picking up items does not change the currently selected item
- GitHub Pages compatible

## Deploy
1. Create a GitHub repository.
2. Upload `index.html`, `style.css`, `app.js`, and the `assets` folder to the repository root.
3. Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.

The 3D multiplayer backend can later connect to Base44 without changing the static hosting model.
