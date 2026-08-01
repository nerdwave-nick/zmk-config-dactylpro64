# MochuKeeb Dactyl Pro 64 Firmware — DYA Studio

ZMK firmware for the 64-key MochuKeeb Dactyl Pro with a PMW3610 trackball.

## Branches

| Branch | Purpose |
| --- | --- |
| `trackball-automouse` | Standard ZMK v0.3 trackball firmware using the MochuKeeb PMW3610 driver |
| `trackball-dyastudio` | DYA Studio firmware with runtime trackball settings |

Use the branch matching the required firmware type. Do not flash firmware built
from the other branch without first resetting settings.

## Build targets

- `charybdis_nano_left`
- `charybdis_nano_right`
- `settings_reset`
