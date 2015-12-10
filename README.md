New Matter MOD-t 3d Printer Repo
================================

This repository is a collection of files (firmware, test files, configurations, etc) for the NewMatter MOD-t 3d Printer.

I am not associated with NewMatter in any way, but here's links to their site:

-	http://newmatter.com
-	http://support.newmatter.com

**WARNING:** I take absolutely no responsibility for anything you do with these files or instructions, play at your own risk!

Files
-----

### `Astroprint.md`

Information on setting up/configuring Astroprint (with GCode) https://www.astroprint.com/

### `Basic_GCode.md`

Basic GCode information for setting up the printer (including START and END commands)

### `clearnozzle.gcode`

The file `clearnozzle.gcode` is intended to help clear a jammed nozzle on the MOD-t. Just connect your MOD-t to your computer with the USB, launch the MOD-t print tool app and select `Settings > Advanced Mode > Print File`

The MOD-t will do it's little calibration dance and then the nozzle will start to heat to 230ºC (actually it will try, but because the MOD-t is firmware limited to a max temp of 220ºC, it will never get there) and then the print head will move up. The move is just there to indicate that it's gotten to temp. The extruder will then try to push filament through, which should be enough to clear most jams. Finally the print head will move back down and the MOD-t will go back to idle.

---

Directories
-----------

### Firmware

This directory contains any firmware files I have been able to find, if you have any that are not in the repo, please open an issue or get in contact me with so I can add them.

Go to the directory and see the `README.md` for documentation

### Slic3r

This directory contains configuration files for Slic3r: http://slic3r.org

Launch Slic3r and select `File > Load Config` and select the file

I recommend going in to Preferences in Slic3r and choosing Expert Mode.

### Cura

Information/Configuration files for Cura https://ultimaker.com/en/products/cura-software

### Calibration Tests

Settings for the `Extrusion multiplier` in the `Filament Settings` tab of Slic3r, example image, and code to print a single wall.

Go to the directory and see the `README.md` for documentation

---

How to contibute
----------------

If you have a copy of firmware files, update suggestions to configurations, or anything else related to the MOD-t ... please feel free to open a new issue and let me know. I'll be more than happy to update or add anything to this repo.

---

### Credits

The majority of the information and files were obtained from `ajfoul`, make sure to check his repository for any other files or updates he may have added: https://github.com/ajfoul/MOD-t