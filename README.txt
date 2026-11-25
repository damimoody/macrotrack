MacroTrack upgraded food-search version

Files: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.

Deploy: In your existing GitHub repository, upload/replace these five files at the repository root and commit the changes. Keep the same repository and GitHub Pages settings.

Food search: searches Open Food Facts for packaged products and includes a small built-in common-food list. Results are displayed per 100 g; choose a gram amount and tap Use this food. This fills the existing manual-entry form; choose a meal and tap Add to food diary. If online packaged-food search is unavailable, matching built-in foods still appear. Verify packaged-food values against the package label. The database may contain incomplete or user-submitted records.

Existing diary data uses the same localStorage key and should remain on the same browser/device after updating. It is stored locally and is not synced across devices. Export a backup before updating as a precaution.
