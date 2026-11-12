# Deblo QBO Legal Website — GitHub Pages

This package contains five static files ready to upload into a **public GitHub repository**. There are **no API keys, tokens, server code, analytics scripts, or external scripts**.

## Files
- `index.html` — landing page linking to the two legal notices
- `eula.html` — end-user license agreement / internal terms
- `privacy.html` — privacy policy
- `styles.css` — shared responsive styling
- `README.md` — publishing and accuracy checklist (this file)

## Publish
1. Create a **public** repository on GitHub named `deblo-qbo-legal` (or another name you prefer).
2. Open the repository and select **Add file → Upload files**. Upload all five files at the **repository root** (not in a subfolder). Commit the changes.
3. Go to **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, then `main` and `/ (root)`, and **Save**.
4. Wait for GitHub to publish and open each live page in a private/incognito browser window to verify public access.
5. Assuming the repository name above, your URLs will be:
   - EULA: `https://YOUR-USERNAME.github.io/deblo-qbo-legal/eula.html`
   - Privacy: `https://YOUR-USERNAME.github.io/deblo-qbo-legal/privacy.html`
   - Home: `https://YOUR-USERNAME.github.io/deblo-qbo-legal/`
6. Replace `YOUR-USERNAME` with your real GitHub username. Enter the **verified working** HTTPS links in Intuit's production app assessment.

You can optionally add a custom domain later, but it is not required to publish these pages.

## Confirm before submitting to Intuit
These pages are **website-ready drafts, not an assertion of compliance**. Someone responsible for the application should check that every statement matches how the app actually works, especially:

- [ ] The name **Deblo QBO Integration** is acceptable as the app name (or update all pages to match the Intuit app name).
- [ ] `accounts@deblo.ca` is the approved public privacy/support contact.
- [ ] The application is exclusively for Deblo-authorized users and accesses the QuickBooks Online company with administrator consent.
- [ ] The listed QBO data categories and intended accounting functions accurately describe the app's real or planned functionality.
- [ ] Whether the app **writes, modifies, or deletes** QBO records, and the review controls for those functions.
- [ ] The real hosting/database/backup locations, providers, and cross-border data transfer practices, which may require more specific disclosures.
- [ ] Any runtime use of AI/LLM APIs or other third-party processors of QBO data, which may require additional disclosure.
- [ ] Authentication, token storage, safeguards, logging, actual retention/deletion behavior, and functioning disconnection procedures.
- [ ] Review for compliance with Intuit's latest app assessment requirements and any legal advice relevant to Deblo.

**Important:** GitHub Pages hosts the public legal documents only. It does **not** provide the backend needed for the OAuth redirect callback, token storage, or QBO API calls. Never commit your Intuit client secret, authorization codes, access/refresh tokens, .env files, or customer accounting data to this repository.

**Last prepared:** November 12, 2026.
