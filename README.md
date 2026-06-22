# Walking and Talking: The Effect of Smartphone Use and Group Conversation on Pedestrian Speed

## Contribution

This paper uses observed pedestrian movements at two Sydney sites to distinguish the effects of smartphone use, group conversation, direction, gender, and following behavior on walking speed. It provides direct empirical evidence about how social interaction and mobile-phone attention alter pedestrian movement in everyday urban settings.

This package is a public upload candidate for the paper by L. R. Walsh, T. T. Xian, D. M. Levinson, and H. S. Rayaprolu, published in TeMA: Journal of Land Use, Mobility and Environment, 12(3), 283-294. DOI: https://doi.org/10.6092/1970-9870/6088. A USyd handle is recorded at https://hdl.handle.net/2123/18775.

## Package status

This package is ready for public upload subject to ordinary final license/provenance review. The source workbooks contain public-place pedestrian observation variables and do not contain direct identifiers such as names, addresses, contact details, respondent IDs, GPS traces, licence plates, or household identifiers. Compact CSV extracts are included for easier paper-level checks.

## Contents

- `paper/final_published_paper.pdf` is the local final published paper reference used for validation.
- `data/source_workbooks/` contains the two relevant source analysis workbooks: City Road Bridge and Bay Street.
- `data/public_reduced_extracts/` contains compact CSV extracts and an extract summary.
- `code/create_reduced_extracts.py` regenerates the compact CSV extracts from the source workbooks.
- `data/DATA_DICTIONARY.csv`, `documentation/PUBLIC_EXTRACT_NOTES.md`, and `ARCHIVE_MANIFEST.csv` document the package boundary and transformations.

## Paper-data match

The paper says observations were collected at City Road Bridge on 2018-04-24 and at Bay Street, Ultimo on 2018-05-01 and 2018-06-13. It reports 180 City Road records and 477 Bay Street records. The extraction script reproduces those counts from the staged workbooks: 180 valid City Road speed observations and 477 Bay Street observations after filtering the `Useful data` sheet to rows with valid speed and paper category code 1, 2, or 3.

## Exclusions

The standalone `Martin place.xlsx` workbook was not staged because Martin Place is not one of the two paper sites. Source video files are not staged and were not found in this package pass. Drafts, letters, presentations, and unrelated audit sidecars are excluded.

Generated: 2026-05-18 01:05:05 AEST

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-22 07:27:17 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Public paper-package repositories include `paper/` PDF reference copies by owner decision; publisher takedown requests can be handled later if they arise.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
