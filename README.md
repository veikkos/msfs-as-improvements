# Garmin fixes for Microsoft Flight Simulator

Currently fixing
- DME decimal places in Garmin GNS 530
    - Without the fix there is always single zero decimal
    - After fix
        - No decimals if >= 10 nm
        - Single decimal if < 10 nm

![DME decimal fix](https://raw.githubusercontent.com/veikkos/msfs-as-improvements/master/dme-decimal.png)
