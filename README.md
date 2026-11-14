# Cuba Shattered 3D

The shattered-mirror Cuba collage rebuilt as solid 3D glass shards, exploded apart, with the artwork mapped onto each shard's top face. Drag to turn the view, scroll to zoom, and use the sliders to change the explosion and glass thickness.

## Files

- `index.html`: the whole page (three.js r128 loads from cdnjs, fonts from Google Fonts)
- `rubbish.jpg`, `fish.jpg`: the two photos used as the glass texture

Keep all three files in the same folder.

## Host it on GitHub Pages

1. Create a new public repository on GitHub, for example `cuba-shattered-3d`.
2. Upload `index.html`, `rubbish.jpg`, `fish.jpg` and this `README.md` to the repository root (Add file > Upload files), then Commit.
3. Open Settings > Pages. Under "Build and deployment", set Source to "Deploy from a branch", choose `main` and `/ (root)`, then Save.
4. After a minute or two the page is live at `https://<your-username>.github.io/cuba-shattered-3d/`.

### Or from the command line

```bash
git init cuba-shattered-3d
cd cuba-shattered-3d
# copy index.html, rubbish.jpg, fish.jpg and README.md into this folder
git add .
git commit -m "Cuba Shattered 3D"
git branch -M main
git remote add origin https://github.com/<your-username>/cuba-shattered-3d.git
git push -u origin main
```

Then turn on Pages as in step 3.

## Test it locally

Opening `index.html` straight from disk can block the photo textures in some browsers. Serve the folder instead:

```bash
python3 -m http.server 8000
```

and open http://localhost:8000.

## Licence

Design, code and text © 2026 Computational Classnotes, licensed CC BY-NC-SA 4.0.
The two photos are frames from a third-party video and are not covered by this licence. Make sure you have permission to publish them, or replace them with your own images using the same file names.
