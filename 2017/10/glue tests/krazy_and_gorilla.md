## Glue Tests

It was finally time to pick a glue to use when assembling a few different projects over
the Halloween weekend. There was a slight problem, though. Or a few problems. Problem 1 - I had
no idea what glue to use for plastic. Problem 2 - these projects were using multiple _kinds_ of
plastic, which can be notoriously hard to fuse together.

https://www.instagram.com/p/Bazg_k5g03r/?taken-by=dwyerdevices

I've used PlasticWeld in the past, but it's a pain to use, mildly toxic, and the last bottle I 
had dried up years ago. A trip to the craft store ensued, with dire consequences: there are a lot
of different glues, and all of them make claims of bonding _anything to anything_. So I did what
any curious person with very little free time on their hands would do: set myself up to systematically
test as many different glues as I could get my hands on.

The tests are fairly straightforward:

 - Test how well each glue bonds together three different types of plastic: ABS, PLA, and PET
 - Each glue and material combination will undergo two different tests: a **load test** and a **shear test**
 
The **load test** stresses how well the glue forms a solid and strong layer between two pieces
of plastic. The **shear test** looks at how well the materials and glue stand up to being ripped
apart, like tearing off a band-aid.

https://www.instagram.com/p/BazekPlAE3K/?taken-by=dwyerdevices

The [load test and shear test tiles](https://www.thingiverse.com/thing:2622828) are each marked
to make tiles (and test results) easier to track. The tests so far only go up to 40 lbs of load or
shear force.

https://www.instagram.com/p/Batxl1kAOzM/?taken-by=dwyerdevices

This is the first batch of tests, covering **KrazyGlue - All Purpose**:

https://www.instagram.com/p/BaziVJlAIhH/?taken-by=dwyerdevices

and **Gorilla Glue - Super Glue**:

https://www.instagram.com/p/Baz1bDmAuPy/?taken-by=dwyerdevices

The best bonding for pieces experiencing load force:

<table>
    <thead>
        <tr>
            <th colspan="4">Best Bonding - Load Pieces</th>
        </tr>
        <tr>
            <th>/</th>
            <th>ABS</th>
            <th>PLA</th>
            <th>PET</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>PET</th>
            <td>Any</td>
            <td>Any</td>
            <td>Any</td>
        </tr>
        <tr>
            <th>PLA</th>
            <td style="color: #42f442">Gorilla Glue</td>
            <td>Any</td>
            <td style="background:#555555"></td>
        </tr>
        <tr>
            <th>ABS</th>
            <td style="color: #42f442">Gorilla Glue</td>
            <td style="background:#555555"></td>
            <td style="background:#555555"></td>
        </tr>
    </tbody>  
</table>

The best bonding for pieces experiencing shear force:

<table>
    <thead>
        <tr>
            <th colspan="4">Best Bonding - Load Pieces</th>
        </tr>
        <tr>
            <th>/</th>
            <th>ABS</th>
            <th>PLA</th>
            <th>PET</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>PET</th>
            <td style="color: #42f442">Gorilla Glue</td>
            <td>Any</td>
            <td>Any</td>
        </tr>
        <tr>
            <th>PLA</th>
            <td>Any</td>
            <td>Any</td>
            <td style="background:#555555"></td>
        </tr>
        <tr>
            <th>ABS</th>
            <td>Any</td>
            <td style="background:#555555"></td>
            <td style="background:#555555"></td>
        </tr>
    </tbody>  
</table>

Of note - of the six tests that failed to hold 40lbs, three of them failed due to ABS material
failure, not glue failures:

https://www.instagram.com/p/Baz15SrANPt/?taken-by=dwyerdevices

The raw test data is available on GitHub: [Glue Test Results](https://github.com/dwyerdevices/projects/blob/master/2017/10/glue%20tests/glue.csv).

  
**Blog Post**: -

**Maker**: [patricknevindwyer](https://www.thingiverse.com/patricknevindwyer)

**Source**: [Tiles for Glue Tests](https://www.thingiverse.com/thing:2622828)

**Model License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Data License**: [Creative Commons - Attribution - Share Alike](http://creativecommons.org/licenses/by-sa/3.0/)

**Material**:

 - Prusa Black PETG 1.75mm
 - Inland Silver PLA 1.75mm
 - Orange Inland ABS 1.75mm

**Print Date**: 2017/10/26

**Print Time**: (9 tiles per batch)

 - Load Tiles ABS: 2 hours
 - Load Tiles PLA: 2 hours 3 minutes
 - Load Tiles PET: 1 hour 59 minutes
 - Shear Tiles ABS: 1 hour 48 minutes
 - Shear Tiles PLA: 1 hour 42 minutes
 - Shear Tiles PET: 1 hour 44 minutes
 
**Estimated Print Time**:

 - Load Tiles ABS: 1 hour 25 minutes
 - Load Tiles PLA: 1 hour 52 minutes
 - Load Tiles PET: 1 hour 29 minutes
 - Shear Tiles ABS: 1 hour 25 minutes
 - Shear Tiles PLA: 1 hour 40 minutes
 - Shear Tiles PET: 1 hour 25 minutes

**Estimated Filament**:

 - Load Tiles ABS: 11.7 meters
 - Load Tiles PLA: 11 meters
 - Load Tiles PET: 11.5 meters
 - Shear Tiles ABS: 12.8 meters
 - Shear Tiles PLA: 11.9 meters
 - Shear Tiles PET: 12.8 meters
 
**Slicer**: Slic3r

**Slicer Settings**:

 - Load Tiles
  - 0.35mm layers
  - 10mm brim
  - 20% infill
  - Supports everywhere
 - Shear Tiles
  - 0.35mm layers
  - 10mm brim
  - 20% infill
  - No supports

**Printer**: Prusa i3 mk2  