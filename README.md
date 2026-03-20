# Creality K2 Pro – Klipper Screws Tilt Adjust

Screw tilt configuration for the **Creality K2 Pro** running **Klipper firmware**.


This repository provides a ready-to-use `screws_tilt_adjust` configuration for the 300×300 K2 Pro bed.

Verified screw coordinates: 2026-03-17  

Bed size: 300 x 300 mm

---

## Installation

Copy `screws_tilt_adjust.cfg` into:

```
~/printer_data/config/
```

Add to the top of `printer.cfg`:

```
[include screws_tilt_adjust.cfg]
```

Restart Klipper.

---

## Usage

Run in the console:

```
LEVEL_BED_SCREWS
```

Klipper will report how much to turn each bed screw.

---

## Screw layout

```
rear_left            rear_right
●-------------------●
|                   |
|                   |
|                   |
●-------------------●
front_left          front_right
```

___

Tested on:
Klipper 0.12+
Creality K2 Pro (300x300 bed)

If you encounter probe-related errors, please ensure your
Klipper installation is up to date.

---

## Credits

Based on a YouTube video by  
[@Jstech3d]  [https://www.youtube.com/watch?v=2zIDn_PHbyQ]  who deserves all the credits.

Configuration adapted from the **K2 Plus** to the **K2 Pro**
by Jacques Lerner.
