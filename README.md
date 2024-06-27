# WRECK-Patch
Mount and Blade Warband compiler with ID nameError fixes and subdirectory support
## Tutorial 
Replace WRECKs compile.py with the custom one.

## Features
* You can create a "mods," folder and the compiler will pick up on it as if it was in the module systems root directory.
* Compiles the IDs for meshes, map_icons, troops, items, and party_templates before compiling the rest of the module to avoid new additions (i.e mod_merger mods, causing a name error.)

## Planned Features

* Further compilation order fixes so that WRECK will never give an error caused by missing ID when the code to properly generate the ID is present.

  
