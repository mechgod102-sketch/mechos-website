# MechOS Website — Multi-Page Animated Upgrade

This build includes:

## New features
- full multi-page structure
- boot-style loading intro overlay
- dedicated download page
- dedicated release notes page
- dedicated community page
- hero video background support
- animated reveal transitions
- tilt effects on showcase graphics
- MechScope / Creator Mode / Performance Center graphics

## Pages
- index.html
- download.html
- release-notes.html
- community.html

## Important placeholder links to replace
Search for `data-placeholder-link` and replace the `href="#"` values with your real:
- GitHub repo
- ISO release URL
- SHA256 file URL
- release notes / public release URL
- Discord invite
- dev updates / social links

## Video background support
The homepage expects:
- `assets/mechos-hero.mp4`

If you add a real MP4 with that filename, it will autoplay as the hero background.
If you do not add it, the site still works and falls back to the static hero image.

## Deploy
This repository includes a GitHub Pages workflow that deploys the static site from `main`.
