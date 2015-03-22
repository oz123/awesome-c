# Awesome C #

A curated list of C good stuff. This list contains *only* [free software][13] for code, and sellers who aren't evil for physical resources.

This is released under the GNU Free Documentation License - its text is provided in the LICENSE file.

Compilers
=========

* [Clang][38] - A C compiler for LLVM. Supports C11. [NCSA][39].
* [CompCert][269] - A fully-verified C compiler. Supports almost all of C89. [GNU GPL2.1][8].
* [GCC][40] - Provides a C compiler as part of its compiler set. Supports C11 and OpenMP. [GNU GPL3][41].
* [PCC][74] - A very old C compiler. Supports C99. [Various licenses][75], all free.
* [TCC][58] - Tiny C Compiler; a small, fast C compiler. Supports C99 (except complex types). [GNU GPL2.1][8].

Crypto
======

* [GnuTLS][112] - A secure communication library, implementing SSL, TLS and DTLS. [GNU LGPL2.1][15].
* [libgcrypt][142] - A general-purpose cryptography library, with a range of available ciphers. [GNU GPL2.1][8] and [GNU LGPL2.1][15].
* [LibreSSL][143] - A BSD fork of OpenSSL. Various licenses, all semi-free.
* [OpenSSL][110] - Implementation of the SSL and TLS protocols, and also includes a cryptography library. [Dual Licensed under the OpenSSL License and the SSLeay License][111]
* [libsodium][198] - A modern and easy-to-use crypto library. [Expat][11].

Database
========

This lists databases and data stores with C APIs.

* [Hiredis][201] - A minimalistic client library for Redis. [3-clause BSD][6].
* [LMDB][105] - An ultra-fast, ultra-compact key-value embedded data store. [newOpenLDAP][106].
* [MariaDB][25] - A robust, scalable and reliable SQL server, designed to be a drop-in replacement for MySQL. [3-clause BSD][6].
* [mongo-c-driver][233] - A high-performance client library for [MongoDB][234]. [Apache2.0][32].
* [PostgreSQL][121] - A powerful object-relational database system. [PostgreSQL licence][122]
* [Redis][51] - An advanced key-value store. [3-clause BSD][6].
* [sophia][244] - A modern, embeddable key-value database. [FreeBSD][24].
* [SQLite][22] - A self-contained, serverless, zero-configuration, transactional SQL database engine with a C interface. Public domain.
* [UnQLite][23] - A self-contained, serverless, zero-configuration, transactional NoSQL engine with a C interface. [FreeBSD][24].

Editors
=======

These are specifically fancier, IDE-type editors. If you want a programmer's text editor, and yours *doesn't* support C, I'd be quite surprised.

* [Anjuta DevStudio][42] - The GNOME IDE. [GNU GPL3][41].
* [Code::Blocks][249] - An extensible, configurable IDE supporting C. [GNU GPL3][41].
* [CodeLite][45] - A cross-platform IDE. [GNU GPL2.1][8].
* [Eclipse][258] - An IDE written in Java. [EPL][259].
* [Geany][43] - A very small and fast IDE. [GNU GPL2.1][8].
* [KDevelop][44] - The KDE IDE. [GNU GPL2.1][8].
* [NetBeans][260] - Another IDE written in Java. [GNU GPL2.1][8] or [CDDL][261].

Environments
============

This is a list of technologies designed to bring Windows into the 21st century with respect to support for C.

* [Cygwin][253] - Designed to emulate a POSIX-compatible environment extensively under Windows. [Various licenses, all free][254].
* [MinGW][251] - A minimalist environment for C development on Windows. [Various licenses, all free][252].


Frameworks
==========

This section has big libraries that provide data structures and other stuff you expect of a 'modern' standard library.

* [APR][78] - Apache Portable Runtime; another library of cross-platform utility functions. [Apache2.0][32].
* [C Algorithms][88] - A collection of common algorithms and data structures for C. [ISC][61].
* [EFL][119] - A large collection of useful data structures and functions. Various licenses, all free.
* [GLib][1] - A library of utility functions and structures, designed to be portable, efficient and powerful. [GNU LGPL3][5].
* [GIO][2] - A modern and easy-to-use VFS API. [GNU LGPL3][5].
* [GObject][3] - An object-oriented system and object model for C. [GNU LGPL3][5].
* [libnih][93] - A lightweight library of C functions and structures. [GNU GPL2.1][8].
* [libU][28] - A small library of basic utilities, including memory allocation, string manipulation and logging. [3-clause BSD][6].
* [qlibc][277] - A simple and powerful C library, designed as a replacement for GLib while focusing on being small and light. [qLib license][278] (similar to [FreeBSD][24]).
* [stb][114] - A range of single-file libraries for C. Public domain.

Game Programming
================

## Engines ##

These are provided as examples of C game programming code.

* [Corange][101] - A game engine in pure C. [FreeBSD][24].
* [ioquake3][107] - The Quake3 engine, freed at last. [GNU GPL2.1][8]
* [Quake][225] - The Quake engine. [GNU GPL2.1][8].
* [Quake2][221] - The Quake2 engine. [GNU GPL2.1][8].

## Resources ##

These are libraries of all sorts that are useful for game programming.

* [Allegro][48] - A cross-platform, video game development and multimedia library. [zlib][49].
* [CSFML][90] - A binding for [SFML][91] in C. [zlib][49].
* [FreeGLUT][99] - An alternative to the OpenGL Utility Toolkit. Allows the creation and management of windows with OpenGL contexts. [X11][100].
* [GLFW][98] - A multi-platform library for creating windows with OpenGL contexts. [zlib][49].
* [RetroArch][231] - The reference frontend for [libretro][232]. [GNU GPL3][41].
* [SDL][50] - A cross-platform library designed to provide low-level access to audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [zlib][49].


Generic Programming
===================

* [klib][76] - Small and lightweight implementations of common algorithms and data structures. [Expat][11].
* [SGLIB][30] - Simple Generic Library; an implementation of a range of generic programming structures and idioms in C. [GNU GPL3][41].

Graphics
========

* [Cogl][127] - A GPU graphics and utilities API. [GNU LGPL2.1][15].
* [Clutter][126] - A UI library based on OpenGL. [GNU LGPL2.1][15].
* [libjpeg][192] - A library for reading and writing JPEG files. Free software license (check the source).
* [libjpeg-turbo][193] - A faster library for reading and writing JPEG files. [Various licences][194].
* [libxmi][174] - A function library for rasterizing 2D vector graphics. [GNU GPL3][41].
* [mozjpeg][200] - An improved JPEG encoder. [3-clause BSD][6].
* [OpenGL][147] - The industry standard for high-performance graphics, with a native C binding. [Various licenses][148].
* [SDL2](https://www.libsdl.org/) - Simple DirectMedia Layer is a cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. [zlib](http://www.zlib.net/)

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

* [Jansson][53] - A C library for encoding, decoding and manipulating JSON. [Expat][11].
* [jsmn][120] - A minimalistic JSON parser. [Expat][11].
* [json-c][220] - A library for working with JSON. [Expat][11].
* [WJElement][77] - Advanced JSON manipulation library, with support for JSON Schema. [GNU GPL3][41].
* [YAJL][60] - A fast C JSON streaming parser library. [ISC][61]


Learning, Reference and Tutorials
=================================

This is a list of resources for learning C programming in general, or something useful relating to C programming.

## Online ##

Reference
---------

* [C: A Reference Manual 5E][181] (online PDF)
* [CERT C Coding Standard][266]
* [C FAQ - comp.lang.c Frequently Asked Questions][262]
* [Draft C11 standard][247]
* [Robert Pike's notes on programming in C][273]
* [The C Programming Language 2E][7] (online PDF)

Beginner
--------

* [A tutorial on pointers][213]
* [Building C Projects][208]
* [C Primer Plus 5E][184] (online PDF)
* [C Programming Wikibook][248] (online PDF)
* [Introduction to 'fun' C][279]
* [POSIX Threads Programming tutorial][263] (a little dated, but most of it is still valid and useful)
* [The GNU C Programming Tutorial][212] (online PDF)
* [Templating in C][267]

Intermediate
------------

* [8 gdb tricks you should know][206]
* [10 C99 tricks][257]
* [Diving into concurrency: trying out mutexes and atomics][202]
* [Introduction to OpenMP][207] (video)
* [OpenMP tutorial][264] (for the OpenMP3 standard)
* [memcpy vs memmove][205]
* [MPI tutorial][265]
* [Object-Oriented Programming with ANSI C][185] (online PDF)
* [The lost art of C structure packing][34]
* [What a C programmer should know about memory][271]
* [What every C programmer should know about undefined behaviour][275]

Advanced
--------

* [A quick tutorial on implementing and debugging malloc, free, calloc, and realloc][204]
* [Bit twiddling hacks][73]
* [I do not know C][272]
* [Implementing smart pointers for the C programming language][240]
* [Inline functions in C][245]
* [Some dark corners of C][210]
* [Writing efficient C and C code optimization][33]
 
Self-study courses
----------

* [C Programming Language Certified Associate preparation course][211]

## Physical ##

Reference
---------

* [C Pocket Reference][182] - A concise reference book for C99.

Beginner
--------

* [C Programming: A Modern Approach][64] - An excellent book to learn the basics from C from.
* [Head First C][102] - A 'head-first' style book for learning C.

Intermediate
------------

* [21st Century C][35] - A very good *second* programming book on C.
* [Understanding and Using C Pointers][36] - An in-depth resource on pointers in C.
* [ZeroMQ][183] - A book for using ZeroMQ with C.

Advanced
--------

* [Expert C Programming: Deep C Secrets][55] - An interesting, in-depth and *entertaining* look at the innards of C.

Multimedia
==========

* [FFMPEG][63] - A complete, cross-platform solution to record, convert and stream audio and video. [GNU LGPL2.1][15], with some parts under [GNU GPL2.1][8].
* [GStreamer][123] - A framework for audio and visual media. [GNU LGPL2.1][15].
* [lodepng][69] - A simple PNG image decoder and encoder, requiring no other dependencies. [3-clause BSD][6].

Networking and Internet
=======================

* [asnlc][138] - A compiler of ASN.1 specifications into C source code. [FreeBSD][24].
* [czmq][226] - A high-level binding for ZeroMQ. [MPL2.0][227]
* [GNU adns][155] - An advanced, easy-to-use, asynch-capable DNS client library and utilities. [GNU GPL3][41].
* [GNU SASL][160] - An implementation of the Simple Authentication and Security Layer and a few common SASL mechanism. [GNU GPL3][41].
* [GnuTLS][112] - A secure communication library, implementing SSL, TLS and DTLS. [GNU LGPL2.1][15].
* [gumbo-parser][196] - An HTML5 parsing library in C99. [Apache2.0][32].
* [http-parser][197] - An HTTP request/response parser. [Expat][11].
* [libcurl][65] - A client-side URL transfer library, supporting a wide range of formats. [curl license][66]
* [LibEtPan][222] - A mail library providing an efficient network for IMAP, SMTP, POP and NNTP. [3-clause BSD][6].
* [libev][144] - Yet another event loop. [FreeBSD][24].
* [libevent][124] - An event loop replacement for network servers. [3-clause BSD][6].
* [libgss][161] - Generic Security Service. [GNU GPL3][41].
* [libhttpd][166] - A library to add basic web server capabilities to an application or embedded device. [GNU GPL3][41].
* [libidn][164] - An implementation of the Stringprep, Punycode and IDNA specifications. [GNU LGPL2.1][15].
* [libmicrohttpd][165] - A small C library that makes it easy to run an HTTP server as part of another application. [GNU LGPL2.1][15].
* [libsoup][167] - A GNOME HTTP client/server library. Uses GObject. [GNU LGPL2.1][15].
* [LibreSSL][143] - A BSD fork of OpenSSL. Various licenses, all semi-free.
* [lwan][199] - An experimental, scalable, high-performance HTTP server. [GNU GPL2.1][8].
* [mihl][169] - A library for implementing an embedded HTTP server. [FreeBSD][24].
* [mongoose][171] - Embedded web server for C. [GNU GPL2.1][8].
* [nanomsg][139] - A C-based implementation of ZeroMQ. [Expat][11].
* [neon][168] - An HTTP and WebDAV client library with a C interface. [GNU LGPL3][5].
* [onion][170] - HTTP server library, designed to be easy to use. [Apache2.0][32].
* [OpenSSL][110] - Implementation of the SSL and TLS protocols, and also includes a cryptography library. [Dual Licensed under the OpenSSL License and the SSLeay License][111]
* [oSip][179] - A SIP implementation in C without additional dependencies. [GNU GPL3][41].
* [socket99][203] - A wrapper library for the BSD sockets API.
* [Tox][145] - A communication platform, designed to be a Skype-killer. [GNU GPL3][41].
* [twitc][237] - A mini C library for interacting with the Twitter OAuth API. [GNU GPL3][41].
* [ZeroMQ][52] - High-performance message passing networking library. Implemented in C++, but has a C interface. [GNU LGPL3][5].

Numerical
=========

* [apophenia][188] - A library for statistical and scientific computing. [GNU GPL2.1][8] with some [exceptions][189].
* [ATLAS][137] - Automatically Tuned Linear Algebra Software. [3-clause BSD][6].
* [BLAS][135] - Basic Linear Algebra Subprograms; a set of routines that provide vector and matrix operations. [BLAS license][136]
* [CRlibm][268] - Correctly Rounded mathematical library; a modern implementation of a range of numeric routines. [GN LGPL3][5].
* [FFTW][70] - The Fastest Fourier Transform in the West; a highly-optimized fast Fourier transform routine. [GNU GPL2.1][8].
* [FLINT][255] - Fast Library for Number Theory; a library supporting arithmetic with numbers, polynomials, power series and matrices, among others. [GNU GPL2.1][8].
* [GLPK][159] - GNU Linear Programming Kit; a package designed for solving large-scale linear programming, mixed integer programming and other related problems. [GNU GPL3][41].
* [GMP][79] - GNU Multple Precision Arithmetic Library; a library for arbitrary-precision arithmetic. [GNU GPL2.1][8] and [GNU LGPL2.1][15].
* [GNU MPC][175] - A library for complex number arithmetic. [GNU LGPL3][5].
* [GNU MPFR][176] - A library for arbitrary-precision floating-point arithmetic. [GNU LGPL2.1][15].
* [GNU MPRIA][177] - A portable mathematics library for multi-precision rational interval arithmetic. [GNU GPL3][41].
* [GSL][47] - The GNU Scientific Library; a sophisticated numerical library. [GNU GPL3][41].
* [KISS FFT][71] - A very simple fast Fourier transform library. [3-clause BSD][6].
* [LAPACKE][133] - A C interface to [LAPACK][134]. [3-clause BSD][6].
* [PARI/GP][256] - A computer algebra system for number theory; includes a compiler to C. [GNU GPL3][41].
* [Yeppp!][72] - Very fast, SIMD-optimized mathematical library. [3-clause BSD][6].


Parallel Programming
====================

* [cchan][243] - A small library for channel constructs for inter-thread communication. Public domain.
* [ck][242] - Concurrency primitives, safe memory reclamation mechanisms and non-blocking data structures. [FreeBSD][24].
* [OpenMP][37] - A set of C pragmas designed to allow for easy parallelization of code. Standard (licensing not applicable).
* [pth][180] - A portable implementation for non-preemptive priority-based scheduling for multiple threads of execution. [GNU GPL3][41].
* [pthreads][146] - The POSIX thread library. Standard (no license applicable).
* [TinyCThread][115] - A portable, small implementation of the C11 threads API. [zlib][49].

Regex
=====

> "Some people, when confronted with a problem, think 'I know, I'll use regular expressions'. Now they have two problems." - Jamie Zawinski.

* [PCRE][83] - An implementation of regexes identical to that of Perl 5. [3-clause BSD][6].
* [SLRE][80] - Super Light Regular Expression library; a very small implementation of a subset of Perl regex syntax. [GNU GPL2.1][8].
* [TRE][82] - A POSIX-compliant, feature-full regex library. [FreeBSD][24].
* [T-Rex][81] - Another tiny regex library. [zlib][49].

Serialization
=============

* [c-capnproto][130] - An implementation of the Cap'n Proto serialization protocol. [Expat][11].
* [libavro][140] - A C implementation of the Avro data serialization system. [Apache2.0][32].
* [msgpackalt][132] - A simple, light and fast binary serialization library. [3-clause BSD][6].
* [protobuf-c][129] - An implementation of Google Protocol Buffer in C. [FreeBSD][24].
* [xdr][131] - External Data Representation; a standard for data serialization. Standard (no license applicable).

Source Code Collections
=======================

This contains collections of small source code. If you want something big and integrated, check the Frameworks section.

* [CCAN][103] - Modelled after Perl's CPAN, this is a big collection of C code that does stuff. The full list is [here][104]. Various licenses (all free software).
* [clib][26] - Something of a package manager for C. Comes with a [bunch of libraries of its own][27]. [Expat][11].
* [gnulib][46] - A collection of common GNU code. [GNU GPL3][41].
* [ulib][154] - Another collection of source code. [Expat][11].

Standard Libraries
==================

This contains standard C libraries.

* [Bionic][4] - Google's C standard library, developed for Android. [3-clause BSD][6]
* [dietlibc][9] - A C standard library designed for the smallest possible binaries. [GNU GPL2.1][8].
* [glibc][57] - The GNU C Library; an implementation of the C standard library. [GNU LGPL3][5]. 
* [musl][10] - A standard C library, compatible with POSIX 2008 and C11. Designed for static linking. [Expat][11].

String Manipulation
===================

* [bstrlib][116] - The Better String Library. [3-clause BSD][6] or [GNU GPL2.1][8].
* [ICU][67] - International Components for Unicode; a library for Unicode support. [ICU license][68].
* [libunistring][173] - A library for manipulating Unicode strings in C. [GNU LGPL3][5].
* [libgiconv][163] - A text conversion library. [GNU LGPL2.1][8].
* [SDS][29] - Simple Dynamic Strings; a library for handling C strings in a simpler way, but one that is compatible with normal C string functions. Available via [clib][26]. [FreeBSD][24].

Testing
=======

* [CHEAT][84] - A very simple unit testing framework. [FreeBSD][24].
* [Check][59] - A unit testing framework for C. [GNU LGPL2.1][15].
* [cmocka][141] - A unit testing framework with support for mock objects. [Apache2.0][32].
* [Criterion][246] - A KISS, non-intrusive C test framework. [Expat][11].
* [CUnit][94] - Another unit testing framework for C. [GNU LGPL2.1][15].
* [minunit][92] - Minimal unit testing framework for C. [Expat][11].

Text Editor Extensions
======================

While practically any decent programmer's text editor supports C, there are some extensions that make it more pleasant. This is categorized by editor.

## Emacs ##

* [CEDET][250] - Collection of Emacs Development Environment Tools; designed to provide IDE-like features to Emacs. Built-in. [GNU GPL2.1][8].
* [Flycheck][149] - Modern syntax checking. For C, it can use either GCC or Clang as a back-end. [GNU GPL3][41].
* [Yasnippet][150] - A template system, with C templates for common code snippets. [GNU GPL3][41].

## Vim ##

* [Syntastic][186] - Syntax checking and linting. [Do What The Fuck You Want To license][187].
* [YouCompleteMe][151] - A code completion engine for Vim. [GNU GPL3][41].

Tools
=====

This is a list of useful programs to help you write and debug C code which are *not* editors, libraries or compilers.

* [aimake][97] - A build tool designed to avoid complex configurations. [GNU GPL3][41].
* [c][276] - Compile and execute C "scripts" in one go on the command line. Also has shebang support. [Expat][11].
* [c99sh][113] - Run C files using hash-bang. [FreeBSD][24].
* [cinclude2dot][280] - Graphs include dependencies in a C project using Graphviz. [GNU GPL3][41].
* [GDB][87] - The GNU Project debugger; a debugger for C. [GNU GPL3][41].
* [gprof][86] - A performance analysis tool. Part of GNU binutils. [GNU GPL3][41].
* [libtool][172] - A generic library support script. [GNU GPL3][41].
* [qo][274] - A build system that works without a separate config file. [Expat][11].
* [rr][95] - A debugger that records non-deterministic executions to allow for deterministic debugging. [FreeBSD][24].
* [Valgrind][85] - A range of dynamic analysis tools, including a leak checker. [GNU GPL2.1][8].

Utilities
=========

This is a 'catch-all' category for anything that doesn't fit well anywhere else.

* [bfd][157] - A library for manipulating binary object files. Part of GNU binutils. [GNU GPL2.1][8].
* [ccv][195] - C-based/Cached/Core Computer Vision library; modern computer vision. [3-clause BSD][6].
* [CommonMark][223] - A C implementation of the CommonMark spec. [Variety of licenses, all free][224].
* [docopt.c][270] - A C implementation of a command-line option parser. [Expat][11].
* [dyncall][281] - Another foreign function interface library. [Expat][11].
* [GNU FreeIPMI][158] - An in-band and out-of-band IPMI implementation. [GNU GPL3][41].
* [GNU Libffcall][162] - A collection of libraries for building foreign function interfaces. [GNU GPL3][41].
* [Hans Boehm GC][125] - Garbage collection for C? Don't mind if I do! Various licenses, all free.
* [huffandpuff][214] - A minimal Huffman encoder and decoder. Public domain.
* [libavl][156] - A library containing a range of self-balancing binary trees. [GNU GPL2.1][8].
* [libbson][235] - A BSON utility library. [Apache2.0][32].
* [libCello][96] - A library introducing higher-level programming to C. [3-clause BSD][6].
* [libffi][128] - A portable foreign-function interface library. [Expat][11].
* [libgit2][108] - Pure C implementation of Git. [GNU GPL2 with a linking exception][109].
* [libPhenom][31] - An eventing framework for building high-scalability and high-performance systems. [Apache2.0][32].
* [libucl][239] - A universal configuration library parser. [FreeBSD][24].
* [libuv][56] - Cross-platform asynchronous I/O. [Expat][11].
* [mpc][238] - A parser combinator library. [FreeBSD][24].
* [ncurses][178] - Coloured terminal UI library. [GNU GPL3][41].
* [nope.c][209] - A C-language-based, ultra-light software platform for scalable server-side and networking applications (think node.js for C programmers). [GNU GPL2.1][8].
* [pbc][236] - A protocol buffers library. [Expat][11].
* [rabbitmq-c][228] - A client library for [RabbitMQ][229]. [Expat][11].
* [Ragel][54] - A DSL for state machines that compiles to C. [GNU GPL3][41].
* [udpc][190] - An implementation of the [Universal Design Pattern][191]. [GNU GPL3][41].
* [uthash][117] - A hash table implementation, allowing existing structures to be stored in a hash table easily. [1-clause BSD][118]
* [Viola][241] - A simplification of libCello. [Expat][11].
* [zlib][230] - A massively-spiffy yet delicately-unobtrusive compression library. [3-clause BSD][6].

XML
===

> "XML is crap. Really. There are no excuses. XML is nasty to parse for humans, and it's a disaster to parse even for computers. There's just no reason for that horrible crap to exist." - Linus Torvalds

* [Expat][89] - A stream-oriented XML parser. [Expat][11].
* [ezXML][218] - An easy-to-use, fast and lightweight XML parser. [Expat][11].
* [libroxml][219] - Another library for parsing XML. [GNU LGPL2.1][15].
* [libxml2][62] - A standards-compliant, portable XML parser. [Expat][11].
* [mini-xml][216] - A small XML reading and writing library. No dependencies aside from C standard library. [GNU LGPL2.1 with static linking exception][217].
* [VTD-XML][215] - A very fast XML processing framework. [GNU GPL2.1][8].


[1]: https://developer.gnome.org/glib/
[2]: https://developer.gnome.org/gio/
[3]: https://developer.gnome.org/gobject/stable/
[4]: https://github.com/android/platform_bionic
[5]: http://www.gnu.org/licenses/lgpl.html
[6]: http://directory.fsf.org/wiki/License:BSD_3Clause
[7]: http://books.cat-v.org/computer-science/c-programming-language/The.C.Programming.Language.2nd.Edition.pdf
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
[46]: https://www.gnu.org/software/gnulib/
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
[58]: http://bellard.org/tcc/
[59]: http://check.sourceforge.net/
[60]: https://lloyd.github.io/yajl/
[61]: http://directory.fsf.org/wiki/License:ISC
[62]: http://xmlsoft.org/
[63]: https://www.ffmpeg.org/
[64]: http://knking.com/books/c2/index.html
[65]: http://curl.haxx.se/libcurl/
[66]: http://curl.haxx.se/docs/copyright.html
[67]: http://site.icu-project.org/
[68]: http://source.icu-project.org/repos/icu/icu/trunk/license.html
[69]: http://lodev.org/lodepng/
[70]: http://www.fftw.org/
[71]: http://sourceforge.net/projects/kissfft/
[72]: http://www.yeppp.info/
[73]: https://graphics.stanford.edu/~seander/bithacks.html
[74]: http://pcc.ludd.ltu.se/
[75]: http://pcc.ludd.ltu.se/licenses/
[76]: https://github.com/attractivechaos/klib
[77]: https://github.com/netmail-open/wjelement/
[78]: http://apr.apache.org/
[79]: https://gmplib.org/
[80]: https://github.com/cesanta/slre
[81]: http://tiny-rex.sourceforge.net/
[82]: https://github.com/laurikari/tre/
[83]: http://www.pcre.org/
[84]: https://github.com/Tuplanolla/cheat
[85]: http://www.valgrind.org/
[86]: http://www.gnu.org/software/binutils/
[87]: http://www.gnu.org/software/gdb/
[88]: https://github.com/fragglet/c-algorithms
[89]: http://www.libexpat.org/
[90]: http://www.sfml-dev.org/download/csfml/
[91]: http://www.sfml-dev.org/index.php
[92]: https://github.com/siu/minunit
[93]: https://github.com/keybuk/libnih
[94]: http://cunit.sourceforge.net/
[95]: http://rr-project.org/
[96]: http://libcello.org/
[97]: http://nethack4.org/projects/aimake/
[98]: http://www.glfw.org/
[99]: http://freeglut.sourceforge.net/
[100]: http://directory.fsf.org/wiki/License:X11
[101]: https://github.com/orangeduck/Corange
[102]: http://shop.oreilly.com/product/0636920015482.do
[103]: http://ccodearchive.net/
[104]: http://ccodearchive.net/list.html
[105]: http://symas.com/mdb/
[106]: http://directory.fsf.org/wiki/License:OpenLDAPv2.7
[107]: http://ioquake3.org/
[108]: https://libgit2.github.com/
[109]: https://github.com/libgit2/libgit2/blob/master/COPYING
[110]: https://www.openssl.org/
[111]: https://www.openssl.org/source/license.html
[112]: http://www.gnutls.org/
[113]: https://github.com/RhysU/c99sh
[114]: https://github.com/nothings/stb
[115]: https://tinycthread.github.io/
[116]: http://bstring.sourceforge.net/
[117]: http://troydhanson.github.io/uthash/
[118]: http://troydhanson.github.io/uthash/license.html
[119]: https://www.enlightenment.org/p.php?p=about/efl
[120]: http://zserge.com/jsmn.html
[121]: http://www.postgresql.org/
[122]: http://opensource.org/licenses/postgresql
[123]: http://gstreamer.freedesktop.org/
[124]: http://libevent.org/
[125]: http://www.hboehm.info/gc/
[126]: http://blogs.gnome.org/clutter/about/
[127]: http://www.cogl3d.org/
[128]: https://github.com/atgreen/libffi
[129]: https://github.com/protobuf-c/protobuf-c
[130]: https://github.com/jmckaskill/c-capnproto
[131]: http://en.wikipedia.org/wiki/External_Data_Representation
[132]: https://code.google.com/p/msgpackalt/
[133]: http://www.netlib.org/lapack/lapacke.html
[134]: http://www.netlib.org/lapack/
[135]: http://www.netlib.org/blas/
[136]: http://www.netlib.org/blas/#_licensing
[137]: http://math-atlas.sourceforge.net/
[138]: http://lionet.info/asn1c/compiler.html
[139]: https://github.com/nanomsg/nanomsg
[140]: http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c
[141]: http://cmocka.org/
[142]: https://www.gnu.org/software/libgcrypt/
[143]: https://github.com/libressl-portable/
[144]: http://software.schmorp.de/pkg/libev.html
[145]: https://github.com/irungentoo/toxcore
[146]: http://en.wikipedia.org/wiki/POSIX_Threads
[147]: https://www.opengl.org/
[148]: http://www.sgi.com/tech/opengl/?/license.html
[149]: https://github.com/flycheck/flycheck
[150]: https://github.com/capitaomorte/yasnippet
[151]: http://valloric.github.io/YouCompleteMe/
[152]: https://sites.google.com/site/lccretargetablecompiler/
[153]: https://github.com/drh/lcc/blob/master/CPYRIGHT
[154]: https://code.google.com/p/ulib/
[155]: https://gnu.org/software/adns/
[156]: http://adtinfo.org/libavl.html/index.html
[157]: http://sourceware.org/binutils/docs/bfd/
[158]: https://gnu.org/software/freeipmi/index.html
[159]: https://gnu.org/software/glpk/
[160]: https://gnu.org/software/gsasl/
[161]: https://gnu.org/software/gss/
[162]: https://gnu.org/software/libffcall/
[163]: https://gnu.org/software/libiconv/
[164]: https://gnu.org/software/libidn/
[165]: https://gnu.org/software/libmicrohttpd/
[166]: http://www.hughes.com.au/products/libhttpd/
[167]: https://wiki.gnome.org/action/show/Projects/libsoup?action=show&redirect=LibSoup
[168]: http://www.webdav.org/neon/
[169]: http://mihl.sourceforge.net/
[170]: https://github.com/davidmoreno/onion
[171]: https://github.com/cesanta/mongoose
[172]: https://gnu.org/software/libtool/
[173]: https://gnu.org/software/libunistring/
[174]: https://gnu.org/software/libxmi/
[175]: http://www.multiprecision.org/index.php?prog=mpc&page=home
[176]: http://mpfr.loria.fr/index.html
[177]: https://gnu.org/software/mpria/
[178]: https://gnu.org/software/ncurses/
[179]: https://gnu.org/software/osip/
[180]: https://gnu.org/software/pth/
[181]: https://savedparadigms.files.wordpress.com/2014/09/harbison-s-p-steele-g-l-c-a-reference-manual-5th-ed.pdf
[182]: http://shop.oreilly.com/product/9780596004361.do
[183]: http://shop.oreilly.com/product/0636920026136.do
[184]: http://faculty.euc.ac.cy/scharalambous/csc131/books/C%20book%201.pdf
[185]: http://www.planetpdf.com/codecuts/pdfs/ooc.pdf
[186]: https://github.com/scrooloose/syntastic
[187]: https://github.com/scrooloose/syntastic/blob/master/LICENCE
[188]: https://github.com/b-k/apophenia
[189]: https://github.com/b-k/apophenia/blob/master/install/COPYING2
[190]: https://github.com/kozross/udpc
[191]: http://steve-yegge.blogspot.co.nz/2008/10/universal-design-pattern.html
[192]: http://libjpeg.sourceforge.net/
[193]: http://libjpeg-turbo.virtualgl.org/
[194]: http://www.libjpeg-turbo.org/About/License
[195]: https://github.com/liuliu/ccv
[196]: https://github.com/google/gumbo-parser
[197]: https://github.com/joyent/http-parser
[198]: https://github.com/jedisct1/libsodium
[199]: https://github.com/lpereira/lwan
[200]: https://github.com/mozilla/mozjpeg
[201]: https://github.com/redis/hiredis
[202]: http://jvns.ca/blog/2014/12/14/fun-with-threads/
[203]: https://github.com/silentbicycle/socket99
[204]: http://danluu.com/malloc-tutorial/
[205]: http://www.tedunangst.com/flak/post/memcpy-vs-memmove
[206]: https://blogs.oracle.com/ksplice/entry/8_gdb_tricks_you_should
[207]: https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG
[208]: http://nethack4.org/blog/building-c.html
[209]: https://github.com/riolet/nope.c
[210]: https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153
[211]: http://www.cppinstitute.org/?page_id=1487
[212]: http://www.crasseux.com/books/ctut.pdf
[213]: http://home.netcom.com/~tjensen/ptr/pointers.htm
[214]: https://github.com/adamierymenko/huffandpuff
[215]: http://sourceforge.net/projects/vtd-xml/
[216]: http://www.msweet.org/projects.php?Z3
[217]: http://svn.msweet.org/mxml/trunk/COPYING
[218]: http://ezxml.sourceforge.net/
[219]: http://www.libroxml.net/
[220]: https://github.com/json-c/json-c/wiki
[221]: https://github.com/id-Software/Quake-2
[222]: https://github.com/dinhviethoa/libetpan
[223]: https://github.com/jgm/CommonMark
[224]: https://github.com/jgm/CommonMark/blob/master/LICENSE
[225]: https://github.com/id-Software/Quake
[226]: https://github.com/zeromq/czmq
[227]: https://www.gnu.org/licenses/license-list.html#MPL-2.0
[228]: https://github.com/alanxz/rabbitmq-c
[229]: http://www.rabbitmq.com/
[230]: https://github.com/madler/zlib
[231]: https://github.com/libretro/RetroArch
[232]: http://www.libretro.com/
[233]: https://github.com/mongodb/mongo-c-driver
[234]: http://www.mongodb.org/
[235]: https://github.com/mongodb/libbson
[236]: https://github.com/cloudwu/pbc
[237]: https://github.com/sinemetu1/twitc
[238]: https://github.com/orangeduck/mpc
[239]: https://github.com/vstakhov/libucl
[240]: http://snaipe.me/c/c-smart-pointers/
[241]: https://github.com/eatonphil/Viola
[242]: https://github.com/concurrencykit/ck
[243]: http://repo.hu/projects/cchan/
[244]: https://github.com/pmwkaa/sophia
[245]: http://www.greenend.org.uk/rjk/tech/inline.html
[246]: https://github.com/Snaipe/Criterion
[247]: http://www.open-std.org/JTC1/SC22/WG14/
[248]: http://libflow.com/d/c6v1q5ti/C_Programming
[249]: http://www.codeblocks.org/
[250]: http://cedet.sourceforge.net/
[251]: http://mingw.org/
[252]: http://mingw.org/license
[253]: https://cygwin.com/
[254]: https://cygwin.com/licensing.html
[255]: http://flintlib.org/
[256]: http://pari.math.u-bordeaux.fr/
[257]: http://blog.noctua-software.com/c-tricks.html
[258]: http://www.eclipse.org/ide/
[259]: http://directory.fsf.org/wiki/License:EPLv1.0
[260]: https://netbeans.org/
[261]: http://directory.fsf.org/wiki/License:CDDLv1.0
[262]: http://c-faq.com/
[263]: https://computing.llnl.gov/tutorials/pthreads/
[264]: https://computing.llnl.gov/tutorials/openMP/
[265]: https://computing.llnl.gov/tutorials/mpi/
[266]: https://www.securecoding.cert.org/confluence/display/seccode/CERT+C+Coding+Standard
[267]: http://blog.pkh.me/p/20-templating-in-c.html
[268]: http://lipforge.ens-lyon.fr/www/crlibm/index.html
[269]: https://github.com/AbsInt/CompCert
[270]: https://github.com/docopt/docopt.c
[271]: http://marek.vavrusa.com/c/memory/2015/02/20/memory/
[272]: http://kukuruku.co/hub/programming/i-do-not-know-c
[273]: http://kamalatta.ddnss.de/otherdocs/pikestyle.html
[274]: https://github.com/andlabs/qo
[275]: http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html
[276]: https://github.com/ryanmjacobs/c
[277]: https://github.com/wolkykim/qlibc
[278]: https://github.com/wolkykim/qlibc/blob/master/LICENSE
[279]: https://gist.github.com/eatonphil/21b3d6569f24ad164365
[280]: http://www.flourish.org/cinclude2dot/
[281]: http://www.dyncall.org/
