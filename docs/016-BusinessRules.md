# BusinessRules

## Business Rules

### Exporting

Here are the rules for export to PDF or Markup\.

1. Project title and description is injected the in export \- H1 — \# Project Title in markup, <h1\> in PDF
2. Tree sorted by position — all child nodes and documents are sorted by position at every level
3. Parent\-child relationships respected — recursive tree walk follows the hierarchy
4. Component \-  don't inject headings or description
5. Document content is rendered as\-is without injecting the document name