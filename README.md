# Processing-SVG
A library that lets you convert SVG images to PNG images

# Usage

## importing

1. Write "import anthony.SvgEditor;" at the top of your code
2. Add the /bin files to your buid path

## methods

- SvgEditor.svgToPng(String path)
- - Converts the .SVG image at the specified path to a .PNG in the same folder
- - Returns the path for the new image

- SvgEditor.resizeSvg(String path, int _wid, int _hei)
- - Modifies the width and height attributes for the .SVG image
- - Returns true if successful
