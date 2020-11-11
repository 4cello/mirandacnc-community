# Printing Tips
Some of the parts are very large and/or challenging to print. This is a collection of tips to help with printing the parts for the MirandaCNC.

## General Slicer Settings
### Perimeters
The number of perimeters is the most important factor for stability. 

Ivan recommends 3 perimeters and 3 top/bottom shells, but feel free to slap on 1-2 more, just for good measure.

### Infill
While higher infill also improves stability, it also increases the mass of the part, which dampens vibrations.

Ivan used 30% infill for his parts. Most slicers will give you an estimate of filament consumption of a part, so keep an eye on that.

## Specific Components

### Power Supply Box
The original power supply box is 30cm long, which doesn't fit on many printers. This repository contains a version, where the box itself and the covers are cut in half to a more manageable size. The STL files can be found [here](modifications/power_supply_box_halved). The parts are designed to be redundant, so a full box consists of the following parts:

 - 2x PSBOX_HALF
 - 2x PSBOX_HALF_CABLE_HOLE
 - 1x PSBOX_COVER_CUTOUTS
 - 3x any combination of PSBOX_COVER_BLANK and PSBOX_COVER_LOGO

### Carriage
The carriage is another very large part, however there are multiple ways to handle it.

The bottom of the part is not critical, so you can just cut it off. Just make sure you don't cut off any mounting holes for the sliding blocks. Also, double check that you cut off the bottom, not the top. [Image](https://i.imgur.com/QEvIyVc.png)

If the part won't fit flat on the bed, you can print it standing up. You can add [sacrificial layers](https://i.imgur.com/FXWv8qv.png) to cut down on plastic waste and printing time by removing the need for supports. Adding layers in the red spots in the image allows the 3D printer to simply use bridging. The sacrificial layers can be easily removed after the print using a knife. Sacrificial layers can be created either in the CAD program of your choice or directly in some slicers (like PrusaSlicer). Just make sure that the thickness matches your layer height to ensure that your slicer generates exactly one layer.