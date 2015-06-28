# inkscape-powerstroke-fonts

The inkscape powerstroke is a powerful drawing tool. 

https://www.google.com/search?q=inkscape%20powerstroke

I made a demonstration video:

https://www.youtube.com/watch?v=yy2fxxqEZ-A

This repo explores using it for typeface design, which is possible today with the (included as standard) Typography Extension:

![inkscape-typography.png](inkscape-typography.png)

`0-simple-svg-font.svg` is a simple SVGFont file. 

`0-simple-svg-font-opened-ff-saved-as.ufo` is that file opened in FontForge and saved as a UFO, with some metrics set.

The quality of the outlines is not good, and needs adjustment. 
Eduardo Tunni provided example adjusted outlines in the ufo, `0-simple-svg-font-opened-ff-saved-as-adjusted.ufo` and here are visual comparisons:

![0-simple-svg-font-opened-ff-saved-as-adjusted.ufo A](0-A_toggle.gif)

![0-simple-svg-font-opened-ff-saved-as-adjusted.ufo a](0-a-toggle.gif)

`1-simple-stroke-svg-font.svg` is a simple SVGFont file, with an `A` made using a PowerStroke LPE.

`1-simple-stroke-svg-font.ufo` is that file opened in FontForge and saved as a UFO.

Here is the SVG/UFO font opened in FontForge, showing the 'bulky' join of the stroke to the round terminal:

![1-simple-stroke-svg-font-round-terminal.png](1-simple-stroke-svg-font-round-terminal.png)

Edu also provides an adjusted version. 
However, his `1-simple-stroke-svg-font-adjusted.ufo` file has lost some of the character of the original:

![1-simple-stroke-svg-font-adjusted.ufo black](1-black-toggle.gif)

![1-simple-stroke-svg-font-adjusted.ufo outlines](1-outlines-toggle.gif)

* * *

A new idea! `2-rect-as-advanceWidth.svg` is ready to become a simple SVGFont file, but it has `Rect` objects that can set the sidebearings. 
A proposed new python script could use the `Arrange` tools to create spacing text previews for a given string.

* * *

Latest development versions of Inkscape are available:

* Mac: https://code.launchpad.net/~suv-lp/inkscape/osxmenu
* Windows: http://wiki.inkscape.org/wiki/index.php/Installing_Inkscape#Unstable_development_version
