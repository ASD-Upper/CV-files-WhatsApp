# CV in Multiple Formats

This repository contains your CV in multiple formats and instructions for generating PDF and DOC versions.

## Files Included

- `cv.md` - Markdown version of your CV
- `cv.html` - HTML version with styling
- `cv.tex` - LaTeX version for professional PDF output
- `cv.xml` - XML structure for DOC format (advanced users)

## Converting to PDF

### From Markdown

Install Pandoc (https://pandoc.org/installing.html) and then run:

```bash
pandoc cv.md -o cv_from_markdown.pdf
```

### From HTML

Open the HTML file in a browser and use the browser's print function to save as PDF.

### From LaTeX (Best Quality)

Install a LaTeX distribution like TeX Live or MiKTeX, then run:

```bash
pdflatex cv.tex
```

This will generate the highest quality PDF.

## Converting to DOC/DOCX

### From Markdown

Using Pandoc:

```bash
pandoc cv.md -o cv.docx
```

### From HTML

You can open the HTML file in Microsoft Word or Google Docs and then save as DOCX.

## Online Conversion Options

If you prefer not to install software, you can use online conversion tools:

1. Open the Markdown or HTML file in an online Markdown editor like [Dillinger](https://dillinger.io/) or [StackEdit](https://stackedit.io/)
2. Export to PDF or Word format

For the LaTeX file, you can use an online LaTeX editor like [Overleaf](https://www.overleaf.com/) to compile to PDF.

## Editing Your CV

The Markdown version (`cv.md`) is the easiest to edit. After editing, you can regenerate the PDF and DOC versions using the instructions above. 