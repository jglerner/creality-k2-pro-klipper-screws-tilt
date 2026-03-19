# Creality K2 Pro – Klipper Screws Tilt Adjust

Screw tilt configuration for the **Creality K2 Pro** running **Klipper firmware**.

This repository provides a ready-to-use `screws_tilt_adjust` configuration for the 300×300 K2 Pro bed.
Verified screw coordinates: 2026-03-17  
Bed size: 300 x 300

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

---

## Credits

Based on a YouTube video by  
[@Jstech3d]([https://www.youtube.com/watch?v=2zIDn_PHbyQ]

Configuration adapted from the **K2 Plus** to the **K2 Pro**
by Jacques Lerner.
