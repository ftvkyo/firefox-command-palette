# Firefox Command Palette
Control Firefox with Sublime/helm-M-x style fuzzy complete. Use it from the omnibar with the `;` search prefix, or trigger a pop-up with `Ctrl+Space`.

[Available](https://addons.mozilla.org/en-GB/firefox/addon/command-palette-for-firefox/) on the Mozilla Add-ons site.

To build:

  1. Clone this repo and make sure you have node and npm setup and working.
  2. `npm install`
  3. `npm run build`

`firefox-command-palette.zip` will appear.

To install, if you are not signing the extension:

 1. Make sure you are using Firefox ESR, or Firefox Developer Edition, or Firefox Nightly
 2. Open `about:config` and set `xpinstall.signatures.required` to `false`
  - Read more: [Add-on signing in Firefox](https://support.mozilla.org/en-US/kb/add-on-signing-in-firefox)
 3. Open `about:addons` and drag the zip there or use the "Install Add-on from file..." menu option to install the addon

## Credits
This extension uses the Terminal icon from [Font Awesome](https://fontawesome.com). It's [licensed](https://fontawesome.com/license/free) under Creative Commons [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Fuzzy completion is provided by Nicolas Bevacqua's `fuzzysearch` library. It is [MIT](https://github.com/bevacqua/fuzzysearch/blob/master/LICENSE/) licensed and its source code can be found on [GitHub](https://github.com/bevacqua/fuzzysearch/).

This extension, with the exception of the above, is licensed under GPL (see [LICENSE](./LICENSE)).
