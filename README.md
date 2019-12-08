This is a design of a 4/5th axis attachment for a CNC woodworking machine.

The design is made in FreeCAD and does not contain most of the detail yet.

It is intended for drilling holes through 10x10cm and smaller softwood timber. Holes can have many different orientations, though the angle with the surface will at least be 45°.

As holes need to be drilled 'through' the wood they can always be drilled from the top or sides, and the router will at maximum need to be horizontal.

### Components are:

* 20mm thick aluminum plates (EN AW-6060 T66)
* cross roller bearings as joints (Hiwin CRBE03515A) 
* a 90x90cm aluminum extrusion connects to the machine (link 1)
* custom GT5 timing pulleys (125 teeth, radius 99.5mm) attach to links 2 and 3
* nema 34 steppers drive the axis (15 teeth pulley, radius 12mm)

Belts are tensioned by adjusting the position of the motors.

### Forces are: 

Leadshine's Nema 34 stepper model 86CM45 has a holding torque of 4.5Nm 
Check out the calculation of the force and accuracy at the tool tip in the [calculation spreadsheet](error-calculation-timing-belt.ods).

I'm still at the initial phase.

### References:

* [Bearing specs](https://www.hiwin.hu/en/Produktfinder_Detail_2/Bearings/Crossed_roller_bearings/CRBE/20591)
* [Timing belt specs](https://www.electric-skateboard.builders/t/why-dont-people-use-gt3-pulleys-and-belts/71058)
