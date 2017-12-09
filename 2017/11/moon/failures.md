## Moon Lamp

For a Christmas present, I wanted to print a moon enclosure for a lamp. There are a number of
variations on textured moons, and different scales and configurations depending on the hardware
different makers used to create a glowing light effect in the lamp. These are all fantastic. This
isn't about finishing one of those. This is about completely failing to modifiy one of the more
popular, and large scale, moon models into a form suitable for a lamp.

A full scale print of the _Dexter's Moon_ model won't fit within the print volume of the Prusa i3 m2,
and reasonable scale versions at high quality could take _days_ to print. I wanted to make sure
the model and materials were going to work well, so I took an iterative approach; first printing 
a small scale version with the various settings I hope will work for a high quality and durability print.

### Starting Small

15%: https://www.instagram.com/p/Bb93uY-AL1w/?taken-by=dwyerdevices

The 15% version with consistent height layers turned out fine - too small for detail to show
through, but it confirms the need for better quality layers at the top of the print, where the
curvature of the sphere makes even high quality layers stretch out and look bad.

### Experimenting with Variable Height

50%: https://www.instagram.com/p/Bb938RJA3MR/?taken-by=dwyerdevices

The 50% version with variable height layers on the top and bottom failed twice - layer adhesion seemed to be an
issue, and the model portions kept pulling away from the support layer, catching on the PINDA
probe and tearing.

Eventually, printing a 50% scale version with variable layer heights for the top only turned out fairly well; the
north pole of the moon was a bit thin, and needs a few extra layers, and "thin walls" detection needs to be turned
on, otherwise quite a nice print. The final version will need to scale up just a bit more.

### Better Layers at the Poles 

Ok. 25% scale test with Cura, to see if we get better top layers.

25%: https://www.instagram.com/p/Bb94IbVAvFT/?taken-by=dwyerdevices

Ugly tearing, but better quality at the poles. One approach to improve the north pole layers would be to reslice
with an inverted moon, to get the surface quality from the base, and not worry about hte quality of the top part of the print (the bottom
of the moon), which will get removed with the final build. The bottom layers have plenty of support and typically
print much cleaner than the top layers.

### Final Scale

Scaling models is funny; sometimes problems only show up at very specific scales, where multiples
of layer heights don't quite line up, leading to, among other things, entire sections of the model
not adhering. In the case of the Dexter's Moon model, at 75% scale and 0.20mm layers, a gap appeared
in the sliced model, about 15% of the way up the moon. The gap was big enough that the layers above
the gap didn't adhere to the layers below the gap. After three failed prints, with the same characteristics,
at this scale, I opted to use a different model that was pre-scaled and remodeled for the specific
purpose of making a glowing moon lamp.

Chalk this up as a 20+ hour failure.


  
**Blog Post**: [Moon Lamp - Failures](http://www.dwyerdevices.com/2018/01/01/moon-lamp-failures/)

**Maker**: [Dexter_New_Materials](https://www.thingiverse.com/Dexter_New_Materials)

**Source**: [The moon](https://www.thingiverse.com/thing:1014620)

**License**: [Creative Commons - Attribution - Non-commercial](http://creativecommons.org/licenses/by-nc/3.0/)

**Model**: [Dexters_Moon_v2](https://www.thingiverse.com/download:1600569)

**GCode**: -

**Materials**: 

 - Prusa White PLA 1.75mm
 - Inland Gray ABS 1.75mm

**Print Date**: 2017/11/20 - 2017/11/25

**Print Time**:

 - 15% scale test: 1 hour 8 minutes
 - 25% scale test (ABS): 1 hour 2 minutes
 - 50% scale test: 6 hours 21 minutes
 - 75% scale: multiple aborted attempts
 
**Estimated Time**: 

 - 15% scale test: 1 hour 1 minute
 - 25% scale test (ABS): 1 hour 6 minutes
 - 50% scale test: 6 hours 1 minute
 - 75% scale: 10 hours 23 minutes

**Estimated Filament**:

 - 15% scale test: 1.6 meters
 - 25% scale test (ABS): 3.38 meters
 - 50% scale test: 22.1 meters
 - 75% scale: 35.79 meters
**Slicer**: Slic3r/PrusaControl

**Attempted Slicer Settings**:

 - various scales
  - 0.20mm layers
  - 0% infill
  - include supports (zig zag or pillars)
  - variable quality layering for top with larger prints
  - detect thin walls
  - extra perimeters if needed
  - top horizontal layers: 5
 - Upside Down
  - 4 perimeters
  - 75% scale
  - detect thin walls
  - extra perimeters if needed
  - 4 bottom horizontal layers
  - no infill
  - 10mm brim
  - 0.20mm layers
  - supports from print bed
  - pillar supports
  
**Printer**: Prusa i3 mk2  