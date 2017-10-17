
# Current

! create a font test for stencil post

! start list in repo of print ideas


## Update GCODE links in all posts

We had a major fuck-up with all the LFS files and cleaning the repo history, and long story short,
all of the repo links are broken, and now need to point to https://github.com/dwyerdevices/projects

Wait - we have gcode on the SDCard!


## OpenForge - Sewers


Sewer Dungeon during play:

https://www.instagram.com/p/BaR_lN0AI3k/?taken-by=dwyerdevices


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




## Undermountain Dungeon

### Print 1 - Undermountain Portal Gate

Where does the magical portal go? To a small cavern, with four portals surrounding an
altar chisled from stone. Welcome to the Undermountain.

Portal:

https://www.instagram.com/p/BaT_TdfAYWT/?taken-by=dwyerdevices

Altar:

https://www.instagram.com/p/BaMBYzLA3Zg/?taken-by=dwyerdevices

**Sources**: 

 - [Slottsmollan Obelisk](https://www.thingiverse.com/thing:1490817)
 
**License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)
**Maker**:
**Models**: 

 - slottsmollan_obelisk_2x2.stl x2
 - shrine_base_plinth.stl
 
**Material**: Inland Gray ABS 1.75mm
**Print Date**: 2017/10/10
**Print Time**: 

 - slottsmollan_obelisk_2x2.stl: 1 hour 14 minutes
 - shrine_base_plinth.stl: 1 hour 7 minutes
 - shrine_roof.stl: 46 minutes
 
**Estimated Print Time**: 

 - slottsmollan_obelisk_2x2.stl: 53 minutes
 - shrine_base_plinth.stl: 48 minutes
 - shrine_roof.stl: 23 minutes
 
**Estimated Filament**: 

 - slottsmollan_obelisk_2x2.stl: 9.2 meters
 - shrine_base_plinth.stl: 5.7 meters
 - shrine_roof.stl: 4.2 meters

0.35mm layers
10% infill cubic
no supports
10mm brim


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

### Lego Angles

Lego plates built into angles for forming regular polygons.

5-sided polygon (Pentagon): 108° inner angle.

https://www.instagram.com/p/BaH-atDnDuL/?taken-by=dwyerdevices
https://www.instagram.com/p/BaH-atDnDuL/?taken-by=dwyerdevices


 - hexagon

The first batch of pentagon angles didn't fit terribly well with standard legos. Too loose when
connected to the base of a Lego, too tight and unable to snap in when placed on top of a standard
Lego. It's possible the nub holes and through-hole on the plate were an issue, so I printed a few
test pieces of different heights and features to see what worked best.

Follow up with radial groups (3 way, 4 way, 5 way, etc)

**Sources**

 - [Customizable LEGO-Compatible Brick](https://www.thingiverse.com/thing:615256)
 - [Customized Lego Compatible 2x2 Plate](https://www.thingiverse.com/thing:2579304)

**Original License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Models**:

 - [lego_pentagon_108_angle.stl]()
 
**Material**: Inland Gray ABS 1.75mm

**Print Date**: 2017/10/11 - 

**Print Quantity**:

 - 108°: 5

**Print Time**:

 - 108°: 2 hours 15 minutes

**Estimated Print Time**:

 - 108°: 1 hour 55 minutes
 
**Estimated Filament**: -

 - 108°: 3.73 meters

**Slicer Settings**:

 - 0.10mm layers
 - 30% infill cubic
 - 5mm brim

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
