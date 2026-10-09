# Steam Wishlist Tracker — public project website

Static, bilingual (English/Turkish) project overview. This repository contains only the promotional website, not the private SWT application, credentials, logs or home-server data.

## Publish

1. Create a public repository named `steam-wishlist-tracker-site` under the intended GitHub account. Initialize with a README if uploading with the GitHub connector.
2. Put `index.html`, `.nojekyll` and `assets/` at the repository root.
3. In **Settings → Pages → Build and deployment**, select **Deploy from a branch**, then **main** and **/(root)**. Save.
4. Wait for the Pages deployment to succeed and use the live URL reported by GitHub. Do not submit a proposed URL to an affiliate form until it actually loads.

No build step, runtime dependency, API token, tracker or external font is required. Relative asset paths support GitHub Pages project subdirectories. Open `index.html` locally to preview, or use `python -m http.server 8080` from this directory.

## Content

The screenshot is an actual V4.2.2 development view. Prices are historical screen data, not live offers. The page discloses the current refresh bug and separates existing development work from planned improvements. Kinguin product access is unverified; Eneba feed access is not approved. Update these statements only after testing or approval.

Game artwork belongs to its respective owners. The site does not claim endorsement or partnership. Do not upload the SWT application, personal data folders or credentials to this public repository.

## Türkçe

Bu depo yalnız tanıtım sitesini içerir. `index.html` ile `assets` klasörü kök dizinde kalmalı. GitHub Pages kaynağı: `main` ve `/(root)`. Uygulama kaynaklarını, API anahtarlarını veya kişisel verileri eklemeyin. Dil düğmesi İngilizce/Türkçe geçişini sağlar.
