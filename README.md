# norway-life.com

Static blog for [norway-life.com](https://norway-life.com), built with Jekyll and hosted on GitHub Pages. Migrated from WordPress.com in July 2026.

## How it works

- `_posts/` - one file per post, named `YYYY-MM-DD-slug.html`. The slug becomes the URL: `/YYYY/MM/DD/slug/` (same pattern as the old WordPress site, old links keep working).
- `images/` - all images, organized by year/month.
- `about-me.html`, `contact-me.html` - standalone pages.
- `_config.yml` - site title, tagline, and the "Buy me a coffee" link.
- GitHub Pages builds the site automatically on every push to `main`. No local tooling needed.

## Adding a new post

Create `_posts/YYYY-MM-DD-my-post-slug.html`:

```
---
layout: post
title: "My post title"
date: YYYY-MM-DD HH:MM:SS
categories: ["Life with breast cancer"]
---

<p>Post content in plain HTML, same as WordPress.</p>
```

Commit and push. The post appears on the homepage and in the RSS feed (`/feed.xml`) within a minute or two.
