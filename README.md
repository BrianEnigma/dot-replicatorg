# Overview 

This project represents my ~/.replicatorg folder and the various Skeinforge
profiles contained within.  It tracks the changes I make to the profiles so
that I can remember what worked, what didn't, and so that I can clone my
profiles to new machines.

# Profiles

## Initial

The following profiles came with the 3D 5G shield/cable <http://www.thingiverse.com/thing:11837>

 - 3G 5D (Dimension) Example v2/
 - 3G 5D Shield (RPM) 1.75mm ABS MK7/
 - 3G 5D Shield (RPM) 1.75mm PLA MK7/

The 1.72mm folders are completely untouched (I don't yet have 1.75mm filament),
though I made some minor changes to the Example v2 folder.  Downloaded version
had Multiply turned on (it was trying to build 8 of each thing) and had no
raft defined.  The ReplicatorG UI seems to suppress the raft section if you have
raft disabled and leave it untouched if you have raft enabled.  With no raft
section in the config, the UI checkbox for enable/disable raft had no effect.

## Mine

The MK6 test2 was a copy of the 3G 5D Dimension example as I played with some
parameters.  I honestly don't completely remember what I changed.  I think I
slowed down the X/Y speeds really slow to match that of the MK5 because I was
having some print issues (that I since found were unrelated).

The Brian MK6 profile is the one I currently use and continue to fine-tune.  I
left the speed the same in the original, but slowed down the flow rate.  The
original settings were spewing out too much plastic -- it was not obvious at 
first, but on a tall print, things got a little italic or wobbily.  The print
would skew a bit in one direction, then skew in the other.  I had to back down
the flow rate to find the right balance between a clean build and good lamination
between layers.  If you set it too low, the layers don't bind to each other well.
If you set it too high, it seems like you get these skew/italic issues (at least,
as best as I could tell).

Next up: I'd like to figure out more of the Oozebane and/or Reverse sections
because, even at the lower flow rates, I'm getting some pretty globby prints in
detailed (more tower-like) sections.  

