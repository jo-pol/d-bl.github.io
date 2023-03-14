---
layout: default
title: d-bl - Diagrams for Bobbin lace
---

d-bl - Diagrams for Bobbin lace
===============================

D-BL offers a roof to a suite of projects/applications related to bobbin lace.
Currently, the main focus is on continuous bobbin lace though decorated braids can also benefit.
The applications are available with an open source license and the documentation has a creative-commons license. 

Use cases
---------

* Browse lace grounds (both classic as experimental)
* Design new lace grounds (or alter a found ground) 
* Explore various stitches in those grounds
* Prickings for lace grounds

Site map
--------

* explore pair/thread diagrams
    * predefined patterns
        * [tesselace](/tesselace-to-gf/) (pair diagrams without stitches)
        * [sampler](/gw-lace-to-gf/) of Gertrude Whiting (traditional grounds, not all patterns can be used)
        * [MAE-gf](/MAE-gf/) All kinds of patterns, traditional and innovative
        * [nets](/GroundForge/nets) page (a few basic pair diagrams with mirrored and/or rotated versions of a single stitch)
    * DIY new/customized patterns ([edit pattern section](/GroundForge/tiles) _to be isolated on a separate page_, [how to](/GroundForge-help/Advanced))  
      to adjust a pattern start with a link from the sets of pages above
* prickings
    * Inkscape plugins (a 3rd party editor)
        * [installation](/inkscape-bobbinlace/)
        * dotted grids ([regular](/inkscape-bobbinlace/Regular-Grids) / [polar](/inkscape-bobbinlace/Polar-Grids) )
        * pair diagrams [regular / polar](/inkscape-bobbinlace/Ground-from-Template)
    * downloadable (for any 3rd party vector based editor)
        * [polar](/polar-grids/) dotted grids
        * pair diagrams
            * follow SVG links from [tesselace](/tesselace-to-gf/) pages, download and adjust angle and/or pin positions
            * DIY based on this url example
              ```
              https://d-bl.github.io/GroundForge/sheet.html?patch=5-M9,-50F;checker
              ```  
              _to be explained somewhere else_:  
              value for `patch` is `tile` value of other urls  
              `checker` can also be `brick` (note that patterns may have other tilings)  

Contact
-------

* [Contact form](https://groundforge.wordpress.com/): a private message to the support team (no account required)
* [Issues](https://github.com/d-bl/GroundForge/issues) on github: list of known bugs and desired features (browse without account)
* [Discord](https://discord.com/channels/1074087445169184940) channel: chat in text, voice and/or video (visible only with an account)
* [Instagram](https://www.instagram.com/explore/tags/groundforge/): show off patterns and samples (partially visible without account, please tag your posts with `#groundforge`; mixed with some black smithing)

History of D-BL and GroundForge
-------------------------------

D-BL started as DiBL under google-code.
When a new provider was needed an account by that name was already taken and the _i_ replaced by a dash.

The polar grids were exercises for new technology.

Timeline

* **end of 2001**:  
  The first release for [flanders](/flanders/) thread diagrams
* **before 2008**:  
  A desktop application with a few more traditional grounds, each predefined with a tedious process and some custom XML. 
* **2013**:  
  Redesign using SVG, a combination of a web application and inkscape plugins  
  this allowed again more patterns but still had a a limeted choice of stitches 
* **fall 2015**:  
  Proof of concept with [force graphs](#glossary),
  Inspiration for this [cheat-sheet](/GroundForge/images/matrix-template.png).  
  Both reduced the burden of complex GUIs with file IO and parsing complex data structures.
* **2017**:
  * Discovery of Jo Edkins' index on an out-copyright book, the sampler of Gertrude Whiting.
  * Request for a guinea pig to review GroundForge.
  * Discovery of the Droste effect: using thread diagrams as pair diagrams.
* **August 2021**:
  birth of the nets page
* **May 2022**:
  birth of the pdf/print friedly page
* **January 2022**:
  birth of symmetry page,  
  it needs redevelopment from scratch to translate the pair diagrams into thread diagrams

FAQ
---

* ...

Glossary
--------

* **D-BL** - **D**iagrams for **B**obbin **L**ace - an umbrella for a suite of projects/applications related to bobbin lace.
* **force graph algorithms** - evenly distribute nodes and links, and organize items so that links are of a similar length. These algorithms balance attraction and repulsive forces. 
* **github** - hosting service for software development and version control. Free for open source projects.
* **GroundForge** - a suite of tools for continuous bobbin lace. Focussing on transforming pair diagrams to thread diagrams.
* **stitch** - interaction between two pairs, for the application a stitch may consist of stitch-pin-stitch