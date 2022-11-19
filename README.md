# ffcp-klipper-mod
Hi! I'm getting used to Github so go easy on me : )

This is for my configuration file for running Klipper on the FlashForge Creator Pro.
My goal for this project is to revitalize a huge amount of open source 3D printer
designs. I believe anything that runs a main control board based off the open source
"MightyBoard" design would be a good candidate.

My files are configured for running one extruder, despite my Creator Pro having 2. I
am planning on swapping the hotend for an e3d V6 clone. This is for flow, weight
savings, increased speed, ease of maintenance, and availability of replacement parts.
If you'd like to run the stock dual extruders, you can add another extruder in the 
config and add nozzle offsets in Cura, but most of the other settings should be the
same.

Here's a list of designs that may benefit from my work:

- FlashForge Creator Pro        Confirmed
- FlashForge Creator Pro Max
- FlashForge Creator
- FlashForge Creator X
- MakerBot Replicator 1 Dual
- MakerBot Replicator 2
- MakerBot Replicator 2X        Confirmed
- CTC Bizer
- Monoprice Maker Architect
- PowerSpec 3D Pro
- Qidi Tech One                 Confirmed
- Wanhao Duplicator 4S          Confirmed

A good amount of these designs have a really solid, stiff enclosure, and were 
built with pretty good quality parts from the factory, and are still in use. In 
fact, some are still being sold today!

Here's my machine configuration so you know what to expect when using my config file.
X (Width): 266mm
Y (Depth): 153mm
Z (Height): 179mm
Bed: Borosilicate (I believe slightly larger than the original)
Nozzle: 0.4mm
Control Board: SKR Mini E3 v3
Extruders: 1 (left one, closer to the part cooling fan)
Hotend Temp Probe: Thermistor (not the stock thermocouple) !!!!!

As with any random files you download on the internet, read through the .cfg
file before you do anything to make sure it fits the needs of your machine. You
may have to re-scale the X and Y coordinates if you have a smaller bed.

To rescale the bed coordinates I manually jog the print head to find the 
furthest printable area still on the bed, and I consider that 0. Then I jog the print
head until it's as far as it will go off the bed, and make that number a negative one.
This ensures that the front left corner of the bed is 0,0.

For additional information, visit my website and check out the article I wrote on
converting my FFCP to run Klipper.

https://msptrick.blogspot.com/2022/11/flashforge-creator-pro-control-board.html
