<!-- filepath: /Y:/project/DCTL-MLAA/readme.md -->
# MLAA.dctl

## Overview

This project is a port of Morphological Anti-Aliasing (MLAA) to DCTL (DaVinci Color Transform Language) for use in DaVinci Resolve.

## Features

- Implements MLAA in DCTL to provide anti-aliasing effects.
- Original code is sourced from AMD's MLAA11 project ([Reference1](https://github.com/GPUOpen-LibrariesAndSDKs/MLAA11)).
- References GLSL ported code ([Reference2](https://www.shadertoy.com/view/cllXRB)).

## Installation

1. Obtain the `MLAA.dctl` file.
2. Copy `MLAA.dctl` to the DCTL folder of DaVinci Resolve:

   - Windows: `C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT\`
   - macOS: Not supported yet.

## Usage

1. Open your project in DaVinci Resolve.
2. In the Color page, add a new node and apply the DCTL effect.
3. Select `MLAA.dctl`.
4. Adjust the `ShowEdgesOnly` parameter as needed.

## License

This project is released under the MIT License.
