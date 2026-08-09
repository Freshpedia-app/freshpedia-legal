# freshpedia-legal

Public hosting for the Freshpedia app's legal documents via GitHub Pages.

Published at:

- https://freshpedia-app.github.io/freshpedia-legal/privacy
- https://freshpedia-app.github.io/freshpedia-legal/terms

These are the URLs the app links to from Settings and the ones the Google Play listing points at, so they must not break.
GitHub does not redirect Pages after an org rename - if this repo or the org is ever renamed again, verify the new address serves before updating `PRIVACY_URL` and `TERMS_URL` in the app's `src/app/settings.tsx`.

Source of truth lives in the private app repo (PRIVACY.md / TERMS.md).
When those change, copy the changes here so the published pages stay current.
