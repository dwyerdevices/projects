
The Prusa i3 tossed up one of its first calibration errors for me today; 

    Bed leveling failed. Sensor triggered too high. Waiting for reset.

That seems bad. A bit of googling, and a quick trip to the [Prusa Forums](http://shop.prusa3d.com/forum/original-prusa-i3-mk2-f23/calibrate-z-problem-bed-leveling-failed-sensor-tri-t1319.html) 
pointed to something being mis-aligned between the Z axis heights stored to the printers EEPROM during
calibration at the factory, and the bed height currently detected by the PINDA probe during pre-print
calibration. Which of the 9 calibration points it happens at seems to vary for people - for me it was
calibration point 2. 

Toggling the power to the printer to reset didn't solve the problem - the pre-print
calibration would always fail at the 2nd calibration point. A careful read of the forums and user 
manual indicated that re-running the full XYZ calibration was probably the best option; at some
point the printer got jostled, or the surface under the printer warped, and the current print
bed height was too different from the stored calibration height for at least one of the
calibration points.

I unloaded the currently loaded filament from the printer before running the full XYZ calibration. The second
or third step of full calibration has the printer mapping 4 points on the print bed to establish
the XY axis. During this phase the manual advises that you place a standard sheet of paper on the
bed to track whether the print nozzle is impacting the bed (that would be bad - and the manual helpfully
suggests that you should _immediately_ powerdown the printer if you notice the sheet of paper getting
caught and dragged by the print nozzle). I had problems with this step; the first three times I tried
the nozzle would catch the sheet of paper. 

Before the fourth try at recalibration I _really carefully_ inspected and cleaned the print nozzle, and noticed as I did
that about 0.5mm of filament had been poking out from the nozzle. Trimming off that filament
and cleaning the nozzle seemd to do the trick: the fourth recalibration went flawlessly.

The last step of recalibration, as suggested by a message from the printer on the control LCD and in
the Prusa manual, is printing the _V2Calibration.gcode_ model. Printing the model only takes two minutes,
but provides an easy way to validate that the Z axis is properly calibrated to get the print nozzle to the
right height for printing. If the nozzle is too high, filament won't adhere, and you'll just drag bundles of
filament around the print bed. If the nozzle is too low, you'll flatten out the filament too much as it prints, or
worse, impact the print bed with the nozzle. I used the **Live Adjust Z** controls of the printer to
fine tune the Z axis as much as I could to get a clean print of _V2Calibration.gcode_. Given how quick
the model prints, it took 3 consecutive prints to get things adjust to the point where the model was
printing smoothly and evenly.

Hoping that this had been enough, I jumped back to the model I had been attempting to print
when the "Bed leveling failed. Sensor triggered too high. Waiting for reset." error popped up, but I couldn't
get a print to successfully lay down the first layer. More **Live Adjust Z** tweaking resulted in an
overall Z axis offset of about _0.425mm_. After that, and a bit of glue, I got the original
model I had been attempting to print off to a good start.