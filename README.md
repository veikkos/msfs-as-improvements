# Garmin GNS 430/530 fixes for Microsoft Flight Simulator

[![Latest release](http://img.shields.io/github/release/veikkos/msfs-as-improvements.svg)](https://github.com/veikkos/msfs-as-improvements/releases/latest)

Currently fixing for GNS 430/530
- Fix DME decimal places
    - Without the fix there is always single zero decimal
    - After fix
        - No decimals if >= 100 nm
        - Single decimal if < 100 nm
- Fix blinking Nearest Airports page by adding working airport icon from G1000
- Fix missing airport icon in Waypoint pages
- Fallback to runway altitude in Waypoint page for airport altitude
- Fix most runway types seen as "Unknown"
- Fix some formatting errors on Nearest Airports page
- Allow selecting VOR frequency in VOR Waypoint page
- Fix invalid temporal values and missing logo on VOR Waypoint page

![DME decimal fix](https://raw.githubusercontent.com/veikkos/msfs-as-improvements/master/dme-decimal.png)
