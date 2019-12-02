This is a design of a 4/5th axis attachment for a CNC woodworking machine.

The design is made in FreeCAD and does not contain most of the detail yet.

It is intended for drilling holes through 10x10cm and smaller softwood timber. Holes can have many different orientations, though the angle with the surface will at least be 45°.

As holes need to be drilled 'through' the wood they can always be drilled from the top or sides, and the router will at maximum need to be horizontal.

### Components are:

* 15mm thick aluminum plates (EN AW-6060 T66)
* cross roller bearings as joints (Hiwin CRBE03515A) 
* a 90x90cm aluminum extrusion connects to the machine (link 1)
* custom GT3 timing pulleys (130 teeth, radius 62mm) attach to links 2 and 3
* nema 23 steppers drive the axis (20 teeth pulley, radius 9mm)

Belts are tensioned by adjusting the position of the motors.

### Forces are: 

* Leadshine offers Nema 23 stepper motors with a holding torque up to 3.1Nm 
* At the 20 teeth pulley radius of 9mm this translates to 344N applied to the belt
* A 10mm wide timing belt is rated at a maximum of about 200N (GT3) or 280N (GT5) 
* At maximum belt strength, a holding torque of 12,5Nm (GT3) or 17,5Nm (GT5) is available at each axis  
* The tip of a drill, extending 200mm out of the router, would be 350mm off axis center
* At the tip of the drill a force of 35N (GT3) or 50N (GT5) would be available to push sideways against the material (see attached image).

I'm still at the initial phase.

### References:

[Bearing specs](https://www.hiwin.hu/en/Produktfinder_Detail_2/Bearings/Crossed_roller_bearings/CRBE/20591)
[Timing belt specs](https://www.electric-skateboard.builders/t/why-dont-people-use-gt3-pulleys-and-belts/71058)
