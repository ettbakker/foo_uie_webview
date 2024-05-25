
# foo_vis_text

[foo_vis_text](https://github.com/stuerp/foo_vis_text/releases) is a [foobar2000](https://www.foobar2000.org/) component that implements a text information panel.

## Features

* Supports the Default User Interface (DUI) and the [Columns User Interface](https://yuo.be/columns-ui) (CUI).
* Supports dark mode.
* Supports foobar2000 2.0 and later (32-bit and 64-bit version).

## Requirements

* [foobar2000](https://www.foobar2000.org/download) v2.0 or later (32 or 64-bit). ![foobar2000](https://www.foobar2000.org/button-small.png)
* Tested on Microsoft Windows 10 and later.
* Tested with [Columns UI](https://yuo.be/columns-ui) 2.1.0.

## Getting started

* Double-click `foo_vis_text.fbk2-component`.

or

* Import `foo_vis_text.fbk2-component` into foobar2000 using the "*File / Preferences / Components / Install...*" menu item.

## Developing

### Requirements

To build the code you need:

* [Microsoft Visual Studio 2022 Community Edition](https://visualstudio.microsoft.com/downloads/) or later
* [foobar2000 SDK](https://www.foobar2000.org/SDK) 2023-09-23
* [Windows Template Library (WTL)](https://github.com/Win32-WTL/WTL) 10.0.10320
* [Columns UI SDK](https://yuo.be/columns-ui-sdk) 7.0.0

To create the deployment package you need:

* [PowerShell 7.2](https://github.com/PowerShell/PowerShell) or later

### Setup

Create the following directory structure:

    3rdParty
        columns_ui-sdk
        WTL10_10320
    bin
        x86
    foo_vis_text
    out
    sdk

* `3rdParty/columns_ui-sdk` contains the Columns UI SDK 7.0.0.
* `3rdParty/WTL10_10320` contains WTL 10.0.10320.
* `bin` contains a portable version of foobar2000 64-bit for debugging purposes.
* `bin/x86` contains a portable version of foobar2000 32-bit for debugging purposes.
* `foo_vis_text` contains the [Git](https://github.com/stuerp/foo_vis_text) repository.
* `out` receives a deployable version of the component.
* `sdk` contains the foobar2000 SDK.

### Building

Open `foo_vis_text.sln` with Visual Studio and build the solution.

### Packaging

To create the component first build the x86 configuration and next the x64 configuration.

## Change Log

v0.1.0.0, 2024-05-xx, *"Scratchin' the itch"*

* Initial release.

## Acknowledgements / Credits

* Peter Pawlowski for the [foobar2000](https://www.foobar2000.org/) audio player. ![foobar2000](https://www.foobar2000.org/button-small.png)

## Reference Material

* https://learn.microsoft.com/en-us/microsoft-edge/webview2/get-started/win32
* https://learn.microsoft.com/en-us/microsoft-edge/webview2/concepts/user-data-folder?tabs=win32
* https://learn.microsoft.com/en-us/microsoft-edge/webview2/reference/win32/?view=webview2-1.0.2478.35
* https://learn.microsoft.com/en-us/microsoft-edge/webview2/reference/win32/icorewebview2_3?view=webview2-1.0.2478.35#setvirtualhostnametofoldermapping

## Links

* Home page: [https://github.com/stuerp/foo_vis_text](https://github.com/stuerp/foo_vis_text)
* Repository: [https://github.com/stuerp/foo_vis_text.git](https://github.com/stuerp/foo_vis_text.git)
* Issue tracker: [https://github.com/stuerp/foo_vis_text/issues](https://github.com/stuerp/foo_vis_text/issues)
* Wiki: [https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Text_Visualizer_(foo_vis_text)](https://wiki.hydrogenaud.io/index.php?title=Foobar2000:Components/Text_Visualizer_(foo_vis_text)).
## License

![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)