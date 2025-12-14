# Huiyi's Tech Blog

This repository contains the source code for my tech blog hosted on GitHub Pages at [becknian.github.io/tech-blog](https://becknian.github.io/tech-blog).

## How to Add a New Blog Post

1. Create a new file in the `_posts` folder.
2. Name it in the format `YYYY-MM-DD-title-of-post.md` (e.g., `2025-12-15-my-second-post.md`).
3. Add front matter at the top:

```
---
layout: default
title: "Your Post Title"
---
```

4. Write your post content in Markdown below the front matter.
5. Commit and push to the `main` branch. GitHub Pages will automatically rebuild the site.

## Local Development

To preview the site locally, install Jekyll and run:

```
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## Customization

- Edit `_config.yml` for site settings.
- Modify `_layouts/default.html` for the layout.
- Update `css/main.css` for styling.