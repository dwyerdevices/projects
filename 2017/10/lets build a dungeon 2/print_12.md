## OpenForge - Sewer Dungeon

We're building a dungeon. This is a project spanning lots of different prints, until
we generate all of the tiles we need for the dungeon we have in mind. The prints
are spread across:

 - Print One - [Sewer Corners](http://www.dwyerdevices.com/2017/09/24/sewer-dungeon-print-one/)
 - Print Two - [Sewer Tunnel](http://www.dwyerdevices.com/2017/09/24/sewer-dungeon-print-two/)
 - Print Three - [Corners and Ladders](http://www.dwyerdevices.com/2017/09/24/sewer-dungeon-print-three/)
 - Print Four - [Deep Pool](http://www.dwyerdevices.com/2017/09/24/sewer-dungeon-print-4/)
 - Print Five - [Deep Sluice and Deep Pool](http://www.dwyerdevices.com/2017/09/29/sewer-dungeon-print-five/)
 - Print Six - [Barred Sewer](http://www.dwyerdevices.com/2017/09/29/sewer-dungeon-print-six/)
 - Print Seven - [ABS Flooring](http://www.dwyerdevices.com/2017/09/29/sewer-dungeon-print-seven/)
 - Print Eight - [Circular Room Part 1](http://www.dwyerdevices.com/2017/10/02/sewer-dungeon-print-eight/)
 - Print Nine - [Circular Room Part 2](http://www.dwyerdevices.com/2017/10/03/sewer-dungeon-print-nine/)
 - Print Ten - [Circular Room Part 3](http://www.dwyerdevices.com/2017/10/05/sewer-dungeon-print-ten/)
 - Print Eleven - [Bridges](http://www.dwyerdevices.com/2017/10/06/sewer-dungeon-print-eleven/)
 - Print Twelve - [So Much Sluice](http://www.dwyerdevices.com/2017/10/08/sewer-dungeon-print-twelve/)
 - Print Thirteen - [Magic Portal](http://www.dwyerdevices.com/2017/10/14/sewer-dungeon-print-thirteen/)

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

https://www.instagram.com/p/BZ9Qbbeg1W2/?taken-by=dwyerdevices

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

https://www.instagram.com/p/BZ_qkrcAZ3K/?taken-by=dwyerdevices


<table>
    <tr>
        <th></th>
        <th colspan="2">Tiles</th>
        <th style="text-align: center" colspan="3">Time (hh:mm)</th>
        <th style="text-align: center" colspan="2">Filament (meters)</th>
    </tr> 
    <tr>
        <th>Print</th>
        <th>Per</th>
        <th>Total</th>
        <th>Actual</th>
        <th>Estimated</th>
        <th>Total</th>
        <th>Estimated</th>
        <th>Total</th>
    </tr>
    <tr>
        <td>sewer_sluice_curved</td><td>4</td><td>4</td><td>2:35</td><td>2:04</td><td>2:35</td><td>19</td><td>19</td>
    </tr>
    <tr>
        <td>sewer_sluice_straight</td><td>4</td><td>4</td><td>2:26</td><td>1:56</td><td>2:26</td><td>18.2</td><td>18.2</td>
    </tr>
    <tr>
        <td>sewer_deep_sluice_straight_2x2</td><td>4</td><td>8</td><td>2:20</td><td>1:54</td><td>4:40</td><td>16.5</td><td>33</td>
    </tr>
    <tr>
        <td>sewer_deep_sluice_curved_2x2</td><td>4</td><td>8</td><td>2:28</td><td>2:04</td><td>4:56</td><td>17.7</td><td>35.4</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_cross_e_2x2</td><td>4</td><td>8</td><td>1:27</td><td>1:16</td><td>2:54</td><td>10.2</td><td>20.4</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_curved_2x2</td><td>4</td><td>4</td><td>2:27</td><td>2:00</td><td>2:27</td><td>17.4</td><td>17.4</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_tee_a_2x2</td><td>4</td><td>8</td><td>1:51</td><td>1:36</td><td>3:42</td><td>13.4</td><td>26.8</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_cross_b_2x2</td><td>4</td><td>4</td><td>1:38</td><td>1:25</td><td>1:38</td><td>10.9</td><td>10.9</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_tee_b_2x2</td><td>4</td><td>4</td><td>2:01</td><td>1:40</td><td>2:01</td><td>13.7</td><td>13.7</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_tee_c_2x2</td><td>4</td><td>4</td><td>1:58</td><td>1:39</td><td>1:58</td><td>13.7</td><td>13.7</td>
    </tr>
    <tr>
        <td>sewer_pipe_wall_1x1</td><td>4</td><td>4</td><td>2:39</td><td>2:00</td><td>2:39</td><td>16.5</td><td>16.5</td>
    </tr>
    <tr>
        <td>sewer_deep_pool_curve_convex</td><td>4</td><td>4</td><td>3:07</td><td>2:16</td><td>3:07</td><td>20.5</td><td>20.5</td>
    </tr>
    <tr>
        <td>sewer_floor_1x3</td><td>4</td><td>4</td><td>2:16</td><td>1:54</td><td>2:16</td><td>17</td><td>17</td>
    </tr>
    <tr>
        <td>sewer_floor_1x2</td><td>4</td><td>4</td><td>1:25</td><td>1:15</td><td>1:25</td><td>11.1</td><td>11.1</td>
    </tr>
    <tr>
        <td>sewer_deep_sluice_tee_2x2</td><td>4</td><td>4</td><td>1:57</td><td>1:43</td><td>1:57</td><td>14</td><td>14</td>
    </tr>    
    <tr>
        <th colspan="2"></th>
        <th style="text-align: right" colspan="3">42 hours 41 minutes</th>
        <th style="text-align: center" colspan="2">288.6 meters</th>        
    </tr>
</table>

So in the course of this print we made 76 tiles with 288.6 meters of filament. Working with a spool length of [~400 meters per kilogram](https://www.toybuilderlabs.com/blogs/news/13053117-filament-volume-and-length) for ABS, and an average spool cost of around
$15, this print cost about $10.82, or around 14 cents and 33 minutues per tile. Not bad.


**Series**: OpenForge Tiles

**Blog Post**: -

**Maker**: [devonjones](https://www.thingiverse.com/devonjones)

**Model Sets**: 

 - [OpenForge Sewer - Curved Sluice](https://www.thingiverse.com/thing:928340)
 - [OpenForge Sewer - Straight Sluice](https://www.thingiverse.com/thing:922447)
 - [OpenForge Sewer - Deep Sluice](https://www.thingiverse.com/thing:988413)
 - [OpenForge Sewer - Pipe Wall](https://www.thingiverse.com/thing:984443)
 - [OpenForge Sewer - Deep Pool](https://www.thingiverse.com/thing:979839)
 - [OpenForge Sewer - Floor](https://www.thingiverse.com/thing:926862)

**Original License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Models**: 

 - [sewer_sluice_curved.stl](https://www.thingiverse.com/download:1466408)
 - [sewer_sluice_straight.stl](https://www.thingiverse.com/download:1457423)
 - [sewer_deep_sluice_straight_2x2.stl](https://www.thingiverse.com/download:1560094)
 - [sewer_deep_sluice_curved_2x2.stl](https://www.thingiverse.com/download:1560096)
 - [sewer_deep_pool_cross_e_2x2.stl](https://www.thingiverse.com/download:1547519)
 - [sewer_deep_pool_curved_2x2.stl](https://www.thingiverse.com/download:1547520)
 - [sewer_deep_pool_tee_a_2x2.stl](https://www.thingiverse.com/download:1547522)
 - [sewer_deep_pool_cross_b_2x2.stl](https://www.thingiverse.com/download:1547518)
 - [sewer_deep_pool_tee_b_2x2.stl](https://www.thingiverse.com/download:1547523)
 - [sewer_deep_pool_tee_c_2x2.stl](https://www.thingiverse.com/download:1547524)
 - [sewer_pipe_wall_1x2.stl](https://www.thingiverse.com/download:1554475)
 - [sewer_pipe.stl](https://www.thingiverse.com/download:1554474)
 - [sewer_deep_pool_curve_convex.stl](https://www.thingiverse.com/download:1547525)
 - [sewer_floor_1x3.stl](https://www.thingiverse.com/download:1464346)
 - [sewer_floor_1x2.stl](https://www.thingiverse.com/download:1464341)
 - [sewer_deep_sluice_tee_2x2.stl](https://www.thingiverse.com/download:1560093)

**GCode**:

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
 - sewer_floor_1x2_x4.gcode
 - sewer_deep_sluice_tee_2x2_x4_.gocde !! (queued up, not on SD card)

**Material**: Inland Gray ABS 1.75mm

**Print Dates**: 2017/09/30 - 2017/10/08

**Print Time**: **40 hours 44 minutes Total**
 
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
 - 1x2 sewer floor: 1 hour 25 minutes
 - deep sluice tee: 

**Estimated Print Time**: **35 hours 28 minutes Total**

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
 - 1x2 sewer floor: 1 hour 15 minutes
 - deep sluice tee: 1 hour 43 minutes

**Estimated Filament**: **288.6 meters**

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
 - 1x2 sewer floor: 11.1 meters
 - deep sluice tee: 14 meters

**Slicer**: Slic3r

**Slice Settings**:

 - 2-4mm brim
 - 0.35mm layers
 - 10% infill
 - no supports

**Printer**: Prusa i3 mk2