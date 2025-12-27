# Commit Message Guidelines

Use a concise, consistent commit message format to make history easy to read and scan. We recommend the "Conventional Commits" style.

Format:

```
type(scope?): short summary

optional body

optional footer (e.g., BREAKING CHANGE: ...)
```

Common types:

- **feat**: a new feature
- **fix**: a bug fix
- **docs**: documentation only changes
- **style**: formatting, missing semicolons, etc (no code changes)
- **refactor**: code change that neither fixes a bug nor adds a feature
- **perf**: a code change that improves performance
- **test**: adding or updating tests
- **chore**: changes to the build process or auxiliary tools
- **ci**: CI configuration

Guidelines:

- Keep the subject line <= 50 characters when possible.
- Use the imperative, present tense: "Add", not "Added" or "Adds".
- Do not end the subject line with a period.
- Use the body to explain *why* the change was made and any important details.
- Include references to issues or PRs in the footer, e.g. `Closes #12`.

Example:

```
feat(blog): add simple static blog with client-side Markdown

Add `index.html`, `styles.css`, and the `posts/` directory with sample posts.
This makes it easy to add new posts as Markdown files.

Closes #4
```

This repository is small and lightweight — follow these guidelines for clarity and better collaboration.
