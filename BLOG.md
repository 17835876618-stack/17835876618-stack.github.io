# Simple Blog — Usage

This repository contains a tiny static blog that uses client-side JavaScript to render Markdown posts.

Files of interest:

- `index.html` — main blog page (lists posts + renders Markdown using `marked` and `DOMPurify`)
- `styles.css` — basic site styling
- `posts/` — Markdown posts and `posts.json` with the posts list

Add a new post:
1. Create a Markdown file in `/posts/`, e.g. `my-post.md`.
2. Add an entry to `/posts/posts.json` with this structure:

```json
{
  "title": "My Post",
  "date": "2025-12-27",
  "slug": "my-post",
  "file": "my-post.md",
  "excerpt": "A short summary"
}
```

Push your changes to `main` and GitHub Pages will publish the site at `https://<username>.github.io/`.

Tips:
- Use ISO dates (YYYY-MM-DD) to keep posts sorted correctly.
- Keep filenames short and slug-friendly.
