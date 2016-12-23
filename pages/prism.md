---
layout: prism
permalink: /prism
---

The Programmable Ray Integration Shading Model, or PRISM is a GPU volume ray casting module implemented as a VTK class and embeded in the Ibis Neuronav platform. Its unique feature is the ability for users to replace key parts of the ray integration algorithm with custom GLSL code, enabling the implementation of new volume rendering effects with no more than a few lines of code.

To try PRISM:

1. Download IBIS Neuronav
2. Download example IBIS scenes
3. Open scenes in IBIS

## Downloading IBIS Neuronav

The following binaries of IBIS Neuronav should be used with example scenes provided on this page

For macOS (10.8 or newer): 
1. Download the [dmg](https://github.com/IbisNeuronav/PRISMDatabase/releases/download/v1.0/ibis-3.0.0-Dev-OSX-10.10.dmg) file and open it.
2. [optional]Copy ibis.app to Application folder.
3. double-click ibis.app

For Linux (Ubuntu 14.04):
1. Download the [.tar.gz](https://github.com/IbisNeuronav/PRISMDatabase/releases/download/v1.0/ibis-3.0.0-Dev-Ubunu-14.04-x86_64.tar.gz) package.
2. Extract to the desired folder.
3. On the command line, cd to extracted folder and run ./IbisView

## Downloading example IBIS scenes

Download the zipped package for version 1.0 of the examples [here](https://github.com/IbisNeuronav/PRISMDatabase/archive/v1.0.zip).
The examples archived in a Git repository, so updated examples can always be obtained from the repository [here](https://github.com/IbisNeuronav/PRISMDatabase)
Each example is in a different folder. The scene description is found in scene.xml

## Open example scenes in IBIS

1. Run IBIS. 
2. In the menu, select File->Load Scene... 
3. In the file selection dialog, choose the scene.xml file from the desired example folder.
