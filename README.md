# Merikese Leib

Static one-page site for leib.merimeel.ee. Edit `index.html`, commit, push. GitHub Pages publishes `main`.

Photos: originals are cropped and encoded to `img/<name>-<width>.avif` + `.jpg` (ffmpeg crop/scale, avifenc -q 58). Hero is `hero`, gallery uses `kolm`, `kulg`, `eest`, `lahedalt`. Add a new photo by producing the same four files and copying a `<div class="foto"><picture>…</picture></div>` block in the `#galerii` section.

Order form: set the Web3Forms access key in `<form id="tellimusvorm" data-voti="KEY">`. With a key the form POSTs to api.web3forms.com and the order arrives in the inbox the key was created for; without a key, or if the request fails, it falls back to mailto plus a copyable order text.
