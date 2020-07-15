<!--    CHANGELOG FORMAT                                                -->

<!--    Completed Entry template:                                       -->
<!--                                                                    -->
<!--    # Date in DD MMM YYYY format                                    -->
<!--    ### New Features                                                -->
<!--    ### Improvements                                                -->
<!--    ### Fixes                                                       -->

<!--    Entries for pull request template:                              -->
<!--                                                                    -->
<!--    # Changes staged on develop                                     -->
<!--    ### New Features                                                -->
<!--    ### Improvements                                                -->
<!--    ### Fixes                                                       -->
# 15 July 2020
### Improvements
- Added a new utility script, [listMappings](util/listMappings.py), which creates a human readable list of mappings from the STIX mapping data. This script is capable of generating outputs in xlsx, csv, html, and markdown formats. See issue [#7](https://github.com/center-for-threat-informed-defense/attack-control-framework-mappings/issues/7).
- Updated all scripts to allow the user to specify which version of ATT&CK to use.

# 25 June 2020
### Improvements
- Added additional mappings to [nist800-53-r4](frameworks/nist800-53-r4)
- Added flag to [mappingsToHeatmaps](util/mappingsToHeatmaps.py) to allow it to remove previously generated layers when run
### Fixes
- Fixed `domain` field formatting for layers generated by [mappingsToHeatmaps](util/mappingsToHeatmaps.py).

# 24 June 2020
### Improvements
- Added pull request template
- Added [CONTRIBUTING.md](CONTRIBUTING.md)
- Added [CHANGELOG.md](CHANGELOG.md)