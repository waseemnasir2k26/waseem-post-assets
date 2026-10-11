# Changelog

All notable changes to this project are documented in this file.

## [2026.10] - 2026-10-12

- Public image pool for the SkynetLabs LinkedIn auto-poster: `img/` holds LinkedIn-optimised rotation photos and `manifest.json` lists each with its raw.githubusercontent.com URL.
- Reviewed October 2026: `img/` now holds 25 photos and `manifest.json` has 25 entries (pool expanded 2026-09-18). The README still said 8 images and described the manifest as a filename-to-angle mapping; corrected to 25 images and file/category/url entries.
- No images were added, removed or re-encoded this month. README appended with the standard 'Work with SkynetLabs' section.
- Known gaps: no LICENSE or usage terms on publicly served photos; manifest-to-file parity was not scripted, only checked by count.

## [2026.09] - 2026-09-16

- Maintenance review of `waseem-post-assets` — the public image pool for SkynetLabs' LinkedIn auto-poster (n8n workflows LI-01/LI-02). It is deliberately public so the n8n LinkedIn node can fetch each photo as binary and upload it.
- Contents: `img/` with 8 LinkedIn-optimized rotation photos (max 1600px, ~85% JPEG, filenames coded CAFE-WORK / LIFESTYLE / PORTRAIT / TRAVEL / WORK) plus `manifest.json` listing each file with its `raw.githubusercontent.com` URL. No code, no build, no dependencies.
- Status: public repo, last updated 2026-08-27 when the pool and manifest were added. All 8 files in `img/` are present and every manifest entry resolves to a file in the directory.
- Reviewed September 2026: documentation refreshed and tagged v2026.09. No images added, removed or re-encoded, and no manifest URLs changed.
- Known gaps visible in the repo: no CHANGELOG before this release, no LICENSE or usage terms on photos that are publicly served, and the README describes `manifest.json` as a "filename → angle-fit mapping" while the file actually holds only `file` + `url` pairs with no angle-fit field.
