
# Current

! create a font test for stencil post

! start list in repo of print ideas


## Update GCODE links in all posts

We had a major fuck-up with all the LFS files and cleaning the repo history, and long story short,
all of the repo links are broken, and now need to point to https://github.com/dwyerdevices/projects

Wait - we have gcode on the SDCard!



## Another Vase

https://www.instagram.com/p/BaXeJgLAVWp/?taken-by=dwyerdevices


**Maker**: [eggnot](https://www.thingiverse.com/eggnot)

**Source**: [Curved Honeycomb Vase](https://www.thingiverse.com/thing:2376777)

**Original License**: [Creative Commons - Attribution](http://creativecommons.org/licenses/by/3.0/)

**Model**: [sotvl1.stl](https://www.thingiverse.com/download:3798609)

**GCode**: -
**Material**: Inland Turquoise PLA 1.75mm
**Print Date**: 2017/10/17
**Print Time**: 6 hours 48 minutes
**Estimated Print Time**: 4 hours 30 minutes
**Estimated Filament**: 16 meters
**Slicer**: Slic3r
**Slicer Settings**:

 - 75% scale
 - 5 perimeters
 - no top horizontal solid layers
 - 10 bottom horizontal solid layers
 - 0% infill
 - 10mm brim
 - 0.20mm layers


## Bracelet

**Source**: [Double Voronoi Bracelet](https://www.thingiverse.com/thing:1403094)
**License**: [Creative Commons - Attribution - Non-commercial - No Derivatives](http://creativecommons.org/licenses/by-nc-nd/3.0/)
**Maker**: [Protonik](https://www.thingiverse.com/Protonik)
**Model**: [dv3_protonik.stl](https://www.thingiverse.com/download:2179260)
**Material**: Inland Turquoise PLA 1.75mm
**Print Date**: 2017/10/18
**Print Time**: 
**Estimated Print Time**: 7 hours 29 minutes
**Estimated Filament**: 16.1 meters
**Slicer**: Slic3r
**Slicer Settings**:
 
 - 0.20mm layers
 - 10mm brim
 - supports on build plate only
 - 30% infill - cubic

## Undermountain Dungeon


### Print 2 - The Sundered Spire

The magic portal from the sewer dungeon leads to a similar looking portal in the Undermountain, the
lair of an ancient dragon, shut away beneath a dwarven stronghold. The altar at the center of the portal
room has four paths, each leading to a magic portal to another location. One of these paths has collapsed,
leaving a blocked passageway. At the entrance to each passage is a magical obelisk, this obelisk holds the
power and enchantments that activate each of the portals. The obelisk in front of the collapsed passageway
tells a tale of a great confrontation - the obelisk is sundered into two pieces, the magic dissapated, and,
we assume, the portal permanently deactivated.

https://www.instagram.com/p/BaUzKGaA6IN/?taken-by=dwyerdevices

I used the [Slottsmollan Obelisk](https://www.thingiverse.com/thing:1490817) from [devonjones](https://www.thingiverse.com/devonjones)
for the basic magic obelisks. For the Sundered Spire I broke the original model into pieces, and mounted them
on smooth stone tiles.

I used TinkerCad To break apart the obelisk, and add the rough texture of shattered stone. The rough texture
comes from the Terrain Community Shape Generator. Both the obelisk and the generated terrain I used are fairly
complex surfaces. Because of this, joining solid and negative space objects in TinkerCad took 10-15 seconds
before the composite models looked correct.

When I opened up the _base_ model in Slic3r, it couldn't properly render the preview of the model; two of the
faces were missing, showing through to the hollow center of the model. After comparing the size of generated
GCODE files with similar settings between Slic3r and PrusaControl, I guessed that Slic3r was also improperly
slicing the model. I'll gowith PrusaControl for slicing these. 

Huh. Sliced in either PrusaControl or Slic3r, the entire middle of the model is missing from GCODE. The printer
finishes the first centimeter of the print, then jumps up 5 centimeters vertically and tries to continue. Let's
see if we can fix things in [MeshMixer](http://meshmixer.com). Opening the STL file in MeshMixer, and selecting
**Edit** - **Make Solid** and then exporting seems to have done the trick.



**Original Sources**:

 - [OpenForge smooth tile floor](https://www.thingiverse.com/thing:234325)
 - [Slottsmollan Obelisk](https://www.thingiverse.com/thing:1490817)

**Original Source License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Original Maker**: [devonjones](https://www.thingiverse.com/devonjones)

**Models**:

 - [Sundered_Spire_base.stl](https://github.com/dwyerdevices/projects/blob/master/2017/10/sundered%20spire/Sundered_Spire_base.stl)
 - [Sundered_Spire_fallen.stl](https://github.com/dwyerdevices/projects/blob/master/2017/10/sundered%20spire/Sundered_Spire_fallen.stl)

**Print Time**

 - base: 35 minutes
 - fallen: 58 minutes

**Estimated Print Time**

 - base: 33 minutes
 - fallen: 55 minutes

**Estimated Filament**:

 - base: 5.6 meters
 - fallen: 9.2 meters

**Source**:

**Slicer**: Prusa Control

**Slicer Settings**:

 - 0.35mm layers
 - include brim
 - Sparse - 10% infill



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


## Totem and Ida

A totem and Ida from Monument Valley.

Totem Blocks: https://www.instagram.com/p/BaNIXsZgOfI/?taken-by=dwyerdevices

Totem Pieces pre-cleanup: https://www.instagram.com/p/BaPRlrJg7cy/?taken-by=dwyerdevices

Cleaned up Totem pieces:https://www.instagram.com/p/BaPn6Y4AnA3/?taken-by=dwyerdevices

I've combined models that are the same color into single prints

**Source**: [Totem a Friend Monument Valley plus Ida](https://www.thingiverse.com/thing:2050376)
**License**: [Creative Commons - Attribution](http://creativecommons.org/licenses/by/3.0/)
**Models**: [All Models](https://www.thingiverse.com/thing:2050376/zip)
**Maker**: [AliG3D](https://www.thingiverse.com/AliG3D)
**Print Date**: 2017/10/13
**Scaling**: 50% Original
**Materials**:

 - Hatchbox Yellow PLA 1.75mm
 - Inland Turguoise PLA 1.75mm
 
**Print Time**:

 - yellows: 7 hours 58 minutes
 - blues: 45 minutes
 - black:
 - orange:
 - white: 11 minutes
 
**Estimated Print Time**:

 - yellows: 7 hours 51 minutes
 - blues: 42 minutes
 - black: 5 minutes
 - orange: 3 minutes
 - white: 11 minutes
 
**Estimated Filament**:

 - yellows: 36.1 meters
 - blues: 2.2 meters
 - black: 26.8 centimeters
 - orange: 17.6 centimeters
 - white: 56.8 centimeters

**Slicer**: Slic3r
**Slicer Settings**:

 - 50% scale
 - 0.20mm layers
 - 20% infill cubic
 - Surface fill - Hilbert Curve
 - 10mm brim
 

# Next Up


**Glowing Obelisk**

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



**generic tudor house plan tiles**

**better spool holder**

 a one-size-fits-all holder with insertable rod?
 
**Clip Case for CCG**

Slide over case with two inserts that act as cotter pins

**Odometer style counter for measuring total printed filament**
