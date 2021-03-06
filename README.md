# Import Colors

Import colors from swatches file to Sketch.  **(For Sketch 53+)**

## Installation

- [Download](https://github.com/Ashung/import-colors-sketch/releases/latest/download/import-colors.sketchplugin.zip) zip file, unzip and double click on the ".sketchplugin" file.
- Search "import colors" from [Sketch Runner](http://sketchrunner.com/).

## Features

### V1.0.x (for Sketch 53 ~ 68.x)

- Import Colors to Document / Global
- Import Colors as Library
- Export Document / Global Colors to .txt or .clr file
- Convert Colors to .txt or .clr File
- Reset Global Colors

### V2.0.x (for Sketch 69+)

- Import Colors to Color Variables
- Import Colors as Library
- Import Colors and Update Color Variables
- Convert Color Variables to .txt or .clr File
- Export Color Variables to .txt or .clr file

## Supported Formats

| Name                       | Extension        | Support Application                 |
| -------------------------- | ---------------- | ----------------------------------- |
| Apple Color Picker Palette | `.clr`           | macOS Color Picker <sup>1</sup>     |
| Adobe Color Swatch         | `.aco`           | Photoshop <sup>2</sup>              |
| Adobe Color Table          | `.act`           | Photoshop <sup>2</sup>              |
| Adobe Swatch Exchange      | `.ase`           | Photoshop, Illustrator <sup>2</sup> |
| GIMP Palette               | `.gpl`           | GIMP, Inkscape                      |
| Sketch Palette             | `.sketchpalette` | Sketch (old version)                |
| Sketch Preset              | `.sketchpreset`  | Sketch <sup>3</sup>                 |
| Sketch Document            | `.sketch`        | Sketch <sup>3</sup>                 |
| Text File                  | `.txt`, `.text`  | Text Editor <sup>4</sup>            |

1. In Sketch run "View" - "Show Colors", select palette tab, then click the gear icon, to open .clr files.
2. The color save in CMYK, LAB, Grayscale model from .aco or .ase file, maybe have different hex value between Sketch and Photoshop.
3. Only import document colors.
4. Save colors in each lines, like `red: #ff0000`, color support hex, CSS color name, 8-digit hex, rgb, rgba, hsl, hsla.

## License

MIT

## Donate

[Buy me a coffee](https://www.buymeacoffee.com/ashung) or donate [$2.00](https://www.paypal.me/ashung/2) [$5.00](https://www.paypal.me/ashung/5) [$10.00](https://www.paypal.me/ashung/10) via PayPal.

-----

> **NOTE**
> _This plugin was created using `skpm`. For a detailed explanation on how things work, checkout the [skpm Readme](https://github.com/skpm/skpm/blob/master/README.md)._
