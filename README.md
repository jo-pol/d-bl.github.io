[Overview](https://d-bl.github.io/) of applications for bobbin lace makers.


Domain knowledge
================

Domain knowledge for contributors to any of the projects with little knowledge about (grid based types of) bobbin lace.

## General

The tools provided by D<sub>i</sub>BL are dealing with the following major types of diagrams:

* color coded pair diagrams
* thread diagrams
* prickings

Both types of diagrams are two-in two-out directed graphs. In a pair diagram one line represents two threads: a pair. In a color coded pair diagram the color of an intersection tells a lace maker which stitch to make: how to weave or plait the pairs at that point before grabbing one or two other pairs.

In thread diagrams interruptions of the lines emulate the over under effect of the woven threads. [GroundForge](https://d-bl.github.io/GroundForge/) provides topological neutral pair and thread diagrams and a pattern sheet with geometrical variations of the neutral pair diagram. Play around with stitches to see what happens, the most common stitches are tc, ctc and tctc. Note that threads follow another path than a pair when choosing an odd number of c's for a stitch.

A pricking is usually just black and white and applies a third abstraction level. At least it contains dots where the pins should go through the cardboard into the (very stiff) pillow to support the stitches and keep the lace in shape while creating it. Annotations between the dots should keep the lace maker on track.

See also this [overview of diagrams](https://d-bl.github.io/GroundForge/help/#approach), with images but aiming at users (read: lace designers) of GroundForge rather than developers.

## Thread styles

The thread style plugin is a supplement for the thread diagrams of the [predecessor](http://jo-pol.github.io/DiBL/grounds/) of GroundForge. The predecessor generates diagrams from templates, only one type of diagram at a time, the diagrams are not topological neutral and only a limited set of stitches is supported. GroundForge assigns line numbers to classes of line segments to paint the threads and no longer needs the plugin.

## Grounds-from-templates / pattern sheets

The ground-from-template plugin is a predecessor of the pattern sheets provided via the TessaLace index of GroundForge. The sheets should work for other SVG editors than InkScape alone. Each sheet may contain multiple patterns with the same topology, the intersections on these sheets are bound to a square grid. The patches on one sheet can be reshaped into one another by nudging the positions of the intersections, other variations are possible by ignoring the square grid.
