# Paraskevas Leivadaros - Personal Website
This repository contains a personal website built with [Docusaurus](https://docusaurus.io/).

## Live URL
- Live site: https://paraskevasleivadaros.github.io/

## What Is In This Site
- Home page profile content
- Resume link and resume page
- Projects page
- Blog content (currently hidden from navigation)

## Tech Stack
- Docusaurus 3
- React 19
- MDX pages for site content

## Local Development
Install dependencies:

```bash
yarn install
```

Start local dev server:

```bash
yarn start
```

Create production build:

```bash
yarn build
```

Serve production build locally:

```bash
yarn serve
```

## Deploy To GitHub Pages
Deploy from `main` with GitHub Actions:

```bash
git push origin main
```

Important GitHub Pages setting:

- Repository Settings -> Pages -> Source should use `GitHub Actions`.

## Project Structure
- `src/pages/index.mdx` - main homepage content
- `src/pages/projects.mdx` - projects page
- `src/pages/resume.mdx` - resume page
- `blog/` - blog posts and author metadata
- `docusaurus.config.js` - site configuration and navigation

## Notes
- This repository is configured as a GitHub Pages user site served from the root domain (`/`).
