# Hermes Alfred

Public website and privacy documentation for **Hermes Alfred**, a privacy-first personal life manager.

🌐 **Live site:** [https://tkonate.github.io/alfred/](https://tkonate.github.io/alfred/)

## What is Hermes Alfred?

Hermes Alfred is a privacy-first personal life manager designed to help its user organize personal information, routines, planning, sport, finances, nutrition and projects with continuity and low cognitive load.

When connected to a Google account, it can access Gmail, Calendar, Drive, Contacts, Docs, and Sheets — exclusively to provide the features requested by the connected user.

## Pages

| Page | URL |
|------|-----|
| Home | [tkonate.github.io/alfred](https://tkonate.github.io/alfred/) |
| Privacy Policy | [tkonate.github.io/alfred/privacy.html](https://tkonate.github.io/alfred/privacy.html) |
| Terms of Use | [tkonate.github.io/alfred/terms.html](https://tkonate.github.io/alfred/terms.html) |

## Purpose

This repository serves three purposes:

1. **Public presentation** — a professional homepage for Hermes Alfred
2. **OAuth compliance** — required pages for Google Cloud OAuth verification
3. **Privacy documentation** — a complete privacy policy and terms of use

## GitHub Pages

GitHub Pages is enabled on the `main` branch via GitHub Actions. The site deploys automatically on every push to `main`.

To enable manually:
1. Go to **Settings → Pages**
2. Set **Source** to **GitHub Actions**

## Modifying Content

All pages are static HTML in the root directory. Edit the relevant file and push to `main`:

```bash
# Edit a page
vim index.html

# Commit and push
git add index.html
git commit -m "Update homepage"
git push
```

The site rebuilds automatically via the GitHub Actions workflow.

## Security

> **This repository contains public presentation and compliance pages only.**
> It does not contain the private Hermes Alfred runtime, personal data, OAuth tokens or production configuration.

- No secrets, tokens, or `.env` files are committed
- No personal data is exposed beyond the public contact email
- OAuth tokens are stored locally in the private runtime environment

## Project Status

🟢 Active — This site is live and maintained.

## Contact

For questions, data deletion requests, or support:
[d3miurge@proton.me](mailto:d3miurge@proton.me)

## License

MIT — see [LICENSE](LICENSE).
