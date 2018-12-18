# CURA 3.6+ profile for NewMatter MOD-t 3D-Printer

This is a mashup of the original settings for NewMatter's MOD-t 3dPrinter by [energywave](https://www.thingiverse.com/thing:1535333) on thingiverse updated to work for the latest CURA release (currently v3.6).

## Installation

### 1. Copy Files

- Place `modt.def.json` into `resources/definitions`
- Place `modt_platform.stl` into `resources/meshes`

On OSX you find the `resources` folder when clicking right on CURA, `Show Package Contents` and then navigating to `Contents/Resources`. On Windows it should be under `Program files\Cura 3.x\`.

### 2. Setup Printer

Open CURA. Add a new Printer. Select `Other/MODt`. Check if the values still apply (sometimes changes on updated CURA versions). Add the Printer.

### 3. Import Profile

Go to Profiles. Click Import. Select `modt.curaprofile`

### 4. Adjust Settings

Thats it. Depending on what filament you use, adjust it for your needs. Especially check out the `Printing Temperature` and `Flow` settings.
