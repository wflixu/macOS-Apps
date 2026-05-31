# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository purpose

This is a curated list of awesome macOS open source apps, maintained in two files: `README.md` (English) and `README_CN.md` (Chinese). There is no build system, no tests, and no application code. When adding or editing entries, both files must be updated in sync.

## README conventions

- Categories are `##` headings (e.g. `## Developement`, `## Productivity`).
- Each entry is a `- [App Name](GitHub URL)` bullet. Native macOS apps get a `![native]` badge after the link. Paid apps get `![paid]`.
- Badge references are defined at the bottom of the file:
  - `[native]: https://img.shields.io/badge/native-D9603E`
  - `[paid]: https://img.shields.io/badge/paid-FFC131?&logoColor=black`
- Descriptions are brief and end without a period (unless multi-sentence).

## Editing guidelines

- Insert new entries alphabetically within their category.
- When an app is renamed or replaced, update both the link text and URL.
- Remove entries that are no longer maintained instead of annotating them.
- Commit messages should use Chinese, following the style from `git log --oneline`.
