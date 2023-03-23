---
layout: default
title: a suite of projects and applications
---

D-BL offers a roof to a suite of projects and applications related to bobbin lace.
Currently, the main focus is on continuous bobbin lace though decorated braids can also benefit.
The applications are available with an open source license and the documentation has a creative-commons license. 

Use cases
=========

* Browse lace grounds (both classic as experimental)
* Design new lace grounds (or alter a found ground) 
* Explore various stitches in those grounds
* Prickings for lace grounds

Site map
========

* Galleries with predefined patterns linked to GroundForge  (where you can play with stitches and thread colors)
    * [tesselace](/tesselace-to-gf/) (pair diagrams without stitches)
    * [sampler](/gw-lace-to-gf/) of Gertrude Whiting (traditional grounds, not all patterns can be used)
    * [MAE-gf](/MAE-gf/) All kinds of patterns, traditional and innovative
    * [nets](/GroundForge/nets) page with [samples](/MAE-gf/docs/stitches) (a few basic pair diagrams with mirrored and/or rotated versions of a single stitch)
* Traditional grounds in the galleries above
    * rose/virgin ground on [tesselace](/tesselace-to-gf/#rose-family),
      on [MAE-gf](/MAE-gf/docs/roses), [GW-A2-P71](/GroundForge/print?whiting=A2_P71&tile=831,4-7,-5-&headside=d,-,c,-&footside=b,-,a,-&footsideStitch=ctctt&patchWidth=9&patchHeight=10&k1=lctctt&d1=ct&c1=ctct&b1=ct&a1=rctctt&d2=ctct&b2=ctct&k3=lctctt&c3=ctct&a3=rctctt&tileStitch=ctct&headsideStitch=ctctt&shiftColsSW=-2&shiftRowsSW=2&shiftColsSE=2&shiftRowsSE=2),
      ...
    * paris/kat [nets](/GroundForge/nets), ...
    * ...
* DIY new/customized patterns
  * links from the galleries above leading to the [tiles page](/GroundForge/tiles), sometimes via the [print/pdf friendly page](/GroundForge/print)
    * get thread diagrams for different stitches (diagrams section)
    * modify the pair diagrams (edit pattern section)
    * use thread diagrams as pair diagrams (Droste effect)
  * create patterns with
    * [mirrored and rotated](/GroundForge/symmetry) repeats (no transformation to pair diagrams)
    * Free [tile](/GroundForge/tiles) boundaries (edit pattern section)
  * move pin positions
    * see: prickings - downloadable - pair diagrams DIY
    * to be developed tutorials for other diagrams and inkscape plugins
* prickings
    * plugins for Inkscape (a 3rd party editor)
        * [installation](/inkscape-bobbinlace/)
        * dotted grids ([regular](/inkscape-bobbinlace/Regular-Grids) / [polar](/inkscape-bobbinlace/Polar-Grids) )
        * pair diagrams [regular / polar](/inkscape-bobbinlace/Ground-from-Template)
    * downloadable (for any 3rd party vector based editor)
        * [polar](/polar-grids/) dotted grids
        * pair diagrams (the whole swatch changes when changing a single repeat, the dance leader)
            * follow SVG links from [tesselace](/tesselace-to-gf/) pages, download and adjust angle and/or pin positions
            * DIY based on this url example
              ```
              https://d-bl.github.io/GroundForge/sheet.html?patch=5-M9,-50F;checker
              ```  
              _to be explained somewhere else_:  
              value for `patch` is `tile` value of other urls  
              `checker` can also be `brick` (note that patterns may have other tilings)  

---
[same image with links](images/site-map.svg)
![](images/site-map.svg)

---

Contact
=======

* [Contact form](https://groundforge.wordpress.com/): a private message to the support team (no account required)
* [Issues](https://github.com/d-bl/GroundForge/issues) on GitHub: list of known bugs and desired features (browse without account)
* [Discord](https://discord.com/channels/1074087445169184940) channel: chat in text, voice and/or video (visible only with an account)
* [Instagram](https://www.instagram.com/explore/tags/groundforge/): show off patterns and samples (partially visible without account, please tag your posts with `#groundforge`; mixed with some black smithing)

History of D-BL and GroundForge
===============================

D-BL started as DiBL under google-code.
When a new provider was needed an account by that name was already taken and the _i_ replaced by a dash.

The polar grids were exercises to master new technology.

Timeline
--------

* **end of 2001**:  
  The first release for [flanders](/flanders/) thread diagrams
* **before 2008**:  
  A [desktop application](https://github.com/d-bl/bobbinwork/wiki)
  with a few more traditional grounds, each predefined with a tedious process and some custom XML.
  This had a textual tree view of the diagrams, drilling down from spider to stitches to cross/twist.
* **2013**: 
  * Discovery of PhD research in progress that lead to [tesselace](https://web.archive.org/web/20221127125331/https://tesselace.com/)
  * Redesign using SVG, a combination of a [web application](/DiBL/grounds/index.html) and inkscape plugins  
    this allowed again more patterns but still had a limited choice of stitches 
* **fall 2015**:  
  Proof of concept with [force graphs](#glossary),
  Inspiration for this [cheat-sheet](/GroundForge/images/matrix-template.png).  
  Both reduced the burden of complex GUIs with file IO and parsing complex data structures.
* **2017**:
  * Discovery of Jo Edkins' [index](http://www.theedkins.co.uk/jo/lace/whiting/index.htm)
    on an out-copyright book, the [sampler](https://www.metmuseum.org/blogs/collection-insights/2018/gertrude-whiting-bobbin-lace-sampler)
    by Gertrude Whiting.
  * Request for a guinea pig to review GroundForge.
  * Discovery of the Droste effect: using thread diagrams as pair diagrams.
* **August 2021**:
  * tutorials for a workshop at IOLI UnConn 2.0 hosted by _the lace museum_
  * birth of the nets page
* **May 2022**:
  birth of the pdf/print friendly page
* **January 2023**:
  birth of the symmetry page,  
  it needs redevelopment from scratch to translate the pair diagrams into thread diagrams

FAQ
===

* ...

Glossary
========

See also [icons](GroundForge/icons)

* **D-BL** - **D**iagrams for **B**obbin **L**ace - an umbrella for a suite of projects/applications related to bobbin lace.
* **force graph algorithms** - evenly distribute nodes and links, and organize items so that links are of a similar length. These algorithms balance attraction and repulsive forces. 
* **GitHub** - hosting service for software development and version control. Free for open source projects.
* **GroundForge** - a suite of tools for continuous bobbin lace. Focussing on transforming pair diagrams to thread diagrams.
* **stitch** - interaction between two pairs, for the application a stitch may consist of stitch-pin-stitch