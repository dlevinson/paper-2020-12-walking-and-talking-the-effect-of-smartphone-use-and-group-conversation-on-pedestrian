# Walking and Talking: The Effect of Smartphone Use and Group Conversation on Pedestrian Speed

This package is a private/restricted upload candidate for the paper by L. R. Walsh, T. T. Xian, D. M. Levinson, and H. S. Rayaprolu, published in TeMA: Journal of Land Use, Mobility and Environment, 12(3), 283-294. DOI: https://doi.org/10.6092/1970-9870/6088. A USyd handle is recorded at https://hdl.handle.net/2123/18775.

## Package status

This package should be uploaded only to a private GitHub repository or a restricted annex until the pedestrian-observation data are reviewed for deidentification. The source workbooks contain exact timestamps and free-text visual descriptions from public-place video observation. The package therefore keeps raw workbooks in a restricted folder and provides privacy-reduced CSV extracts for review.

## Contents

- `paper/final_published_paper.pdf` is the local final published paper reference used for validation. Check article-license terms before making the PDF public in a repository.
- `data/restricted_source_workbooks/` contains the two relevant source analysis workbooks: City Road Bridge and Bay Street. These are private/restricted review files.
- `data/public_deidentified/` contains candidate deidentified CSV extracts and an extract summary. These remove exact entry/exit timestamps, free-text descriptions/notes, and selected quasi-identifying body/appearance columns.
- `code/create_deidentified_extracts.py` regenerates the deidentified CSV extracts from the restricted source workbooks.
- `data/DATA_DICTIONARY.csv`, `documentation/DEIDENTIFICATION_NOTES.md`, and `ARCHIVE_MANIFEST.csv` document the package boundary and transformations.

## Paper-data match

The paper says observations were collected at City Road Bridge on 2018-04-24 and at Bay Street, Ultimo on 2018-05-01 and 2018-06-13. It reports 180 City Road records and 477 Bay Street records. The extraction script reproduces those counts from the staged workbooks: 180 valid City Road speed observations and 477 Bay Street observations after filtering the `Useful data` sheet to rows with valid speed and paper category code 1, 2, or 3.

## Exclusions

The standalone `Martin place.xlsx` workbook was not staged because Martin Place is not one of the two paper sites. Source video files are not staged and were not found in this package pass. Drafts, letters, presentations, and unrelated audit sidecars are excluded.

Generated: 2026-05-18 01:05:05 AEST

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:32:54 AEST

- Pipeline: `READY-TO-UPLOAD/PRIVATE`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
