Fake Diffusion Limited Aggregation Effector for CINEMA 4D
======================

>A Python effector for creating diffusion limited aggregation-like effects in CINEMA 4D.

#[Download](http://bit.ly/132qL8R)

![DLA Render](http://www.creativetools.se/blog_static/media/7386_veckans-ct-freebie:-dla-i-cinema-4d.jpg)

Note that this script only works with CINEMA 4D-versions _Studio_ and _Broadcast_

##File contents

The C4D file contains a number of objects:
* CT DLA Effector
* Cloner
  * Sphere
* Sphere

_CT DLA Effector_ is the actual DLA generator, the others can be replaced by your own objects. Note that the
clone count in the Cloner is animated, resulting in an animated growth of the fractal shape.

##Settings
The _CT DLA Effector_ object has a number of settings in the _User Data_ tab.

* Seed
    * Each seed generates a new sequence of random numbers and gives you a new variation of the fractal.
* Radius
    * The radius of the cloned objects (in the default scene the small spheres).
* Scatter points
    * The number of clones to generate before starting the dla simulation.
* Collision Points
    * The number of clones to check for collision before placing the new clone. A low value will give you a faster simulation but the chance for intersections will be higher.
* Max Iterations
    * A limit to the number of times to try generating a clone before giving up.

##CG News
Visit the Creative Tools blog for your daily dose of CG news.
###[English](http://translate.google.com/translate?js=n&sl=auto&tl=en&u=http://www.creativetools.se/blog/)
###[Swedish](http://www.creativetools.se/blog/)
