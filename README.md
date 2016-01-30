# 3D-Printer-Configs
This repository holds configuration files for 3D printer software.

These configurations are for slicing to a G-Code file for upload to Repetier Server to which the printers are attached. Repetier Server has its own configuration for each of the the printers for which these config files have been written. Therefore, the config files presented here may not have additional pre- or post-print G-Code that might be needed if printing directly to a printer through USB.

## slic3r (for G-Code output to file for upload to Repetier Server)

Contains config files for slic3r. To use, load using the File | Load Config... menu. After loading the object to slice, the config must be selected for the Print Settings, Filament Settings, and Printer Settings tabs. This can be done under each of the tabs, OR selected for each on the far right of the Plater tab.

### slic3r configs for Printrbot Simple Metal

These configurations are for a Printrbot without a heated bed that prints only PLA. A configuration is provided for fast prints and another for quality prints. They include a brim to hold down the parts better and a skirt to prime the extruder.
