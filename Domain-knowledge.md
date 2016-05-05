Domain knowledge for contributors with little knowledge about (grid based types of) bobbin lace.

# General

The tools provided by DiBL are dealing with at least the following types of diagrams: color coded pair diagrams thread diagrams and prickings. The diagrams are two-in two-out directed graphs. In a pair diagram one line represents two threads: a pair. In a color coded pair diagram the color of an intersection tells a lace maker which stitch to make: how to weave or plait the pairs at that point before grabbing one or two other pairs.

A pricking is usually just black and white and applies a third abstraction level. At least it contains dots where the pins go should go through the cardboard to support the stitches and keep the lace in shape while creating it. Annotations between the dots should keep the lace maker on track.

In thread diagrams interruptions of the lines emulate the over under effect of the woven threads. [GroundForge](https://d-bl.github.io/GroundForge/) provides topological neutral pair and thread diagrams and a pattern sheet with geometrical variations of the neutral pair diagram. Follow the instructions and play around to see what happens, the most common stitches are tc, ctc and tctc. Note that threads follow another path than a pair when choosing an odd number of c's for a stitch.

# Thread styles

The thread style plugin is a supplement for the thread diagrams of the [predecessor](http://jo-pol.github.io/DiBL/grounds/) of GroundForge. The predecessor generates diagrams from templates, only one type of diagram at a time and the diagrams are not topological neutral. GroundForge assigns line numbers to classes of line segments to paint the threads and no longer needs the plugin, but it doesn't support the diagonal patterns of the [Bridges paper](https://tesselace.com/research/bridges2012/).

# Grounds from templates / pattern sheets

The ground-from-template plugin is a predecessor of the [pattern sheets](https://github.com/d-bl/GroundForge/tree/gh-pages/patterns) provided along the pair and thread diagrams on GroundForge. The uploaded pattern sheets should work for other editors than InkScape alone. Each sheet may contain multiple patterns with the same topology. The patches can be [reshaped](https://github.com/d-bl/GroundForge/wiki/Reshape-Patterns) into one another and intermediate versions by nudging the positions of the intersections.
