# TI-83+ Personal Program Archive

This project contains programs I coded directly on my TI-83+ graphing calculator between roughly 2001 and 2004.
At the time, there didn't exist (or I didn't have) programs and applications that perform the very basic (pun intended) functionality in these custom programs.
As such, these programs probably aren't very useful to anybody today.
However, I wanted to archive them for posterity, so here they are.

I transferred the programs from my TI-83+ using a TI Graphlink USB device and the [TiLP](http://lpg.ticalc.org/prj_tilp/) software on Ubuntu Linux 16.04 LTS.
The raw 8Xp files are located in the `8Xp` directory.

In order to view the TI-BASIC source on the computer, I decoded the 8Xp files using [SourceCoder](https://www.cemetech.net/sc/).
The decoded sources are located in the `src` directory.
These sources are what you see when you load the programs onto a TI-83+ and view them with `PRGM -> EDIT`.


## Programs

* `AREAVOL`: Print area and volume formulations for some geometric shapes - triangle, cylinder, pyramid, sphere, and cone.
* `DELVAR`: Delete cached variables from calculator - A-Z, theta, L1-L6, etc.
* `QUADEQ`: Compute solutions to the quadratic formula by inputting `A`, `B`, and `C` (for a polynomial `A`x<sup>2</sup> + `B`x + `C`).
* `TEMP`: Convert between Celsius, Fahrenheit, and Kelvin temperature scales.


## Licensing

BSD-3-Clause, (c) 2004, Connor Imes.
