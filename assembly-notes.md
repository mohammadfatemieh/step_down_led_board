Transistors are all small N-Channel mofsets which can be switched off 3.3v.
The one spec'd has a Vgs of 1.8V, rated for a few amps, and is fairly
inexpensive.

If you are running off 24V, you need to populate both buck modules.  They go
on the bottom, or on the top looming over the Pi header (thus install Pi
header first).  If you are running off 12V, just jumper pins 1 to 3 of M1.

The small mosfets can be switched by your 3D printer controller board; it just
needs common ground.  Alternatively, you can connect the solder jumpers on the
underside to control from the Pi.
