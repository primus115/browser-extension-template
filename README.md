# Browser Extension Template

A minimal template for creating browser extensions.

## Files

- `manifest.json`: Configuration file for the extension
- `popup.html`: The popup UI
- `popup.js`: JavaScript for the popup
- `styles.css`: CSS styling
- `icons/`: Folder for extension icons
- `generate_icons.js`: Helper for icon generation

## Getting Started

1. Add your icons to the `icons/` folder (16x16, 48x48, and 128x128 pixels)
2. Load the extension in your browser:
   - Chrome: Go to `chrome://extensions/`, enable "Developer mode", click "Load unpacked", and select this folder
   - Firefox: Go to `about:debugging#/runtime/this-firefox`, click "Load Temporary Add-on", and select the `manifest.json` file
3. Customize the files to build your extension
