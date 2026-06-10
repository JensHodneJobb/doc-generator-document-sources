# EXAMPLE-002-SIMPLE-PDF

Minimal source project for one Markdown document and one PDF output.

## What is included

- `config.yaml`: smallest valid config (one category)
- `chapters/01-document.md`: the document you edit
- `style.css`: minimal stylesheet
- `assets/`: empty by design (optional)
- `output/`: generated files land here

## Build PDF

From `C:\source\github\doc-generator`:

```powershell
C:\ProgramData\anaconda3\python.exe buildModularDocument.py C:\source\github\doc-generator-document-sources\EXAMPLE-002-SIMPLE-PDF PDF
```

This produces:

- `output/EXAMPLE-002 Single Document.md`
- `output/EXAMPLE-002 Single Document.pdf`
