# Merikese Leib

Static one-page site for leib.merimeel.ee. Edit `index.html`, commit, push. GitHub Pages publishes `main`.

Photos: originals are cropped and encoded to `img/<name>-<width>.avif` + `.jpg` (ffmpeg crop/scale, avifenc -q 58). Hero is `hero`, gallery uses `kolm`, `kulg`, `eest`, `lahedalt`. Add a new photo by producing the same four files and copying a `<div class="foto"><picture>…</picture></div>` block in the `#galerii` section.
