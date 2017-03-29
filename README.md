This is a small Pi hat that has simple goals:

- Power the Pi off 12 or 24V
- Control some LEDs (digital output)
- Control some additional FETs on 5/12/24V

Since the Pi doesn't have good PWM support, use fully off or fully on per
channel for best results.  The buck modules go on the bottom, and it hangs off
the GPIO header as its only support.

Check the branch list for other versions.
