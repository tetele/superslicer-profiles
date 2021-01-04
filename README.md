# SuperSlicer profiles for the BLV MGN Cube 3D printer

**This is just a stub and community contributions are more than welcome.**

This repository aims to set up a [SuperSlicer](https://github.com/supermerill/SuperSlicer) profile for the multiple variations of the wonderful [BLV MGN Cube 3D printer](https://www.blvprojects.com/blv-mgn-cube-3d-printer). Architecturally, it is heavily inspired by the profile for [Voron printers](https://github.com/supermerill/SuperSlicer/blob/master/resources/profiles/Voron.ini), but it also takes some inspiration from the [Prusa profile](https://github.com/supermerill/SuperSlicer/blob/master/resources/profiles/PrusaResearch.ini).

## Installation

### Windows
Open File Explorer and navigate to `%APPDATA%\Roaming\SuperSlicer\vendor`. Download the `BLV.ini` file in this folder and restart SuperSlicer if it was already running.

## Usage

*The profiles here do not take machine-specific parameters into account (like PID tuning parameters, pressure advance/linear advance values etc.). You will have to properly tune your printer before expecting these profiles to work wonders on your machine.*

After starting SuperSlicer, you should run the configuration wizard (Configuration > Configuration wizard), select BLV as the vendor on the left and then select your printer setup from the wizard.

**Your printer configuration might not be available. If that is the case, use the [issue tracker](https://github.com/tetele/superslicer-profiles/issues/new?assignees=&labels=New+configuration&template=missing-printer-configuration.md&title=%5BCONFIG%5D+) to request a specific profile.**

If you've found and added your printer, then you will have new items in the available printer, filament and print profile lists, all under `System presets`. Select your printer configuration, filament and print profile (customize them if necessary) and enjoy your new slicer settings.

## Issues

If you encounter issues, please report them in the [GitHub issue tracker](https://github.com/tetele/superslicer-profiles/issues). **Please state what setup you have (what extruder, what hotend, how they are connected), otherwise your report cannot be handled.**

## Contributing

The BLV MGN Cube is a highly customizable machine, so there are a ton of configurations in which it can run. As such, particular settings can only come from the community of users.

Feel free to create a pull request for any new configuration you want.
