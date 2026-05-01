# Contributing to cp-editorial-data

Thanks for contributing to cp-editorial-data. This document describes the expected workflow for this repository.

## Getting Started

1. Fork this repository and clone your fork.
2. Create a branch for your change.
3. Add or update the relevant editorial PDF file(s).
4. Confirm the path and filename follow the conventions below.
5. Open a pull request with a clear description.

## Path and Filename

Use the existing directory hierarchy whenever possible:

`<Category>\<Organization or Series>\<Contest or Season>\<File>.pdf`

Examples from this repository:

- `Petrozavodsk Programming Camp\Summer 2024\Day 1 - Welcome Contest.pdf`
- `Open Cup\XXI Open Cup named after E.V. Pankratiev\Stage 14 - Grand Prix of Tokyo.pdf`

Guidelines:

- Keep files in the most specific existing folder.
- Preserve the original contest/event naming style and capitalization.
- Use `.pdf` for editorial files.
- Avoid unrelated renames or moves in the same pull request.

## Pull Requests

Before submitting, follow the repository PR checklist in `.github/PULL_REQUEST_TEMPLATE.md`:

- Describe the purpose and scope of your change.
- Review editorial content for correctness.
- Confirm links and references are valid (when updated).
- Include only files related to your change.

If your change is a correction, attribution update, or removal request, you can also open an issue using the templates in `.github/ISSUE_TEMPLATE`.
