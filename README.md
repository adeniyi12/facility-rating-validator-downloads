# Facility Rating Validator downloads

Download the desktop application for macOS or Windows. Python and a GitHub account are not required.

## Version 0.6.4 preview

- [Mac — Apple Silicon (M-series)](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.4/FacilityRatingValidator-0.6.4-macOS-arm64.zip)
- [Mac — Intel (v0.6.3)](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.3/FacilityRatingValidator-0.6.3-macOS-x64.zip)
- [Windows — x64 (v0.6.3)](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/download/v0.6.3/FacilityRatingValidator-0.6.3-Windows-x64.zip)

[Release notes and SHA-256 checksums](https://github.com/adeniyi12/facility-rating-validator-downloads/releases/tag/v0.6.4)

Extract the entire ZIP before launching. On Mac, copy `FacilityRatingValidator.app` to Applications. On Windows, keep the extracted folder and its dependencies together and open `FacilityRatingValidator.exe`.

These are unsigned preview packages. The Mac application is not Apple Developer ID signed or notarized, and Windows has no publisher signature. Your operating system may warn about or block the download or launch.

The application stores databases and settings in your user application-data folder, separately from the installed application. Back up your data before upgrading.

The v0.6.4 packages passed automated tests and bundled checks for database operation, calculation, Excel read/write, and desktop startup. Interactive acceptance testing on your target machine is still recommended.

This repository contains downloads and installation information. Application development is maintained separately.

## Changes in 0.6.4

- Screens one or more facilities against a new load request in MW or a planner study value in MVA.
- Flags equipment below the required rating at the selected temperature and condition, and identifies missing ratings.
- Lists possible replacements from the equipment catalog for flagged equipment.
