# Math 2C03 public website repository

This is the public GitHub Pages source repository for Math 2C03, Fall 2026.
The GitHub repository is `davidearn/math2c`. Treat every tracked file as
immediately public.

## Repository role

The canonical website authoring source is in `../repoprivate/site/`. Approved
site files and selected student-facing documents will be published here using
an explicit allowlist. Do not copy the private repository wholesale.

The site should build from the default `main` branch. Do not create a nested
clone or a separate local `gh-pages` working tree.

Do not initialize Git, create GitHub repositories, commit, push, or deploy
unless the user asks.

## Public-safety rules

Never add:

- student names, numbers, email addresses, accommodations, grades, rosters,
  submissions, scans, or exports;
- solutions, answer keys, test banks, unreleased questions, or private test and
  examination source;
- private administrative email or documents;
- secure Echo360 links; or
- lecture days, times, or the classroom location.

Refer students to MOSAIC for lecture scheduling and location. Avenue is the
secure access point for Echo360 material.

Do not publish proprietary textbook figures or wording. Check PDFs and images
for private metadata and unintended answer material before release.

## Content controls

Do not change mathematical content or notation without asking the user first.
Make substantive authoring changes in the private repository, not in published
copies here. If a public file is generated, modify its source instead.

## Directory roles

- `assets/`: reusable website presentation files, such as CSS, public images,
  icons, and small site-wide scripts. Do not use it as a catch-all for lecture
  PDFs or assessments.
- `lectures/`: released lecture PDFs and related student-facing files.
- `assignments/`: public assignment information and released handouts.
- `polls/`: approved student-facing poll material.
- `tutorials/`: released tutorial material.
- `tests/` and `final/`: only material explicitly approved for public release,
  normally logistics or past material without restricted solutions.
- `handouts/`: general public course handouts that do not fit another category.

## Working conventions

- Use Canadian spelling in prose.
- Avoid spaces in new filenames and directories.
- Preserve unrelated user changes.
- Treat documentation as part of every state change. When repositories, files,
  dependencies, workflows, or publication state change, immediately search
  README files, AGENTS.md files, source comments, and build configuration for
  stale references and update them in the same task. Perform a final
  stale-reference search before reporting completion.
- Build the site and check links after meaningful changes.
- Visually inspect changed pages and layout-sensitive documents.
- Do not add prompt/response logging or automatic commits.
