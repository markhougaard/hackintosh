# Hackintosh status

- Can't choose USB in BIOS to boot from 😑

## Hardware

[PC Part Picker](https://pcpartpicker.com/list/cK4p7T).

- Gigabyte H310N Mini ITX LGA1151 Motherboard
- Intel Core i3-9100 3.6 GHz Quad-Core Processor
- G.Skill Ripjaws V Series 16 GB (2 x 8 GB) DDR4-3200 CL16 Memory
- Western Digital Blue 250 GB 2.5" Solid State Drive
- Noctua NH-L9i chromax.black 33.84 CFM CPU Cooler
- be quiet! Pure Power 11 400 W 80+ Gold Certified ATX Power Supply
- NZXT H210i Mini ITX Tower Case

## OpenCore

- Version 0.6.0
- Used the "[Sanity Checker](https://opencore.slowgeek.com/)" for the `config.plist` and it's green checkmarks all the way down

## BIOS Settings

- Followed all steps here: <https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings>
- Couldn't find the option to disable "CFG Lock", but both `AppleCpuPmCfgLock` and `AppleXcpmCfgLock` are added to Kernel -> Quirks as detailed in the docs.
