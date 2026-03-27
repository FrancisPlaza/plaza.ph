# plaza.ph

Personal blog and portfolio of Francis Plaza. *Ingenium, Veritas et Vis.*

Live at **[plaza.ph](https://plaza.ph)**

## Tech stack

- [Jekyll](https://jekyllrb.com/) 4 — static site generator
- [minima](https://github.com/jekyll/minima) theme
- [GitHub Pages](https://pages.github.com/) — hosting and deployment

## Local development

**Prerequisites:** Ruby and Bundler.

```bash
bundle install
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`.

## Writing a post

Add a Markdown file to `_posts/` using the naming convention `YYYY-MM-DD-slug.md` with the following front matter:

```yaml
---
layout: post
title: "Post title"
date: YYYY-MM-DD HH:MM:SS +0800
categories: category
---
```

## Deployment

Pushing to `main` triggers a GitHub Actions workflow that builds the Jekyll site and deploys it automatically to GitHub Pages.
