# Garmin fixes for Microsoft Flight Simulator

Currently fixing
- DME decimal places in Garmin GNS 530
    - Without the fix there is always single zero decimal
    - After fix
        - No decimals if >= 100 nm
        - Single decimal if < 100 nm
- Blinking Nearest Airports page on Garmin GNS 530/430 by adding working Airport logos from G1000
- Fallback to runway height in Waypoint search for Airport altitude

![DME decimal fix](https://raw.githubusercontent.com/veikkos/msfs-as-improvements/master/dme-decimal.png)
