# Scope and layout

This repository holds personal, reusable agent skills, not customer playbooks or organization-specific workflows. Skills live in `.devin/skills/<name>/SKILL.md`.

Preserve the skills' meaning when copying or updating them. Keep machine-specific home paths, private screen content, customer information, credentials, and generated application state out of the repository.

The `attobrowser`, `cdpkit`, and `screen-history` skills refer to separate tool repositories. Their executable and source paths belong to those tool checkouts, not this collection. Do not install or launch those tools merely to validate a skill.

# Verification

There is no application build or automated test suite. For skill changes:

- Check YAML frontmatter: each skill needs a string `name` matching its directory and a nonempty string `description`; optional `triggers` contains `user` and/or `model`.
- Use the Devin skill search with this repository as the project path to verify discovery.
- Compare imported text with its source, separating intentional portability changes from accidental edits.
- Review referenced tool paths and dependencies, Markdown/code fences, and private or machine-specific material.
- Run `git diff --check` and `git diff --cached --check` before committing.
