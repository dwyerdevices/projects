
# Current

! create a font test for stencil post

! start list in repo of print ideas


## Update GCODE links in all posts

We had a major fuck-up with all the LFS files and cleaning the repo history, and long story short,
all of the repo links are broken, and now need to point to https://github.com/dwyerdevices/projects

Wait - we have gcode on the SDCard!


## OpenForge - Sewers

Thing: 

 - [OpenForge Sewers](https://www.thingiverse.com/thing:922445)

 
Models: 

 - [All](https://www.thingiverse.com/thing:922445/zip)
 
Maker: https://www.thingiverse.com/devonjones


Updated Slic3r and PrusaControl after print #3

**Series**: OpenForge tiles

**All**:
0.35mm Fast Print
10% infill cubic
no supports
Prusa Gray PLA 1.75mm / Inland Gray ABS 1.75mm


### Print Twelve - So Much Sluice

With rough drawings of the dungeon on paper, it's time to start printing up
various pieces in large quantities. This print is batches of sluice curves,
straight pieces, deep pools, and other tiles I've already trialed and started
to arrange into our dungeon. 

https://www.instagram.com/p/BZucq7FAF6G/?taken-by=dwyerdevices

For each batch, I'm printing 4 copies of a model per print. I've found that I
can fit up to 12 2x2 dungeon tiles onto the print bed, but that has a high print
failure rate, with filament near the edge of the bed having poor adhesion. I could
probably push this up to 6 copies per print without negatively affecting the
print error rate, but 4 copies per print puts each batch at right around 2-3 hours
per print, which makes it easier to fit multiple prints into the day.

https://www.instagram.com/p/BZuc4SlgHB5/?taken-by=dwyerdevices

I've laid out the entire dungeon on paper in roughly the configuration I want, and
have partially built out tiles for selected areas to gauge which pieces I need
more of. 

https://www.instagram.com/p/BZzL9q-Anrc/?taken-by=dwyerdevices

Most of the low profile tiles are quick to print, but the details pieces, like the
bridges, and the taller pieces, like walls, take a long time to print. I think I've
decided that I won't be walling in the entire dungeon. Strategic places will get
walled in as needed during play, like when line of sight and cover become an
issue. Otherwise, the printing of walls and corner fill alone could take weeks.


By printing out 4-8 of most of the tile variants I'm using, I'll very likely end
up with extra tiles not used in the final layout, which is fine. It'll take slightly
longer over all to print, but makes managing all of the printing much, much easier.


When I sliced the convex curve tiles, I tried out a different fill pattern for the
top and bottom layers, namely - the Hilbert Curve fill pattern. The default fill, which
uses diagonal lines, creates a fairly smooth and regular surface. At the layer quality
these tiles were printed at, the Hilbert Curve fill creates a noisy and somewhat incomplete
surface. Small gaps between the space filling curve are evident.

While slicing the 1x3 floor tiles, I tried out the Octogram Spiral fill pattern
for the top and bottom layers. The pattern isn't visible on the top of the tiles, 
but is definitely visible on the bottom. At this print resolution, the octagram spiral
pattern may have better coverage, with fewer gaps, on the bottom of tiles.

**Things**: 

 - [OpenForge Sewer - Curved Sluice](https://www.thingiverse.com/thing:928340)
 - [OpenForge Sewer - Straight Sluice](https://www.thingiverse.com/thing:922447)
 - [OpenForge Sewer - Deep Sluice](https://www.thingiverse.com/thing:988413)
 
**Models**: 

 - [sewer_sluice_curved.stl](https://www.thingiverse.com/download:1466408)
 - [sewer_sluice_straight.stl](https://www.thingiverse.com/download:1457423)
 - [sewer_deep_sluice_straight_2x2.stl](https://www.thingiverse.com/download:1560094)
 - [sewer_deep_sluice_curved_2x2.stl](https://www.thingiverse.com/download:1560096)
 - [sewer_deep_pool_cross_e_2x2.stl]
 - [sewer_deep_pool_curved_2x2.stl]
 - [sewer_deep_pool_tee_a_2x2.stl]
 - [sewer_deep_pool_cross_b_2x2.stl]
 - [sewer_deep_pool_tee_b_2x2.stl]
 - [sewer_deep_pool_tee_c_2x2.stl]
 - [sewer_pipe_wall_1x2.stl]
 - [sewer_pipe.stl]
 - [sewer_deep_pool_curve_convex.stl]
 - [sewer_floor_1x3.stl]
 
 - Sewer Stone 2x2 x6
 

GCodes: 
 - sewer_sluice_curved_x4.gcode
 - sewer_sluice_straight_x4.gcode
 - sewer_deep_sluice_straight_2x2_x4.gcode **x2**
 - sewer_deep_sluice_curved_2x2_x4.gcode **x2**
 - sewer_deep_pool_cross_e_2x2_x4.gcode **x2**
 - sewer_deep_pool_curved_2x2_x4.gcode
 - sewer_deep_pool_tee_a_2x2_x4.gcode **x2**
 - sewer_deep_pool_cross_b_2x2_x4.gcode
 - sewer_deep_pool_tee_b_2x2_x4.gcode
 - sewer_deep_pool_tee_c_2x2_x4.gcode
 - sewer_pipe_wall_1x1_x4.gcode
 - sewer_deep_pool_curve_convex_x4.gcode
 - sewer_floor_1x3_x4.gcode
 
Print Date: 2017/09/30 - 2017/10/05

Print Time: 
 
 - curved: 2 hours 35 minutes
 - straight: 2 hours 26 minutes
 - deep sluice straight: 2 hours 20 minutes
 - deep sluice curved: 2 hours 28 minutes
 - deep pool: 1 hour 27 minutes
 - deep pool curved: 2 hours 27 minutes
 - deep pool tee a: 1 hours 51 minutes
 - deep pool cross b: 1 hour 38 minutes
 - deep pool tee b: 2 hours 1 minute
 - deep pool tee c: 1 hour 58 minutes
 - sewer pipe wall 1x2 (with pipes): 2 hours 39 minutes
 - sewer deep pool convex curve: 3 hours 7 minutes
 - 1x3 sewer floor: 2 hours 16 minutes
 
Est Print Time: 

 - curved: 2 hours 4 minutes
 - straight: 1 hour 56 minutes
 - deep sluice straight: 1 hour 54 minutes
 - deep sluice curved: 2 hours 4 minutes
 - deep pool: 1 hour 16 minutes
 - deep pool curved: 2 hours
 - deep pool tee a: 1 hour 36 minutes
 - deep pool cross b: 1 hour 25 minutes
 - deep pool tee b: 1 hour 40 minutes
 - deep pool tee c: 1 hour 39 minutes
 - sewer pipe wall 1x2 (with pipes): 2 hours
 - sewer deep pool convex curve: 2 hours 16 minutes
 - 1x3 sewer floor: 1 hour 54 minutes
  
Est Filament: 

 - curved: 19 meters
 - straight: 18.2 meters
 - deep sluice straight: 16.5 meters
 - deep sluice curved: 17.7 meters
 - deep pool: 10.2 meters
 - deep pool curved: 17.4 meters
 - deep pool tee a: 13.4 meters
 - deep pool cross b: 10.9 meters
 - deep pool tee b: 13.7 meters
 - deep pool tee c: 13.7 meters
 - sewer pipe wall 1x2 (with pipes): 16.5 meters
 - sewer deep pool convex curve: 20.5 meters
 - 1x3 sewer floor: 17 meters
 
Brim Size: 2mm
Material: Inland Gray ABS 1.75mm
Slicer: Slic3r

0.35mm layers
10% infill
no supports

### Print Thirteen - Magical Portal

This dungeon has a larger purpose; a magical portal at the end of the dungeon hints
at a bigger dungeon complex, and story, yet to unfold. This model is an excellent
self contained magic circle that will fit into the existing dungeon layout without
much trouble.

I'm trying a few new print settings for this print. First off, I'm using the 3D honey
comb fill, which should create a stronger infill with less material than other infill
patterns. In an effort to reduce print time even further, I'm testing out Slic3r's feature
for doing thicker infill layers. In this mode the perimeter layers are printed at the
configured layer size (in this case 0.35mm), but the infill layers are printed thicker,
and only laid down every 3 layers.

https://www.instagram.com/p/BZ134dWgjut/?taken-by=dwyerdevices

The combined infill parameters had me a bit wary after the print first started. With a
basic layer quality of 0.35mm, and combined fill every 3 layers, the infill height would
seem to be 1.05mm, which is more than double the extruder size. I've kept a close eye
on the print, and so far everything seems to be working, but the honeycomb infill does
have visible vertical gaps between each layer.

This is also the first print where I've needed to swap in a new filament spool mid
print.

**Source**: [OpenForge Magic Circle Tiles](https://www.thingiverse.com/thing:242715)
**Maker**: [devonjones](https://www.thingiverse.com/devonjones)
**Model**: [walled_magic_circle_1.stl](https://www.thingiverse.com/download:445910)
**Material**: Inland Gray ABS
**Print Date**: 2017/10/04
**Print Time**: 4 hours 1 minute
**Estimated Print Time**: 3 hours 57 minutes
**Estimated Filament**: 41.7 meters

0.35mm layers
10% infill 3d honeycomb
no supports
4mm brim
combine infill every 3 layers


### Print ? - Alls the Walls

Batch printing walls.

Interesting to note: when generating the estimates for print time and filament, PrusaControl wouldn't load
the full STL or generated GCODE I built in Slic3r - it just locked up the entire computer, nearly causing
a full hard boot. For the estimates, I used the base wall tile, and scaled up by a factor of 12.

**Model**: sewer_wall_2x2.stl x12
**Print Date**: ?
**Print Time**: ?
**Estimated Print Time**: 10 hours 48 mintues
**Estimated Filament**: 85.2 meters

Inland Gray ABS 1.75mm
0.35mm layers
10% infill 3d honeycomb
no supports
4mm brim
hilbert curve top/bottom fill

## Bestiary - Goblins

https://www.youmagine.com/designs/goblins

## Ada Lovelace Token

**Model**: -
**Print Date**: 2017/10/06
**Material**: Inland Gray ABS 1.75mm
**Print Time**:
**Estimated Print Time**: 7 minutes
**Estimated Filament**: 27.6 cm
**Slicer**: PrusaControl

0.1mm layers
10% infill
no supports
include brim


# Next Up


**settlers interlocking tiles/board**


**Ruler v2:**
- through hole ticks
- no bump outs
 - more gap measures
- numeric through holes
- lengthen to 15cm
- dotted/dashed line through holes

**Curves and Angles ruler**

**Printing small features bit:**
- layers as multiples of min feature size
- dynamic layer sizing
- text and curves and segments

**software engineering stencile**

**network design stencil**

**cloud computing stencil**

**stellated polyhedra**
 
**jewelry**

**letter form test**

**better spool holder**

 a one-size-fits-all holder with insertable rod?
 
**Clip Case for CCG**

Slide over case with two inserts that act as cotter pins

**Odometer style counter for measuring total printed filament**
