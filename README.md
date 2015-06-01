Cities: Skylines Terrain Generator 
==================================

Quickly generate great looking terrain to be used as a base for creating your own maps!

This mod is available on the [Steam Workshop](http://steamcommunity.com/sharedfiles/filedetails/?id=453425585)

This mod creates random fractal terrains using the diamond square algorithm.

This mod will work with new maps only! If you already have placed watersources, roads, ship paths, etc those might get lost when creating a new terrain, or will go all goofy depending on your map. I.e. watersources can get underground where you won't be able to move/delete them. 

This mod adds a new 'tree' button in the bottom button bar in the Map Editor. (I couldn't find any other usable icon atm).

There are a few parameters to play with.

* Smoothness defines the global 'rockyness' of the terrain. 10 is real smooth, below 5 is probably useless.

* Scale defines the height of the terrain. A scale of 0 will generate a flat terrain.

* Offset will shift the centerpoint of the terrain. With the scale at 1.0 some clipping might occur which you can adjust using this offset.

* Blur; 0 means no blurring, 2 generates real soft terrains.

After creating a new terrain you must modify your water level, click 'Reset Water To Sea Level' a couple of times and put the simulation speed to max. It can take a while for the water to settle. Leave it running for a few minutes atleast.

Just play around and have fun !

Thanks to other modders for their work on UI code. Kudos to [Cities-Skylines-Mapper](https://github.com/lxteo/Cities-Skylines-Mapper) [Crossings](https://github.com/bernardd/Crossings) and [Skylines-FPSCamera](https://github.com/AlexanderDzhoganov/Skylines-FPSCamera)

This mod was basically inspired by [Charles Randall](http://www.bluh.org/code-the-diamond-square-algorithm/) and another excellent explanation is from [Hunter Loftis](http://www.playfuljs.com/realistic-terrain-in-130-lines/)

Learn more about the [diamond square algorithm](http://en.wikipedia.org/wiki/Diamond-square_algorithm) and on [Gameprogrammer.com](http://www.gameprogrammer.com/fractal.html)

If you find bugs or have feedback let me know!

