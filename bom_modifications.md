# Universal BOM Modifications
## Z-Travel
### Vertical Beams
When using 60mm vertical beams, the Z travel is quite limited, 
to the extent that it can be challenging to change cutting bits even when moving the slider all the way to the top.

To combat this, you can use longer vertical beams. While some have doubled the length, going from 60mm to 90-100mm seems more reasonable
to ensure that the cutting bit can reach all the way down to the wasteboard, as well as giving a little peace of mind when considering rigidity of the frame.

When extending the vertical beams, you need to consider the following:
- The threaded rods that run through the vertical beams need to be extended by the same amount
- The stock electronics and power supply boxes don't fit between the upper and lower frame, so you will need modified versions. Before designing your own, try checking the [modifications](modifications) folder or ask around on the Discord, chances are that somebody has already done the work.

### Z Rails
While extending the vertical beams gives you more travel in the upward Z direction, there is also something to be gained in the downward direction.

The stock 200mm linear rails used to attach the vertical slider to the carriage are a little to short, so the blocks slip (at least partially) off the rails before the theoretical minimum Z position is reached.

A simple fix is to use 250mm linear rails and mount them in such a way that they are still flush with the bottom of the slider, but stick out over the top. While this doesn't look as clean, it ensures that your machine can utilize the full Z travel as constrained by the slider and carriage parts.

# Reduction Version (HTD-5M)
## Screw Lengths
The stepper motor screws are listed as M3x50mm in the BOM, which is insanely long. While it is not unthinkable, that you need 50mm screws for your motors, you probably want to use M3x16 or M3x18mm ones.

## Bearings
When using 608 bearings for belt redirection, it is possible that the clearance between the "upwards" and "downwards" part of the belt is to tight. Instead, use 698zz bearings, which have a smaller outside diameter. You will need to add some washers between the sideplate and the bearings, because the bearings are also thinner.
# Base Version (GT2)
nothing here yet

# Full Metal Version
nothing here yet