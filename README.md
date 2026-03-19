# Creality K2 Pro – Klipper Screws Tilt Adjust

Configuration for screw leveling on the Creality K2 Pro running Klipper.

Verified screw coordinates: 2026-03-17

Bed size: 300x300

## Installation

Copy `screws_tilt_adjust.cfg` into:

~/printer_data/config/

Add to the top of `printer.cfg`:

[include screws_tilt_adjust.cfg]

Restart Klipper.

## Usage

Run in the console:

LEVEL_BED_SCREWS

Klipper will report how much to turn each bed screw.

## Screw layout

```
rear_left rear_right
●---------------●
|               |
|               |
|               |
●---------------●
front_right front_left
```

Based on a video in YouTube by          and adapted for Creality K2 Pro by Jacques Lerner
