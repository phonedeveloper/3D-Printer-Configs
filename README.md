# 3D-Printer-Configs
This repository holds configuration files for 3D printer software.

These configurations are for slicing to a G-Code file for upload to Repetier Server to which the printers are attached. Repetier Server has its own configuration for each of the the printers for which these config files have been written. Therefore, the config files presented here may not have additional pre- or post-print G-Code that might be needed if printing directly to a printer through USB.

## Repetier Server

We are beginning to use Repetier Server at Makersmiths to provide 3D print services to members. The Repetier-Server folder holds the contents of /var/lib/Repetier-Server/configs, which holds configurations for the printers we use. An opportunity to import a configuration file is provided when you start the add-a-printer process.

For the Printrbot Simple Metal, G-Code has been added to cause the printer to begin the auto-level process before each print. Without this, a G-Code file might level only at origin, and the print area may in fact be higher or lower, causing the first layer to either be mashed into the bed or printed above it and not adhere.

## slic3r (for G-Code output to file for upload to Repetier Server)

Contains config files for slic3r. To use, load using the File | Load Config... menu. After loading the object to slice, the config must be selected for the Print Settings, Filament Settings, and Printer Settings tabs. This can be done under each of the tabs, OR selected for each on the far right of the Plater tab.

### slic3r configs for Printrbot Simple Metal

These configurations are for a Printrbot without a heated bed that prints only PLA. A configuration is provided for fast prints and another for quality prints. They include a brim to hold down the parts better and a skirt to prime the extruder.
