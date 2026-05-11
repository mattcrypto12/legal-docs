# Legal Docs Repository

This repository is a standalone public site for legal documents only.

It is designed so app repositories can stay private while reviewers and users still get permanent, public URLs for terms, privacy policies, and similar legal pages.

## Files

- `index.md` - landing page listing projects
- `wings-of-sol/index.md` - project landing page
- `wings-of-sol/terms.md` - Wings of Sol Terms of Use
- `wings-of-sol/privacy.md` - Wings of Sol Privacy Policy
- `_layouts/default.html` - shared site layout
- `assets/styles.css` - site styling
- `_config.yml` - GitHub Pages / Jekyll config

## Current Project

This repo currently includes legal pages for Wings of Sol using these values:

- Operator: Matt Crypto
- Support email: matt.crypto1212@gmail.com
- Governing law: Tennessee, USA
- Venue: Nashville, Tennessee
- Website link: points to the Wings of Sol legal section on the published site
- Mailing address: removed

If you later want to switch from a personal name to a company name, update the project pages before republishing.

## Adding Another Project

For another app like RentQuest, add a new folder at the repo root, for example:

- `rentquest/index.md`
- `rentquest/terms.md`
- `rentquest/privacy.md`

Then add that project to the root `index.md` list.

## Publish With GitHub Pages

1. Rename the default branch to `main` if needed.
2. Create a new public GitHub repository, ideally named `legal-docs`.
3. Add the remote:

   `git remote add origin https://github.com/YOUR-USERNAME/legal-docs.git`

4. Commit and push:

   `git add .`

   `git commit -m "Add Wings of Sol legal pages"`

   `git push -u origin main`

5. In GitHub, open the repository settings and enable Pages from the `main` branch root.
6. Wait for the Pages deploy to complete.

Your public URLs should then look like:

- `https://YOUR-USERNAME.github.io/legal-docs/`
- `https://YOUR-USERNAME.github.io/legal-docs/wings-of-sol/terms/`
- `https://YOUR-USERNAME.github.io/legal-docs/wings-of-sol/privacy/`

## If The Repo Name Changes

Update `baseurl` in `_config.yml` to match the GitHub Pages path.

Examples:

- repo name `legal-docs` -> `baseurl: "/legal-docs"`
- custom domain -> `baseurl: ""`

## Suggested Store Submission URLs

Use the final public Pages URLs in the Solana dApp Store publisher portal, not raw GitHub file links and not Google Docs links.

## Scope Guardrail

Do not add app source code, assets, builds, or private repository content here. This repo should remain a public legal-docs-only site.

