# RA6T2 Bootloader

## Project baseline

This repository contains an e² studio project targeting the Renesas RA6T2.
The project configuration identifies the following:

- MCU: RA6T2, device `R7FA6T2BD3CFP`
- Board support package: `ra6t2_mck`
- Renesas Flexible Software Package (FSP): 5.9.0
- Configured toolchain: GCC ARM Embedded
- Build configurations: `Debug` and `Release`

The exact e² studio and GCC toolchain versions used to create the project have
not been recorded. Confirm the physical board model before relying on the board
support package as a description of the connected hardware.

## Build

1. Open e² studio with the RA FSP 5.9.0 platform and the required RA6T2 support
   installed.
2. Import this directory using **File > Import > Existing Projects into
   Workspace**.
3. Select the `Debug` configuration and build the `RA6T2_Bootloader` project.
   Use `Release` when a release build is needed.

## Baseline verification

The baseline has **not yet been verified**: no build result or on-board test
has been recorded. The current development environment does not have e² studio
or the configured ARM build tools available, so compilation could not be run
here.

Before treating this as a verified baseline, build the project in e² studio and,
if the target board is available, flash and run it. Record the e² studio and
toolchain versions, build result, exact board model, and observed run behavior
here.
