# Visual_1083_Commuter
Information about the Visual 1083 luggable.

![V1083 without LCD](/Pictures/V1083_no_LCD.jpg)

## Power Supply
The internal power supply is switchable, by moving a wire, between 115VAC and 230VAC.  The fuse should also be changed: 1A for 115VAC, 0.5A for 230VAC.<br>
It contains three RIFA filtering capacitors that should be replaced, especially if original.<br>
- 0.1µF X-class, 250V, 15 or 20mm pin spacing (C2)
- 0.01µF (10nF/10000pF) X-class, 250V, 10 or 15mm pin spacing (C1 & C22)

![V1083 PSU](/Pictures/V1083_PSU.jpg)

## Cooling Fan
There is a cooling fan situated next to the power supply.  As this is an AC fan ... with no markings (in my case, at least) ... you will likely need to replace it if you are switching voltages - assume it's a 115VAC-rated fan.<br>
Its dimensions are 80mm square and 42mm deep.

## ISA Expansion
The Commuter has a DC62 port that is compatible with the IBM Model 5161 Expansion chassis.  To enable the use of expansion cards (such as an XT-IDE interface for CF storage), an expansion chassis will need to be built.<br>
Two possible options are:
- Quick 'n' dirty: [make](https://github.com/schlae/ibm-extender) or buy a 5161 Receiver card and customise an existing ISA backplane (such as one for the [Amstrad PPC](http://www.enide.net/webcms/index.php?page=ppc512-640-isa-expansion)) by adding power & clock
- More work: create a custom ISA backplane with surface mount 5161 Receiver functionality built-in

## Videos
- Part 1: https://youtu.be/goFxArGyGIE
- Part 2: https://youtu.be/txY1wbdtyFk
- Part 3: https://youtu.be/gmmH77M2TRg
