# PCM Workshop: Getting Started with 3D Printing: Fidget Spinners

## Find out more about printing at the Physical Computing Makerspace: 
https://groups.cs.umass.edu/makerspace/how-to-3d-print/


### 3D Printing Basics:
  * 3D printers work by extruding material (hot plastic, metal, chocolate, etc.) layer-by-layer.
    - We’ll be using 1.75mm PLA - Polylactic Acid, extruded at ~220°C (430°F).
  * Most prints start with a 3D object file (.stl, .obj, .step, etc.). You can make your own or find them on many websites like Thingiverse, Printer World, or Printables.
    - We’ll be making our own!
  * A slicer program converts the 3D object file into g-code, the language of 3D printers.
  * The 3D printer interprets the g-code into the movement several stepper motors and heating elements to do the 3D printing.


### Tinkercad:
* Go to https://www.tinkercad.com then login or sign up with a Personal Account
* Select the Create button to start a new 3D Design
* Drag solid objects onto the Workplane
* Design tips:
  * Align objects with the Align button
  * Combine multiple objects with the Union Group button
  * Resize objects by dragging the corner control points for each object
  * Cut objects by turning Solid objects into Holes, then grouping them with Union Group
  * Search through the lists of many interesting shapes


### Let’s Get Designing!
* Go to https://www.tinkercad.com/joinclass
* Enter the class code: TXH UVP KQT
* (If needed, join with "Email or Username" or however you logged in earlier)
* Go to Classes on the left menu if you aren’t directed to it right away
* Select: Fidget Spinner Workshop, then Fidget Spinner, then Fidget Spinner Template
* (Alternatively, download the example models here, then import them into Tinkercad). 
* Design Requirements:
  * The central hole must have a diameter of 22mm (the default value) to accommodate the bearing
  * The height of the fidget spinner must be 7mm, which is the height of the bearing
  * Avoid overhangs between the Workplane and the fidget spinner
* For more on how to 3D print: https://groups.cs.umass.edu/makerspace/how-to-3d-print/


### Slice And Print!
* Export/download your fidget spinner as an .stl file.
* Open Prusa Slier, then import (or drag) your .stl file to the build plate.
* Set the settings in the upper right of the window as follows (these are sometimes the defaults):
 * Prints settings: 0.2 mm SPEED
 * Filament: Generic PLA
 * Printer: Original Prusa MK4 Input Shaper 0.4 nozzle, or Original Prusa i3 MK3S & MK3S+
 * Supports: None
 * Infill: 15%
* Click on "Slice now" in the lower right of the window
* Export the g-code to a USB drive (MK4) or SD card(MK3). The button to export is in the lower right of the window.
* Bring the portable media into the printer and follow the instructions.
* Check back later for your awesome fidget spinner!
