
# Current

! create a font test for stencil post

! start list in repo of print ideas


## Update GCODE links in all posts

We had a major fuck-up with all the LFS files and cleaning the repo history, and long story short,
all of the repo links are broken, and now need to point to https://github.com/dwyerdevices/projects

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
Prusa Gray PLA 1.75mm

### Print One - Corner

Partially a test print of the sewer tiles. A bend in the sewer tunnel, or a covex
corner in a larger sewer sluice pool. Very clean print, again. These tiles are quick,
easy, and very very sturdy. Some issues with adhesion on the first few layers of the
larger 2x2 tiles which is causing the corners to pull away from the print bed, but the
upper surfaces of the print are unaffected.

https://www.instagram.com/p/BZW5BdhgFaH/?taken-by=dwyerdevices

Models: 

 - sewer_corner_convex.stl
 - sewer_wall_1x1.stl x2
 - sewer_sluice_curved.stl
 - sewer_sluice_straight.stl x2

GCode: sewer_corner_01.gcode
Print Date: 2017/09/20
Print Time: 3 hours 25 minutes
Est Print Time: 3 hours 3 minutes (PrusaControl)
Est Filament: - (PrusaControl)

### Print Two - Sewer Tunnel

This print has failed twice already due to loose bed adhesion. It's covering nearly
the entire printable surface, but the pieces are disconnected, so any irregularities
or unevenness in the print bed are hard to correct for.

https://www.instagram.com/p/BZW5N9NgCGn/?taken-by=dwyerdevices

Models:

 - sewer_wall_2x1.stl x6
 - sewer_sluice_straight.stl x2
 - sewer_sluice_end.stl
 - sewer_corner_concave.stl x1
 - sewer_pipe_wall-1x2.stl
 - sewer_pipe.stl

GCode: sewer_tunnel_01.gcode
Print Date: 2017/09/22
Print Time: 8 hours 53 minutes
Est Print Time: 8 hours 16 minutes (PrusaControl)
Est Filament: 64.5 meters (PrusaControl)

### Print Three - Corners and Ladders

I missed a corner in Print Two, and haven't yet done any detail pieces other than the
wall with a pipe, so now is the chance. The 1x1 tiles have terrific adhesion to the
print bed; so much so that this print (or, rather, extracting this print from the
printer) resulted in breaking a print trying to remove it from the print bed (first time
for me, but certainly not the last).

https://www.instagram.com/p/BZYiaf2gjSI/?taken-by=dwyerdevices

Models:

 - sewer_ladder_1x1.stl x3
 - sewer_corner_convex.stl x3
 - sewer_corner_concave.stl x3

GCode: sewer_singles_01.gcode
Print Date: 2017/09/22
Print Time: 4 hours 41 minutes
Est Print Time: 4 hours 5 minutes (PrusaControl)
Est Filament: 29.2 meters (PrusaControl)

### Print Four - Deep Pool

These turned out really well, and really quickly. Because, of course I did, I neglected
to print the center tile for the deep pool. I'll need to add that to a later batch, likely of more
deep pool tiles to make a larger area. The edges of the pool, and the upper face of the curved
corners, are built to mesh well with basic floor pieces, which I haven't printed
many of yet - soon to come.



For this set of tiles I added a 2mm brim to see if it made any difference
in the adhesion of the tiles, and to see if it possibly solved the problem
of "peeled away" corners I've seen on other tiles. Worked perfectly, and added
only a few minutes of cleanup post-print. The brims peel away cleanly and quickly
once a corner of the brim has been pulled away from the printed model.

Models:

 - sewer_deep_pool_curved_2x2.stl x4
 - sewer_deep_pool_cross_b_2x2 x1
 - sewer_deep_pool_tee_a_2x2.stl x3
 
GCode: sewer_deep_pool_01.gcode
Print Date: 2017/09/23
Print Time: ?
Est Print Time: 3 hours 45 minutes (PrusaControl)
Est Filament: 27.2 meters (PrusaControl)
Brim size: 2mm
 
 
### Print Five - Deep Sluice and Deep Pool

**Model Set**: 
 
 - [Sewer Deep Sluice](https://www.thingiverse.com/thing:988413)
 - [Open Forge Sewer Deep Pool](https://www.thingiverse.com/thing:979839)
 
**Models**:

 - sewer_deep_sluice_straight_2x2.stl x3
 - sewer_deep_sluice_tee_2x2.stl x1
 - sewer_deep_sluice_curved_2x2.stl x2
 - sewer_deep_sluice_deadend_2x2.stl x2
 - sewer_deep_pool_cross_e_2x2.stl x1

GCode: sewer_deep_sluice_01.gcode
Print Date: 2017/09/23
Print Time: 6 hours 37 minutes
Est Print Time: 6 hours 37 minutes (PrusaControl 0.9.3_390_beta)
Est Filament: 45.7 meters (PrusaControl 0.9.3_390_beta)
Brim Size: 2mm

### Print Six - Barred Sewer

Whooops. Printed the bars_top-3x.stl first, which is too short to span a 2x wide sluice tile. Need to
use the 4x instead.

**Model Set**: [OpenForge Barred Sewer](https://www.thingiverse.com/thing:947965)

**Models**:

 - sewer_wall_2x1_a.stl
 - sewer_wall_2x1_b.stl
 - sewer_sluice_straight_barred.stl
 - bars_top-4x.stl

GCode: sewer_barred_01.gcode
Print Date: 2017/09/24
Print Time: ?
Est Print Time: 2 hours 38 minutes (PrusaControl 0.9.3_390_beta)
Est Filament: 19 meters (PrusaControl 0.9.3_390_beta)
Brim Size: 2mm



## Bestiary - Red Dragon

Resized and rotated in TinkerCad, converted to STL. Scaled down to 56mm.

Thing: [ice dragon (repaired)](https://www.thingiverse.com/thing:620234/#files)
Model: https://www.thingiverse.com/download:997950
Print Date: 2017/09/24
Print Time: ?
Est Print Time: 3 hours 33 minutes (PrusaControl 0.9.3_390_beta)
Est Filament: 9.2 meters (PrusaControl 0.9.3_390_beta)
Slicer: PrusaControl 0.9.3_390_beta
Filament: Hatchbox Red 1.75mm PLA

0.35mm layers
20% infill
Supports Everywhere
Print Brim


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
