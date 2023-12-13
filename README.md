# FreeCAD-Cookie-Cutter
A FreeCAD Addon to create Cookie Cutters from Sketches and DXF-Files

![](images/fusion-360-cookie-cutter-addin.png)

## Project plan

The goal of this project is to create a cookie cutter addon for FreeCAD before 22.12.2023, so that others can use it to make cookies for christmas.

Requirements for the MVP:
- The Addon is written in Python
- The Addon is a Macro, not a Workbench
- Creates a native Part::Feature object of the cookie cutter in the active FreeCAD document, this enables everyone to open the cookie cutter, without any addon installation
- The user selects a sketch or part of a closed wire in the GUI, the selected sketch is only allowed to contain ONE closed wire
- The cross-section of the Cookie Cutter is predefined in its shape and dimensions. It looks similar to the cross-section implemented in the Fusion 360 Cookie Cutter Addin
- The cross-section gets swept along the selected closed wire
- The cookie cutter is intended to be 3D printed. The shape of the Cookie Cutter is orientated in a way, in which its easy to 3D print it, removing the need to rotate it in the slicer software
- Wrong user inputs should be prohibited and the user should be assisted and told what he/she should do to create the Cookie Cutter shape
- The entire Cookie Cutter addon has to have a Plug-and-Play feeling, no tinkering around required
