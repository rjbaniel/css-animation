CSS3 Animation
==============
#### Main visual elements
- **Flipping Name and Info**
- **Border Animation**
- **Rotating Vector Image**

#####Flipping Name and Info
Based off of a tutorial at [Site Point](http://www.sitepoint.com/css3-transformations-3d-backface-visibility/).

Made possible by positioning the divs for the "front" and the "back" so that they lie right on top of each other, then rotating the "back" 180 degrees and setting the backface-visibility property to hidden, which hides an element when it is rotated away from the user. backface-visibility needs the -webkit browser prefix for Chrome and Safari.

#####Border Animation
Based off of a tutorial at [Tympanus Codrops](http://tympanus.net/codrops/2014/02/26/creating-a-border-animation-effect-with-svg-and-css/).

Made possible by creating an SVG "line" three times as long as the side that the border is being made for, and using the stroke-dasharray property to make the line dashed, with the dashes and the gap between them as long as the side. Then the line is transitioned so that the blank part of the line and then the dash (which was origninally invisible) come into the element. This is done for each of the sides.

#####Rotating Vector Image
Done using basic @keyframes animation when the parent div for the SVG element is in its active state.
