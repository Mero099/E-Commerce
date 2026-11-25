# Shoping Project

A React storefront built with Vite.

## Run locally

Install dependencies and start the development server:

```bash
npm ci
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

The production build is written to `dist`. The build also creates `dist/404.html`
so direct links and page refreshes work with GitHub Pages.

## Deploy to GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys
the site whenever changes are pushed to `main`. The Vite base path is configured
for this repository (`/Shoping-project/`).

In the repository settings, open **Pages** and set the build and deployment
source to **GitHub Actions**. After the workflow succeeds, the site is available
at <https://mero099.github.io/Shoping-project/>.
