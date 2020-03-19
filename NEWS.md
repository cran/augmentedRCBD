# augmentedRCBD  0.1.2

## UPDATED FUNCTIONS:
* `augmentedRCBD` - Added features to handle negative adjusted means; Fixed bug in computation of Tukey HSD and SE (Thanks to ahmad@cau.edu.cn).
* `report.augmentedRCBD` - Fixed missing row names in the table of 'Standard Errors and Critical Differences'.
* `gva.augmentedRCBD` - Added features to handle negative GV and/or hBS.
* `augmentedRCBD.bulk` - Added features to handle negative adjusted means, GV and/or hBS.
* `report.augmentedRCBD.bulk` - Added features to handle negative adjusted means, GV and/or hBS.
* `freqdist.augmentedRCBD` - Fixed compatability issues with updated implementation of `unit` function/class in `grid` package.

## OTHER NOTES:
* Added reference for expected value of mean square being used in `gva.augmentedRCBD`.
* Added further details for selection intensity in `gva.augmentedRCBD`.

# augmentedRCBD  0.1.1

## UPDATED FUNCTIONS:
* `report.augmentedRCBD.bulk` - Fixed issue with non syntactically valid column names.
* `augmentedRCBD` - Changed `emmeans::cld` to `multcomp::cld` to account for the changes in `emmeans` 1.3.5.

## VIGNETTE:
* Added vignette "Data Analysis with augmentedRCBD".

## OTHER NOTES:
* Fixed return/value in `gva.augmentedRCBD` documentation.

# augmentedRCBD  0.1.0

* First release

# augmentedRCBD  0.0.0.9000

* Pre-release
