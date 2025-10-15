# Munrove Portfolio

A personal portfolio website built with Cecil static site generator.

## About

This is a personal portfolio showcasing projects and professional experience.

## Setup

1. Install Cecil (if not already installed):
   ```bash
   composer global require cecil/cecil
   ```

2. Build the site:
   ```bash
   ./cecil.phar build
   ```

3. Preview locally:
   ```bash
   ./cecil.phar serve
   ```

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions.

## Structure

- `pages/` - Content pages (Markdown)
- `layouts/` - Custom layout templates
- `assets/` - Images and other assets
- `themes/` - Theme files (Hyde theme)
- `_site/` - Generated static site (don't edit directly)
