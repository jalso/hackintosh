# Hackintosh-10900K-Z490-Gaming-Edge-WiFi
Hackintosh build for an i9-10900K on an MSI MPG Z490 Gaming Edge Wi-Fi

## Major Versions
- OpenCore v0.6.7
- macOS Catalina 10.15.7

## [Build Specs](https://pcpartpicker.com/list/9b7GYg)
- Intel Core i9-10900K
- MSI MPG Z490 Gaming Edge Wi-Fi
    - Audio: Realtek ALC1200-VD1
    - LAN: Realtek RTL8125B 2.5G
    - Wireless Card & Bluetooth: Intel AX201
- 32 GB RAM
- Integrated Graphics card

## What's tested and working?

- Audio
  - OK
- LAN
    - The kext for our LAN adapter does not auto-negotiate and thus needs to be manually set to 1000baseT.
- USB
    - OK
- Sleep/Wake, Restart, Shutdown
- 2x DELL U2414H LCD Monitors, connected via HDMI and DisplayPort


## Issues 

- Wi-Fi
  - Not working
    - Tried itlwm.kext, also run Heliport - i got an error, that the itlwm is not loaded
- Bluetooth
  - Not working

- During boot I see everything twice on my LCD's, but the login screen appears only on my 1st monitor. 
My second monitor is not recognised (black screen), after login the first one has broken GUI (weird stripes, broken application windows). I must turn 
off and on my second monitor to fix this issue.
