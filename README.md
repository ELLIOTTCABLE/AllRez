AllRez
======

Debugging tool to print a ton of display/GPU/Thunderbolt debugging information on macOS — including attached-display info, EDIDs, DisplayPort/DPCD state, and an `iogdiagnose`-style IOGraphics dump tailored to the running Darwin version.

(Also: `dumpdpcd`, which decodes a DPCD capture from a binary file.)

Installation
------------

You can download the latest release as a binary from [GitHub Releases](../../releases/latest).

For automation purposes, these may serve you well:
- [`ubi`](https://github.com/houseabsolute/ubi), the "Universal Binary Installer" - useful for one-off installs; or
- [mise-en-place](https://mise.jdx.dev/), useful mostly if you already use it as a runtimes package-manager and/or want AllRez around more durably:

```console
$ ubi --project joevt/AllRez --in ~/.bin
# or
$ mise install --global "github:joevt/AllRez"
```
