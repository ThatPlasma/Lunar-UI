# A modified version of P2:CE's Panorama UI

This directory contains a modified version of P2:CE's Panorama UI

## Folder Structure
- `browser/` -- Contains a webkit css file for browser widget
- `fonts/`  -- Contains the fonts used in Panorama
- `layout/` -- All UI layouts go here. They're in XML, not HTML 
- `scripts/` -- All JavaScript scripts go here. We use ES6 JS
- `styles/` -- All CSS/SCSS/SASS stylesheets go here. Note that Panorama CSS is an extended version of normal CSS. Some properties will be missing
- `dev_keybinds.cfg` -- These keybinds will only be loaded if -dev is passed to the game. By default we bind F6 to open the debugger, F7 to reload changed files, and F8 to reload everything, as well as some other functions.
- `panorama.cfg` -- This cfg defines various panorama directories, associating them with a name 
- `default_keybinds.cfg` -- This is just a list of the default panorama keybinds
