# Regional Search Intelligence — GitHub Pages site

## Before publishing

1. Replace **[REPLACE WITH PUBLIC CONTACT EMAIL]** in `index.html`, `privacy.html`, and `terms.html` with an address you are willing to publish. Do not put OAuth secrets, refresh tokens, or customer IDs into this repository.
2. Review the privacy and terms pages to ensure they accurately describe the application as actually operated. They are starter drafts, not a legal review.
3. Create a **public** GitHub repository, e.g. `regional-search-intelligence-site`.
4. Upload `index.html`, `privacy.html`, `terms.html`, `style.css`, and `.nojekyll` to the repository root and commit.
5. In GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**.
6. Once deployed, the URLs will normally be:
   - `https://YOUR_GITHUB_USERNAME.github.io/regional-search-intelligence-site/`
   - `https://YOUR_GITHUB_USERNAME.github.io/regional-search-intelligence-site/privacy.html`
   - `https://YOUR_GITHUB_USERNAME.github.io/regional-search-intelligence-site/terms.html`
7. In Google Cloud Console, project `gapi-512017`, open **Google Auth Platform → Branding**. Add these links in the corresponding fields and check any other required fields. Review Google's authorized-domain and ownership-verification requirements. **GitHub's shared github.io domain may not satisfy domain ownership verification; a domain you control may be necessary.**
8. Submit the OAuth brand for verification, then retry the Google Ads API Basic Access request after brand approval.

## Important

This static site is informational. It does not host the Python application, authenticate users, or solve Google API approval by itself. OAuth credentials and `oauth_token.json` must remain private and outside this repository.
