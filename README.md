# Modal CraftSyth Ctrlr Panel

The aim of this project to create a very basic Ctrlr panel for Modal CarftSynth from scratch.

## Requirements

### To use it

In order to use the panel you shall download and install [Ctrlr](http://ctrlr.org/).
With that, you can use this panel as a standalone application or host it as VST/AU plugin in your favorite DAW.

### Contribute

You are more than welcome to modify, expand, enhance this panel and believe me, you can do it, even in case you are not an experienced hacker (me neither). Tools, resources used in this project:
    * [Inkscape](https://inkscape.org/en/) - to create scalable graphic elements such as the little icons for the wave shapes
    * [Gimp - GNU Image Manipulation Program](https://www.gimp.org/) - to design the actual panel graphics
    * [Neuropol](http://www.dafont.com/neuropol.font) - the fancy futuristic typeface you see in the official app
    * [Ctrlr](http://ctrlr.org/) - awesome project to control any MIDI enabled hardware
    * [Lua](https://www.lua.org/) - LUA scripting language used in Ctrlr
    * Any text editor - nothing fancy, even notepad.exe is fine

#### Folder structure

Well, I like that the things are organized and this project is no exception to that, so I created this folder structure:


```
CarftSynth
    |
    +-- Resources
    |       |
    |       +-- Design
    |       |
    |       +-- Fonts
    |       |
    |       +-- Images
    |       |
    |       +-- Palettes
    |
    +-- CraftSynth_*.panel
    |
    +-- Readme.txt
```

Not a rocket science, however a little explanation migth be useful.

##### Resources/Design

This folder contains the Inkscape and Gimp files. Feel free to unleash your designer personality and create new elements, panel layouts as you wish. The shapes were recreated manually in the spirit of the official app design.

##### Docs

Guess what, in this folder I collected some information related to CraftSynth.

##### Resources/Images

This folder contains the graphic elements that are used in the actual panel.

##### Lua

Lua scripts used in the panel.

##### Resources/Palettes

The ```CraftSynth.gpl``` file in this folder can be used in Inkscape and Gimp as well, as a color palette. The actual colors were shamelessly eyedropped from the picture of the official app.

##### CarftSynth_*.panel

The ```CraftSynth_*.panel``` file is the actual panel, ready to be used in Ctrlr application.

## Licence

The code used for the panel is distributed under GNU General Public Licence version 3. 
Design elements are covered by Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Licence (CC BY-NC-SA 4.0).

