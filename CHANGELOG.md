# Changelog

All notable changes to DCShop are listed here.

## 1.0.0 – 2026-09-27

First public paid release.

### Added

- Room drawing, collector placement, and a main built from 90° and 45° sticks
- Machine catalog, one branch per machine, blast gate, and flex
- Legal-stick rules: a change that cannot be built is refused, with a reason on the status line
- Analysis for one open machine at a time from the drawn pipe, elbows, and flex (lengths are measured from the floor, not typed)
- Green / yellow / red for chip-carrying velocity only
- Report for collector capacity: CFM, FPM, static pressure, equivalent feet, cyclone and filter losses
- Built-in collector classes: derated planning curves and published manufacturer curves, labeled as different things
- Size recommendations for main and branch, apply and re-run
- Save / reopen shop files
- Printable export of the whole floor plus the analysis (not a screenshot)
- Sample shop and user manual
- Windows installer (per-user, optional desktop shortcut)
- End-user license agreement

### Known issues

- Windows SmartScreen may warn; the installer is not Authenticode-signed yet
- One machine open at a time is the supported analysis case
- Planning estimates will not match a sloppy install, crushed flex, or a leaky blast gate
