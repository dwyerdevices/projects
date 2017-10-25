
## Undermountain Dungeon - Print 2

We're building another dungeon, this time the Undermountain. The Undermountain is a series of
tunnels and rooms that once belonged to a dwarven stronghold, but have been taken over by an
ancient wyrm and its devout goblin worshipers. This is a project spanning lots of different prints, until
we generate all of the tiles we need for the dungeon we have in mind. The prints
are spread across:

 - Print One - [Enter the Undermountain](http://www.dwyerdevices.com/2017/10/19/undermountain-dungeon-print-1/)
 - Print Two - [The Sundered Spire](http://www.dwyerdevices.com/2017/10/24/undermountain-dungeon-print-2/)


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


**Series**: OpenForge Tiles

**Blog Post**: [The Sundered Spire](http://www.dwyerdevices.com/2017/10/24/undermountain-dungeon-print-2/)

**Maker**: [patricknevindwyer](https://www.thingiverse.com/patricknevindwyer)

**Source**: [The Sundered Spire](https://www.thingiverse.com/thing:2594414)

**Models**:

 - [Sundered_Spire_base.stl](https://www.thingiverse.com/download:4226519)
 - [Sundered_Spire_fallen.stl](https://www.thingiverse.com/download:4226521)

**Original Sources**:

 - [OpenForge smooth tile floor](https://www.thingiverse.com/thing:234325)
 - [Slottsmollan Obelisk](https://www.thingiverse.com/thing:1490817)

**Original Source License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Original Maker**: [devonjones](https://www.thingiverse.com/devonjones)

**GCode**: -

**Material**: Inland Gray ABS 1.75mm

**Print Date**: 2017/10/16

**Print Time**

 - base: 35 minutes
 - fallen: 58 minutes
 
**Estimated Print Time**

 - base: 33 minutes
 - fallen: 55 minutes

**Estimated Filament**:

 - base: 5.6 meters
 - fallen: 9.2 meters

**Slicer**: Prusa Control

**Slicer Settings**:

 - 0.35mm layers
 - include brim
 - Sparse - 10% infill

**Printer**: Prusa i3 mk2