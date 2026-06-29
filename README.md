# Mohammed Alsouri - personal site

A static personal website for applications and project proof. No build step, no framework, no backend.

```
omgbroops/
├── index.html
├── styles.css
├── script.js
├── .nojekyll
├── assets/
│   ├── favicon.svg
│   └── placeholders/
└── README.md
```

## Preview locally

Open `index.html` directly, or run a small server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

This repo publishes as a project site at:

`https://omgbroops.github.io/omgbroops/`

1. Commit and push to `main`.
2. On GitHub, open `Settings -> Pages`.
3. Choose `Deploy from a branch`.
4. Branch: `main`, folder: `/ (root)`.
5. Save and wait for GitHub Pages to publish.

## Links currently used

| Item | URL |
| --- | --- |
| Email | `mailto:maofficial2009@gmail.com` |
| GitHub | `https://github.com/omgbroops` |
| Polyshield | `https://polyshield.vercel.app/` |
| CareCompass | `https://carecompassonline.org/` |
| Calculus Instagram | `https://instagram.com/idislikelhopital` |
| JSwingX | `https://github.com/omgbroops/JSwingX` |

## Adding images

The site already has image slots. Add files under `assets/` with these names:

| Slot | File |
| --- | --- |
| Polyshield | `assets/polyshield-dashboard.png` |
| CareCompass | `assets/carecompass.png` |
| JSwingX | `assets/jswingx-ui.png` |
| Indie games | `assets/game-screenshot.png` |
| Pumps & Pipes | `assets/pumps-pipes.png` |
| Social preview | `assets/og-image.png` |

Recommended image size: 1600px wide for screenshots/photos. For `assets/og-image.png`, use `1200 x 630` and then uncomment the `og:image` meta tag in `index.html`.
