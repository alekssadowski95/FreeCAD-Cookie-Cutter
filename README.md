# FreeCAD-Cookie-Cutter
A FreeCAD Addon to create Cookie Cutters from Sketches and DXF-Files

![](images/fusion-360-cookie-cutter-addin.png)

## Project plan

The goal of this project is to create a cookie cutter addon for FreeCAD before 22.12.2023, so that others can use it to make cookies for christmas.
- The Addon is written in Python
- The Addon is a Macro, not a Workbench
- Creates a native Part::Feature object of the cookie cutter in the active FreeCAD document, this enables everyone to open the cookie cutter, without any addon installation
- The cookie cutter object is based on a Sketch selection. The selected sketch is only allowed to contain ONE closed wire
