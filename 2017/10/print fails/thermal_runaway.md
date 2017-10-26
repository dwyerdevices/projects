## Print Fail - Bed Thermal Runaway

Half way through printing a series of pieces for a Cosplay prop, I was
greeted by this:

https://www.instagram.com/p/Baq7Oq9gRGl/?taken-by=dwyerdevices

I tried restarting the print for the model I was using, and it automatically
stopped with the same error twice more, each time about 5 minutes into the
print.

The Prusa Support site has a section on [thermal runaway](http://help.prusa3d.com/mk2-electronics/thermal-runaway-and-temperature-drops), and
various forums seem full of questions about Thermal Runaway, with relatively few
useful answers. In my case, running PID Calibration (from the Info Screen go to **Calibration**
and then **PID Calibration**) fixed the problem.

PID Calibration is a nearly automatica process - the printer will prompt to
to set the _hotend_ temperature to 210°, after which it will raise and lower
the temp through five cycles, as it tries to tune it's [PID Controller](https://en.wikipedia.org/wiki/PID_controller).

**Blog Post**: [Print Fail - Bed Thermal Runaway](http://www.dwyerdevices.com/2017/10/25/print-fail-bed-thermal-runaway/)