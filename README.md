A sample WebMonetization extension to demonstrate WebMonetization in a Firefox implementation (prototype) at https://github.com/sidvishnoi/gecko-webmonetization/. This extension is based on the [Coil WebMonetization extension](https://github.com/coilhq/web-monetization-projects/tree/189b612/packages/coil-extension).

## How to use?

1. Download a Firefox release from https://github.com/sidvishnoi/gecko-webmonetization/releases/tag/2021-02-04. Extract and run the main `firefox` executable.
2. Load the extension:
   - (Persistent)
     1. Download the [Extension XPI file](https://github.com/sidvishnoi/wm-firefox-extension-coil/raw/main/dist/webmonetizationdemo-1.0-fx.xpi)
     2. Drag and drop downloaded XPI file into the browser and accept confirmation prompt.
   - (Temporarily)
     1. Download the [zip](https://github.com/sidvishnoi/wm-firefox-extension-coil/archive/main.zip) and extract.
     1. Visit `about:debugging#/runtime/this-firefox`
     1. Click "Load Temporary Add-on…" and select any file from the extension folder when prompted.
3. Go to `about:addons`, open Preferences for this extension and enter your Coil credentials.
4. Visit my [WebMonetization playground](https://sidvishnoi.github.io/wm-playground/) and try out various demos.
