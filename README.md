# memory-bound.github.io

Personal blog for AI, ML, and DL learnings and notes. Built to be hosted directly on GitHub Pages.

---

## How to Manage Blog Posts

### 1. Adding a New Post
Create a new Markdown file inside the `_posts/` directory following the naming format:
`_posts/YYYY-MM-DD-title-slug.md`

Example: `_posts/2026-11-11-intro-to-marketing-mix-modelling.md`

Add frontmatter at the top of the file:
```markdown
---
layout: post
title: "Introduction to Marketing Mix Modelling"
date: 2026-11-11
---

Write your blog post content here in Markdown...
```

### 2. Adding & Managing Images
1. Save your image inside the `assets/images/` directory (you can create subfolders per post or topic, e.g. `assets/images/mmm/diagram.png`).
2. Reference the image in your Markdown post using standard Markdown:
```markdown
![Diagram Description]({{ '/assets/images/mmm/diagram.png' | relative_url }})
```

---

## Publishing to the Web

Any commit pushed to the `main` branch will automatically be built by GitHub Pages and published to:
`https://memory-bound.github.io`
