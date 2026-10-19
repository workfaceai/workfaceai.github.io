# Cedar invite links — cedar.workface.ai

A GitHub Pages site (free hosting) served at https://cedar.workface.ai, so a Cedar invite can be a
tappable link (`https://cedar.workface.ai/i/#…`) that opens Cedar straight from a text.

1. github.com → "+" → New organization → Free → name `workfaceai`.
2. In that organization → New repository → `workfaceai.github.io` → Public → Create.
3. Push this folder (the one-line command in the note, or `publish-site.command`).
4. DNS at the registrar for workface.ai: one `CNAME` record, host `cedar`, value `workfaceai.github.io`.
5. Repository → Settings → Pages → Custom domain `cedar.workface.ai` → Save → when the check passes, tick Enforce HTTPS.
6. https://cedar.workface.ai/i/ shows the page with a padlock.
7. Xcode → Signing & Capabilities → Associated Domains shows `applinks:cedar.workface.ai`.
8. Build 33.
