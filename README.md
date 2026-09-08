# Input Metrics

Reference documentation for the canonical Snowflake structure, historical mappings, and validation rules used to standardize Raptive SEO Input Metrics.

## Current snapshot

- Canonical template: **August 2026 — Site List Row 2**
- Row 1 grouping headers are ignored
- Coverage: **February 2025 through August 2026** (19 reporting months)
- Validated dataset: **88,219 rows**
- Grain: one row per **SITE_ID × REPORTING_MONTH**
- Output: **76 columns** (64 canonical Row 2 fields, REPORTING_MONTH, derived INSTALL_YEAR, and 10 lineage fields)
- Duplicate grain keys: **0**
- INSTALL_YEAR is derived from the year in MONTH_ENROLLED

The row-level historical CSV and packaged skill are intentionally not stored in this repository.

## Repository contents

| Artifact | Purpose |
|---|---|
| [Validation and historical mapping report](docs/seo_input_metrics_validation_report.md) | Monthly coverage, source inventory, exclusions, renamed-field mappings, missing fields, quality flags, and true definition changes |
| [Canonical schema](schema/seo_input_metrics_canonical_schema.csv) | Ordered column contract, Snowflake types, definitions, and observed source headers |
| [Snowflake DDL](snowflake/seo_input_metrics_snowflake_ddl.sql) | Ready-to-run table definition for `AUDIENCE_GROWTH.SEO.INPUT_METRICS_MONTHLY` |

## Canonical rules

- Use the latest approved Input Metrics workbook as the schema authority.
- For Google Sheets and XLSX inputs, use **Site List Row 2** as column names and ignore Row 1.
- Preserve zero as a real value; use null only for missing or unavailable data.
- Map renamed fields only when definitions remain equivalent.
- Flag genuine definition changes instead of merging them silently.
- Exclude drafts, duplicates, files marked “do not use,” and ambiguous metrics unless explicitly approved.
- Validate uniqueness at `SITE_ID × REPORTING_MONTH`.
- Generate files only; do not append directly to Snowflake.

## Example skill questions

- “Convert this month’s SEO Input Metrics Google Sheet into an append-ready Snowflake CSV.”
- “Does this workbook match the August 2026 Row 2 canonical schema?”
- “Which columns in this file are new, missing, renamed, excluded, or definitionally different?”
- “Add this reporting month to the historical Input Metrics CSV and verify one row per SITE_ID × REPORTING_MONTH.”
- “Create a validation report, canonical schema CSV, and updated Snowflake DDL from these Input Metrics files.”
- “Which files in this Drive folder are duplicates, drafts, or marked not to use?”
- “Map historical metric names to the current canonical columns without merging true definition changes.”
- “Check that zero and null values were preserved correctly during conversion.”
- “Derive INSTALL_YEAR from MONTH_ENROLLED and report rows where it cannot be populated.”
- “Explain why a historical metric is null or excluded in the canonical dataset.”

## Updating this reference

When a newly approved workbook changes Row 2, regenerate all three artifacts together and document any definition boundary in the validation report before treating the new structure as canonical.
