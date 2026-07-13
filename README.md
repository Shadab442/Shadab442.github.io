# Shadab Mahboob Academic Website

This repository contains the source for [https://shadab442.github.io](https://shadab442.github.io), an academic website built with Jekyll and GitHub Pages.

The site is organized around a small set of content collections:

- `_pages/` for standalone pages such as the homepage, CV, and section indexes
- `_publications/` for publication entries
- `_talks/` for talks and presentations
- `_teaching/` for teaching experience
- `images/` for profile and site images
- `files/` for downloadable documents such as PDFs

## Editing content

Most updates only require editing Markdown files:

- Homepage: `_pages/about.md`
- CV: `_pages/cv.md`
- Publications: add or edit files in `_publications/`
- Talks: add or edit files in `_talks/`
- Teaching: add or edit files in `_teaching/`
- Navigation: `_data/navigation.yml`
- Site-wide settings: `_config.yml`

The repository also includes optional helper scripts in `markdown_generator/` for generating Markdown entries from TSV data. The current site content can be maintained directly in Markdown, so those scripts are optional rather than required.

## Local development

If you want to preview the site locally:

1. Install Ruby, Bundler, and Node.js.
2. Run `bundle install`.
3. Run `bundle exec jekyll serve`.
4. Open `http://127.0.0.1:4000`.

## Repository notes

- Deployment is handled by GitHub Pages through `.github/workflows/pages.yml`.
- The repo has been cleaned up to remove stock demo posts, sample pages, and placeholder assets from the original template.
- A short maintenance guide lives in `docs/site-organization.md`.
