# 2026.09 — Maintenance release

- Maintenance review of `waseem-post-assets` — the public image pool for SkynetLabs' LinkedIn auto-poster (n8n workflows LI-01/LI-02). It is deliberately public so the n8n LinkedIn node can fetch each photo as binary and upload it.
- Contents: `img/` with 8 LinkedIn-optimized rotation photos (max 1600px, ~85% JPEG, filenames coded CAFE-WORK / LIFESTYLE / PORTRAIT / TRAVEL / WORK) plus `manifest.json` listing each file with its `raw.githubusercontent.com` URL. No code, no build, no dependencies.
- Status: public repo, last updated 2026-08-27 when the pool and manifest were added. All 8 files in `img/` are present and every manifest entry resolves to a file in the directory.
- Reviewed September 2026: documentation refreshed and tagged v2026.09. No images added, removed or re-encoded, and no manifest URLs changed.
- Known gaps visible in the repo: no CHANGELOG before this release, no LICENSE or usage terms on photos that are publicly served, and the README describes `manifest.json` as a "filename → angle-fit mapping" while the file actually holds only `file` + `url` pairs with no angle-fit field.
