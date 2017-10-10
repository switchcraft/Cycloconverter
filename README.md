# Cycloconverter
Thyristor based cycloconverter laboratory platform.

A project to play with when we are tired off transistors. For now just a place to gather some ideas.

If you are clueless, please start here: https://en.wikipedia.org/wiki/Cycloconverter

## Goals
* Three phase to three phase cycloconverter
* Support 230 and 400 volt three phase input
* At least 3 kW rated output power

## Hardware
The design should be modular, i.e a circuit board should only consist of six thyristors. By combining six of these modules it is possible to build a three phase cycloconverter. 

### Thyristor
BT152 Thyristor in TO220 package, datasheet: http://www.ween-semi.com/documents/BT152_SERIES.pdf

### Pulse transformer
Pulse transformer

## Controller
Probably a microcontroller in the Texas instruments Piccolo series.
