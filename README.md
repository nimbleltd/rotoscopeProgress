Rotoscope in the Browser: 
==========================
a.k.a. lightsaber effect in the browser

Goal: create a prototype to prove one can provide controls and a lightsaber style 
canvas to allow a browser user to create a lightsaber effect.

Using [this](http://blogs.sitepointstatic.com/examples/tech/canvas-curves/bezier-curve.html) example from Craig Butler
I learned how to create controls and linetypes.  With guidance from my [mentor](https://github.com/cade) 
he demoed how to fill in the shape. From there I add a drop shadow (for lightsaber glow).

Also, using Boaz Senders [rotoscope example](http://static.bocoup.com/code/popcorn.js/Rotoscoper/) to capture the roto for each image.

Conclusion
----------
Combining these two methods I was able to demonstrate that it is possible to rotoscope in the browser. Yeah!

To Further develop:
-----
Rewrite app.js to work with a proper Database and not use locaStorage(), would like to store control points
and not the image itself, a png.
Export out a resulting coposited movie.
ect...
