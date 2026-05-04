# BEST App — Surface Screenshot Sheets

978 application surfaces split across 14 JPEG sheets. Each sheet: 8 columns × 9 rows, tiles 748×500px. At 1000px render width each tile is ~93×63px — scan for layout/state, fetch originals for detail.

## How to use

Import `index.json` first to see what each sheet covers:

```
github_import_files paths=["index.json"] repo="ksaidipalmera/cdn-eab982392721b0d4"
```

Then import sheets by number:

```
github_import_files paths=["sheet-01-of-14.jpg"] repo="ksaidipalmera/cdn-eab982392721b0d4"
```

## Sheet index

| File | Tiles | Surfaces covered |
|------|-------|-----------------|
| sheet-01-of-14.jpg | 72 | about … audit-s2 › fix-ai-loop-base |
| sheet-02-of-14.jpg | 72 | audit-s2 › fix-ai-loop-question … audit-v12 › source-materials |
| sheet-03-of-14.jpg | 72 | audit-v12 › workflow-studio … audit-v4 › module-ai |
| sheet-04-of-14.jpg | 72 | audit-v4 › pack-basics … audit-v7 › diff-fix-review-diff-open |
| sheet-05-of-14.jpg | 72 | audit-v7 › inline-after-enter … deliverables › after-map-i |
| sheet-06-of-14.jpg | 72 | deliverables › after-mapping-i … form-studio › build-add-field-preview |
| sheet-07-of-14.jpg | 72 | form-studio › build-add-field-surface … form-studio › search-empty |
| sheet-08-of-14.jpg | 72 | form-studio › search-empty-fix_verified … pack-library › search-empty-fix_verified |
| sheet-09-of-14.jpg | 72 | pack-library › singapore-pack … pack-studio › index |
| sheet-10-of-14.jpg | 72 | pack-studio › index_search-canada … project-runtime › exports-deep-detail |
| sheet-11-of-14.jpg | 72 | project-runtime › exports-route … projects_partial_progress_index |
| sheet-12-of-14.jpg | 72 | projects_partial_progress_runtime … source-materials › delete-fix-confirmation |
| sheet-13-of-14.jpg | 72 | source-materials › delete-fix-menu … workflow-studio › import-dialog-current |
| sheet-14-of-14.jpg | 42 | workflow-studio › import-export-before … workflow_studio |

## Getting originals

Original screenshots live in `/home/khali/best-loop/state/screenshots/` on the build machine. Surface keys in the index match filename prefixes — e.g. `pack-studio › index` → `pack-studio__index*.png`.
