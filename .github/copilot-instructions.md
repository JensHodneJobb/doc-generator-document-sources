# Copilot Instructions: Markdown Consistency

Scope: all files under this repository.

## Authoring rules

- Keep chapter content pure Markdown.
- Do not add raw HTML/XML tags in chapter Markdown files (no `<div>`, `<p>`, `<span>`, etc.).
- Use Markdown syntax for headings, emphasis, lists, links, images, and tables.
- Use semantic Markdown attribute-list classes for layout intent when needed.

## Figure pattern

Use this pattern for captioned images:

```md
![Alt text](../assets/example-image.svg){.figure-full}
*{{figure:example-id | Caption text.}}*
{:.figure-caption .figure-full-caption}
```

Prefer semantic classes such as:

- `figure-full`
- `figure-left`
- `figure-right`
- `figure-caption`
- `figure-full-caption`
- `figure-left-caption`
- `figure-right-caption`

Do not target specific image filenames in CSS.

## CSS scope

- Keep `style.css` for reusable, template-level styles.
- Keep document-specific one-off styling in semantic classes, not file-path selectors.
- Avoid inline styles in Markdown.
