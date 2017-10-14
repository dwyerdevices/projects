## Surface Tests

One of the options you can play with in Slic3r changes the infill pattern used on the bottom and
top visible surfaces of a print. Different from the interior infill pattern, the surface pattern
changes the look and texture of horizontal planes.

By default Slic3r will use a _rectilinear_ surface pattern; simple parallel lines at a 45° angle. 
I decided it would be fun to compare the alternative surface fill patterns available in Slic3r (as of Slic3r Prusa Edition 1.37.1).

To make the comparison easier, I designed a simple set of small objects, each labeled with what would
be the print resolution used to print them. For this set of tests I generated prints at four resolutions (0.05mm, 0.10mm, 0.20mm, and 0.35mm)
using four different surface fills: Octagram Spiral, Archimedean Chords, Hilbert Curve, and Concentric fill.

The entire set of printed test tiles:

https://www.instagram.com/p/BaC_QDXAWvc/?taken-by=dwyerdevices

The quality and finish of the surface patterns seems to be highly dependent on the quantity
of infill used on the interior of the print - some fill patterns have longer lines that benefit
from denser infill for bridging support. In later sections I'll pick out the best (in my 
non-quantitative opinion) patterns for the different print resolutions I tried out.

### Octagram Spiral

The Octagram Spiral patterns looks like an eight pointed star, with repeated right angles
filling out the sides and corners:

https://www.instagram.com/p/BZ9SGeOAofx/?taken-by=dwyerdevices

While this pattern looks nice and has an even and gap-less fill for 0.10mm and 0.20mm resolution,
it does leave occasional pits and small gaps at 0.35mm. For this pattern, like the others, the 0.05mm
resolution print is a loss.

### Archimedean Chords

The chord pattern looks like a series of overlapping circular bands:

https://www.instagram.com/p/BZ9o-IYA-1p/?taken-by=dwyerdevices

The chord pattern created a fantastic surface in the 0.10mm print. The 0.20mm and 0.35mm prints
were gap-free and had consistent shape, but also suffered from slight puckering and raised
edges along the chords. 

### Hilbert Curve

The Hilbert Curve pattern is a dense printed version of the [Hilbert space-filling curve](https://en.wikipedia.org/wiki/Hilbert_curve),
and presents as a fractal pattern of right angles forming a continuous, uninterrupted line
across the surface:

https://www.instagram.com/p/BZ_aYVqg7u5/?taken-by=dwyerdevices

At 0.10mm resolution the Hilbert Curve surface fill is clear and distinct; you can trace the
lines across the whole surface. At 0.20mm the features become indistinct, and while a pattern
is evident in the noise, the surface appears as just that: noise.

At 0.35mm the space filling curve suffers from extreme pitting, with a grid like
pattern of holes in the surface.

### Concentric Fill

As far as I can discern, the concentric fill attempts to match the fill lines
against the edges of the fill surface in parallel, with the different angles
of lines meeting in the center. You can see the segments of lines attempting to
parallel the curved and irregular angles of the quarter-circle cut out and extruded
numbers:

https://www.instagram.com/p/BaCuJhbA50d/?taken-by=dwyerdevices

The finish on the 0.10mm, 0.20mm, and 0.35mm were all quite good, with the tight
intersections of different line sets on the 0.35mm print creating a slightly
jagged joint.


### 0.35mm Resolution

Looking at just the 0.35mm resolution tiles, the Octagram Spiral and Archimedean
Chords stand out as the cleanest surfaces. 

https://www.instagram.com/p/BZ_hb9FAmHq/?taken-by=dwyerdevices

If I had to choose, I would go with the **Archimedean Chord** surface fill: the angled
joints between lines on the Octagram surface can sometimes create a rough bump, while
the circles of the Chord pattern avoid such problems.

### 0.20mm Resolution

At 0.20mm resolution all of the surface fills work well, and which one to use
would depend quite a bit on what is being printed. 

https://www.instagram.com/p/BaCurJsgrz-/?taken-by=dwyerdevices

The Hilbert curve, while still noisy at this resolution, creates a diffuse pattern
when light is reflected in the surface. For prints using a sparse internal infill, I would
probably choose the **Octagram Spiral**, as it minimizes, to some extent, long filament
strands stretching across the entire print. For prints with denser infill and more complex
edge geometry, I would choose the **Archimedean Chord** infill, which will minimize
odd and irregular joints which might cause a rough or buckled surface.

### 0.10mm Resolution

The patterns and lines of the surface fills are really clear at 0.10mm:

https://www.instagram.com/p/BaCwH7DgJm6/?taken-by=dwyerdevices

At this resolution the **Hilbert Curve** stands out as a clean, diffuse, and consistent
surface. The other surface fills have fine enough detail that they can distract from the
print itself - it's hard not to notice the lines and curves, humans are fantastic pattern
matchers. On close inspection the Hilbert Curve also has a very distinct, and very noticable
pattern, but when viewed from more than a few inches away, the pattern fades away, and the
surface just appears lightly, but regularly, textured.


### 0.05mm Resolution

The structural infill of the printed models played a large part in the print quality at
0.05mm resolution; significant gaps between structures and ultra-fine filament strands
don't mix well:

https://www.instagram.com/p/BaCyK6qAjXZ/?taken-by=dwyerdevices

All of the surfaces infills exhibited the same flaws, in the same places: the gaps in
infill. It's impossible to make a useful decision about an optimal surface pattern with
these prints, but some fared better than others. The long lines in the Concentric fill
had the worst bubbling and holes, while the **Octagram Spiral**, with its shorter lines, minimized
the problems (but didn't completely avoid them).


**Blog Post**: -

**Maker**: [patricknevindwyer](https://www.thingiverse.com/patricknevindwyer/about)

**Sources**: 

 - [Print Token - 0.05mm](https://www.thingiverse.com/thing:2577556)
 - [Print Token - 0.10mm](https://www.thingiverse.com/thing:2577560)
 - [Print Token - 0.20mm](https://www.thingiverse.com/thing:2577561)
 - [Print Token - 0.35mm](https://www.thingiverse.com/thing:2577568)

**Original License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Models**:

 - [print token 0.35mm.stl](https://www.thingiverse.com/download:4193859)
 - [print token 0.20mm.stl](https://www.thingiverse.com/download:4193859)
 - [print token 0.10mm.stl](https://www.thingiverse.com/download:4193858)
 - [print token 0.05mm.stl](https://www.thingiverse.com/download:4193852)

**GCode**:
 
 - 0.35 mm:
  - [Concentric](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.35mm_concentric.gcode)
  - [Hilbert Curve](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.35mm_hilbert.gcode)
  - [Archimedean Chords](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.35mm_chords.gcode)
  - [Octagram Spiral](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.35mm_spiral.gcode)
 - 0.20 mm:
  - [Concentric](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.20mm_concentric.gcode)
  - [Hilbert Curve](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.20mm_hilbert.gcode)
  - [Archimedean Chords](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.20mm_chords.gcode)
  - [Octagram Spiral](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.20mm_spiral.gcode)
 - 0.10 mm:
  - [Concentric](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.10mm_concentric.gcode)
  - [Hilbert Curve](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.10mm_hilbert.gcode)
  - [Archimedean Chords](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.10mm_chords.gcode)
  - [Octagram Spiral](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.10mm_spiral.gcode)
 - 0.05 mm:
  - [Concentric](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.05mm_concentric.gcode)
  - [Hilbert Curve](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.05mm_hilbert.gcode)
  - [Archimedean Chords](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.05mm_chords.gcode)
  - [Octagram Spiral](https://github.com/dwyerdevices/projects/blob/master/2017/10/surface%20tests/print%20token%200.05mm_spiral.gcode)

**Material**: Inland Gray ABS 1.75mm

**Print Date**: 2017/10/07 - 2017/10/09

**Print Time**: 

 - 0.35 mm:
  - Concentric: 18 minutes
  - Hilbert Curve: 15 minutes
  - Archimedean Chords: 15 minutes
  - Octagram Spiral: 15
 - 0.20 mm:
  - Concentric: 25 minutes
  - Hilbert Curve: 26 minutes
  - Archimedean Chords: 20 minutes
  - Octagram Spiral: 23 minutes
 - 0.10 mm:
  - Concentric: 35 minutes
  - Hilbert Curve: 36 minutes
  - Archimedean Chords: 36 minutes
  - Octagram Spiral: 38 minutes
 - 0.05 mm:
  - Concentric: 1 hour 25 minutes
  - Hilbert Curve: 1 hour 17 minutes
  - Archimedean Chords: 1 hours 17 minutes
  - Octagram Spiral: 1 hour 19 minutes

**Estimated Print Time**:

 - 0.35 mm: 8 minutes
 - 0.20 mm: 18 minutes
 - 0.10 mm: 31 mintues
 - 0.05 mm: n/a
 
**Estimated Filament**:

 - 0.35 mm: 1.1 meters
 - 0.20 mm: 1.1 meters
 - 0.10 mm: 1.2 meters
 - 0.05 mm: n/a

**Slicer**: Slic3r PE 1.37.1

**Slicer Settings**:

 - no supports
 - 4mm brim
 - 10% infill
 - Top/Bottom Fill Pattern:
  - concentric
  - Hilbert curve
  - Archimedean chords
  - Octagram spiral

**Printer**: Prusa i3 mk2  