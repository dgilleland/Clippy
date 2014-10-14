[Clippy](http://bennettfeely.com/clippy)
======

Shape up your website with CSS clip-paths!

Clippy is a tool for generating values for shape functions for the new and cool CSS clip-path property. The property accepts several basic shapes that will be able to create with Clippy and their current implementation status:

* `circle()` Currently disabled, still buggy when using a ratio that's not 1:1.
* `ellipse()` Improved, handles now switch to best side.
* `polygon()` Includes common preset shapes plus the ability to create a custom shape
* `inset()` Improved, now supports radius value


#### Details
* Utilizes [draggabilly.js](https://github.com/desandro/draggabilly) for the handles which each correspond to a point for CSS clip path. Works really well on touch devices, especially with the `touch-action: none`.
* For development, using Grunt with SCSS, autoprefixer, uncss, minification for CSS, HTML, and javascript.
* Material-ish design inspiration.
* Mobile-first design, making things work great on mobile touch devices first and working responsively upwards from there.


#### To do

* ✓ Make a panel card with quick information about the `clip-path` property.
* ✓ Add ability to make custom shapes
* ✓ Add radius support for `inset` shape.
* Looking into: Add HTML5 localstorage to save things.
* Looking into: See how Clippy could be used with [CSS Shapes module](http://dev.w3.org/csswg/css-shapes/#basic-shape-functions)

***

#### Browser Support for Clip Path

[caniuse.com](http://caniuse.com/#search=clip-path)
