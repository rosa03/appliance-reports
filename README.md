# Appliance Executive Status Reports

This repository stores Appliance Executive Status Reports in Markdown so they can be maintained in a structured, reviewable, and version-controlled way. It provides a standard template, a consistent folder layout, and a simple operating model for ongoing executive reporting.

## Repository layout

- `templates/` stores the source Markdown template for new reports.
- `reports/` stores completed and in-progress reports, organized by year.
- `assets/` stores diagrams, images, and other report-linked visual assets.
- `exports/` stores generated PDFs and other export files.
- `docs/` stores process documentation for how reporting should be maintained.

## Creating a new report

1. Copy `templates/appliance-report-template.md`.
2. Save the new file into the relevant year folder under `reports/`.
3. Name the file using the convention `YYYY-MM-DD-appliance-status-report.md`.
4. Update the front matter and report content for the reporting period.

Example:

```text
reports/2026/2026-07-01-appliance-status-report.md
```

## Naming convention

All report files should use:

```text
YYYY-MM-DD-appliance-status-report.md
```

This keeps reports sortable by date and easy to locate.

## Diagrams and images

Store diagrams, screenshots, and report images in `assets/`. Link to them from reports using relative Markdown paths so the report remains portable within the repository.

## Exported PDFs

Store exported PDF versions of reports in `exports/`. Keep the Markdown report as the source of truth and use PDF exports only for distribution when needed.

## Why version history matters

Git history provides an audit trail of report changes over time. It helps teams:

- trace when decisions, risks, and status changes were recorded
- understand how executive messaging evolved between reporting periods
- preserve reporting consistency through reusable structure and reviewable edits
- support governance and assurance by retaining a history of who changed what and when
