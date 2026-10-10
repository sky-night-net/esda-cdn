# ESDA CDN

Public image assets for the ESDA website. Source code, credentials, databases and application uploads are not included.

Images keep the website page folders and numbered identifiers. Photos are optimized WebP copies at original resolution; logos use lossless WebP. PNG originals remain in the private local website project.

Delivery: `https://cdn.jsdelivr.net/gh/sky-night-net/esda-cdn@<commit>/images/<page>/<image>.webp`.

Use an immutable commit hash in website URLs. `manifest.json` maps original website paths to CDN paths and records dimensions and file sizes. No API key is required for public image delivery.
