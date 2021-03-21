# Universal Assembly Tips
Remember to check out the [jigs](jigs) folder for useful assembly helpers.

## X Axis Installation
1. Use calipers depth gauge to center the first rail and get the correct offset from 
the side, the important thing here is the distance from the edge. How in the middle it is 
and how far it is from the side is not as important as making sure the distance to the 
edge is equal. (Or just use the [rail alignment jig](jigs/linear_rail_alignment))
2. Clamp it down, recheck square, and punch two holes on the end with a transfer
punch. Alternatively, you could use a normal punch and try to align it, or a drill bit. All 
you need is a mark. Then take the rail off, use a normal punch to define that hole, and drill and tapp. 
3. Repeat step 2 for all 22 other holes but instead of clamps, I used the bolts on the 
rail. Use fluid while drilling and while tapping. 
4. That is the first rail done. For the 2nd do the same thing exept instead of trying to 
center the rail copy the offset from the first rail. If you do this make sure that you are 
measuring from the bottom or top of each rail. You need them to have the same offset or 
as close as possible. 
5. Install the screws into the rail and the beam onto the frame. 
6. Install the carriage onto the x, use m3x20 here. Some holes may need to be drilled larger to fit.  

## Rail alignment
"the Y-axis rails aren't that important, but in the X both rails need to be parallel 
so don't fasten the rails until the carriage is installed, then move the carriage to one side, fasten 
a couple of bolts on that side, slide it to the other side and fasten a couple of bolts on the other 
side and then you can go and fasten everything" -Ivan

# Reduction Version (HTD-5M)
## Belt Tensioners
X axis:
- Install tensioner on left side (away from carriage motor), so the belt bearings don't crash into it. You will need to drill a hole into your printed part for the screw to fit through.
- Doesn't require an extra belt tensioner, since screw goes through left carriage instead. However, you might want to print the mirrored version of the belt tensioner, if you stick with the stock ones (although I'm not sure if this makes a functional difference).

Y axis:
- Move tensioners as far back as possible, to prevent x axis crashing into it.

## Endstops
- Use GT2 belt clip thingys as endstops only, no belts attached.
- There are custom endstops available [here](modifications/endstop_limit_switch), where limit switches can be attached to. However, these are untested

# Base Version (GT2)