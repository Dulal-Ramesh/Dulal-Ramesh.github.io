# Ramesh Dulal Academic Portfolio

This repository contains the source for my academic portfolio website, built with Jekyll and hosted with GitHub Pages.

## Local Development

Install dependencies:

```sh
bundle install
```

Build the site:

```sh
bundle exec jekyll build
```

Serve locally:

```sh
bundle exec jekyll serve
```

The local site is available at `http://localhost:4000`.

## Main Content Files

- `_data/settings.yml`: navigation, social links, and contact information.
- `_data/research/`: publications, work in progress, and conference entries.
- `_data/cv/`: education and academic experience shown on the CV page.
- `_data/courses-taught.yml`: teaching entries and syllabus links.
- `index.md`, `research.md`, `teaching.md`, `cv.md`, and `personal.md`: top-level pages.
- `assets/`: profile photo, CV PDFs, syllabus PDFs, icons, and vendor CSS/JS.

## Theme

The site is based on the open-source `academic-jekyll-theme`, with local customizations in `_layouts/`, `_includes/`, `_sass/`, and `assets/css/`.
