# Site Organization Guide

This repository is maintained as a content-first academic website.

## Primary source of truth

- Edit site pages directly in `_pages/`
- Edit publication entries directly in `_publications/`
- Edit talk entries directly in `_talks/`
- Edit teaching entries directly in `_teaching/`

The generated site should reflect these Markdown files, not notebooks or temporary exports.

## Folder roles

- `_pages/`: homepage, CV, section landing pages, utility pages
- `_publications/`: one file per publication
- `_talks/`: one file per talk or presentation
- `_teaching/`: one file per teaching role
- `images/`: site images
- `files/`: downloadable supporting documents
- `markdown_generator/`: optional bulk-import helpers, not part of the deployed site
- `talkmap/`: static assets for the talk map page

## Maintenance rules

- Keep only pages that are visible or intentionally reachable.
- Remove template/demo content instead of editing around it.
- Prefer direct Markdown maintenance unless bulk import is clearly needed.
- Keep `_config.yml` limited to settings that are actively used by the site.
- When adding new sections, update both `_pages/` and `_data/navigation.yml` deliberately.
