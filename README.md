[Japanese Readme](README-ja.md)
# vscode-svgviewer
SVG Viewer for Visual Studio Code
[Visual Studio Marketplace](https://marketplace.visualstudio.com/items/cssho.vscode-svgviewer)

[![](https://vsmarketplacebadge.apphb.com/version/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
[![](https://vsmarketplacebadge.apphb.com/installs/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)
[![](https://vsmarketplacebadge.apphb.com/rating/cssho.vscode-svgviewer.svg)](https://marketplace.visualstudio.com/items?itemName=cssho.vscode-svgviewer)

## Usage 
0. Press Ctrl+P and type `ext install SVG Viewer` with a trailing space. 
0. Press Enter and restart VSCode.
0. Open a SVG File.
0. Choose process from `Command Palette` or `Shortcut`.

![palette](img/palette.png)

### View SVG - `Alt+Shift+S O`
Display SVG on an Editor

### Export PNG - `Alt+Shift+S E`
Convert from SVG to PNG

### Export PNG with explicitly size - `Alt+Shift+S X`
Convert from SVG to PNG with explicitly size

### Copy data URI scheme - `Alt+Shift+S C`
Convert from SVG to data URI scheme and copy to the clipboard

### View SVG and export PNG by Canvas - `Alt+Shift+S V`
Display and Convert
Thanks @kexi

![preview](img/preview.png)

### Options
The following Visual Studio Code setting is available for the SVG Viewer.  This can be set in `User Settings` or `Workspace Settings`.

```javascript
{
    // Show Transparency Grid
	"svgviewer.transparencygrid": true,

    // Open or not open the preview screen automatically
    "svgviewer.enableautopreview": true,

    // How to open the screen (vscode.ViewColumn)
    "svgviewer.previewcolumn": true
}
```