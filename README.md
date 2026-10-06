# Luria Voice documentation

This repository contains the Mintlify documentation site for Luria Voice, the Quarto + Typst framework for generating professional neuropsychological evaluation reports.

## Overview

The site documents how to:

- scaffold Luria Voice report projects
- install and configure required dependencies
- write patient metadata and report content
- render polished PDF reports
- customize branding and output settings

## Repository layout

- `docs.json` — Mintlify site configuration and navigation
- `*.mdx` — documentation pages
- `concepts/` — conceptual overview and report structure guides
- `guides/` — step-by-step usage and workflow tutorials
- `configuration/` — brand, Quarto, and dependency configuration docs
- `templates/` — template-specific documentation for adult, pediatric, forensic, and Luria formats
- `images/` and `logo/` — branding and site assets
- `style.css` — site-level styling overrides

## Local development

From the repository root, start the docs locally:

```bash
mint dev
```

If the Mintlify CLI is not installed globally, use:

```bash
npx mint dev
```

The local preview will open in your browser with the live Mintlify docs server.

## Link validation

Check the documentation for broken links:

```bash
mint broken-links
```

Or:

```bash
npx mint broken-links
```

## Notes

This project is a documentation site, not the report template source itself. Most content is written in MDX and organized by topic, so updates are typically made by editing the relevant page under `concepts/`, `guides/`, `configuration/`, or `templates/`.
