# Rackside support site

Static pages for GitHub Pages: `index.html` (support + FAQ), `privacy/`, `terms/`.
All links are relative, so it works at `USERNAME.github.io/` or `USERNAME.github.io/REPO/`.

## Placeholders to fill before publishing
- `rackside.sup@outlook.com` (3 pages) → the support email address.

## After publishing
- Put the privacy URL in the app: `LegalLinks.privacy` in `Techfieldnotebook/Models/Subscription.swift`.
- App Store Connect: Support URL = site root, Privacy Policy URL = `/privacy/`.
- Terms of Use links to Apple's standard EULA.
