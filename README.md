# SEGWAY P/N: 21072-00001 REV: AJ
Reverse engineered information for the Segway motor with part number 21072-00001, revision AJ.

## Manufacturer Description
> The motors of the Segway PT are unique in many ways. Produced by Pacific Scientific, a business branch of Danaher, they are the most powerful motors that have ever been produced in their weight and size class. Both motors require 330 watts for continuous operation and produce a short time peak performance of up to 4 PS.
> 
> ![The Motor](/images/motoren.jpg)
>
> The motors use brushless servo-technology. This means there are no mechanical contacts that wear out and thereby reduce output. The magnets are comprised of an extremely powerful and rare earth metal: Neodym-Iron-Bor. Each motor is fitted with two independent windings, from which each of it’s own circuit boards are steered. Under normal conditions of use, the windings work parallel to each other and divide the workload. In the case of a malfunction the motor deactivates the malfunctioning winding and controls the remaining one to maintain control over the Segway PT until it is brought to a stop. The motor accurately calibrates the output from up to 8000 turns per minute, which enables a very high power level within a short range. By measuring the position of the magnets, redundant, contactless and analogue sensors give feedback from the motor to the control units. The motor axis is the only movable part.

Source: http://www.segway.ch/en/infos/technologie.php

## Schematic
This is the approximate schematic for one side of the motor. There are two of these on a given motor.

![Schematic](/images/schematic.png)

The motor appears to be configured in a Wye/Star configuration, with the relay being the center of the the Wye/Star. If the relay is unpowered, there is no connectivity between any of the coil wires. If the relay is powered with 12V, there is continuity between all coil wires.

The specs for the hall sensors are unknown, but tested with 5V, they draw about 18mA in total and gives out readings between 1.2V and 3.7V depending on the rotation of the motor.

## Further Information
The PCB (P/N: 23244-99001 REV: ab) controlling the motor uses 50A MOSFETs.
