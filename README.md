# sortie de metro paris — legal site

Static legal pages for the [sortie de metro paris](https://github.com/radinave1) Android app, hosted on GitHub Pages.

Published URL (after enabling Pages):
- Landing: https://radinave1.github.io/sortie-de-paris-metro/
- Privacy Policy: https://radinave1.github.io/sortie-de-paris-metro/privacy.html
- Terms of Service: https://radinave1.github.io/sortie-de-paris-metro/terms.html
- Support: https://radinave1.github.io/sortie-de-paris-metro/support.html

The privacy URL is referenced by Google Play store listing and by the mobile app in `app.json > extra.store.privacyPolicyUrl`.

## Sync with the in-app legal pages

The source of truth for legal text is `src/legal/legalDocuments.ts` in the app-mobile repository. When that file changes, regenerate the HTML in this repo to match. The two must stay identical because Google Play reviewers cross-check the public policy against the in-app version.

## Enabling GitHub Pages

After pushing this repo:

1. GitHub → Settings → Pages.
2. Source: `Deploy from a branch`.
3. Branch: `main`, folder: `/ (root)`.
4. Save. The site is live at the URLs above within ~1 minute.

## Contact

radinave@gmail.com
