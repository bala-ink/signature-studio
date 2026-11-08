# Signature Studio

A single-file, fully offline signature pad for the browser. Draw with a trackpad, mouse, stylus, or finger and export your signature as JPEG or PNG at the exact size and aspect ratio your form requires.

No installs, no build step, no dependencies, no server.

**Live demo:** <https://bala-ink.github.io/signature-studio/>

**Source code:** <https://github.com/bala-ink/signature-studio>

## Features

- Draw with a Mac trackpad, mouse, stylus, or touch screen
- Live WYSIWYG canvas that matches the exported image exactly
- Any output size and aspect ratio, with handy presets
- JPEG export with a white background (typical for exam/application forms)
- PNG export with a transparent background
- Adjustable pen thickness
- Adjustable JPEG quality with a live file-size estimate
- Undo (`Cmd/Ctrl + Z`), clear, and resize without losing your drawing
- Everything runs client-side — nothing is uploaded anywhere

## Use it locally

Open `index.html` in any modern browser (Safari, Chrome, Firefox, Edge). That's it.

## Publish it

### Netlify Drop (fastest)

1. Go to <https://app.netlify.com/drop>
2. Drag this folder (or just `index.html`) onto the page
3. Share the URL you get

### GitHub Pages

1. Create a repository and add `index.html` (and `README.md` if you like)
2. Open **Settings → Pages**
3. Under **Build and deployment**, choose **Deploy from a branch**, then `main` / root
4. Share the published URL

### Cloudflare Pages

1. Open **Workers & Pages → Create → Pages → Upload assets**
2. Upload this folder
3. Share the URL

### Vercel

1. Import the repository or run `vercel` in this folder
2. Share the deployment URL

## Tips for form uploads

- Check the form's instructions for the exact **pixel size**, **aspect ratio**, and **maximum file size**.
- If a form requires JPEG, use the JPEG option so the background is solid white.
- If a file-size limit is rejected, lower the JPEG quality a little and download again.
- Keep the signature inside the canvas; anything drawn outside is clipped.

## Feature requests & bug reports

Have an idea for a feature, or found a bug? Please open an issue:

<https://github.com/bala-ink/signature-studio/issues/new>

Helpful details to include:

- What you were trying to do
- Your browser and device (e.g. Safari on macOS, Chrome on Windows)
- The output size / aspect ratio you used (if relevant)
- A screenshot, if possible

Pull requests are welcome too.

## Privacy

All drawing and exporting happens locally in your browser. No data, images, or signatures are sent to any server.

## License

MIT © 2026 BALAJI D. See [LICENSE](LICENSE).
