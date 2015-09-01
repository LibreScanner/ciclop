# Ciclop

In this repository you will find the source files for the [bq Ciclop 3D scanner](http://diwo.bq.com/en/tag/ciclop) [[es](http://diwo.bq.com/tag/ciclop)]. Also in [thingiverse](http://www.thingiverse.com/thing:740357). If you are missing something, please do not hesitate to [file an issue on github](https://github.com/bqlabs/ciclop/issues).

![][ciclop]

Ciclop may be controlled by Horus software. You can find here the [firmware](https://github.com/bqlabs/horus-fw) and the [desktop application](https://github.com/bqlabs/horus).

## License 

Ciclop is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

Please read the LICENSE file for more details.

## Directory structure

 * `step`: The original Ciclop step files. This folder is frozen. Find the latest version in the `freecad` folder

 * `stl`: Ciclop STL files. It also contains parts with support for 3D printing

 * `dxf`: Ciclop DXF files. It contains all methacrylate pieces cutted with laser

 * `svg`: Ciclop SVG files. This folder contains all drawings for 2D printing

 * `freecad`: Ciclop source files in [FreeCAD](http://www.freecadweb.org/). This is a work in progress. All the original files are being migrated to Freecad (see below)

 * `Ciclop-BOM.ods`: Ciclop Bill of Materials. Document for [LibreOffice](https://www.libreoffice.org/)

![][ciclop-parts]

**Please note**: The original Ciclop design was made in Autodesk Inventor(tm) which is proprietary software. Since we love open formats we are migrating the Ciclop parts to [FreeCAD](http://www.freecadweb.org/), which is a multiplatform open source CAD software. We invite people from the community to join us and help us to complete the task.

[ciclop]: doc/images/ciclop.jpg
[ciclop-parts]: doc/images/ciclop-parts.jpg
