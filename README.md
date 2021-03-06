#Miniature-wookie - just another mixin lib

## Contents
* [About](#about)
* [Quick start](#quick-start)
    - [Grid system](#grid-system)
    - [Layout tools](#layout-tools)
    - [Igniting tools](#igniting-tools)
    - [Typographic rhythm](#typographic-rhythm)
* [TODO](#todo)
* [Changelog](#changelog)
* [License](#license)

## About
This is a set of useful mixins for [Sass\Scss](http://sass-lang.com/) and [Less](http://lesscss.org/) and simple grid system for common projects.

Why "miniature-wookie"? - I don't know, it's just github repo naming advice ;)

## Quick start
Ok, for now there are three mixin libs like common elements, grid and weird mixn for pixel perfect dev. Just include it to your stylesheet and apply desirable mixin. Each lib have their own readme with detailed explanations.
You can visit project [home page](http://orlovmax.com/lab/tools/miniature-wookie) for some details, demos and tutorials.

### Grid system
Basicly this grid system was created for Inclusion framework and was like internal mixin, but I thougt that it may be useful as standalone thing. Interesting lib with four mixins and infinite abilities. Why this bicycle instead of famous and stable grid systems? - There are no answer. That grid systems are cool and they inspired me to create my own with convenient options. Actually with this lib you can create almost all grids just using one mixin - gs-column(). It can take all necessarry options for grid system math and overwrite defaults. Shortcodes for these mixin you can find [here](https://github.com/front-end-lab/miniature-wookie/blob/master/grid-system-generator/README.md)
Also you can visit project [home page](http://orlovmax.com/lab/tools/miniature-wookie_grid-system) for some details, demos and tutorials.

### Layout tools
It's nice set with two mixins, that allows to develop on the principle of pixel-perfect. It contains two separate mixins: first - layout mixin, the second - graph paper that positioned over the page.
Usage is very simple: first you need to import the library and apply mixin to <body> tag, with desired options. This will result in the imposition of `layout.jpg` over web page. Image width will be equal to 100% and opacity - 50%. Optionally available "graph paper" default grid is not shown because its opacity is equal to zero. Shortcodes for these mixin you can find [here](https://github.com/front-end-lab/miniature-wookie/blob/master/layout-tools/README.md).
Also you can visit project [home page](http://orlovmax.com/lab/tools/pixel-perfect-dev) for some details, demos and tutorials.

### Igniting tools
This is the logical extension of two very useful mixins for debugging - `testbg()` and `testout()` - add semi-transparent background and outline to elements.
This tool is mixin, that applies to the root tag or global scope and can highlight specific or all elements and add to them colored outline. 
Shortcodes for these mixin you can find [here](https://github.com/front-end-lab/miniature-wookie/blob/master/ignition-tools/README.md)

### Typographic rhythm
Mixin library to create a typographic system using scale and vertical rhythm.
In general this tool was inspired by Gridlover, ModularScale and Compass vertical rhythm tool.
Shortcodes for these mixin you can find [here](https://github.com/front-end-lab/miniature-wookie/blob/master/typographic-rhythm/README.md)

## TODO
* Less grid system
* Less typographic rhythm tool

## Changelog
* (April 5, 2016)
    - Elements lib, mixins lib removed as unused, readme updated
* (October 15, 2015)
    - Typography rhythm sass, scss, stylus versions added
* (October 12, 2015)
    - Typography rhythm init, file naming changed
* (June 12, 2015)
    - Igniting tools release
* (June 10, 2015)
    - Igniting tools init
* (June 07, 2015)
    - _mixins libs added for sass, scss, stylus, less
* (June 05, 2015)
    - Elements lib development deprecated in favor of autoprefixer
* (May 09, 2015)
    - Stylus version added
* (January 11, 2015)
    - Sass version added
* (November 16, 2014)
    - Demo and readme added
* (November 3, 2014)
    - Layout tools added
* (October 28, 2014)
    - Grid system added

## License
[MIT](http://opensource.org/licenses/MIT)
