# Aura Blade — GitHub Pages Website

This is a static HTML website for the Aura Blade mobile game publisher.

## Files
- `index.html` — homepage
- `about.html` — publisher overview
- `privacy.html` — detailed publisher privacy policy
- `contact.html` — support/privacy contact page
- `delete-account.html` — data/account deletion request page
- `assets/style.css` — responsive styling

## IMPORTANT BEFORE PUBLISHING
1. Replace `YOUR_SUPPORT_EMAIL` and `YOUR_PRIVACY_EMAIL` everywhere with real monitored email addresses.
2. Audit the SDK table in `privacy.html` against every production app. Keep only services actually integrated in each game, or keep the "may be used" wording only if it accurately describes your publisher practices.
3. Make the Google Play Data safety form match the actual production APK/AAB and SDK behavior.
4. Confirm your target audience/child-directed status for each app and configure advertising/consent accordingly.
5. If an app creates accounts, provide a working account deletion mechanism and keep this page synchronized with it.
6. Add your legal publisher/company name and business address if your legal counsel or applicable law requires it.
7. Review all third-party SDK privacy documentation and current Google Play policies before publishing.

## GitHub Pages
For a project site such as:
https://gamingstudio786.github.io/AuraBladesite/

Create/use a repository named `AuraBladesite`, upload all files with `index.html` at the repository root, then:
GitHub → repository → Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` → Folder: `/ (root)` → Save.

The site may take several minutes to become available.

## Custom domain
If you later buy a domain, configure it under Settings → Pages → Custom domain and add the DNS records requested by GitHub.

## Legal note
This template is not legal advice. Privacy requirements depend on the actual app, SDKs, jurisdictions, target audience, consent implementation, and data flows.
