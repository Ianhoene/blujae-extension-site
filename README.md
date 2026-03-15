# Blujae Extension Overview

This repository is the public-facing home for the Blujae Chrome extension.

It is intended to support a public GitHub repo and Chrome Web Store listing with clear, static documentation about what the extension does and how it handles data.

## Included files

- `index.html`: public product overview
- `privacy.html`: privacy policy
- `terms.html`: terms of use
- `styles.css`: shared styling for the site

## Suggested next steps

1. Push this folder to a new public GitHub repository.
2. Enable GitHub Pages or another static hosting option.
3. Use the published `privacy.html` URL in the Chrome Web Store listing.
4. Review the privacy policy against your live backend retention, support, and logging practices before submission.

## Drafting basis

This starter set is based on the current extension behavior visible in code:

- profile and draft data stored in `chrome.storage.local`
- visible job-page content extracted for analysis
- backend requests for job-fit analysis
- optional resume upload and parsing during onboarding
