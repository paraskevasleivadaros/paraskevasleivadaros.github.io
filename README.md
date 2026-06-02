# Paraskevas Leivadaros - Personal Website

This repository contains a personal website built with [Docusaurus](https://docusaurus.io/).

## Live URL

- Current project site: https://paraskevasleivadaros.github.io/docusaurus-2/

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
npm install
```

Start local dev server:

```bash
npm start
```

Create production build:

```bash
npm run build
```

Serve production build locally:

```bash
npm run serve
```

## Deploy To GitHub Pages

Deploy with Docusaurus:

```bash
GIT_USER=paraskevasleivadaros npm run deploy
```

Important GitHub Pages setting:

- Repository Settings -> Pages -> Source must use `gh-pages` branch and `/ (root)`.

## Project Structure

- `src/pages/index.mdx` - main homepage content
- `src/pages/projects.mdx` - projects page
- `src/pages/resume.mdx` - resume page
- `blog/` - blog posts and author metadata
- `docusaurus.config.js` - site configuration and navigation

## Notes

- This repository is configured as a project site (`/docusaurus-2/`).
- If you want this to be your root domain (`paraskevasleivadaros.github.io`), move the site to a repository named `paraskevasleivadaros.github.io` and set `baseUrl: '/'`.
