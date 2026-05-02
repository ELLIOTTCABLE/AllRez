AllRez
======

Debugging tool to print a ton of display/GPU/Thunderbolt debugging information on macOS — including attached-display info, EDIDs, DisplayPort/DPCD state, and an `iogdiagnose`-style IOGraphics dump tailored to the running Darwin version.

(Also: `dumpdpcd`, which decodes a DPCD capture from a binary file.)

Installation
------------

You can download the latest release as a binary from [GitHub Releases](../../releases/latest).

For automation purposes, [`ubi`](https://github.com/houseabsolute/ubi) or [mise-en-place](https://mise.jdx.dev/) may serve you well:

```console
$ ubi --project joevt/AllRez --in ~/.bin
# or
$ mise install --global "github:joevt/AllRez"
```
