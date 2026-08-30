# VL.DeepSpace

A starter kit for developing applications for the [Ars Electronica Deep Space](https://ars.electronica.art/solutions/de/deepspace/).

## Features
- Wall/Floor stereoscopic camera rig
- Floor tracking 

For use with vvvv, the visual live-programming environment for .NET: http://vvvv.org

## Requirements

- [vvvv gamma 8.0 preview](https://vvvv.org/download/) 

## Getting started
- In the [Help Browser](https://thegraybook.vvvv.org/reference/hde/findinghelp.html) search for "VL.DeepSpace" and click the download icon
- When downloaded, check out the examples coming with the pack
- Save an example in a local work folder to modify it

## Commandline arguments
Here is a list of valid commandline arguments and their defaults in case they are not set:

|Argument|Default|Description|
|----------|----------|----------|
--FloorIP| |**Mandatory** for both wall and floor: IP of the floor PC
--WallDimensions|"16.0, 6.0"|Physical dimensions of the wall in meters
--FloorDimensions|"16.0, 6.0"|Physical dimensions of the floor in meters
--TuioIP|0.0.0.0|IP of the Tuio listener
--TuioPort|3333|Port of the Tuio listener
--OscPort|34567|Port of the OSC listener
--Fullscreen|false|Whether or not to start in fullscreen

As an alternative to specifying arguments via commandline, they can also be specified using a "settings.json" file next to the .vl or exported .exe file.

## Contributing
- Report issues on [the vvvv forum](https://forum.vvvv.org/c/vvvv-gamma/28)
- For custom development requests, please [get in touch](mailto:devvvvs@vvvv.org)
- When making a pull-request, please make sure to read the general [guidelines on contributing to vvvv libraries](https://thegraybook.vvvv.org/reference/extending/contributing.html)