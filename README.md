# Awesome C #

A curated list of C good stuff. I give preference to [free software][13] for code, and sellers who aren't evil for physical resources.

This is released under the GNU Free Documentation License - its text is provided in the LICENSE file.

Compilers
=========

* [Clang][38] - A C compiler for LLVM. Supports C11. [NCSA][39].
* [GCC][40] - Provides a C compiler as part of its compiler set. Supports C11 and OpenMP. [GNU GPL3][41].
* [TCC][42] - Tiny C Compiler; a small, fast C compiler. Supports C99 (except complex types). [GNU GPL2][8].


Database
========

* [leveldb][46] - A simple persistent key-value store. Available via [clib][26]. [3-clause BSD][6].
* [MariaDB][25] - A robust, scalable and reliable SQL server, designed to be a drop-in replacement for MySQL. [3-clause BSD][6].
* [Redis][51] - An advanced key-value store. [3-clause BSD][6].
* [SQLite][22] - A self-contained, serverless, zero-configuration, transactional SQL database engine with a C interface. Public domain.
* [UnQLite][23] - A self-contained, serverless, zero-configuration, transactional NoSQL engine with a C interface. [FreeBSD][24].

Editors
=======

These are specifically fancier, IDE-type editors. If you want a programmer's text editor, and yours *doesn't* support C, I'd be quite surprised.

* [Anjuta DevStudio][42] - The GNOME IDE. [GNU GPL3][41].
* [CodeLite][45] - A cross-platform IDE. [GNU GPL2][8].
* [Geany][43] - A very small and fast IDE. [GNU GPL2][8].
* [KDevelop][44] - The KDE IDE. [GNU GPL2][8].


Game Programming
================

* [Allegro][48] - A cross-platform, video game development and multimedia library. [zlib][49].
* [SDL][50] - A cross-platform library designed to provide low-level access to audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [zlib][49].


Generic Programming
===================

* [SGLIB][30] - Simple Generic Library; an implementation of a range of generic programming structures and idioms in C. No license specified.


Graphical User Interface
========================

These are specifically [widget toolkits][12].

* [Elementary][17] - A widget toolkit. Part of the [EFL][18]. [GNU LGPL2.1][15].
* [GTK+][14] - A cross-platform widget toolkit. [GNU LGPL2.1][15].
* [IUP][16] - Another cross-platform widget toolkit. [Expat][11].
* [Tk][19] - A basic widget toolkit. Part of Tcl/Tk. [Tcl/Tk License][20].
* [XForms Toolkit][21] - A widget toolkit designed for the XWindow system. [GNU LGPL2.1][15].

JSON
=======

* [Jannson][53] - A C library for encoding, decoding and manipulating JSON. [Expat][11].


Learning and Tutorials
======================

This is a list of resources for learning C programming in general, or something useful relating to C programming.

## Online ##

* [Writing efficient C and C code optimization][33]
* [The lost art of C structure packing][34]

## Physical ##

* [21st Century C][35] - A very good *second* programming book on C.
* [Expert C Programming: Deep C Secrets][55] - An interesting, in-depth and *entertaining* look at the innards of C.
* [Understanding and Using C Pointers][36] - An in-depth resource on pointers in C.

Networking
==========

* [ZeroMQ][52] - High-performance message passing networking library. [GNU LGPL3][41].


Numerical
=========

* [GSL][47]: The GNU Scientific Library; a sophisticated numerical library. [GNU GPL3][41].


Package Manager
===============

* [clib][26] - Something of a package manager for C. Comes with a [bunch of libraries of its own][27]. [Expat][11].

Parallel Programming
====================

* [OpenMP][37] - A set of C pragmas designed to allow for easy parallelization of code. Standard (licensing not applicable).


Standard Libraries
==================

This includes both C standard library implementations and libraries seeking to provide most of what a 'modern' standard library would have (containers, string processing, etc).

* [Bionic][4] - Google's C standard library, developed for Android. [3-clause BSD][6]
* [dietlibc][9] - A C standard library designed for the smallest possible binaries. [GNU GPL2][8].
* [GLib][1] - A library of utility functions and structures, designed to be portable, efficient and powerful. [GNU LGPL3][5].
* [glibc][57] - The GNU C Library; an implementation of the C standard library. [GNU LGPL3][5].
* [GIO][2] - A modern and easy-to-use VFS API. [GNU LGPL3][5].
* [GObject][3] - An object-oriented system and object model for C. [GNU LGPL3][5].
* [klibc][7] - A minimalistic subset of the standard C library. [GNU GPL2][8] or [3-clause BSD][6].
* [libU][28] - A small library of basic utilities, including memory allocation, string manipulation and logging. [3-clause BSD][6]. 
* [musl][10] - A standard C library, compatible with POSIX 2008 and C11. Designed for static linking. [Expat][11].

Testing
=======

* [CUnit][34] - A unit testing framework for C. [GNU GPL2][8].


Utilities
=========

This is a 'catch-all' category for anything that doesn't fit well anywhere else.

* [libPhenom][31] - An eventing framework for building high-scalability and high-performance systems. [Apache2.0][32].
* [libuv][56] - Cross-platform asynchronous I/O. [Expat][11].
* [Ragel][54] - A DSL for state machines that compiles to C. [GNU GPL3][41].
* [SDS][29] - Simple Dynamic Strings; a library for handling C strings in a simpler way, but one that is compatible with normal C string functions. Available via [clib][26]. [FreeBSD][24].


[1]: https://developer.gnome.org/glib/
[2]: https://developer.gnome.org/gio/
[3]: https://developer.gnome.org/gobject/stable/
[4]: https://github.com/android/platform_bionic
[5]: http://www.gnu.org/licenses/lgpl.html
[6]: http://directory.fsf.org/wiki/License:BSD_3Clause
[7]: ftp://ftp.kernel.org/pub/linux/libs/klibc/
[8]: http://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[9]: http://www.fefe.de/dietlibc/
[10]: http://www.musl-libc.org/
[11]: http://directory.fsf.org/wiki/License:Expat
[12]: http://en.wikipedia.org/wiki/Widget_toolkit
[13]: http://en.wikipedia.org/wiki/Free_software
[14]: http://www.gtk.org/
[15]: http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html
[16]: http://webserver2.tecgraf.puc-rio.br/iup/
[17]: http://docs.enlightenment.org/auto/elementary/
[18]: http://www.enlightenment.org/p.php?p=about/libs
[19]: http://www.tcl.tk/
[20]: http://www.tcl.tk/software/tcltk/license.html
[21]: http://xforms-toolkit.org/
[22]: http://www.sqlite.org/
[23]: http://unqlite.org/
[24]: http://directory.fsf.org/wiki?title=License:FreeBSD
[25]: https://mariadb.com/
[26]: https://github.com/clibs/clib
[27]: https://github.com/clibs/clib/wiki/Packages
[28]: http://www.koanlogic.com/libu/
[29]: https://github.com/antirez/sds
[30]: https://github.com/stefanct/sglib
[31]: http://facebook.github.io/libphenom/index.html
[32]: http://directory.fsf.org/wiki/License:Apache2.0
[33]: http://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization
[34]: http://www.catb.org/esr/structure-packing/
[35]: http://shop.oreilly.com/product/0636920033677.do
[36]: http://shop.oreilly.com/product/0636920028000.do
[37]: http://openmp.org/wp/about-openmp/
[38]: http://clang.llvm.org/
[39]: http://directory.fsf.org/wiki/License:IllinoisNCSA
[40]: https://gcc.gnu.org/
[41]: http://www.gnu.org/licenses/gpl.html
[42]: http://anjuta.org/
[43]: http://www.geany.org/
[44]: https://www.kdevelop.org/
[45]: http://www.codelite.org/
[46]: https://github.com/clibs/leveldb
[47]: http://www.gnu.org/software/gsl/
[48]: http://alleg.sourceforge.net/readme.html
[49]: http://directory.fsf.org/wiki/License:Zlib
[50]: https://www.libsdl.org/
[51]: http://redis.io/
[52]: http://zeromq.org/
[53]: http://www.digip.org/jansson/
[54]: http://www.colm.net/open-source/ragel/
[55]: http://dl.acm.org/citation.cfm?id=179241
[56]: https://github.com/libuv/libuv
[57]: http://www.gnu.org/software/libc/
