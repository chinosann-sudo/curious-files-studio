# Curious Files Studio — public informational website

Public, static HTML/CSS pages for the privately operated Curious Files Studio YouTube API client. This repository is **public** and must contain **NO SECRETS** and no private YouTube automation code.

## Files
- `index.html`: overview and access model
- `privacy.html`: privacy practices (YouTube API, GitHub Actions, Google OAuth and data deletion)
- `terms.html`: website and API terms
- `404.html`: error page
- `assets/site.css`: responsive styles; no JavaScript, fonts, trackers or external assets
- `assets/favicon.svg`: simple local geometric icon

## Publish to GitHub Pages for $0 (GitHub Free)
1. In GitHub create a separate repository called `curious-files-studio`, visibility **Public**; initialize with README.
2. Upload/commit all website files to that repository's `main` branch (or connect your GitHub account to ChatGPT and have the assistant add the files).
3. Navigate to repository **Settings > Pages > Build and deployment**.
4. Set **Source: Deploy from a branch**, **Branch: main**, **Folder: /(root)**, then **Save**.
5. Wait for Pages deployment; visit your site's published URL shown in repository Settings > Pages. The expected default format is `https://<github-username>.github.io/curious-files-studio/`, but verify the real live link.
6. Check home, privacy and terms from a private/incognito window before inserting URLs into any YouTube API audit form.

## Important audit distinctions
- The `Primary Access URL` can point to this public informational site, but the actual client is **not publicly accessible**. Clearly answer **No** to the public-access question and provide a private reviewer walkthrough or demonstration if Google asks for it. Google's team decides whether the submitted URL meets review requirements.
- Do not paste an invented or unverified URL into the form.
- A public site alone does **not** establish API compliance, remove the private-upload restriction, or meet YouTube's consent/revocation requirements by itself. The private underlying uploader may need further changes and reviewer evidence.
- In Google Cloud, make the public brand/name consistent with this site; avoid using the YouTube name as part of your app branding without permission. Updating the OAuth client display name is not the same as rotating its ID or secret.
- The operator should review the public policy carefully; if any statement doesn't match actual operations or retention settings, fix it before publishing or submitting to Google.
- To give the public a private way to contact you, consider adding a dedicated support email later. The GitHub Issues method is public and unsuitable for credentials or personal details.