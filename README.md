# Munrove Portfolio

A personal portfolio website built with Cecil static site generator.

## About

This is a personal portfolio showcasing projects and professional experience.

## Setup (macOS)

### 1. Install PHP

If you don't already have PHP installed:

```bash
brew install php
```

Verify:

```bash
php -v
```

### 2. Build the site

If `cecil.phar` is included in the repository:

```bash
php cecil.phar build
```

Or make it executable once:

```bash
chmod +x cecil.phar
./cecil.phar build
```

### 3. Preview locally

```bash
php cecil.phar serve
```

Or:

```bash
./cecil.phar serve
```

Then open:

```text
http://localhost:8000
```

### Alternative: Install Cecil globally with Composer

```bash
composer global require cecil/cecil
```

Then you can run:

```bash
cecil build
cecil serve
```

## Deployment

The site is automatically deployed to GitHub Pages via GitHub Actions.

## Structure

- `pages/` - Content pages (Markdown)
- `layouts/` - Custom layout templates
- `assets/` - Images and other assets
- `themes/` - Theme files (Hyde theme)
- `_site/` - Generated static site (don't edit directly)
