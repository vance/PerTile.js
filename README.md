PerTile.js
==========

Multi-Resolution Periodic Tile Engine

The PerTile library is for visually manipulating and exploring periodic image tile sets. A periodic image tile set is a series of images whose contents span iner-page boundaries both horizontally and vertically. The prototype engine will only support column-major periodic arrangments, but could be configured for row-major in the future.

At a minimum it should support

   - Use a configurable base resolution, tile count, column count (eventually row count)
   - Accept multi-touch and mouse input
   - Change viewport zoom (continuously)
   - Change viewport pan (continuously)
   - Multi-resolution image loading and unloading
   - Go-to-pixel (center on pixel in given tile)
   - Go-to-window (goto a rectangle bounding box)
   - Support interactivity (return current click location described in page and pixel coordinate)
   - Click-to-center
   - Work as an AMD compatable module
   
This library is inteneded for reuse, but it's primary purpose is to support the foreverscape-engine:

The ForeverScape is a massive 2.3 football field long hand-drawn illustration that tiles like wallpaper (every page connects to the next). This is a javascript implementation that allows users to explore the ForeverScape universe. Use it as a re-sizable component and add optional interactivity features through the interaction and scripting API.



ATTENTIION

While this license grants rights to software per the GNU General Public License Version 2, it does not grant rights to reproduce any linked resources such as images. This software is intended to be a presentation layer. Permission to use the images is denied unless granted in writing by Vance Feldman or ForeverScape, LLC. Without authorization, resources cannot be hosted on a public server or otherwise be linked to or presented to any party. Violations will be prosecuted to the furthest extent of the law.
