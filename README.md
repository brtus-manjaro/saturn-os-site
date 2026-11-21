# Saturn OS website

A static project site using the supplied Saturn OS artwork. No build step is needed.

## Preview

Open `index.html` directly or serve the repository with `python3 -m http.server 8000`.

## Publish on GitHub Pages

In the repository, open **Settings → Pages**, select **Deploy from a branch**, then choose **main** and **/(root)**. Save the settings.

## Add the live image

When the ISO is ready, upload it to a GitHub Release or another public download host. In the download section of `index.html`, update the status text and replace the ISO pending paragraph with an anchor using the real download URL and the `button` class. Include the published SHA-256 checksum if available.
