# Public Extract Notes

The paper uses public-place pedestrian observations at City Road Bridge and Bay Street. Header review of the source workbooks found observation variables, exact timing, free-text notes/descriptions, and observer-coded attributes, but no names, addresses, contact details, respondent IDs, GPS traces, licence plates, or household identifiers.

## Public reduced extracts

`city_road_bridge_observations_reduced.csv` is generated from the City Road workbook's `Raw data` sheet. The script keeps rows with numeric seconds elapsed and speed, which gives the 180 observations reported in the paper. It omits exact entry and exit times, the original reference number, and the free-text `Description` field because those columns are not needed for the paper-level checks.

`bay_street_observations_reduced.csv` is generated from the Bay Street workbook's `Useful data` sheet. The script keeps rows with numeric speed and paper category code 1, 2, or 3, which gives the 477 observations reported in the paper. It omits video-relative entry/exit times, `Notes`, estimated age, height and body-size adjustment columns, and appearance/footwear columns not needed for the paper-level result checks.

## Release boundary

The source workbooks and compact extracts are public-package candidates. Source video files are not included and were not found in this package pass.

Generated: 2026-05-18 01:05:05 AEST
