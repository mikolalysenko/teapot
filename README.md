teapot
======

[The Utah teapot](http://en.wikipedia.org/wiki/Utah_teapot) needs no introduction, but for [the unintiated here is a brief history](http://www.sjbaker.org/wiki/index.php?title=The_History_of_The_Teapot).

<img src="https://raw.github.com/mikolalysenko/teapot/master/CACMcover.512.jpg" width=40% style="margin-left:auto; margin-right:auto;">

Installation
============
Via npm:

    npm install teapot
    
Then you can use the mesh in your projects as follows:

    var teapot = require("teapot");
    drawMesh(teapot.cells, teapot.positions);

Credits
=======
(c) 1984 Matin Newell.  Public Domain.

CACM cover image by James Arvo and David Kirk.

CommonJS port maintained by Mikola Lysenko