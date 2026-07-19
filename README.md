# kyriehan-statement

Static policy and support pages for App Store metadata.

## Structure

- `index.html`: site home, useful as a public hub
- `assets/site.css`: shared styles
- `apps/<app-slug>/index.html`: app overview / optional marketing URL
- `apps/<app-slug>/privacy/index.html`: Privacy Policy URL
- `apps/<app-slug>/support/index.html`: Support URL

## Current apps

- `SignMint`
- `Outfit Ledger`
- `Chroma Pocket`
- `DailyLuck Oracle`

## Suggested GitHub Pages URLs

After publishing this folder to GitHub Pages, you can use URLs like:

- `https://<your-github-username>.github.io/kyriehan-statement/apps/signmint/privacy/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/signmint/support/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/signmint/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/outfit-ledger/privacy/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/outfit-ledger/support/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/outfit-ledger/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/chroma-pocket/privacy/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/chroma-pocket/support/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/chroma-pocket/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/dailyluck-oracle/privacy/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/dailyluck-oracle/support/`
- `https://<your-github-username>.github.io/kyriehan-statement/apps/dailyluck-oracle/`

## How to add another app

1. Copy `apps/signmint/` to `apps/<new-app-slug>/`
2. Update the app name, description, and contact details in the copied files
3. Add the new app card to `index.html`
4. Publish to GitHub Pages

## Before publishing

Replace any placeholder contact details that you want to customize, especially in:

- `apps/signmint/index.html`
- `apps/signmint/support/index.html`
