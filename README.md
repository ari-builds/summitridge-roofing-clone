# Summit Ridge Roofing Solutions — Clone

A static mirror of [summitridge-roofing-psi.vercel.app](https://summitridge-roofing-psi.vercel.app/),
with all assets (images, video, logo, CSS) downloaded locally and served from this repository's subpath.

Live: https://ari-builds.github.io/summitridge-roofing-clone/

## Structure

```
index.html      # single page, anchor navigation
styles.css
logo.png
BEFORE.png
AFTER.png
Vehicle.png
video.mp4
images/         # locally mirrored Unsplash assets
```

## Hosting notes

Asset references are root-absolute and prefixed with `/summitridge-roofing-clone/` so the site
works as a GitHub Pages *project* site. Deployment is handled by `.github/workflows/deploy.yml`.
