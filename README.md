# SOL Instruments (Solar TII) MS Series Library for LabVIEW
LabVIEW instrument driver for SOL Instruments (Solar TII) MS series monochromator-spectrographs.

Tested on Solar TII MS3504i and MS2001i.

## Requirements
LabVIEW 2015 and higher.

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
