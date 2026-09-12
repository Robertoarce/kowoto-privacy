# Kowoto — public site

This repository holds the public web pages for the Kowoto app (iOS, App Store id 6802379102).

GitHub Pages publishes this repository from the `main` branch, at the root folder.

## Pages

| Page | URL |
| --- | --- |
| Home and support | https://robertoarce.github.io/kowoto-privacy/ |
| Privacy Policy | https://robertoarce.github.io/kowoto-privacy/privacy/ |
| Terms of Use | https://robertoarce.github.io/kowoto-privacy/terms/ |

## Why this repository exists

The Apple App Store listing points at these pages. Apple needs the privacy policy link to work.

The pages used to live in the `gh-pages` branch of the private `kowoto` repository. GitHub Pages does not publish a site from a private repository on the free plan. That is why the old links returned 404.

This repository is public, so Pages publishes it.

## Editing

Each page is one `index.html` file. There is no build step. Commit to `main` and GitHub publishes the change in about one minute.

When you change the Privacy Policy or the Terms of Use, update the "Last updated" date on the page.

## Contact

support@kowoto.app
