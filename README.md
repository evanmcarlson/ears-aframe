# 8th Wall: Ears Aframe

Self-hosted migration of a legacy 8th Wall cloud project (A-Frame). No app key required; runs entirely
from static files. The engine binary loads from the CDN with `data-preload-chunks="face"`; 8frame
(8th Wall's A-Frame fork) is served locally from `external/scripts/`.

## Usage

1. `npm install`
2. `npm run serve`
3. To test on a mobile device, follow [these instructions](https://8th.io/test-on-mobile).

## Deployment

Pushing to `main` runs the GitHub Actions workflow in `.github/workflows/deploy.yml`, building the
project and publishing `dist/` to GitHub Pages. Build locally with `npm run build`.
