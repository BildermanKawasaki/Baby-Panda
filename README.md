# 🐼 Baby-Panda
## Introduction
Baby Panda is a core-XY printer with moving conveyor build plate to enable continuous printing. It borrows a lot of it's motion system from the Voron 2.4, and was designed to repurpose as many parts as possible from a pair of Ender 3 Pro/V2 printers. 

## Building Baby Panda
There are currently no build instructions for Baby Panda. The best way to get started is to check out available documentation:
* [BOM](https://github.com/robwaldhauser/Baby-Panda/blob/main/BOM%20Spreadsheet.ods) - Baby Panda bill of materials (.ods format)
* [STLs](https://github.com/robwaldhauser/Baby-Panda/tree/main/STLs) - model files for each part
* [CAD](https://github.com/robwaldhauser/Baby-Panda/tree/main/CAD) - An archive containing a .step file with a fully assembled Baby Panda

If you have any questions, head over to the [Build Biome Discord server](https://discord.gg/SpCVg9wG) and ask them in the #🐼baby-panda channel. 

### The Frame
The standard Baby Panda frame can be built entirely from extrusions salvaged from 2 Ender 3 Pros or Ender 3 V2s (one of each should work ok too).

!(Standard Baby Panda Frame)[images/standard_frame.png "standard frame"]

In the standard configuration, the 3 4040 extrusions from the base of one Ender form the base of the Baby Panda frame, and the base extrusions of the other Ender  form the top. The uprights from each ender, which will need to be drilled out for blind joints using the [jig](https://github.com/robwaldhauser/Baby-Panda/blob/main/STLs/Drilling%20Jig.stl) available in the CAD section, connect the top of the frame to the bottom in each corner.

If desired, for additional rigidity and/or to facilitate enclosure of the printer, 2 additional 2020 extrusions can be purchased and installed in either of the following configurations:

![standard frame with extra 2020s](images/standard_frame_plus_2_2020s.png)
*standard frame with extra 2020s*

![standard frame with 2020s replacing top 4040](images/standard_frame_plus_2_2020s_less_top_4040_crossbar.png)
*standard frame with 2020s replacing top 4040*