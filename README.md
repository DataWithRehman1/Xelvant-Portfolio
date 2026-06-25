# Xelvant Portfolio

A responsive, single-page portfolio for Xelvant, a data science and automation agency serving e-commerce brands.

## Live site

[xelvant.dev](https://xelvant.dev)

## Features

- Responsive SaaS-style interface
- Service and case-study sections
- GitHub project links
- Accessible navigation and calls to action
- Lightweight, zero-build deployment
- GitHub Pages deployment workflow

## Tech stack

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript

## Run locally

No installation or build step is required. Open `index.html` directly in a browser, or serve the directory with any static server.

For example, with VS Code Live Server:

1. Open the repository in VS Code.
2. Right-click `index.html`.
3. Select **Open with Live Server**.

## Deploy with GitHub Pages

The included workflow deploys the site automatically whenever changes are pushed to the `main` branch.

In the GitHub repository:

1. Open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Push to `main` or run the **Deploy Xelvant to GitHub Pages** workflow manually.

## Project structure

```text
.
├── .github/
│   └── workflows/
│       └── deploy-pages.yml
├── .gitignore
├── .nojekyll
├── CNAME
├── README.md
└── index.html
```

The `CNAME` file configures the deployment for `xelvant.dev`. The domain's DNS must point to GitHub Pages before the custom domain becomes active.

## Copyright

© 2026 Xelvant. All rights reserved.
