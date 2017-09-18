## Moon in the Palm of Your Hand

Space is a popular topic around the house. We build Lego spaceships, we create video
games about space travel, the whole family crowds onto the couch to watch SpaceX launches (provided they
happen before bed time), and inumerable conversations come back to the expanse, scale, and
content of space.

I've been scouring Thingiverse, Shapeways, and 3D modeling sites looking for good
planetary models, and happened upon a model of the moon with accurate cratering by [Dexter_New_Materials](https://www.thingiverse.com/Dexter_New_Materials). This
looked like a great model for teaching, playing, and exploring. 

This was just around the time that [PrusaControl](http://www.prusaprinters.org/prusacontrol-release/) was released, and I decided to try it out
with this model. Some things worked well: material estimations and model print time
estimates looked accurate (and high: 20+ hours for a full scale and quality print). Some
things worked not so well. Or not at all: PrusaControl locked up trying to slice
this model, and I eventually gave up on debugging and switched over to Slic3r PE.

I opted to print a lower quality, scaled down version of the model to see how it
looked once printed. The normal size of the model has an approximately 20cm diameter (just _barely_ fitting
into the print volume of the Prusa i3 mk2), so I scaled down 50% to about a 10cm
diameter. That, combined with a hollow shell, resulted in just over 3 hours of print
time.

https://www.instagram.com/p/BY4XoEyAAeR/?taken-by=dwyerdevices

The lack of inner structure, and the low print quality, made the poles of the moon
a bit messy; gaps, strings, and rough edges. This model is an excellent candidate
for trying out [Smooth Variable Layer Height](http://www.prusaprinters.org/smooth-variable-layer-height-awesome-supports-slic3r-prusa-edition/) layer
editing in Slic3r PE - printing the layers near the poles at a finer layer height
will help smooth and correct the messiness. The rest of the model looked good even
at low quality, so there's no need to print the entire model at high quality. Using
Smooth Variable Layer Height should give us the best of both worlds; a quick print with
detail where it's needed.

**Blog Post**: [Moon in the Palm of Your Hand](http://www.dwyerdevices.com/2017/09/14/moon-in-the-palm-of-your-hand/)

**Maker**: [Dexter_New_Materials](https://www.thingiverse.com/Dexter_New_Materials)

**Source**: [The moon](https://www.thingiverse.com/thing:1014620)

**Original License**: [Creative Commons - Attribution - Non Commercial](http://creativecommons.org/licenses/by-nc/3.0/)

**Model**: [Dexters_Moon_v2.stl](https://www.thingiverse.com/download:1600569)

**GCode**: [Dexters_Moon_v2_0.35mm.gcode](https://github.com/dwyerdevices/prints/blob/master/2017/09/Moon/Dexters_Moon_v2_0.35mm.gcode)

**Material**: Natural Color ABS 1.75mm

**Print Date**: 2017/09/10

**Print Time**: 3 hours 3 minutes

**Slicer**: Slic3r PE 1.36.2

**Original Size**: 20cm diameter

**Scaled Size**: 10cm diameter (50%)

**Slice Settings**:

 - 0.35mm Layers (Draft / Fast Print)
 - 1mm brim
 - 0% infill (Hollow Shell)
 - Include Supports
 - Supports only on Print Bed
 

**Printer**: Prusa i3 mk2