# Document Sources

Source files for use with [doc-generator](https://github.com/) (local path: `C:\source\github\doc-generator`).

## Structure

Each top-level folder is a single document project:

```
<DOC-ID>/
├── config.yaml      # Document metadata & generator config
├── style.css        # Document styling
├── assets/          # Images, reference.docx, etc.
├── chapters/        # Markdown chapter files (numbered)
└── output/          # Generated artifacts (gitignored)
```

## Current documents

- `EXAMPLE-001/` — Example document
- `SA40-0001/` — SA40-0001 specification

## Usage

Generate a document by running the doc-generator against the project folder. Generated files are written to each project's `output/` directory and are not tracked in git.
