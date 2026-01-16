# CSE 198 Winter 2026 - Course Website

This repository hosts the course website for CSE 198 HKN Outreach, built with Jekyll and the "Just the Docs" theme.

## Licensing

- **Code/config:** Apache License 2.0 (see `LICENSE`).
- **Site/course content (Markdown text, syllabus, guides, images/media):** © 2026 Andrew Jeter — **All rights reserved**, unless a page/file states otherwise (see `NOTICE`).

## Setup & Editing

### Prerequisites
- Ruby & Bundler
- Jekyll

### Running Locally
1. Install dependencies:
   ```bash
   bundle install
   ```
2. Serve the site:
   ```bash
   bundle exec jekyll serve
   ```
3. Visit `http://localhost:4000`

### How to Update Content

#### Schedule
Edit `_data/schedule.yml` to update the weekly schedule table.

#### Deadlines & Events
Edit `_data/deadlines.yml` or `_data/events.yml` to update key dates and outreach opportunities.

#### Pages
Markdown files are located in `docs/` or the root directory. Use standard Markdown with Just the Docs front matter:
```yaml
---
layout: default
title: Page Title
nav_order: 1
parent: Parent Page Name # Optional
---
```
