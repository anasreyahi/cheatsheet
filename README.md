This template provides a three-column layout suitable for a formula sheet, reference page, or cheatsheet. It is designed to integrate with the [paper](https://github.com:jasedit/papers_base) system, which extends the MultiMarkdown LaTeX support to more easily encapsulate LaTeX templates.

# Usage

1. Clone this repository into the `templates/` subdirectory of the paper system.
2. In a paper's frontmatter, ensure the following values are set:
```
Base Header Level: 3
latex input: cheatsheet/setup.tex
latex footer: cheatsheet/footer.tex
```

Optionally, you can set the `my margin` value to some size to adjust the margins for the page, to fine tune how much of the page is in use. By default, the margin is set to `0.5in`.