# Contributing to the Janelia Gather map

## Objects

Anyone with access to the Janelia map can help customize our House of Science by placing furniture, posters, and other objects. Just enable builder mode in the left-hand toolbar and select the object you want to place. 

## Map

We are looking for creative and artistic Janelians to help build out additional sections of Janelia. We can link these sections to the main map using portals, just like Bob's is currently linked. If you have interest in constructing a particular area (a pod, lab space, the cafeteria, etc.) please contact Konrad Rokicki in Scientific Computing.

### Builder Instructions

Download the [Tiled Map Editor](https://www.mapeditor.org/) and open `tiled/Janelia.tmx` to edit the map image, or create your own map.

To upload your map to Gather:
* export all layers to `final/<MapName>.png` using *File / Export As Image*
* turn off the Background layer and export to `final/<MapName>FG.png`
* turn off the Foreground layer and export to `final/<MapName>BG.png`

You can commit all of these files to git.

The last two images need to be imported into Gather. You can [watch Gather's MapMaker tutorial](https://www.youtube.com/watch?v=cwgixlNM6-w) to get oriented with their online tools.

