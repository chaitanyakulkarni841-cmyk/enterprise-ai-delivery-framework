# How to upload your portfolio documents

[Home](README.md)

## The simple rule

Write and design your main content in your preferred document or presentation tool. Export it as a PDF with images. Upload that PDF into the relevant stage folder. Keep the folder's README as the navigation page; do not replace it with the report.

You may upload one document at a time or several files together. Do not upload a ZIP expecting GitHub to unpack it into folders.

## Choose the destination

| File | Destination |
|---|---|
| Reusable method/framework PDF | The relevant stage under `framework/` |
| Blank interview guide, scoring sheet, or Excel template | That framework stage's `templates/` folder |
| Completed Brightwheel stage report PDF | Matching stage under `case-studies/brightwheel-email-triage/docs/` |
| Completed case-study business workbook | `case-studies/brightwheel-email-triage/workbooks/` |
| Evaluation workbook, outputs, or comparison report | `case-studies/brightwheel-email-triage/evals/reports/` |
| Case-study screenshots, diagrams, or PDF preview images | `case-studies/brightwheel-email-triage/assets/images/` |
| Editable case-study diagram/document/presentation source | `case-studies/brightwheel-email-triage/assets/editable/` |
| Make scenario export | `case-studies/brightwheel-email-triage/solution/make/` |
| Actual prompts, routing configuration, schemas, controls | Their labeled folders under the case's `solution/` |
| Illustrative Enterprise Architecture discovery PDF | `examples/enterprise-architecture-discovery/` |
| Portfolio-wide hero graphic or T-shaped diagram | `assets/images/` |
| Executive summary or full-portfolio PDF | `exports/` |

## Upload through the browser

Open the destination folder on GitHub, choose **Add file → Upload files**, select or drag in your files, review the names, enter a descriptive commit message, and commit the upload. GitHub supports multiple files in one upload. Browser uploads are limited to 25 MiB per file and up to 100 files at a time; compress large image-heavy PDFs or split them by stage.

Official instructions: https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

## Naming and navigation

Use clear names such as `discovery-report.pdf`, `opportunity-assessment.xlsx`, `workflow-overview.png`, and `triage.blueprint.json`. The suggested filenames in folder guides are examples—not files that already exist.

After uploading, edit that folder's README and add the real document link. Example syntax:

```markdown
[Read the discovery report](discovery-report.pdf)
```

To show an image directly on the Brightwheel case's landing page after uploading it:

```markdown
![Email-triage workflow overview](assets/images/workflow-overview.png)
```

Keep links relative to the README containing them. Add descriptive image text. Keep the PDF's text selectable, headings clear, and figures readable. Include document status, version/date, and assumptions. Avoid broken links to planned files.

## Before each public upload

Check PDFs, hidden spreadsheet sheets/comments, editable documents, screenshots, and Make exports for sensitive material. Remove credentials, private webhook URLs, customer/school details, confidential interview notes, and information you lack permission to publish. Keep actual interviews and measured results separate from illustrative content.

## Placeholders

Each placeholder is a real README that explains what to upload. No empty or fake PDF, image, Excel workbook, model result, or working automation has been created. Update the relevant status and evidence links as real artifacts are added.
