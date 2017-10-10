# Cycloconverter
Thyristor based cycloconverter laboratory platform.

A project to play with when we are tired off transistors. For now just a place to gather some ideas.

If you are clueless, please start here: https://en.wikipedia.org/wiki/Cycloconverter
https://www.electrical4u.com/cycloconverter/

## Goals
* Three phase to three phase cycloconverter
* Support 230 and 400 volt three phase input
* At least 3 kW rated output power

## Hardware
The design should be modular, i.e a circuit board should only consist of six thyristors. By combining six of these modules it is possible to build a three phase cycloconverter.

Then the same modules may also be used in single phase cycloconverters (two modules), or simply as a voltage regulator for a DC-motor (a single module, or two modules).

### Thyristor
BT152 Thyristor in TO220 package, datasheet: http://www.ween-semi.com/documents/BT152_SERIES.pdf

### Pulse transformer
A pulse transformer is used to drive the thyristors. The Murata 786 series looks promising, or we could wind our own.

Murata 786:
http://www.farnell.com/datasheets/1578604.pdf

A possible core, that we happen to have an abundant supply of:
http://c1170156.r56.cf3.rackcdn.com/UK_PMA_TN26_15_10-3E25_DS.pdf

### Cooling
Heat sink for the thyristors?

### Current measurements
Hall effect sensors?

### Voltage measurement
The controller needs knowledge of the input line voltage in order to acurately determine when to send triggering pulses for the thyristors.

Isolation amplifier, or hall effect sensor?

## Controller
Probably a microcontroller in the Texas instruments Piccolo series.
