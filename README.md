# Digital Signage — GitHub Pages starter

This minimal starter contains the files you need to run a simple video player on **GitHub Pages**.

**What it contains**
- `index.html` — player page that plays `video.mp4` in full screen and reloads the video file every 5 minutes without reloading the whole page.
- `.nojekyll` — prevents GitHub Pages from running Jekyll (important for plain files).
- `README.md` — this file.

**How to use**

1. Create a new GitHub repository (public).
2. Upload these files to the repository root:
   - `index.html`
   - `.nojekyll`
   - your `video.mp4` (exact filename `video.mp4`)
3. In the repository, go to **Settings → Pages**, set the source to the `main` branch and folder `/ (root)` and save.
4. Wait a minute and open: `https://<your-username>.github.io/<repository-name>/`

**Notes & tips**
- GitHub web upload refuses files >100 MB. If your MP4 is larger, use Git (or host video externally and set the `<source>` URL in `index.html`).
- Browsers may block autoplay with sound; the player uses `muted` so it auto-plays. You can remove `muted` if you want sound but then user interaction may be required.
- For production use (many displays / 4K) use CDN or host video files in S3 / CloudFront and reference the URL in `index.html`.

If you want a more advanced dashboard, pairing, or Fire TV app skeleton, tell me and I will generate the extended repo.
