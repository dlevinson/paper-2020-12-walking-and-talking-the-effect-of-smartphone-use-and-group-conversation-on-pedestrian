# Deidentification Notes

The paper uses individual pedestrian observations derived from public-place video. The raw staged workbooks are useful for private verification, but they are not treated as public-release data in their current form.

## Public candidate extracts

`city_road_bridge_observations_deidentified.csv` is generated from the City Road workbook's `Raw data` sheet. The script keeps rows with numeric seconds elapsed and speed, which gives the 180 observations reported in the paper. It drops exact entry and exit times, the original reference number, and the free-text `Description` field.

`bay_street_observations_deidentified.csv` is generated from the Bay Street workbook's `Useful data` sheet. The script keeps rows with numeric speed and paper category code 1, 2, or 3, which gives the 477 observations reported in the paper. It drops video-relative entry/exit times, `Notes`, estimated age, height and body-size adjustment columns, and appearance/footwear columns not needed for the paper-level result checks.

## Residual review needed

The candidate public extracts still contain row-level behavior, gender-coded observations, and location/date context. They should be reviewed before public release. The raw workbooks should remain private/restricted unless a stronger deidentification decision is made later.

Generated: 2026-05-18 01:05:05 AEST
