# Garmin GNS 430/530 fixes for Microsoft Flight Simulator

[![Latest release](http://img.shields.io/github/release/veikkos/msfs-as-improvements.svg)](https://github.com/veikkos/msfs-as-improvements/releases/latest)

Currently fixing for GNS 430/530
- DME decimal places
    - Without the fix there is always single zero decimal
    - After fix
        - No decimals if >= 100 nm
        - Single decimal if < 100 nm
- Blinking Nearest Airports page by adding working Airport logos from G1000
- Fallback to runway altitude in Waypoint search for Airport altitude
- Fix most runway types seen as "Unknown"

![DME decimal fix](https://raw.githubusercontent.com/veikkos/msfs-as-improvements/master/dme-decimal.png)
