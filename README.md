# LabVIEW Instrument Driver for SOL Instruments (Solar TII) MS Series Monochromator-Spectrographs
Tested on Solar TII MS3504i and MS2001i.

## Disclaimer
This library was written using reverse engineering due to the lack of the device protocol information.

## Requirements
LabVIEW 2015 and higher.

## Installation
[VIPM package](https://www.vipm.io/package/plasmapper_lib_pl_sol_instruments_ms/)

## Features
1. Configure grating/wavelength/mirror/slit.
2. Open/close shutter.
3. Automatic reconnection to device.

## Configuration file
Manufacturer .cfg file (e.g. MS3504.cfg) is required to initialize the device.

## Extra
[Utility Library](https://github.com/plasmapper/utility-labview) can be used to save/load VI state, so that class control that contains current device configuration preserves its state.

## Examples
### SOL Instruments MS.vi
Example VI that demonstrates all library features.

## Links
[Imaging monochromator-spectrographs of MS series](https://solinstruments.com/en/products/spectroscopy/monochromator-spectrographs)
