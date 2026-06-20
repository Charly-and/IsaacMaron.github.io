# Isaac Maron — Portfolio

Single-page engineering portfolio. Deploy via GitHub Pages — no build step needed.

## Deploy to GitHub Pages

1. Push this folder to a GitHub repo (e.g. `Charly-and.github.io` or `portfolio`)
2. Go to **Settings → Pages → Source → Deploy from branch → main / root**
3. Live at `https://charly-and.github.io`

## Adding images

Each project section has a placeholder comment like:
```
<!-- Replace with: <img src="images/sorter.jpg" alt="Sorting system"> -->
```
Drop your photo in the `images/` folder and swap the placeholder `<div class="img-slot">` contents for an `<img>` tag. The CSS handles cropping automatically.

## Adding your headshot

In the hero section, find:
```html
<div class="photo-slot">
  <span class="photo-hint">...</span>
</div>
```
Replace the `<span>` with `<img src="images/photo.jpg" alt="Isaac Maron">`.
