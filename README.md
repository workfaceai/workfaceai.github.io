# Cedar invite links — cedar.theworkface.ai

A GitHub Pages site (free hosting) served at https://cedar.theworkface.ai, so a Cedar invite can be a
tappable link (`https://cedar.theworkface.ai/i/#…`) that opens Cedar straight from a text.

1. github.com → "+" → New organization → Free → name `workfaceai`.
2. In that organization → New repository → `workfaceai.github.io` → Public → Create.
3. Push this folder (the one-line command in the note, or `publish-site.command`).
4. DNS at the registrar for theworkface.ai: one `CNAME` record, host `cedar`, value `workfaceai.github.io`.
5. Repository → Settings → Pages → Custom domain `cedar.theworkface.ai` → Save → when the check passes, tick Enforce HTTPS.
6. https://cedar.theworkface.ai/i/ shows the page with a padlock.
7. Xcode → Signing & Capabilities → Associated Domains shows `applinks:cedar.theworkface.ai`.
8. Build 33.
