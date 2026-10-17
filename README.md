# St. Martin Institute of Technology — GitHub Pages redesign

A responsive static website reconstructed from the September 24, 2026 WordPress backup.

## Publish
1. Extract this ZIP locally.
2. Upload the **contents** of the extracted folder to the root of the public repository `kckenz-creator/kckenz-creator.github.io` (replace the previous site files).
3. Under Settings → Pages select Deploy from a branch → `main` → `/(root)`.
4. Test at https://kckenz-creator.github.io.
5. Do not set the custom domain until the design and content have been approved.

## Notes
- This is a new design, not an exact recreation of the WordPress theme.
- Content and imagery were recovered from the supplied backup; course names and descriptions are retained.
- The original application payment instructions are displayed with a verification warning. Verify details before launch.
- News was under construction and staff names were not provided in the source.
- Email links depend on the visitor's email app. GitHub Pages cannot process server-side forms.
- Keep domain registration and email hosting active if they are separate services.
- Never publish the WordPress SQL backup, wp-config.php or WordPress user credentials.
- Fonts load from Google Fonts and fall back to system fonts if blocked.


FIXED VERSION: CSS is embedded in each HTML page so missing styles.css cannot cause an unstyled page. Image files must still be uploaded in assets/uploads; verify assets/uploads/2024/09/computerlab.jpg and classroom.jpg are present in GitHub repository. Replace old repository content rather than nesting the folder.


## Responsive revision
Updated responsive CSS is included both in styles.css and embedded within every HTML page. Preserve all directories when uploading via GitHub Desktop. Test at 375px, 768px and 1440px browser widths. Browser-level visual rendering has not been verified in this environment.
