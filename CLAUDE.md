# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Purpose

This is a bilingual (English + Chinese) recipe collection. All recipes are written in both languages and saved as `.md` files.

## User Preferences

- **Flavors:** Savory & umami, sweet & tangy
- **Spice:** Mild only
- **Diet:** No restrictions
- **Cook time target:** 30–45 minutes per recipe
- **Goal:** Easy daily recipes using commonly available supermarket ingredients

## Folder Structure

```
recipes/<region>/   → approved recipes, organized by cuisine
candidates/         → generated drafts pending user review
sources/            → recommended websites, books, YouTube channels, apps
_template.md        → the standard bilingual recipe format to follow
```

Supported regions: `chinese`, `italian`, `french`, `korean`, `indian`, `thai`

## Recipe Workflow

1. Generate new recipes and save them to `candidates/`
2. User reviews — if approved, move to `recipes/<region>/`; if rejected, delete

## Recipe Format

Every recipe must follow `_template.md` exactly:

- **Filename:** `kebab-case.md` (e.g. `honey-garlic-chicken.md`)
- **Header block:** cuisine, serves, prep time, cook time
- **Ingredients:** bilingual table with columns `Amount | Ingredient | 用量 | 食材`
- **Instructions:** two separate sections — `### English` then `### 中文`
- **Notes:** bilingual bullet points for tips, substitutions, storage
