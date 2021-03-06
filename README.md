# BspViewer

![](https://img.shields.io/badge/.net-v4.5.2-blue.svg)
![](https://img.shields.io/badge/build-passing-green.svg)

Rendering BSP v30 files from Halflife and it's modifications. (CSTRIKE, TFC, VALVE)

![BspViewer](https://github.com/PSneijder/BspViewer/blob/master/Assets/BspViewer.gif)

## Reasons
In November of 1998, I first played Half-Life and loved it! Since then I became interested in first person shooter games and in particular how the levels are created and rendered in real time. I found myself in between jobs and so I embarked on an effort to learn about 3D rendering with the goal of creating my own 3D rendering engine. Since I am a developer and not an artist I didn't have the skills to create my own models, levels, and textures. So I decided to attempt to write a rendering engine that would render existing game levels. I mainly used information and articles I found on the web about Quake 2, Half Life, WAD and BSP files. The Half-Life SDK and a lot of C++ projects floating around the web were useful resources too.

## Controls
```
W                Move forward
S                Move backward
A                Move sidewards left (strafe)
D                Move sidewards right (strafe)
E or Space/Shift Move up
Q or Ctrl        Move down

Left             Rotate left
Right            Rotate right
Up               Look up
Down             Look down
```

## TODOs
* <strike>Reading BSP and WAD3 files</strike>
* <strike>Binary-Space-Partition</strike>
* <strike>Render BSP</strike>
* <strike>Free-Look-Camera</strike>
* Potentially-Visible-Set (PVS - to significantly improve rendering performance)
* Textures
* Collision Detection
* Shaders

## Recent Changes
See [CHANGES.txt](CHANGES.txt)

## Committers
* [Philip Schneider](https://github.com/PSneijder)

## Licensing
The license for the code is [ALv2](http://www.apache.org/licenses/LICENSE-2.0.html).
