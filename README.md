# adbd-runsv

adbd as a runsv service for Magisk/KernelSU.

## Dependencies

- [runsvdir-magisk](https://github.com/sorubedo/runsvdir-magisk)

## Usage

1. Install both modules in Magisk/KernelSU.
2. Disable System adb service in settings app (instead by this service)
2. Edit `/data/adb/runsvdir/sv/adbd/conf` to change port (default: 5555).
3. Enable `adbd` from the runsvdir WebUI.