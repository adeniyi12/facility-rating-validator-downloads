# Facility Rating Validator downloads

Download the desktop application for macOS or Windows. Python and a GitHub account are not required.

## Version 0.6.3 preview

- [Mac — Apple Silicon (M-series)](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.3/FacilityRatingValidator-0.6.3-macOS-arm64.zip)
- [Mac — Intel](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.3/FacilityRatingValidator-0.6.3-macOS-x64.zip)
- [Windows — x64](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.3/FacilityRatingValidator-0.6.3-Windows-x64.zip)

[Release notes and SHA-256 checksums](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/tag/v0.6.3)

Extract the entire ZIP before launching. On Mac, copy `FacilityRatingValidator.app` to Applications. On Windows, keep the extracted folder and its dependencies together and open `FacilityRatingValidator.exe`.

These are unsigned preview packages. The Mac application is not Apple Developer ID signed or notarized, and Windows has no publisher signature. Your operating system may warn about or block the download or launch.

The application stores databases and settings in your user application-data folder, separately from the installed application. Back up your data before upgrading.

All three packages passed automated tests and bundled checks for database operation, calculation, Excel read/write, and desktop startup. Interactive acceptance testing on your target machine is still recommended.

This repository contains downloads and installation information. Application development is maintained separately.

## Changes in 0.6.3

- Creates or updates a facility during report import; substation is optional.
- Preserves report metadata and supplied ratings, defaults unspecified units to MVA, and improves repeat-import matching.
- Supports scenarios with multiple equipment replacements or removals.
- Deletes facilities and their saved calculation/scenario data after confirmation, while retaining catalog equipment.
- Supports copying and pasting Excel rating ranges with validation and undo.
- Shows eight day/night conditions in the editor while preserving older saved values.
- Protects against stale facility reviews and rolls back failed imports and schema upgrades.
