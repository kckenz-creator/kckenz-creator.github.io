# St Martin Institute of Technology — GitHub Pages migration

This is a **first-pass static reconstruction from the Hostinger WordPress backup of 24 September 2026**, not a verified pixel-identical WordPress export. Pages, content and uploaded media were recovered. Theme files are retained under `assets/theme` as a reference, but the WordPress PHP theme cannot run on GitHub Pages. The new CSS is a temporary accessible approximation.

## Publishing
1. Create a **public** GitHub repository (e.g. `school-website`).
2. Upload **the contents of this folder**, including `.nojekyll`, to the repository root. Do not upload the original SQL or hosting backup.
3. Settings → Pages → Deploy from a branch → `main` / root.
4. Test at the GitHub Pages preview URL before changing DNS. Because this build uses root-relative paths, a project-repository preview (`username.github.io/repository`) will not correctly resolve assets. For preview, use a repository named `username.github.io`, or configure a temporary custom domain.
5. Configure custom domain `stmartininstituteoftechnologyokigwe.com` in Pages, then set DNS records using GitHub's current instructions. Keep Hostinger live until tested. Verify HTTPS.
6. If using `www`, configure that alias too. Preserve MX/TXT email DNS records.

## Limitations and checks
- No WordPress admin, PHP, database, comments, login, search or server-side forms.
- Compare every page and menu against the live site before cutover. Some WordPress widgets, shortcode content, dynamic layouts, navigation structures and theme settings cannot be recovered from raw post HTML alone.
- Check embedded external URLs, downloadable files, images and links.
- Content is only as current as the September 24 backup.
- Some uploaded media may contain private information; review the assets before publishing.
- If the existing website has active forms, enrollment, payments or email integration, implement replacements before switching.
