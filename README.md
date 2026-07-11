# Yanjing Yang Academic Homepage

This repository contains a personal academic homepage built with GitHub Pages, Jekyll, and the Academic Pages template.

## Main Files

- `_config.yml`: site title, URL, author profile, links, email, and sidebar information.
- `_pages/about.md`: homepage content.
- `_data/navigation.yml`: top navigation links.
- `images/pensonal.jpg`: sidebar avatar.
- `files/`: PDFs, CV files, slides, and other downloadable assets.

## Local Preview

Install Ruby and Bundler first, then run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Open:

```text
http://localhost:4000
```

Docker is also supported if Docker Desktop is installed:

```bash
docker compose up
```

## Publish With GitHub Pages

Create a public repository named:

```text
Yang-Yanjing.github.io
```

Then add it as the remote and push:

```bash
git remote add origin https://github.com/Yang-Yanjing/Yang-Yanjing.github.io.git
git branch -M main
git push -u origin main
```

After GitHub Pages finishes building, the site should be available at:

```text
https://yang-yanjing.github.io
```
