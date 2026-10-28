# Power Query Ingestion Framework: Quarterly Chargeback Data Prep

**Case study** · Enterprise IT, Americas region · Role: Supervisor, Onsite IT & Automation Systems (2024–2026)

A reusable Power Query ETL framework that replaced an inherited, manual quarterly data-prep process for chargeback reporting. Figures marked as estimates are estimates.

---

## Situation

I inherited a manual process: the Americas region relied on manually populated Excel files for quarterly chargeback processing. The files arrived in inconsistent formats, used variable column names, were spread across multiple SharePoint folders, and needed hours of cleanup every quarter. The result was high overhead, inconsistent data quality, a risk of human error, delays in financial reconciliation, and no reusable ingestion pattern.

## Task

Design a reusable ingestion framework in Power Query that pulls completed chargeback data from the quarterly report files, normalizes schema differences, applies consistent transformations, and produces clean, analysis-ready data with minimal manual preparation.

## Action

- **Multi-file SharePoint ingestion:** connected Power Query directly to credentialed SharePoint Online document libraries, with pattern-based filtering so only the relevant quarterly files are ingested and queries don't need editing each quarter.
- **Schema normalization:** standardized column names across the source files, enforced data types to prevent downstream errors, and built a reusable "column harmonization" function.
- **Transformation and cleanup:** removed null rows, duplicates and file-specific inconsistencies, applied the business rules consistently, and added the calculated fields the chargeback logic required.
- **Reconciliation-ready output:** produced one unified dataset compatible with the downstream Excel models, structured for year-end validation against the vendor's report.

## Result

- An estimated **70–90% reduction** in recurring manual preparation time, with no loss in accuracy against the source data
- Consistent, repeatable ingestion every quarter
- The main source of schema-related errors and rework removed
- A reusable ingestion pattern for future datasets

## Lessons learned 

- **Normalize before you apply business rules.** Fixing column names and types first kept every later step simple to reason about.
- **Pattern-based file selection removes a quarterly chore.** The query adapted to new files without being edited.