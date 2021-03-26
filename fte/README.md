# FTE skins
This skin allows different shirt and short colors. As of 2019, can only be used with DarkPlaces and FTE (and qRack, as i've been told).

## how to use?
'/teamskin highres'
'/enemyskin highres'
then set '/enemycolor' and '/teamcolor' to your desire (see below)

you can also set your own color (for your player model). Example:
color 0x00ff00 0xff00ff
this will set your top colour to green and your lower colour to magenta

## how to choose colors?
its just 24bit colours prefixed with the standard 0x hex prefix, in RGB order.
you can use any CSS hex color, just make sure they have the 0x prefix.
eg: pick a color from this website, and add the 0x prefix: https://www.htmlcsscolor.com/

## can i use the normal quake colors, ie. color 4 for red?
yes. pre-baked colours work the same way, just with the upper+lower textures being treated as pure black


## how:
it just scales the upper+lower textures by the top/bottom colours and adds them to the base texture.

## contribute:
you can contribute by creating a normalmap and a glossmap for this skin. this would give a nicer result when you're using per-pixel lighting. contact mushi or spike.

 
 
