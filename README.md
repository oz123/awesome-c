# Awesome C #

A curated list of C good stuff. This list contains *only* [open source][13]
code (as defined by the linked Open Source Definition), and sellers who
aren't evil for physical resources.

This is released under a Creative Commons-Attribution-ShareAlike license,
version 4 (SPDX code ``CC-BY-SA-4.0``). You can find its text in the LICENSE file.

**An important note:** This project does *not* index anything C++-related; only
pure C stuff is considered.

**Note for contributors:** If you want to make a pull request, please read
CONTRIBUTING.md first.

## Contents ##

* [AI](#ai)
* [Benchmarking](#benchmarking)
* [Build Systems](#build-systems)
* [Compilers](#compilers)
* [Compression](#compression)
* [Concurrency and Parallelism](#concurrency-and-parallelism)
* [Crypto](#crypto)
* [Database](#database)
* [Data Structures](#data-structures)
* [Debugging](#debugging)
* [Documentation Generation](#documentation-generation)
* [Editors](#editors)
* [Embeddable Scripting Engines](#embeddable-scripting-engines)
* [Frameworks](#frameworks)
* [Game Programming](#game-programming)
* [Graphics](#graphics)
* [Graphical User Interface](#graphical-user-interface)
* [Hashing](#hashing)
* [Learning, Reference and Tutorials](#learning-reference-and-tutorials)
  * [Reference resources online](#reference-resources-online)
  * [Beginner resources online](#beginner-resources-online)
  * [Intermediate resources online](#intermediate-resources-online)
  * [Advanced resources online](#advanced-resources-online)
  * [Reference books](#reference-books)
  * [Beginner books](#beginner-books)
  * [Intermediate books](#intermediate-books)
  * [Advanced books](#advanced-books)
* [Lexing and Parsing](#lexing-and-parsing)
* [Memory Management](#memory-management)
* [Multimedia](#multimedia)
* [Networking and Internet](#networking-and-internet)
* [Numerical](#numerical)
* [Profiling](#profiling)
* [Regex](#regex)
* [Serialization](#serialization)
* [Source Code Collections](#source-code-collections)
* [Standard Libraries](#standard-libraries)
  * [Template Libraries](#template-libraries)
* [String Manipulation](#string-manipulation)
* [Structured File Processing](#structured-file-processing)
	* [CSV](#csv)
	* [JSON](#json)
	* [INI](#ini)
	* [Others](#others)
	* [XML](#xml)
	* [YAML](#yaml)
* [Testing](#testing)
* [Text Editor Extensions](#text-editor-extensions)
* [Tools](#tools)
* [Utilities](#utilities)
* [Web Frameworks](#web-frameworks)
* [Windows Environments](#windows-environments)

## AI ##

Computer vision, neural nets, machine learning, and other similar things.
Basically, if your university calls it AI, it lives here.

* [ccv][195] - C-based/Cached/Core Computer Vision library; modern computer
  vision. [``BSD-3-Clause``][BSD-3-Clause]
* [Cranium][525] - Portable, header-only ANN library in C99. [``MIT``][MIT]
* [FANN][325] - Fast Artifical Neural Network library; an implementation of
  neural networks. [``GPL-2.0-only``][GPL-2.0-only]
* [Genann][412] - Simple ANN in C89, without additional dependencies. [``Zlib``][Zlib]
* [KANN][327] - Two-file ANN library. [``MIT``][MIT]
* [LibDEEP][477] - Deep learning library. [``BSD-3-Clause``][BSD-3-Clause]
* [m2cgen][610] - A CLI tool to transpile trained classic ML models into a native C code with zero dependencies. [``MIT``][MIT]
* [sod][611] -  An Embedded Computer Vision & Machine Learning Library. [``GPL-3.0-only``][GPL-3.0-only]

## Benchmarking ##

Comparing the performance of various subsystems across different chip/system architectures.

* [b63][553] - Light-weight micro-benchmarking tool for C. [``Apache-2.0``][Apache-2.0]

## Build Systems ##

Tools that automate the building and testing of projects in C.

* [Autotools][583] - Also known as the GNU build system (automake, autoconf, libtool...)
  is one of the most widely used build systems (configure && make). [GPL-1.0-or-later][335]
* [Autotools project skeleton][584] - A simple autotools skeleton (template) to quickly bootstrap
  new projects. [``BSD-2-Clause``][BSD-2-Clause]
* [CMake][329] - Cross-platform family of tools designed to build, package and test
  software. [``BSD-3-Clause``][BSD-3-Clause]
* [GNU Make][324] - Tool which controls the generation of executables and other
  non-source files of a program. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Meson][368] - Extremely fast, user-friendly build system. Based on Ninja. [``Apache-2.0``][Apache-2.0]
* [Premake][435] - Command-line utility which reads a scripted definition of a
  software project and uses it to generate project files for Visual Studio and
  GNU Make. Other targets are also being worked on. [``BSD-3-Clause``][BSD-3-Clause]
* [SCons][521] - Software construction tool using Python. [``MIT``][MIT]
* [xmake][271] - Cross-platform build utility. [``Apache-2.0``][Apache-2.0]
* [zproject][420] - Project generator and build system support tool. [``MPL-2.0``][MPL-2.0]

## Compilers ##

Compilers, as well as compiler- and compilation-related tooling.

* [ccache][466] - Compiler cache designed to speed up recompilation. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Clang][38] - Compiler for LLVM. Supports C11. [``NCSA``][NCSA]
* [cproc][574] - A C11 compiler using QBE as a backend. [``ISC``][ISC]
* [distcc][452] - Program that allows builds to be distributed among several
  machines. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [Firm][361] - Library that provides a graph-based intermediate
  representation, optimizations and assembly code generation suitable for use in
  compilers. Comes with an example C front-end under the same
  license. [``LGPL-2.1-only``][LGPL-2.1-only]
* [GCC][40] - Provides a C compiler as part of its compiler set. Supports
  C11. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [PCC][74] - Venerable compiler. Supports C99. [Various licenses][75], all
  open source.

## Compression ##

* [blosc][445] - Extremely fast, multi-threaded, meta-compressor library.
  Various licenses, all open source.
* [Brotli][24] - General-purpose lossless compression algorithm library. Has
  speeds comparable to DEFLATE, but much higher compression ratios.
  [``MIT``][MIT].
* [clzip][432] - C version of the high-quality data compressor [Lzip][433] (LZMA
  implementation). [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [CRoaring][481] - C implementation of [Roaring bitmaps][482]. [``Apache-2.0``][Apache-2.0]
* [FiniteStateEntropy][2] - Two highly efficient compression codecs optimized
  for modern CPUs. [``BSD-2-Clause``][BSD-2-Clause]
* [DENSITY][506] - Super-fast compression library. [``BSD-3-Clause``][BSD-3-Clause]
* [heatshrink][514] - Data compression/decompression library for embedded and
  real-time systems. [``ISC``][ISC]
* [fast\_zlib][533] - Improved zlib, which runs 2 to 10 times faster.
  [``BSD-3-Clause``][BSD-3-Clause]
* [fastLZ][586] - Lightning-fast lossless compression library (LZ77 type). Embbedable on small target like ARM Cortex-M families. Source code directly embbedable on your project ( a pair of h/c files), no dynamic memory allocation. [``MIT``][MIT]
* [huffandpuff][214] - Minimal Huffman encoder and decoder. Public domain.
* [libzip][587] - C library for reading, creating and modifying zip archives.
  [``BSD-3-Clause``][BSD-3-Clause]
* [libbzip2][427] - Patent-free, high-quality data compression
  library. [``BSD-4-Clause``][BSD-4-Clause]
* [Lizard][489] - Formerly LZ5; an efficient compressor with fast
  decompression. Achieves compression ratios comparable with zip and zlib at
  decompression speeds of 1000MB/s and faster. [``BSD-2-Clause``][BSD-2-Clause]
* [lz4][508] - Library for an extremely fast compression algorithm.
  [``BSD-2-Clause``][BSD-2-Clause]
* [lzo][338] - Fast data compression library.
  [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [pixz][49] - Parallel, indexed xz compressor. [``BSD-2-Clause``][BSD-2-Clause]
* [shoco][363] - Compressor for small text strings. [``MIT``][MIT]
* [SIMDComp][519] - Simple library for compressing lists of integers using
  binary packing. Makes use of SIMD instructions on x86.
  [``BSD-3-Clause``][BSD-3-Clause]
* [smaz][364] - Efficient string compression library.
  [``BSD-3-Clause``][BSD-3-Clause]
* [squash][393] - Compression abstraction library, complete with some
  utilities. [``MIT``][MIT]
* [TurboPFor][471] - Fastest integer compression.
  [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [TurboRLE][484] - Most efficient run-length encoding. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [zip][520] - Really really small zip archive processing library.
  [``Unlicense``][Unlicense]
* [Zlib][230] - Massively spiffy yet delicately unobtrusive compression
  library. [``BSD-3-Clause``][BSD-3-Clause]
* [libarchive][548] - libarchive is a portable, efficient C library that can read and write streaming archives in a variety of formats.
  [``BSD-3-Clause``][BSD-3-Clause]
* [zlib-ng][1] - Zlib replacement with optimizations for 'next-generation'
  systems. [``BSD-3-Clause``][BSD-3-Clause]
* [Zstandard][510] - Fast, lossless compression algorithm, targeting real-time
  compression scenarios at zlib-level or better compression ratios.
  [``BSD-3-Clause``][BSD-3-Clause]

## Concurrency and Parallelism ##

* [cchan][243] - Small library for channel constructs for inter-thread
  communication. Public domain.
* [checkedthreads][465] - A simple library for
  parallelism, with built-in checking for race conditions. [``BSD-2-Clause``][BSD-2-Clause]
* [ck][242] - Concurrency primitives, safe memory reclamation mechanisms and
  non-blocking data structures. [``BSD-2-Clause``][BSD-2-Clause]
* [FCFS RWLock][540] - First-come first-served Readers/Writers lock for POSIX threads. [``CC0-1.0``][CC0-1.0]
* [Libaco][599] - A blazing fast and lightweight C asymmetric coroutine library. [``Apache-2.0``][Apache-2.0]
* [libconcurrent][390] - Concurrent programming library, using coroutines, for
  C11. [``BSD-3-Clause``][BSD-3-Clause]
* [libcsp][572] - High performance concurrency C library influenced by the CSP model. [``MIT``][MIT]
* [libdill][442] - Library which makes structured concurrent programming
  easy. [``MIT``][MIT]
* [libhl][478] - Library implementing a thread-safe API to manage a range of data
  structures. Also provides some supporting functions and structures for
  concurrent and lockfree programming. [``LGPL-3.0-only``][LGPL-3.0-only]
* [liburcu][474] - Data synchronization library, which scales linearly with the
  number of cores. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [mill][352] - Go-style concurrency. [``MIT``][MIT]
* [oclkit][311] - Two-file OpenCL wrapper. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [OCL-MLA][312] - OpenCL Mid-Level Abstractions. [``BSD-3-Clause``][BSD-3-Clause]
* [OpenMP][37] - Set of pragmas designed to allow for easy parallelization of
  code. Standard (licensing not applicable).
* [Open MPI][284] - Message passing interface implementation. [``BSD-3-Clause``][BSD-3-Clause]
* [pal][459] - Optimized library for maths, parallel processing and data
  movement. [``Apache-2.0``][Apache-2.0]
* [pth][180] - Portable implementation for non-preemptive priority-based
  scheduling for multiple threads of execution.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [pthreads][146] - POSIX thread library. Standard (no license applicable).
* [TinyCThread][115] - Portable, small implementation of the C11 threads
  API. [``Zlib``][Zlib]

## Crypto ##

Mostly library implementations of well-known cryptographic algorithms or
protocols.

* [GNU SASL][160] - Implementation of the Simple Authentication and Security
  Layer and a few common SASL mechanism. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GnuTLS][112] - Secure communication library, implementing SSL, TLS and
  DTLS. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libgcrypt][142] - General-purpose cryptography library, with a range of
  available ciphers. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [OpenSSL][110] - Implementation of the SSL and TLS protocols. Also includes a
  cryptography library. [Dual Licensed under the OpenSSL License and the SSLeay License][111].
* [liboqs][493] - Library for quantum-resistant cryptographicl algorithms.
  [``MIT``][MIT]
* [libsodium][198] - Modern and easy-to-use crypto library. [``MIT``][MIT]
* [libtomcrypt][299] - Fairly comprehensive, modular and portable
  cryptographic toolkit. Public domain.
* [mbed TLS][291] - Another crypto implementation. [``Apache-2.0``][Apache-2.0]
* [MIRACL][480] - Multiprecision Integer and Rational Arithmetic Cryptographic
  Library; an SDK for elliptic curve cryptography.
  [``AGPL-3.0-or-later``][AGPL-3.0-or-later]
* [retter][507] - Collection of hash functions, ciphers, tools, libraries and
  materials related to cryptography and security. Public domain.
* [s2n][359] - C99 implementation of the TLS/SSL protocols, designed to be
  simple, fast and with security as a priority. [``Apache-2.0``][Apache-2.0]
* [sphlib][526] - Set of implementations of various hash functions, including
  several cryptographic ones. [``MIT``][MIT]
* [trezor-crypto][485] - Heavily optimized crypto algorithms for embedded
  devices. [``MIT``][MIT]
* [bfish][598] - A single include ANSI-C Blowfish ECB crypto library. Public
  domain.

## Database ##

Databases and data stores with C APIs.

* [BerkeleyDB][380] - Library for a high-performance embedded database for
  key-value data. [``AGPL-3.0-only``][AGPL-3.0-only]
* [DuckDB][702] - Fast in-process analytical database, with C API. [``MIT``][MIT] 
* [EJDB2][568] - Embeddable JSON Database engine. [``MIT``][MIT]
* [Groonga][524] - Columnar store with full-text search. [``LGPL-2.1-only``][LGPL-2.1-only]
* [Hiredis][201] - Minimalistic client library for Redis.
  [``BSD-3-Clause``][BSD-3-Clause]
* [libmongoc][233] - High-performance client library for [MongoDB][234]. [``Apache-2.0``][Apache-2.0]
* [LMDB][105] - Ultra-fast, ultra-compact key-value embedded data store. [``OLDAP-2.8``][OLDAP-2.8]
* [MySQL][551] - The world's most popular open source database. [``GPL-2.0-only``][GPL-2.0-only]
* [PostgreSQL][121] - Powerful object-relational database system. [``PostgreSQL``][PostgreSQL]
* [Redis][51] - Advanced key-value store. [``BSD-3-Clause``][BSD-3-Clause]
* [sophia][244] - Modern, embeddable key-value database.
  [``BSD-2-Clause``][BSD-2-Clause]
* [sparkey][509] - Simple constant key/value storage library. Designed for
  read-heavy loads with infrequent, large bulk inserts.
  [``Apache-2.0``][Apache-2.0]
* [SQLite][22] - Self-contained, serverless, zero-configuration, transactional
  SQL database engine. Public domain.
* [UnQLite][23] - Self-contained, serverless, zero-configuration,
  transactional NoSQL engine. [``BSD-2-Clause``][BSD-2-Clause]
* [WhiteDB][512] - Lightweight database library, operating entirely in main
  memory. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [FlashDB][703] - An ultra-lightweight database that supports key-value and 
  time series data. [``Apache-2.0``][Apache-2.0]
* [TDengine][704] - High-performance, cloud native time-series database. 
  [``AGPL-3.0-only``][AGPL-3.0-only]

## Data Structures ##

* [C-Macro-Collections][550] - Generate simple and generic data structures using macros. [``MIT``][MIT]
* [CLIST][371] - Simple and lightweight [dynamic array][25] implementation.
  [``BSD-2-Clause``][BSD-2-Clause]
* [Collections-C][406] - Library of generic data structures. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [ds][541] - Common Data Structures and Algorithms. [``MIT``][MIT]
* [igraph][544] - A graph processing library.
  [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [kdtree][337] - Simple library for working with KD-trees. [``BSD-3-Clause``][BSD-3-Clause]
* [libavl][156] - Library containing a range of self-balancing binary
  trees. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libcdada][585] - A small, portable, MACRO-less library for basic data structures
  (list, set, map, queue...) in C (C++ backend). [``BSD-2-Clause``][BSD-2-Clause]
* [liblfds][411] - Portable lock-free data structure library. Public domain
  (more exactly, whatever license you want).
* [libsrt][305] - Soft and hard real-time data structures.
  [``BSD-3-Clause``][BSD-3-Clause].
* [list.h][538] - Implementations for singly linked and doubly linked list functions.
  [``GPL-3.0-only``][GPL-3.0-only]
* [M\*LIB][350] - Library for generic, but typesafe C containers. Implemented as
  header-only. [``BSD-2-Clause``][BSD-2-Clause]
* [offbrand][498] - Collection of generic, reference-counted data structures.
  [``MIT``][MIT]
* [PackedArray][241] - Random-access array of tightly packed unsigned integers of
  any desired width. Has a SIMD-optimized implementation. [``WTFPL``][WTFPL]
* [rb3ptr][561] - Red-Black tree. Exposes almost all implementation primitives, so can be used for
  scenarios like augmentation, multiple compatible ordering functions, and more. [``MIT``][MIT]
* [uthash][273] - Single-file hash table implementation. [``BSD-1-Clause``][BSD-1-Clause]
* [vector.h][154] - Header library for typed lists. [``MIT``][MIT]

## Debugging ##

Because we all have to do it sometimes. Various tools for making debugging
easier or better, as well as libraries or code that allows better debugging
work.

* [C-Reduce][403] - Tool that takes a large C file with a property of interest
  and automatically produces a much smaller C file that has the same
  property. Intended to help create minimal bug-demonstrating cases in complex
  code. [``BSD-3-Clause``][BSD-3-Clause]
* [CBMC][309] - C Bounded Model Checker; a tool for verification of array
  bounds, pointer safety and user-specified assertions.
  [``BSD-4-Clause``][BSD-4-Clause]
* [cflow][404] - Analyzes a collection of source files and prints a graph
  charting control flow in the program. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Complexity][307] - Tool for measuring the complexity of source
  code. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [CScout][410] - Source code analyzer and refactoring browser for C
  programs. [``GPL-3.0-only``][GPL-3.0-only]
* [DDD][320] - Graphical front-end for a range of command-line
  debuggers. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [debug][467] - One-header library for easier 'printf debugging'.
  [``MIT``][MIT]
* [ESBMC][567] - Efficient SMT-based Bounded Model Checker; a tool for verification of
   single and multithread programs, user assertions, overflow, and pointer/memory safety. [``Apache-2.0``][Apache-2.0]
* [GDB][87] - GNU Project debugger. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [lldb][468] - LLVM debugger. [``NCSA``][NCSA]
* [rr][95] - Debugger that records non-deterministic executions to allow for
  deterministic debugging. [``BSD-2-Clause``][BSD-2-Clause]
* [Valgrind][85] - Range of dynamic analysis tools, including a leak
  checker. [``GPL-2.0-only``][GPL-2.0-only]

## Documentation Generation ##

* [Cxref][317] - Generates documentation in either LaTeX, HTML, RTF or
  SGML. [``GPL-2.0-only``][GPL-2.0-only]
* [DocOnce][322] - Modestly tagged markup language that can be used to
  generate a range of formats. [``BSD-3-Clause``][BSD-3-Clause]
* [Doxygen][318] - De-facto standard tool for generating documentation from
  annotated sources. Can generate a large range of formats. [``GPL-2.0-only``][GPL-2.0-only]

## Editors ##

Fancier, IDE-type editors. If you want a programmer's text editor, look
elsewhere. Besides, whatever you use most likely supports C anyway.

* [Anjuta DevStudio][42] - GNOME IDE. [``GPL-2.0-only``][GPL-2.0-only]
* [Code::Blocks][249] - Extendable, configurable IDE supporting
  C. [``GPL-3.0-only``][GPL-3.0-only]
* [CodeLite][45] - Cross-platform IDE. [``GPL-2.0-only``][GPL-2.0-only]
* [Geany][43] - Small and fast IDE. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [KDevelop][44] - KDE IDE. [``GPL-2.0-only``][GPL-2.0-only]
* [zinjaI][578] - Simple, lightweight and feature-rich IDE. [``GPL-3.0-only``][GPL-3.0-only]

## Embeddable Scripting Engines

When C isn't the right solution, or when you need a more dynamic configration engine:

* [Duktape][591] - Embeddable Javascript engine with a focus on portability and compact footprint [``MIT``][MIT].
* [MetaCall][607] - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, Wasm, Java, Cobol and more. [``Apache-2.0``][Apache-2.0]

## Frameworks ##

Big libraries that provide data structures and other stuff you expect of a
'modern' standard library.

* [APR][78] - Apache Portable Runtime; another library of cross-platform utility
  functions. [``Apache-2.0``][Apache-2.0]
* [C Algorithms][88] - Collection of common algorithms and data structures. [``ISC``][ISC]
* [CPL][308] - The Common Pipeline Library; a set of libraries designed to be a
  comprehensive, efficient and robust software toolkit.
  [``GPL-2.0-only``][GPL-2.0-only]
* [EFL][119] - Large collection of useful data structures and
  functions. Various licenses, all open source.
* [GLib][701] - Library of utility functions and structures, designed to be
  portable, efficient and powerful. [``LGPL-2.1-only``][LGPL-2.1-only]
* [klib][76] - Small and lightweight implementations of common algorithms and
  data structures. [``MIT``][MIT]
* [libcork][476] - Utility functions and structures, designed for
  resource-constrained systems. Can be embedded. [``BSD-3-Clause``][BSD-3-Clause]
* [libnih][93] - Lightweight library of functions and
  structures. [``GPL-2.0-only``][GPL-2.0-only]
* [libU][28] - Small library of basic utilities, including memory allocation,
  string manipulation and logging. [``BSD-3-Clause``][BSD-3-Clause]
* [PBL][346] - Large library of utilities, featuring data structures, among
  other things. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [plibsys][588] - Cross-platform system C library. Zero third-party dependencies, uses only native system calls. [``MIT``][MIT]
* [qlibc][277] - Simple and powerful library, designed as a replacement for
  GLib while focusing on being small and light. [``BSD-2-Clause``][BSD-2-Clause]
* [sc][595] - Common libraries and data structures for C. [``MIT``][MIT]
* [TBOX][398] - Multi-platform library with a large number of
  capabilities. [``Apache-2.0``][Apache-2.0]
* [pspsdk][620] - An open-source SDK for PSP homebrew development. [Various licences][621].

## Game Programming ##

Engines, libraries and other helpful things specifically for making games.

* [Allegro][48] - Cross-platform, video game development and multimedia
  library. [``Zlib``][Zlib]
* [AssetKit][571] 🎨 3D asset importer/exporter/util library based on COLLADA/glTF specs [``MIT``][MIT]
* [astera][594] - C99 Cross Platform 2D Game Library  [``MIT``][MIT]
* [cglm][542] - 📽 Optimized OpenGL/Graphics Math (glm) for C. [``MIT``][MIT]
* [Chipmunk2D][303] - Fast and lightweight 2D game physics library. [``MIT``][MIT]
* [cmt][570] - 🎮 C Bindings/Wrappers for Apple's METAL Graphics Framework. [``MIT``][MIT]
* [Corange][101] - Game engine in pure C. [``BSD-2-Clause``][BSD-2-Clause]
* [CSFML][90] - Binding for [SFML][91]. [``Zlib``][Zlib]
* [Darkplaces][369] - Modified version of the Quake2 engine. [``GPL-2.0-only``][GPL-2.0-only]
* [Epoxy][414] - Library for handling OpenGL function pointer management. [``MIT``][MIT]
* [exengine][618] - 3D game engine in C99 with a starting template. [``MIT``][MIT]
* [Flecs][557] - A Multithreaded Entity Component System written for C89 & C99 [``MIT``][MIT]
* [Freecell Solver][539] - Set of libraries and command-line programs for
  automatically solving FreeCell and some similar variants of card Solitaire. [``MIT``][MIT]
* [FreeGLUT][99] - Alternative to the OpenGL Utility Toolkit. Allows the
  creation and management of windows with OpenGL contexts. [``X11``][X11]
* [GLFW][98] - Multi-platform library for creating windows with OpenGL
  contexts. [``Zlib``][Zlib]
* [img2ascii][707] - 🖼️ A command-line tool for converting images to ASCII art [``MIT``][MIT]
* [ioquake3][107] - Quake3 engine, freed at last.
  [``GPL-2.0-only``][GPL-2.0-only]
* [kazmath][446] - Maths library for games. [``BSD-2-Clause``][BSD-2-Clause]
* [libao][376] - Cross-platform audio library with a wide variety of
  outputs. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [librg][558] - Pure C99 game networking library for building simple and elegant cross-platform multiplayer client-server solutions. [``Apache-2.0``][Apache-2.0]
* [MATHC][534] - Math library for 2D and 3D programming. [``ZLib``][Zlib]
* [Orx][370] - Portable, lightweight, plugin-based, data-driven, 2D-oriented
  game engine. [``Zlib``][Zlib]
* [Quake][225] - Quake engine. [``GPL-2.0-only``][GPL-2.0-only]
* [Quake2][221] - Quake2 engine. [``GPL-2.0-only``][GPL-2.0-only]
* [raylib][516] - Simple and easy-to-use library to learn video game
  programming. [``Zlib``][Zlib]
* [RetroArch][231] - Reference frontend for [libretro][232]. [``GPL-3.0-only``][GPL-3.0-only]
* [SDL2][50] - Cross-platform library designed to provide low-level access to
  audio, keyboard, mouse, joystick and graphics hardware via OpenGL. [``Zlib``][Zlib]
* [sdl-gpu][457] - Library for high-performance, modern 2D graphics. Based on
  SDL. [``MIT``][MIT]
* [SIGIL][429] - Sound, Input and Graphics Integration Library; a simple
  alternative to other libraries for doing all those things. Various licenses,
  all open source.
* [uastar][535] - Minimal A\* implementation. [``ZLib``][Zlib]

## Graphics ##

Programmatic manipulation of graphics in C; if you want to make a GUI, the
Graphical User Interface section has what you need.

* [AssetKit][571] 🎨 3D asset importer/exporter/util library based on COLLADA/glTF specs [``MIT``][MIT]
* [Cairo][384] - 2D graphics library. [``LGPL-2.1-only``][LGPL-2.1-only] or [``MPL-1.1``][385].
* [cmt][570] - 🎮 C Bindings/Wrappers for Apple's METAL Graphics Framework. [``MIT``][MIT]
* [giflib][401] - Library for reading and writing gif images. [``MIT``][MIT]
* [graphene][515] - Thin layer of graphical data types. [``MIT``][MIT]
* [heman][365] - Tiny library of image utilities dealing with height maps,
  normal maps, distance fields and the like. [``MIT``][MIT]
* [libcaca][366] - ASCII renderer for terminal-based interfaces. [``WTFPL``][WTFPL]
* [libgd][402] - Library for the dynamic creation of images by programmers. [``MIT``][MIT]
* [libimagequant][300] - Small, portable library for high-quality conversion of
  RGBA images to 8-bit indexed colour images. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libjpeg-turbo][193] - Faster library for reading and writing JPEG files.
  [Various licences][194].
* [libpng][382] - Official PNG reference library. [``Libpng``][Libpng]
* [libRSVG][417] - Library to render SVG files using Cairo. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libsixel][17] - Library implementing the SIXEL protocol, allowing beautiful
  graphics in your terminal. [``MIT``][MIT]
* [libspng][68] - A simpler interface for reading and writing PNG files.
  [``BSD-2-Clause``][BSD-2-Clause]
* [libvips][511] - Image processing library. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libxmi][174] - Function library for rasterizing 2D vector
  graphics. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [lightmapper][444] - Single-file library for lightmap baking, using an
  existing OpenGL renderer. Public domain.
* [little CMS][600] - A Color Management System. It provides fast transforms between ICC profiles.  [``MIT``][MIT]
* [mozjpeg][200] - Improved JPEG encoder. [``BSD-3-Clause``][BSD-3-Clause]
* [nanovg][505] - Anti-aliased 2D vector drawing library on top of OpenGL, for
  UI and visualizations. [``Zlib``][Zlib]
* [OpenGL][147] - Industry standard for high-performance graphics, with a
  native C binding. [Various licenses][148].
* [PlutoVG][590] - A standalone 2D vector graphics library in C [``MIT``][MIT]
* [SAIL][601] - ⛵ The missing small and fast image decoding library for humans (not for machines) [``MIT``][MIT]

## Graphical User Interface ##

Widget toolkits, or things meant to be used in a similar way to them.

* [GTK+][14] - Cross-platform widget toolkit. [``LGPL-2.1-only``][LGPL-2.1-only]
* [IUP][16] - Another cross-platform widget toolkit. [``MIT``][MIT]
* [microui][616] - Tiny immediate-mode UI library written in portable ANSI C. [```MIT```][MIT]
* [nappgui][705] - Professional SDK to build cross-platform desktop applications using C. [``MIT``][MIT]
* [nuklear][408] - Small, C89, single-header widget toolkit. Public domain.
* [tinyfiledialogs][426] - Single-file library for simple dialogs. Compatible
  with many other toolkits and OSes. [``Zlib``][Zlib]
* [Tk][19] - Basic widget toolkit. Part of Tcl/Tk. [``TCL``][TCL]
* [XForms Toolkit][21] - Widget toolkit designed for the XWindow
  system. [``LGPL-2.1-only``][LGPL-2.1-only]
* [LVGL][575] - embedded GUI with easy-to-use graphical elements, beautiful visuals and
  a low memory footprint. [``MIT``][MIT]
* [luigi][614] - A barebones single-header GUI library for Win32, X11 and Essence. [``MIT``][MIT]

## Hashing ##

Hash function implementations for *non*-crypto purposes. Cryptographic hashes
can be found in the Crypto section.

* [CLHash][495] - Library implementing the ridiculously fast CLHash hashing
  function. Only works on Intel Haswell or newer. [``Apache-2.0``][Apache-2.0]
* [HighwayHash][527] - Fast, strong, SIMD-using hash function. Also contains
  an implementation of SipHash (although this is slower).
  [``Apache-2.0``][Apache-2.0]
* [SpookyHash][326] - Extremely fast hash function.
  [``BSD-3-Clause``][BSD-3-Clause]
* [t1ha][530] - Fast Positive Hash - a portable, fast hash function.
  [``BSD-3-Clause``][BSD-3-Clause]
* [xxHash][522] - Extremely fast hashing algorithm. Comes in 32 and 64-bit
  varieties. [``BSD-2-Clause``][BSD-2-Clause]

## Learning, Reference and Tutorials ##

Resources for learning C programming in general, or something useful relating
to C programming.

### Reference resources online ###

* [Benchmarks of the Lockless Memory Allocator][450]
* [C FAQ - comp.lang.c Frequently Asked Questions][262]
* [Comparison of C/POSIX standard library implementations for Linux][362]
* [Draft C89 standard][6]
* [Draft C99 standard][258]
* [Draft C11 standard][247]
* [Finding the best 64-bit simulation PRNG][529]
* [SEI CERT C Coding Standard][266]
* [tinyc.game][559] - Tiny C games you can compile and run RIGHT NOW http://tinyc.games [``MIT``][MIT]

### Beginner resources online ###

* [A tutorial on pointers][213]
* [A tutorial on portable Makefiles][528]
* [Building C Projects][208]
* [C Programming Wikibook][248]
* [Introduction to \`fun' C][279]
* [Learning C with GDB][349]
* [memcpy vs memmove][205]
* [POSIX Threads Programming tutorial][263] (a little dated, but most of it is
  still valid and useful)
* [The GNU C Programming Tutorial][212] (online PDF)
* [Templating in C][267]
* [What a C programmer should know about memory][227]
* [CodeforWin: Learn C Programming, Data Structures Tutorials and Exercises online][605]
* [Learn C: Free and Open-Source Interactive C Tutorial][606]
* [How to program a text adventure in C][615]

### Intermediate resources online ###

* [8 gdb tricks you should know][206]
* [10 C99 tricks][257]
* [A comprehensive MPI tutorial resource][454]
* [Build Your Own Text Editor][700]
* [Diving into concurrency: trying out mutexes and atomics][202]
* [Generic C reference counting][443]
* [How to write portable C without complicating your build][490]
* [Introduction to OpenMP][207] (video)
* [OpenMP tutorial][264] (for the OpenMP3 standard)
* [MPI tutorial][265]
* [Scalable C - Writing Large-Scale Distributed C][391]
* [Some unknown features or tricks in C language][374]
* [What every C programmer should know about undefined behaviour][275]

### Advanced resources online ###

* [Advanced metaprogramming in C][357]
* [A quick tutorial on implementing and debugging malloc, free, calloc, and realloc][204]
* [Bit twiddling hacks][73]
* [Implementing smart pointers for the C programming language][240]
* [Inline functions in C][245]
* [Metaprogramming custom control structures in C][343]
* [Solving the temporary storage problem of C macros][358]
* [Some dark corners of C][210]
* [Writing efficient C and C code optimization][33]
* [Compiling Algebraic Data Types in Pure C99][608]

### Reference books ###

* [C: A Reference Manual 5E][181] - Full reference book for C99.
* [C in a Nutshell 2E][418] - Concise reference book for C11.
* [C Pocket Reference][182] - Concise reference book for C99.
* [The C Programming Language 2E][7] - Original book on C, by its creators.

### Beginner books ###

* [C Primer Plus 6E][184] - Complete tutorial on programming in C11.
* [C Programming: A Modern Approach][64] - Excellent book to learn the basics
  of C.
* [Head First C][102] - 'Head-first' style book for learning C.

### Intermediate books ###

* [21st Century C][35] - Good _second_ programming book on C.
* [Understanding and Using C Pointers][36] - In-depth resource on pointers in
  C.
* [ZeroMQ][183] - Book for using ZeroMQ with C.

### Advanced books ###

* [Expert C Programming: Deep C Secrets][55] - Interesting, in-depth and
  entertaining look at the innards of C.
* [Modern C, Third Edition: Covers the C23 standard][425] - In Modern C, Third Edition you’ll learn to harness C’s full potential using the latest tools and techniques.

## Lexing and Parsing ##

Libraries specifically for lexical analysis (or lexing) and syntactic analysis
(or parsing).

* [flex][491] - Fast lexical analyzer generator. [``BSD-2-Clause``][BSD-2-Clause]
* [GNU Bison][492] - General-purpose parser generator that converts an
  annotated context-free grammar into a range of parsers. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [hammer][356] - Parser combinators for binary formats.
  [``GPL-2.0-only``][GPL-2.0-only]
* [mpc][238] - Parser combinator library. [``BSD-2-Clause``][BSD-2-Clause]
* [owl][576] - A parser generator for visibly pushdown languages. [``MIT``][MIT]
* [re2c][34] - Lexer generator, producing fast lexers, with access to its
  internals. Public domain.

## Memory Management ##

Whether a different, faster malloc or outright garbage collection, anything
to do with managing C memory lives here.

* [Boehm GC][125] - Garbage collection for C. Various
  licenses, all open source.
* [jemalloc][293] - Malloc implementation that emphasizes avoidance of
  fragmentation and scalable concurrency support.
  [``BSD-2-Clause``][BSD-2-Clause]
* [Lockless Memory Allocator][451] - Efficient memory allocator.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libcsptr][66] - Smart pointers for C. [``MIT``][MIT]
* [rpmalloc][126] - Thread-caching, fast memory allocator, naturally aligned on
  32-byte boundaries. Public domain.
* [talloc][353] - Hierarchical, reference-counted memory pool system with
  destructors. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [tlsf][531] - Two-Level Segregated Fit allocator; a general-purpose, dynamic
  memory allocator designed to meet real-time requirements. [Up-to-date
  implementation][532]. [``BSD-3-Clause``][BSD-3-Clause]

## Multimedia ##

* [aubio][523] - Library for audio and music analysis. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [FFMPEG][63] - Complete, cross-platform solution to record, convert and
  stream audio and video. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [GStreamer][123] - Framework for audio and visual media. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libmpv][348] - Music-playing library. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [libsndfile][458] - Library for reading and writing sound files. Supports
  many formats. [``LGPL-2.1-only``][LGPL-2.1-only] or
  [``LGPL-3.0-only``][LGPL-3.0-only]
* [libsoundio][372] - Library for cross-platform, real-time audio input and
  output. Has a range of back-ends. [``MIT``][MIT]
* [libVLC][556] - Complete multimedia library for audio and video
  encoding, decoding, playing and streaming. [``GPL-2.0-only``][GPL-2.0-only]
* [lodepng][69] - Simple PNG image decoder and encoder, requiring no other
  dependencies. [``BSD-3-Clause``][BSD-3-Clause]
* [minimp3][536] - Lightweight MP3 decoder single header library. [``CC0-1.0``][CC0-1.0]
* [Soundpipe][513] - Lightweight music DSP library. [``MIT``][MIT]

## Networking and Internet ##

Low-level networking and internet-related stuff. If you want something more
comprehensive and high-level, you may want the Web Frameworks section.

* [asnlc][138] - Compiler of ASN.1 specifications into C source code. [``BSD-2-Clause``][BSD-2-Clause]
* [CHL][422] - C Hypertext Library - A library for writing web applications in
  C. [``GPL-3.0-only``][GPL-3.0-only]
* [czmq][226] - High-level binding for ZeroMQ. [``MPL-2.0``][MPL-2.0]
* [Dyad.c][554] - Lightweight, easy, asynchronous networking library. [``MIT``][MIT]
* [GNU adns][155] - Advanced, easy-to-use, asynch-capable DNS client library
  and utilities. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [gumbo-parser][196] - HTML5 parsing library in C99.
  [``Apache-2.0``][Apache-2.0]
* [H20][127] - A new-generation HTTP server. [``MIT``][MIT]
* [llhttp][197] - HTTP request/response parser. [``MIT``][MIT]
* [ldns][339] - Library to simplify DNS programming.
  [``BSD-3-Clause``][BSD-3-Clause]
* [libcurl][65] - Client-side URL transfer library, supporting a wide range of
  formats. [``curl``][curl]
* [LibEtPan][222] - Mail library providing an efficient network for IMAP,
  SMTP, POP and NNTP. [``BSD-3-Clause``][BSD-3-Clause]
* [libev][144] - Yet another event loop. [``BSD-2-Clause``][BSD-2-Clause]
* [libevent][124] - Event loop replacement for network servers. [``BSD-3-Clause``][BSD-3-Clause]
* [libhttpd][166] - Library to add basic web server capabilities to an
  application or embedded device. [``GPL-2.0-only``][GPL-2.0-only]
* [libhv][564] - Cross platform event loop library. [``BSD-3-Clause``][BSD-3-Clause]
* [libidn][164] - Implementation of the Stringprep, Punycode and IDNA
  specifications. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libmicrohttpd][165] - Small library that makes it easy to run an HTTP
  server as part of another application. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libnl][582] - `libnl` is a collection of libraries to provie APIs to the
  Netlink protocol (replacement for ioctl). It's primary use is to communicate
  with the Linux kernel, to modify networking state (interfaces, routing etc...).
  [``LGPL-2.1-only``][LGPL-2.1-only]
* [libonion][170] - HTTP server library, designed to be easy to
  use. [``Apache-2.0``][Apache-2.0]
* [libpcap][566] - API provides to various kernel packet capture mechanism. [``BSD-3-Clause``][BSD-3-Clause]
* [libquickmail][399] - Library intended to give developers a way to send
  email from their applications. Supports multiple To/Cc/Bcc recipients and
  attachments without size limits. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libsagui][172] - Library for cross-platform HTTP servers. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [libuhttpd][577] - A very flexible, lightweight and fully asynchronous HTTP server
  library based on libev and http-parser for Embedded Linux. [``MIT``][MIT]
* [LibVNCServer][464] - Cross-platform libraries to implement VNC server and/or
  client functionality. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [libwebsock][261] - Easy-to-use and powerful web socket library.
  [``LGPL-3.0-only``][LGPL-3.0-only]
* [libzmq][581] - Core ZeroMQ library, a high-performance asynchronous
  messaging library, aimed at use in distributed or concurrent applications.
  C API (backend C++) [``GPL-3.0-or-later``][GPL-3.0-or-later] with static
  linking exception
* [lwan][199] - Experimental, scalable, high-performance HTTP
  server. [``GPL-2.0-only``][GPL-2.0-only]
* [mongoose][171] - Embedded web server. [``GPL-2.0-only``][GPL-2.0-only]
* [MQTT-C][549] - A portable MQTT C client for embedded systems and PCs alike. [``MIT``][MIT]
* [nanomsg][139] - C-based implementation of ZeroMQ. [``MIT``][MIT]
* [NNG][106] - nanomsg-next-generation - lightweight brokerless messaging.
  [``MIT``][MIT]
* [oSip][179] - SIP implementation without additional
  dependencies. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [silgy][579] - Asynchronous HTTP(S) engine for C/C++ projects. [``MIT``][MIT]
* [socket99][203] - C99 wrapper for the BSD sockets API. [``ISC``][ISC]
* [twitc][237] - Mini library for interacting with the Twitter OAuth API. [``MIT``][MIT]
* [uriparser][100] - Strictly RFC 3986-compliant URI parsing and handling library.
  [``BSD-3-Clause``][BSD-3-Clause]
* [Wslay][460] - WebSocket library. Implements version 13 of the WebSocket
  protocol, as described in RFC 6455. [``MIT``][MIT]
* [zyre][419] - Framework for proximity-based peer-to-peer applications. [``MPL-2.0``][MPL-2.0]

## Numerical ##

* [apophenia][188] - Library for statistical and scientific computing. [``GPL-2.0-only``][GPL-2.0-only]
* [Arb][497] - Library for arbitrary-precision interval arithmetic.
  [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [ATLAS][137] - Automatically Tuned Linear Algebra Software. [``BSD-3-Clause``][BSD-3-Clause]
* [clBLAS][439] - BLAS functions written in OpenCL. [``Apache-2.0``][Apache-2.0]
* [cmathl][546] - Math library with a great variety of mathematical functions with CMake build support. Seeks to be close to C89/C90 compliant for portability. [``MIT``][MIT]
* [Cuba][316] - Library for multidimensional numerical integration. [``LGPL-3.0-only``][LGPL-3.0-only]
* [fft-c][537] - A high-performance Fourier Transform from netlib's fftpack; wrapped in a user-friendly format [``MIT``][ MIT]
* [FFTW][70] - The Fastest Fourier Transform in the West; a highly optimized
  fast Fourier transform routine. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [FLINT][255] - Fast Library for Number Theory; a library supporting arithmetic
  with numbers, polynomials, power series and matrices, among
  others. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [GLPK][159] - GNU Linear Programming Kit; a package designed for solving
  large-scale linear programming, mixed integer programming and other related
  problems. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GMP][79] - GNU Multple Precision Arithmetic Library; a library for
  arbitrary-precision arithmetic. [``GPL-2.0-only``][GPL-2.0-only] or [``LGPL-3.0-only``][LGPL-3.0-only]
* [GNU MPC][175] - Library for complex number arithmetic. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [GNU MPFR][176] - Library for arbitrary-precision floating-point
  arithmetic. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [GNU MPRIA][177] - Portable mathematics library for multi-precision rational
  interval arithmetic. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GSL][47] - The GNU Scientific Library; a sophisticated numerical
  library. [``GPL-3.0-only``][GPL-3.0-only].
* [KISS FFT][71] - Simple fast Fourier transform library. [``BSD-3-Clause``][BSD-3-Clause]
* [LAPACKE][133] - Interface to [LAPACK][134]. [``BSD-3-Clause``][BSD-3-Clause]
* [LibTomMath][461] - Portable, number-theoretic, multiple-precision integer
  library. Supports algebra, digit manipulation, modular reductions, and various
  number-theoretic routines. Public domain.
* [LibTomPoly][463] - Polynomial-related maths library. Public domain.
* [PARI/GP][256] - Computer algebra system for number theory; includes a
  compiler to C. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [PETSc][282] - Suite of data structures and routines for scalable parallel
  solution of scientific applications modelled by partial differential
  equations. [``BSD-2-Clause``][BSD-2-Clause]
* [SCS][483] - Splitting Conic Solver; a numerical optimization package for
  solving large-scale convex cone problems. [``MIT``][MIT]
* [SLEPc][283] - Library for the solution of large, sparse eigenvalue
  problems on parallel computers. [``LGPL-3.0-only``][LGPL-3.0-only]
* [TomsFastMath][462] - Set of optimized maths operations (in assembly),
  suitable for cryptographic use. Public domain.
* [Yeppp!][72] - Fast, SIMD-optimized mathematical library. [``BSD-3-Clause``][BSD-3-Clause]

## Profiling ##

* [gperftools][295] - Collection of utilities for measuring and improving
  performance. [``BSD-3-Clause``][BSD-3-Clause]
* [gprof][86] - Performance analysis tool. Part of GNU binutils.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [OProfile][475] - Statistical profiler for Linux. Can profile any code
  (including the kernel!) with low overhead and without recompilation. [``GPL-2.0-only``][GPL-2.0-only]
* [perf][375] - Linux kernel-based profiler with a lot of functionality.
  [``GPL-2.0-only``][GPL-2.0-only]

## PDF ##

* [pdfio][612] - PDFio is a simple C library for reading and writing PDF files.[``Apache-2.0``][Apache-2.0]

## Regex ##

* [Onigmo][518] - Fork of Oniguruma, supporting more advanced regexps.
  [``BSD-2-Clause``][BSD-2-Clause]
* [Oniguruma][517] - Regex library supporting a wide range of encodings, and
  incorporating many security-oriented fixes. [``BSD-2-Clause``][BSD-2-Clause]
* [PCRE][83] - Implementation of regexes identical to that of
  Perl 5. [``BSD-3-Clause``][BSD-3-Clause]
* [SLRE][80] - Super Light Regular Expression library; a small
  implementation of a subset of Perl regex syntax.
  [``GPL-2.0-only``][GPL-2.0-only]
* [TRE][82] - POSIX-compliant, feature-full regex library. [``BSD-2-Clause``][BSD-2-Clause]

## Serialization ##

* [binn][400] - Binary serialization format, meant to be compact, fast and
  easy-to-use. [``Apache-2.0``][Apache-2.0]
* [c-capnproto][130] - Implementation of the Cap'n Proto serialization
  protocol. [``MIT``][MIT]
* [cmp][377] - Implementation of the [MessagePack][379] serialization
  protocol. [``MIT``][MIT]
* [flatcc][187] - [FlatBuffers][145] compiler and library.
  [``Apache-2.0``][Apache-2.0]
* [libavro][140] - Implementation of the Avro data serialization system. [``Apache-2.0``][Apache-2.0]
* [mpack][378] - Another implementation of the [MessagePack][379] serialization
  protocol. [``MIT``][MIT]
* [OPIC][397] - Object Persistence in C; a revolutionary serialization framework,
  with matching on-disk and in-memory representations. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [protobuf-c][129] - Implementation of Google Protocol Buffer. [``BSD-2-Clause``][BSD-2-Clause]
* [tpl][473] - Small binary serialization library. [``MIT``][MIT]
* [xdr][131] - External Data Representation; a standard for data
  serialization. Standard (no license applicable).
* [pbtools][555] - Google Protocol Buffers C source code generator. [``MIT``][MIT]

## Source Code Collections ##

Collections of small source code. If you want something big and integrated, check
the Frameworks section.

* [CCAN][103] - Modelled after Perl's CPAN, this is a big collection of code
  that does stuff. The full list is [here][104]. Various licenses, all
  open source.
* [clib][26] - Something of a package manager. Comes with
  a [bunch of libraries of its own][27]. [``MIT``][MIT]
* [gnulib][46] - Collection of common GNU code. Various licenses, all
  open source.
* [libdjb][292] - Collection of libraries doing various things. (Apparently)
  public domain.
* [mmx][448] - Collection of single-header libraries. Various licenses, all
  open source.
* [par][456] - Bunch of single-file libraries. [``MIT``][MIT]
* [Snippets][220] - Useful code snippets and header-only libraries.
  Public domain.
* [stb][114] - Range of single-file libraries. Public domain.
* [tinyheaders][108] - Collection of header-only libraries, primarily oriented
  toward game development. [``Zlib``][Zlib]
* [zpl][602] - C99 cross-platform header-only library with many goodies. [``BSD-3-Clause``, ``Unlicense``][BSD-3-Clause, Unlicense]

## Standard Libraries ##

Implementations of the (standard-mandated) C standard library.

* [Bionic][4] - Google's standard library, developed for Android. [``BSD-3-Clause``][BSD-3-Clause]
* [cloudlibc][486] - Standard library based on the concept of
  [capability-based security][487]. [``BSD-2-Clause``][BSD-2-Clause]
* [dietlibc][9] - Standard library designed for the smallest possible
  binaries. [``GPL-2.0-only``][GPL-2.0-only]
* [glibc][57] - The GNU C Library; an implementation of the standard
  library. [``LGPL-2.1-only``][LGPL-2.1-only].
* [musl][10] - Standard library, compatible with POSIX 2008 and C11. Designed
  for static linking. [``MIT``][MIT]
* [PDCLib][447] - The Public Domain C Library. Implements most of C99 and some of
  C11. [``CC0-1.0``][CC0-1.0]
* [uClibc-ng][12] - Small C library for developing embedded systems.
  [``LGPL-2.1-or-later``][LGPL-2.1-or-later]

### Template libraries

* [CTL][613] - C CONTAINER TEMPLATE LIBRARY (CTL) [``MIT``][MIT]

## String Manipulation ##

* [bstring][116] - The Better String Library. [``BSD-3-Clause``][BSD-3-Clause]
* [ICU][67] - International Components for Unicode; a library for Unicode
  support. [``ICU``][ICU]
* [levenstein.c][360] - [Levenstein distance][334] algorithm implementation.
  [``MIT``][MIT].
* [libunistring][173] - Library for manipulating Unicode
  strings. [``LGPL-3.0-only``][LGPL-3.0-only]
* [libgiconv][163] - Text conversion library. [``LGPL-2.1-only``][LGPL-2.1-only]
* [librope][479] - UTF-8 rope ('heavy' string) library. [``MIT``][MIT]
* [SDS][29] - Simple Dynamic Strings; a library for handling strings in a
  simpler way, but one that is compatible with normal C string
  functions. Available via [clib][26]. [``BSD-2-Clause``][BSD-2-Clause]
* [stmr.c][383] - [Porter Stemmer][367] algorithm implementation. [``MIT``][MIT]
* [str][587] - Yet another string library for C language. [``BSD-3-Clause``][BSD-3-Clause]
* [StringZilla][623] - Up to 10x faster SIMD and SWAR-accelerated string search, sort, hashes, edit distances, alignments, and generators. [``Apache-2.0``][Apache-2.0]
* [utf8.h][472] - Single-header UTF-8 library, designed to mimic C-style string
  functions. Public domain.
* [utf8proc][469] - Library for processing UTF-8 data. [``MIT``][MIT]

## Structured File Processing ##

This includes libraries for things like XML, JSON, CSV, and other similar formats.

### CSV ###

* [libcsv][387] - Simple, streaming CSV parser. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]

### JSON ###

* [Jansson][53] - Library for encoding, decoding and manipulating JSON. [``MIT``][MIT]
* [jfes][488] - JSON For Embedded Systems; simple JSON engine without any
  dependencies. [``MIT``][MIT]
* [jsmn][120] - Minimalistic JSON parser. [``MIT``][MIT]
* [json][39] - Simple, low-memory-use JSON parser. [``MIT``][MIT]
* [json-c][8] - Easily work with JSON in C. Comes with a reference-counted object
  model, and aims for conformance with [RFC 7159][11]. [``MIT``][MIT]
* [json.h][431] - Single-file non-streaming JSON parser. [``Unlicense``][Unlicense]
* [parson][32] - Two-file, C89-compatible JSON parser. [``MIT``][MIT]
* [WJElement][77] - Advanced JSON manipulation library, with support for JSON
  Schema. [``LGPL-2.0-or-later``][LGPL-2.0-or-later] or
  [``LGPL-2.1-or-later``][LGPL-2.1-or-later] or [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [YAJL][60] - Fast streaming JSON parser library. [``ISC``][ISC]

### INI ###

* [inih][547] - Small and simple INI file parser, good for embedded systems. [``BSD-3-Clause``][BSD-3-Clause]
* [iniparser][336] - Parser for .ini files. [``MIT``][MIT]
* [libconfini][122] - Yet another INI parser. [``GPL-3.0-only``][GPL-3.0-only]
* [minIni][109] - Small and portable INI parser. [``Apache-2.0``][Apache-2.0]

### Others ###

* [libbson][235] - BSON utility library. [``Apache-2.0``][Apache-2.0]
* [libcbor][573]: CBOR protocol implementation for C and others. [``MIT``][MIT]
* [libconfuse][135] - Small configuration file parser library. [``ISC``][ISC]
* [libelf][310] - Simple library for parsing ELF files. [``MIT``][MIT]
* [libucl][239] - Universal configuration library parser. [``BSD-2-Clause``][BSD-2-Clause]
* [libxo][407] - Allows an application to generate plain text, XML, JSON and
  HTML output using a common set of function calls. The application decides at runtime what output style should be produced. [``BSD-2-Clause``][BSD-2-Clause]

### XML ###

* [Expat][89] - Stream-oriented XML parser. [MIT][MIT]
* [libxml2][62] - Standards-compliant, portable XML parser. [MIT][MIT]
* [xml][569] - Simple, low-memory-use XML parser / tokenizer. [``MIT``][MIT]

### YAML ###

* [libYAML][341] - YAML 1.1 parser and emitter. [``MIT``][MIT]

## Signal Processing ##

* [libsigrok][601] -  signal analysis software suite that supports various
device types (such as logic analyzers, oscilloscopes, multimeters, and more). [``GPL``][GPL]

## Testing ##

* [CHEAT][84] - Simple unit testing framework. [``BSD-2-Clause``][BSD-2-Clause]
* [Check][59] - Unit testing framework. [``LGPL-2.1-only``][LGPL-2.1-only]
* [ciut][5] - A modern minimal hassle unit test framework. [``MIT``][MIT]
* [clar][470] - Clear and simple unit testing framework. [``MIT``][MIT]
* [CMock][297] - Mock/stub generator. [``MIT``][MIT]
* [cmocka][141] - Unit testing framework with support for mock objects. [``Apache-2.0``][Apache-2.0]
* [Criterion][246] - KISS, non-intrusive test framework. [``MIT``][MIT]
* [ctest][503] - Yet another unit testing framework. [``Apache-2.0``][Apache-2.0]
* [CUnit][94] - Another unit testing framework.
  [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [greatest][58] - Unit testing library in one file, with no memory
  allocation. [``ISC``][ISC]
* [minctest][394] - Unit testing microlibrary. [``BSD-3-Clause``][BSD-3-Clause]
* [munit][392] - Small unit testing framework. [``MIT``][MIT]
* [Nala][560] - A test framework for C projects. [``MIT``][MIT]
* [Rexo][563] - Framework for C89/C++ featuring automatic registration of tests and a polished API. [``Unlicense``][Unlicense]
* [Tau][609] -  A Micro Unit testing framework for C/C++ (~1k lines of code). Includes a rich set of assertion macros, supports automatic test 
registration and can output to multiple formats, like the TAP format or JUnit XML. Supported on Linux, macOS, FreeBSD, and Windows. [``MIT``][MIT]
* [theft][302] - Property-based testing (similar to [Quickcheck][301]). [``MIT``][MIT]
* [Unity][296] - Simple unit testing framework. [``MIT``][MIT]
* [utest][386] - Single-header unit testing library. [``Unlicense``][Unlicense]

## Text Editor Extensions ##

While practically any decent programmer's text editor supports C, there are some
extensions that make it more pleasant. These are labelled by editor.

* [CCompletion][92] - Notepad++ autocompletion plugin. Works with all
  identifiers recognized by Ctags. This is a download link. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [CEDET][250] - Collection of Emacs Development Environment Tools; designed to
  provide IDE-like features to Emacs. Built-in.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Flycheck][149] - Modern syntax checking for Emacs. For C, it can use either
  GCC or Clang as a back-end. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Neomake][441] - Async :make and linting framework for Neovim/Vim. [``MIT``][MIT]
* [Syntastic][186] - Syntax checking and linting for Vim. [``WTFPL``][WTFPL]
* [YASnippet][150] - Emacs code template system, with C templates for common
  snippets. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [YouCompleteMe][151] - Code completion engine for Vim.
  [``GPL-3.0-only``][GPL-3.0-only]

## Tools ##

Useful programs to help you write and debug C code which are *not* editors,
libraries or compilers.

* [Artistic Style][314] - Fast and small automatic source code formatter that
  supports C. [``LGPL-3.0-only``][LGPL-3.0-only]
* [address-sanitizer][288] - Fast memory error detector.
  [``Apache-2.0``][Apache-2.0]
* [bcc][619] - A byte array generator to import binary files directy from C in
  the spirit of xxd. [``ISC``][ISC]
* [c][276] - Compile and execute C "scripts" in one go on the command line. Also
  has shebang support. [``MIT``][MIT]
* [c99sh][113] - Run C files using hash-bang. [``BSD-2-Clause``][BSD-2-Clause]
* [cdecl][347] - Online service to translate C declarations into English and
  vice versa. Public domain.
* [cinclude2dot][280] - Graphs include dependencies in a project using
  Graphviz. [GPL-1.0-or-later][335] or [``GPL-2.0-or-later``][GPL-2.0-or-later] or
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [ClangCheck][502] - Static analysis tool, designed to work with Clang.
  [``NCSA``][NCSA]
* [conan.io][304] - Something of a package manager for C. [``MIT``][MIT].
* [Cppcheck][501] - Static analysis tool. Despite the name, works well with C.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Glade][328] - RAD tool to enable quick development of GTK+
  GUIs. [``GPL-2.0-only``][GPL-2.0-only]
* [GMSL][331] - GNU Make Standard Library; a collection of additional
  functionality for GNU Make. [``BSD-3-Clause``][BSD-3-Clause]
* [GNU Global][330] - Source code tagging tool. [``GPL-3.0-only``][GPL-3.0-only]
* [GPP][269] - General-purpose preprocessor. More versatile than the C
  preprocessor, but more flexible than m4.
  [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [Highlight][333] - Converts source code to formatted text with nice
  highlighting. [``GPL-3.0-only``][GPL-3.0-only]
* [include-what-you-use][289] - Helps find unecessary inclusions and make
  suggestions for fixing them. Based on LLVM/Clang (and only works with
  it). [``NCSA``][NCSA]
* [incbin][592] - Include binary files in your C/C++ applications with ease [``Unlicense``][Unlicense]
* [indent][315] - Formats C source code automatically to make it easier to
  read. Also converts from one style of source to another. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [SMACK][500] - Modular software verification toolchain and a self-contained
  software verifier. Currently only works with programs compiled using Clang.
  [``MIT``][MIT]
* [unifdef][290] - Removes #ifdef and #if directives with their delimited text
  without touching any other part of the file. [``BSD-3-Clause``][BSD-3-Clause] or
  [``BSD-2-Clause``][BSD-2-Clause]

## Utilities ##

A 'catch-all' category for anything that doesn't fit well anywhere else.

* [ApeTagLibs][345] - Library for working with APEv2 tags. [``MIT``][MIT]
* [argparse][413] - Command-line argument parsing library, inspired by
  Python's argparse module. [``MIT``][MIT]
* [attr][425] - Commands for manipulating filesystem extended
  attributes. [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [bfd][157] - Library for manipulating binary object files. Part of GNU
  binutils. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Caffeine][496] - Library for building daemons and services for Linux and
  FreeBSD systems. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [CException][298] - Implementation of exceptions. [``MIT``][MIT]
* [CommonMark][223] - Implementation of the CommonMark spec.
* [cosmopolitan][597] - fast portable static native textmode containers (build C programs for Linux\Mac\Windows in one go)
  [Variety of licenses, all open source][224].
* [cpu\_features][319] - Get CPU features at runtime. [``Apache-2.0``][Apache-2.0].
* [CRIU][440] - Checkpoint/Restore In Userspace; a software tool (with a C API)
  for 'freezing' a running application to disk, then restoring
  it. [``GPL-2.0-only``][GPL-2.0-only] or [``LGPL-2.1-only``][LGPL-2.1-only]
* [D-Bus][430] - Simple way for applications to talk to one
  another. [``AFL-2.1``][AFL-2.1] or [``GPL-2.0-or-later``][GPL-2.0-or-later]
* [Discount][438] - Simple implementation of a Markdown parser. [``BSD-3-Clause``][BSD-3-Clause]
* [dlx][388] - Implementation of [Knuth's Algorithm X][389], with example
  solvers. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [docopt.c][270] - Implementation of a command-line option parser. [``MIT``][MIT]
* [dyncall][281] - Another foreign function interface library. [``MIT``][MIT]
* [GNU FreeIPMI][158] - In-band and out-of-band IPMI
  implementation. [``GPL-3.0-only``][GPL-3.0-only]
* [GNU gperf][351] - Perfect hash function generator, given a list of
  strings. Outputs C code. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [GNU Libffcall][162] - Collection of libraries for building foreign function
  interfaces. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Hoedown][405] - Fully standards-compliant, extension-supporting, UTF-8
  aware, fast Markdown parser. [``MIT``][MIT]
* [Kitsune][355] - Efficient, general-purpose framework for dynamic software
  updating. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [libCello][96] - Library introducing higher-level programming to
  C. [``BSD-3-Clause``][BSD-3-Clause]
* [libcmark][436] - Library for parsing the CommonMark dialect of
  Markdown. [``BSD-2-Clause``][BSD-2-Clause]
* [libcoap][136] - Implementation of the [Constrained Application Protocol][117].
  [``GPL-2.0-or-later``][GPL-2.0-or-later] or [``BSD-2-Clause``][BSD-2-Clause]
* [libcox][373] - Library which permits cross-platform system calls and
  standard utilities across different operating systems.
  [``BSD-2-Clause``][BSD-2-Clause]
* [libffi][128] - Portable foreign-function interface library. [``MIT``][MIT]
* [libgeohash][499] - Pure C implementation of the Geohash algorithm.
  [``BSD-3-Clause``][BSD-3-Clause]
* [libgit2][61] - Portable implementation of the Git core methods, provided as a
  re-entrant linkable library. [Custom license][41].
* [libgss][161] - Generic Security Service.
  [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [libimobiledevice][354] - Cross-platform protocol library to communicate
  with iThings. [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libnfc][332] - Platform-independent Near-Field Communication
  library. [``LGPL-3.0-only``][LGPL-3.0-only]
* [libpostal][434] - Library for parsing and normalization of street addresses
  around the world. Powered by statistical NLP and open geo data. [``MIT``][MIT]
* [libtrading][455] - Implementation of network protocols for communicating
  with exchanges, dark pools and other trading venues. Supports FIX, FIX/FAST
  and many proprietary protocols. [``BSD-2-Clause``][BSD-2-Clause]
* [libusb][306] - Provides generic access to USB devices.
  [``LGPL-2.1-or-later``][LGPL-2.1-or-later]
* [libuv][56] - Cross-platform asynchronous I/O. [``MIT``][MIT]
* [libvldmail][3] - Your friendly email validation library. No external
  dependencies (not even regexps). [``WTFPL``][WTFPL]
* [linenoise][504] - Small, self-contained alternative to readline and
  libedit. [``BSD-2-Clause``][BSD-2-Clause]
* [libXDGdirs][589] - An implementation of XDG Base Directory Specification
  [``MIT``][MIT]
* [MegaMimes][31] - Library for getting the [MIME][30] types of a file.
  [``MIT``][MIT]
* [ncurses][178] - Coloured terminal UI library. [``MIT``][MIT]
* [netbsd-curses][494] - Simplified and small version of ncurses, with the same
  interface. [``BSD-3-Clause``][BSD-3-Clause]
* [nope.c][209] - Ultra-light software platform for scalable server-side and
  networking applications (think node.js for C programmers). [``GPL-2.0-only``][GPL-2.0-only]
* [obj.h][580] - A single-header supports OOP in pure C. [``MIT``][MIT]
* [parg][274] - A single-file reimplementation of ``getopt`` with better defaults.
  [``CC0-1.0``][CC0-1.0]
* [pbc][236] - Protocol buffers library. [``MIT``][MIT]
* [progressbar][453] - Easy-to-use library for displaying text progress bars.
  [``BSD-3-Clause``][BSD-3-Clause]
* [rabbitmq-c][228] - Client library for [RabbitMQ][229]. [``MIT``][MIT]
* [Ragel][54] - DSL for state machines that compiles to C. [``GPL-2.0-only``][GPL-2.0-only]
* [rmw][622] - safe-remove utility for the command line that can purge items from your waste directories after x number of days. [``GPL-3.0-or-later``][GPL-3.0-or-later]
* [Rogueutil][565] - Cross-platform library for creating text-based user
  interfaces (TUI) [``Apache-2.0``][Apache-2.0]
* [sort][190] - Collection of sorting routines, which type-specialize at
  compile-time with a user-defined type. [``MIT``][MIT]
* [termbox][396] - Library for writing text-based interfaces. [``MIT``][MIT]
* [tinyexpr][395] - Tiny recursive-descent parser, compiler and evaluation
  engine for simple mathematical expressions. [``BSD-3-Clause``][BSD-3-Clause]
* [tm][543] - ⏱ Timer and Timeline Utils for C. [``MIT``][MIT]
* [Tulip Indicators][449] - Library of functions for technical analysis of
  financial data. [``LGPL-3.0-or-later``][LGPL-3.0-or-later]
* [whereami][167] - One-file library for locating the current executable on the
  file system. [``WTFPL``][WTFPL]
* [XLSX I/O][344] - Cross-platform library for reading and writing .xlsx
  files. [``MIT``][MIT]
* [xlsx_drone][596] - Fast Microsoft Excel's *.xlsx reader. [``MIT``][MIT]  
* [zlog][437] - Reliable, pure C logging library.
  [``LGPL-2.1-only``][LGPL-2.1-only]
* [zproto][421] - Protocol framework for ZeroMQ. [``MIT``][MIT]
* [Metalang99][603] - Full-blown preprocessor metaprogramming. [``MIT``][MIT]
* [Datatype99][604] - Algebraic data types for C99. [``MIT``][MIT]
* [EasyLogger][706] - An ultra-lightweight, high-performance C/C++ log library. [``MIT``][MIT]

## Web Frameworks ##

Comprehensive and integrated solutions for building the next brilliant web
application in C.

* [Concord][617] - A Discord API wrapper library written in C. [``MIT``][MIT]
* [facil.io][118] - Mini-framework for web applications. Includes a fast HTTP and
  Websocket server, and also supports custom protocols. [``MIT``][MIT]
* [kcgi][562] - CGI and FastCGI library for C [``ISC``][ISC].
* [KLone][423] - Fully featured, multi-platform, web application development
  framework, targeted especially at embedded systems and
  appliances. [``BSD-3-Clause``][BSD-3-Clause]
* [Kore][415] - Easy-to-use web application framework for writing scalable
  web APIs in C. [``ISC``][ISC]

## Windows Environments ##

Technologies designed to bring Windows into the 21st century with respect to
support for C.

* [Cygwin][253] - Designed to emulate a POSIX-compatible environment extensively
  under Windows. [Various licenses, all open source][254].
* [MinGW-w64][287] - Minimalist environment for C development on Windows with
  64 bit support. [Various licenses, all open source][252].
* [MSYS2][428] - Minimal SYStem 2; aims to provide support for a POSIX
  environment on Windows, with a package manager based on Arch Linux's
  pacman. Packages have individual licenses, otherwise, as MinGW and Cygwin.


[AFL-2.1]: https://spdx.org/licenses/AFL-2.1.html
[AGPL-3.0-only]: https://spdx.org/licenses/AGPL-3.0-only.html
[AGPL-3.0-or-later]: https://spdx.org/licenses/AGPL-3.0-or-later.html
[Apache-2.0]: https://spdx.org/licenses/Apache-2.0.html
[BSD-1-Clause]: https://spdx.org/licenses/BSD-1-Clause.html
[BSD-2-Clause]: https://spdx.org/licenses/BSD-2-Clause.html
[BSD-3-Clause]: https://spdx.org/licenses/BSD-3-Clause.html
[BSD-4-Clause]: https://spdx.org/licenses/BSD-4-Clause.html
[CC0-1.0]: https://spdx.org/licenses/CC0-1.0.html
[curl]: https://spdx.org/licenses/curl.html
[GPL-2.0-only]: https://spdx.org/licenses/GPL-2.0-only.html
[GPL-2.0-or-later]: https://spdx.org/licenses/GPL-2.0-or-later.html
[GPL-3.0-only]: https://spdx.org/licenses/GPL-3.0-only.html
[GPL-3.0-or-later]: https://spdx.org/licenses/GPL-3.0-or-later.html
[ICU]: https://spdx.org/licenses/ICU.html
[ISC]: https://spdx.org/licenses/ISC.html
[LGPL-2.0-or-later]: https://spdx.org/licenses/LGPL-2.0-or-later.html
[LGPL-2.1-only]: https://spdx.org/licenses/LGPL-2.1-only.html
[LGPL-2.1-or-later]: https://spdx.org/licenses/LGPL-2.1-or-later.html
[LGPL-3.0-only]: https://spdx.org/licenses/LGPL-3.0-only.html
[LGPL-3.0-or-later]: https://spdx.org/licenses/LGPL-3.0-or-later.html
[Libpng]: https://spdx.org/licenses/Libpng.html
[MIT]: https://spdx.org/licenses/MIT.html
[MPL-2.0]: https://spdx.org/licenses/MPL-2.0.html
[NCSA]: https://spdx.org/licenses/NCSA.html
[OLDAP-2.8]: https://spdx.org/licenses/OLDAP-2.8.html
[PostgreSQL]: https://spdx.org/licenses/PostgreSQL.html
[TCL]: https://spdx.org/licenses/TCL.html
[Unlicense]: https://spdx.org/licenses/Unlicense.html
[WTFPL]: https://spdx.org/licenses/WTFPL.html
[X11]: https://spdx.org/licenses/X11.html
[Zlib]: https://spdx.org/licenses/Zlib.html

[1]: https://github.com/Dead2/zlib-ng
[2]: https://github.com/Cyan4973/FiniteStateEntropy
[3]: https://github.com/dertuxmalwieder/libvldmail
[4]: https://github.com/aosp-mirror/platform_bionic
[5]: https://github.com/yhfudev/cpp-ci-unit-test.git
[6]: https://port70.net/~nsz/c/c89/c89-draft.html
[7]: https://en.wikipedia.org/wiki/The_C_Programming_Language
[8]: https://github.com/json-c/json-c
[9]: https://www.fefe.de/dietlibc/
[10]: https://musl.libc.org/
[11]: https://tools.ietf.org/html/rfc7159
[12]: https://uclibc-ng.org/
[13]: https://opensource.org/osd
[14]: https://www.gtk.org/

[16]: http://webserver2.tecgraf.puc-rio.br/iup/
[17]: https://github.com/saitoha/libsixel
[18]: https://www.enlightenment.org?p=about%252Flibs
[19]: http://www.tcl.tk/

[21]: http://xforms-toolkit.org/
[22]: https://www.sqlite.org/
[23]: https://unqlite.org/
[24]: https://github.com/google/brotli
[25]: https://en.wikipedia.org/wiki/Dynamic_array
[26]: https://github.com/clibs/clib
[27]: https://github.com/clibs/clib/wiki/Packages
[28]: http://www.koanlogic.com/libu/
[29]: https://github.com/antirez/sds
[30]: https://en.wikipedia.org/wiki/MIME
[31]: https://trumpowen.github.io/MegaMimes
[32]: https://github.com/kgabis/parson
[33]: https://www.codeproject.com/Articles/6154/Writing-Efficient-C-and-C-Code-Optimization
[34]: http://re2c.org/index.html
[35]: http://shop.oreilly.com/product/0636920033677.do
[36]: http://shop.oreilly.com/product/0636920028000.do
[37]: https://www.openmp.org/
[38]: https://clang.llvm.org/
[39]: https://github.com/recp/json
[40]: https://gcc.gnu.org/
[41]: https://github.com/libgit2/libgit2/blob/master/COPYING
[42]: http://anjuta.org/
[43]: https://www.geany.org/
[44]: https://www.kdevelop.org/
[45]: https://www.codelite.org/
[46]: https://www.gnu.org/software/gnulib/
[47]: https://www.gnu.org/software/gsl/
[48]: https://liballeg.org
[49]: https://github.com/vasi/pixz
[50]: https://www.libsdl.org/
[51]: https://redis.io/
[52]: http://zeromq.org/
[53]: http://www.digip.org/jansson/
[54]: http://www.colm.net/open-source/ragel/
[55]: https://dl.acm.org/citation.cfm?id=179241
[56]: http://libuv.org
[57]: https://www.gnu.org/software/libc/
[58]: https://github.com/silentbicycle/greatest
[59]: https://libcheck.github.io/check
[60]: https://lloyd.github.io/yajl/
[61]: https://libgit2.org/
[62]: http://xmlsoft.org/
[63]: https://www.ffmpeg.org/
[64]: http://knking.com/books/c2/index.html
[65]: https://curl.haxx.se/libcurl/
[66]: https://github.com/Snaipe/libcsptr
[67]: http://site.icu-project.org/
[68]: https://libspng.org/
[69]: https://lodev.org/lodepng/
[70]: http://www.fftw.org/
[71]: https://sourceforge.net/projects/kissfft/
[72]: https://bitbucket.org/MDukhan/yeppp
[73]: https://graphics.stanford.edu/~seander/bithacks.html
[74]: http://pcc.ludd.ltu.se/
[75]: http://pcc.ludd.ltu.se/licenses/
[76]: http://attractivechaos.github.io/klib/#About
[77]: https://github.com/netmail-open/wjelement/
[78]: http://apr.apache.org/
[79]: https://gmplib.org/
[80]: https://github.com/cesanta/slre
[81]: http://tiny-rex.sourceforge.net/
[82]: https://github.com/laurikari/tre/
[83]: http://www.pcre.org/
[84]: https://github.com/Tuplanolla/cheat
[85]: http://www.valgrind.org/
[86]: https://www.gnu.org/software/binutils/
[87]: https://www.gnu.org/software/gdb/
[88]: https://fragglet.github.io/c-algorithms
[89]: http://expat.sourceforge.net/
[90]: https://www.sfml-dev.org/download/csfml/
[91]: https://www.sfml-dev.org/index.php
[92]: http://freeweb.siol.net/rmihor/NppCCompletionPlugin.zip
[93]: https://github.com/keybuk/libnih
[94]: http://cunit.sourceforge.net/
[95]: https://rr-project.org/
[96]: http://libcello.org/
[97]: http://nethack4.org/projects/aimake/
[98]: https://www.glfw.org/
[99]: http://freeglut.sourceforge.net
[100]: https://uriparser.github.io
[101]: https://github.com/orangeduck/Corange
[102]: http://shop.oreilly.com/product/0636920015482.do
[103]: http://ccodearchive.net/
[104]: http://ccodearchive.net/list.html
[105]: https://www.symas.com/lmdb
[106]: https://nanomsg.github.io/nng/
[107]: https://ioquake3.org
[108]: https://github.com/RandyGaul/tinyheaders
[109]: https://github.com/compuphase/minIni
[110]: https://www.openssl.org/
[111]: https://www.openssl.org/source/license.html
[112]: http://www.gnutls.org/
[113]: https://github.com/RhysU/c99sh
[114]: https://github.com/nothings/stb
[115]: https://tinycthread.github.io/
[116]: http://mike.steinert.ca/bstring/
[117]: http://coap.technology/
[118]: http://facil.io/
[119]: https://www.enlightenment.org
[120]: https://zserge.com/jsmn.html
[121]: https://www.postgresql.org/
[122]: https://madmurphy.github.io/libconfini/html/index.html
[123]: https://gstreamer.freedesktop.org/
[124]: http://libevent.org/
[125]: https://www.hboehm.info/gc/
[126]: https://github.com/rampantpixels/rpmalloc
[127]: https://h2o.examp1e.net/
[128]: https://github.com/atgreen/libffi
[129]: https://github.com/protobuf-c/protobuf-c
[130]: https://github.com/jmckaskill/c-capnproto
[131]: https://en.wikipedia.org/wiki/External_Data_Representation
[132]: https://bitbucket.org/martijnj/msgpackalt
[133]: http://www.netlib.org/lapack/lapacke.html
[134]: http://www.netlib.org/lapack/
[135]: https://github.com/martinh/libconfuse
[136]: https://github.com/obgm/libcoap
[137]: http://math-atlas.sourceforge.net/
[138]: http://lionet.info/asn1c/compiler.html
[139]: https://github.com/nanomsg/nanomsg
[140]: http://avro.apache.org/docs/current/api/c/index.html#_introduction_to_avro_c
[141]: https://cmocka.org/
[142]: https://gnupg.org/related_software/libgcrypt
[143]: https://github.com/libressl-portable/
[144]: http://software.schmorp.de/pkg/libev.html
[145]: https://google.github.io/flatbuffers/
[146]: https://en.wikipedia.org/wiki/POSIX_Threads
[147]: https://www.opengl.org/
[148]: http://www.sgi.com/tech/opengl/?/license.html
[149]: https://github.com/flycheck/flycheck
[150]: http://joaotavora.github.io/yasnippet/
[151]: https://github.com/ycm-core/YouCompleteMe
[152]: https://sites.google.com/site/lccretargetablecompiler/
[153]: https://github.com/drh/lcc/blob/master/CPYRIGHT
[154]: https://github.com/swenson/vector.h
[155]: https://www.gnu.org/software/adns/
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
[166]: https://www.hughes.com.au/products/libhttpd/
[167]: https://github.com/gpakosz/whereami
[168]: http://www.webdav.org/neon/
[169]: http://mihl.sourceforge.net/
[170]: https://www.coralbits.com/libonion/
[171]: https://cesanta.com
[172]: https://risoflora.github.io/libsagui/
[173]: https://gnu.org/software/libunistring/
[174]: https://gnu.org/software/libxmi/
[175]: http://www.multiprecision.org/mpc/
[176]: http://mpfr.loria.fr/index.html
[177]: https://gnu.org/software/mpria/
[178]: https://gnu.org/software/ncurses/
[179]: https://gnu.org/software/osip/
[180]: https://gnu.org/software/pth/
[181]: https://savedparadigms.files.wordpress.com/2014/09/harbison-s-p-steele-g-l-c-a-reference-manual-5th-ed.pdf
[182]: http://shop.oreilly.com/product/9780596004361.do
[183]: http://shop.oreilly.com/product/0636920026136.do
[184]: https://www.pearson.com/us/higher-education/program/Prata-C-Primer-Plus-6th-Edition/PGM4399.html
[185]: http://www.planetpdf.com/codecuts/pdfs/ooc.pdf
[186]: https://github.com/vim-syntastic/syntastic
[187]: https://github.com/dvidelabs/flatcc
[188]: http://apophenia.info
[189]: https://github.com/b-k/apophenia/blob/master/install/COPYING
[190]: https://github.com/swenson/sort
[191]: http://steve-yegge.blogspot.co.nz/2008/10/universal-design-pattern.html
[192]: http://libjpeg.sourceforge.net/
[193]: https://libjpeg-turbo.virtualgl.org/
[194]: https://www.libjpeg-turbo.org/About/License
[195]: http://libccv.org/
[196]: https://github.com/google/gumbo-parser
[197]: https://llhttp.org
[198]: https://download.libsodium.org/doc
[199]: https://lwan.ws
[200]: https://github.com/mozilla/mozjpeg
[201]: https://github.com/redis/hiredis
[202]: https://jvns.ca/blog/2014/12/14/fun-with-threads/
[203]: https://github.com/silentbicycle/socket99
[204]: http://danluu.com/malloc-tutorial/
[205]: https://web.archive.org/web/20170620131430/https://www.tedunangst.com/flak/post/memcpy-vs-memmove
[206]: https://blogs.oracle.com/linux/8-gdb-tricks-you-should-know-v2
[207]: https://www.youtube.com/playlist?list=PLLX-Q6B8xqZ8n8bwjGdzBJ25X2utwnoEG
[208]: http://nethack4.org/blog/building-c.html
[209]: https://github.com/riolet/WAFer
[210]: https://docs.google.com/presentation/d/1h49gY3TSiayLMXYmRMaAEMl05FaJ-Z6jDOWOz3EsqqQ/edit?pli=1#slide=id.gaf50702c_0153
[212]: http://www.crasseux.com/books/ctut.pdf
[213]: https://pdos.csail.mit.edu/6.828/2017/readings/pointers.pdf
[214]: https://github.com/adamierymenko/huffandpuff
[215]: https://sourceforge.net/projects/vtd-xml/
[216]: https://michaelrsweet.github.io?Z3
[217]: http://svn.msweet.org/mxml/trunk/COPYING
[218]: http://ezxml.sourceforge.net/
[219]: https://github.com/blunderer/libroxml
[220]: https://github.com/DanielGibson/Snippets/
[221]: https://github.com/id-Software/Quake-2
[222]: http://www.etpan.org
[223]: https://github.com/commonmark/commonmark-spec
[224]: https://github.com/commonmark/commonmark-spec/blob/master/LICENSE
[225]: https://github.com/id-Software/Quake
[226]: http://czmq.zeromq.org
[227]: https://marek.vavrusa.com/memory/
[228]: https://github.com/alanxz/rabbitmq-c
[229]: http://www.rabbitmq.com/
[230]: http://zlib.net
[231]: https://github.com/libretro/RetroArch
[232]: https://www.libretro.com/
[233]: http://mongoc.org/
[234]: https://www.mongodb.org/
[235]: https://github.com/mongodb/libbson
[236]: https://github.com/cloudwu/pbc
[237]: https://github.com/sinemetu1/twitc
[238]: https://github.com/orangeduck/mpc
[239]: https://github.com/vstakhov/libucl
[240]: http://snaipe.me/c/c-smart-pointers/
[241]: https://github.com/gpakosz/PackedArray
[242]: http://concurrencykit.org
[243]: http://repo.hu/projects/cchan/
[244]: http://sophia.systems
[245]: http://www.greenend.org.uk/rjk/tech/inline.html
[246]: https://criterion.readthedocs.io/en/master
[247]: https://port70.net/~nsz/c/c11/n1570.html
[248]: https://en.wikibooks.org/wiki/C_Programming
[249]: http://www.codeblocks.org/
[250]: http://cedet.sourceforge.net/
[251]: http://mingw.org/
[252]: http://mingw.org/license
[253]: https://cygwin.com/
[254]: https://cygwin.com/licensing.html
[255]: http://flintlib.org/
[256]: http://pari.math.u-bordeaux.fr/
[257]: http://blog.noctua-software.com/c-tricks.html
[258]: https://port70.net/~nsz/c/c99/n1256.html
[259]: https://spdx.org/licenses/EPL-1.0.html
[260]: https://netbeans.org/
[261]: https://github.com/JonnyWhatshisface/libwebsock
[262]: http://c-faq.com/
[263]: https://computing.llnl.gov/tutorials/pthreads/
[264]: https://computing.llnl.gov/tutorials/openMP/
[265]: https://computing.llnl.gov/tutorials/mpi/
[266]: https://wiki.sei.cmu.edu/confluence/display/c/SEI+CERT+C+Coding+Standard
[267]: http://blog.pkh.me/p/20-templating-in-c.html
[268]: http://lipforge.ens-lyon.fr/www/crlibm/index.html
[269]: https://logological.org/gpp
[270]: https://github.com/docopt/docopt.c
[271]: https://xmake.io/
[273]: http://troydhanson.github.io/uthash/
[274]: https://github.com/jibsen/parg
[275]: http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html
[276]: https://github.com/ryanmjacobs/c
[277]: http://wolkykim.github.io/qlibc
[278]: https://github.com/wolkykim/qlibc/blob/master/LICENSE
[279]: https://gist.github.com/eatonphil/21b3d6569f24ad164365
[280]: https://www.flourish.org/cinclude2dot/
[281]: http://www.dyncall.org/
[282]: http://www.mcs.anl.gov/petsc/
[283]: http://slepc.upv.es/
[284]: https://github.com/open-mpi/ompi
[285]: http://www.mpich.org/
[286]: http://git.mpich.org/mpich.git/blob_plain/6aab201f58d71fc97f2c044d250389ba86ac1e3c:/COPYRIGHT
[287]: http://mingw-w64.yaxm.org/doku.php/start
[288]: https://github.com/google/sanitizers
[289]: https://github.com/include-what-you-use/include-what-you-use
[290]: http://dotat.at/prog/unifdef/
[291]: https://tls.mbed.org/
[292]: http://www.fefe.de/djb/
[293]: http://jemalloc.net
[295]: https://github.com/gperftools/gperftools
[296]: http://www.throwtheswitch.org/unity
[297]: http://www.throwtheswitch.org/cmock
[298]: http://www.throwtheswitch.org/cexception
[299]: https://www.libtom.net
[300]: https://pngquant.org/lib/
[301]: https://wiki.haskell.org/Introduction_to_QuickCheck2
[302]: https://github.com/silentbicycle/theft
[303]: http://chipmunk-physics.net
[304]: https://conan.io/
[305]: https://faragon.github.io/libsrt.html
[306]: https://libusb.info/
[307]: https://www.gnu.org/software/complexity/
[308]: http://www.eso.org/sci/software/cpl/
[309]: https://www.cprover.org/cbmc/
[310]: https://github.com/0intro/libelf
[311]: https://github.com/matze/oclkit
[312]: http://tuxfan.github.io/ocl-mla/
[313]: http://c2html.sourceforge.net/whatisc2html.html
[314]: http://astyle.sourceforge.net/
[315]: https://www.gnu.org/software/indent/
[316]: http://www.feynarts.de/cuba/
[317]: http://www.gedanken.org.uk/software/cxref/
[318]: http://www.doxygen.nl/
[319]: https://github.com/google/cpu_features
[320]: https://www.gnu.org/software/ddd/ddd.html
[321]: http://docutils.sourceforge.net/
[322]: https://hplgit.github.io/doconce/doc/web/index.html
[323]: http://fabutil.org/
[324]: https://www.gnu.org/software/make/
[325]: https://github.com/libfann/fann
[326]: https://github.com/centaurean/spookyhash
[327]: https://github.com/attractivechaos/kann
[328]: https://glade.gnome.org/
[329]: https://cmake.org/
[330]: https://www.gnu.org/software/global/
[331]: https://gmsl.sourceforge.net/
[332]: https://github.com/nfc-tools/libnfc
[333]: http://www.andre-simon.de/index.php
[334]: https://en.wikipedia.org/wiki/Levenshtein_distance
[335]: https://spdx.org/licenses/GPL-1.0.html
[336]: https://github.com/ndevilla/iniparser
[337]: https://github.com/jtsiomb/kdtree
[338]: http://www.oberhumer.com/opensource/lzo/
[339]: http://www.nlnetlabs.nl/projects/ldns/index.html
[340]: https://wiki.gnome.org/Projects/LibRsvg
[341]: https://www.pyyaml.org/wiki/LibYAML
[342]: https://www.xiph.org/ao/
[343]: https://www.chiark.greenend.org.uk/~sgtatham/mp/
[344]: https://brechtsanders.github.io/xlsxio/
[345]: https://github.com/jeremyevans/ape_tag_libs/tree/master/c
[346]: http://www.mission-base.com/peter/source/
[347]: https://cdecl.org/
[348]: https://mpv.io
[349]: https://www.recurse.com/blog/5-learning-c-with-gdb
[350]: https://github.com/P-p-H-d/mlib
[351]: https://www.gnu.org/software/gperf/
[352]: http://libmill.org/
[353]: https://talloc.samba.org/talloc/doc/html/index.html
[354]: https://github.com/libimobiledevice/libimobiledevice
[355]: http://kitsune-dsu.com/
[356]: https://github.com/abiggerhammer/hammer
[357]: http://250bpm.com/blog:56
[358]: https://web.archive.org/web/20170429175803/http://www.samnip.ps/thought/macro-storage-for-inverse-comma
[359]: https://github.com/awslabs/s2n
[360]: https://github.com/wooorm/levenshtein.c
[361]: https://pp.ipd.kit.edu/firm/
[362]: http://www.etalabs.net/compare_libcs.html
[363]: http://ed-von-schleck.github.io/shoco
[364]: https://github.com/antirez/smaz
[365]: https://github.com/prideout/heman
[366]: https://github.com/cacalabs/libcaca
[367]: http://tartarus.org/martin/PorterStemmer/
[368]: https://mesonbuild.com/
[369]: https://icculus.org/twilight/darkplaces/
[370]: http://orx-project.org
[371]: https://github.com/AlexanderAgd/CLIST
[372]: http://libsound.io
[373]: http://libcox.symisc.net/
[374]: https://proprogramming.org/some-unknown-features-or-tricks-in-c-language/
[375]: https://perf.wiki.kernel.org/index.php/Main_Page
[376]: https://xiph.org/ao/
[377]: https://github.com/camgunz/cmp
[378]: https://github.com/ludocode/mpack
[379]: https://msgpack.org/
[380]: http://www.oracle.com/us/products/database/berkeley-db
[381]: https://spdx.org/licenses/AGPL-1.0.html
[382]: http://www.libpng.org/
[383]: https://github.com/wooorm/stmr.c
[384]: http://cairographics.org/
[385]: https://spdx.org/licenses/MPL-1.1.html
[386]: https://github.com/evolutional/utest
[387]: https://github.com/rgamble/libcsv
[388]: https://github.com/blynn/dlx
[389]: https://en.wikipedia.org/wiki/Knuth's_Algorithm_X
[390]: https://github.com/sharow/libconcurrent
[391]: https://hintjens.gitbooks.io/scalable-c/content/index.html
[392]: https://nemequ.github.io/munit
[393]: https://github.com/quixdb/squash
[394]: https://github.com/codeplea/minctest
[395]: https://github.com/codeplea/tinyexpr
[396]: https://github.com/nsf/termbox
[397]: http://opic.rocks/
[398]: https://github.com/waruqi/tbox
[399]: http://sourceforge.net/projects/libquickmail/
[400]: https://github.com/liteserver/binn
[401]: https://sourceforge.net/projects/giflib/
[402]: https://github.com/libgd/libgd
[403]: https://embed.cs.utah.edu/creduce/
[404]: http://www.gnu.org/software/cflow/
[405]: https://github.com/hoedown/hoedown
[406]: https://github.com/srdja/Collections-C
[407]: https://github.com/Juniper/libxo
[408]: https://github.com/Immediate-Mode-UI/Nuklear
[409]: https://github.com/blunderer/libroxml
[410]: https://www.spinellis.gr/cscout/
[411]: https://liblfds.org/
[412]: https://codeplea.com/genann
[413]: https://github.com/cofyc/argparse
[414]: https://github.com/anholt/libepoxy
[415]: https://kore.io/
[416]: http://zeromq.org/
[417]: https://wiki.gnome.org/action/show/Projects/LibRsvg?action=show&redirect=LibRsvg
[418]: http://shop.oreilly.com/product/0636920033844.do
[419]: https://github.com/zeromq/zyre
[420]: https://github.com/zeromq/zproject
[421]: https://github.com/zeromq/zproto
[422]: https://github.com/it4e/CHL
[423]: http://www.koanlogic.com/klone/
[425]: http://savannah.nongnu.org/projects/attr/
[426]: https://sourceforge.net/projects/tinyfiledialogs/
[427]: http://www.bzip.org/
[428]: http://msys2.github.io/
[429]: http://www.libsigil.com/
[430]: https://www.freedesktop.org/wiki/Software/dbus/
[431]: https://github.com/sheredom/json.h
[432]: http://lzip.nongnu.org/clzip.html
[433]: http://lzip.nongnu.org/lzip.html
[434]: https://github.com/openvenues/libpostal
[435]: https://premake.github.io/
[436]: https://github.com/jgm/cmark
[437]: http://hardysimpson.github.io/zlog/
[438]: http://www.pell.portland.or.us/~orc/Code/discount/
[439]: https://github.com/clMathLibraries/clBLAS
[440]: https://criu.org/Main_Page
[441]: https://github.com/neomake/neomake
[442]: http://libdill.org/
[443]: https://nullprogram.com/blog/2015/02/17
[444]: https://github.com/ands/lightmapper
[445]: http://blosc.org/pages/blosc-in-depth
[446]: https://github.com/Kazade/kazmath
[447]: http://pdclib.e43.eu/
[448]: https://github.com/vurtun/mmx
[449]: https://tulipindicators.org/
[450]: https://locklessinc.com/benchmarks_allocator.shtml
[451]: https://locklessinc.com/
[452]: https://github.com/distcc/distcc
[453]: https://github.com/doches/progressbar
[454]: http://mpitutorial.com/
[455]: http://libtrading.org/
[456]: https://github.com/prideout/par
[457]: https://github.com/grimfang4/sdl-gpu
[458]: http://www.mega-nerd.com/libsndfile/
[459]: https://github.com/parallella/pal
[460]: https://tatsuhiro-t.github.io/wslay/
[461]: http://www.libtom.net/LibTomMath/
[462]: http://www.libtom.net/TomsFastMath/
[463]: http://www.libtom.net/LibTomPoly/
[464]: https://github.com/LibVNC/libvncserver
[465]: https://github.com/yosefk/checkedthreads
[466]: https://ccache.dev/
[467]: https://github.com/esneider/debug
[468]: https://lldb.llvm.org/
[469]: https://github.com/JuliaLang/utf8proc
[470]: https://github.com/vmg/clar
[471]: https://github.com/powturbo/TurboPFor
[472]: https://github.com/sheredom/utf8.h
[473]: https://github.com/troydhanson/tpl
[474]: http://liburcu.org/
[475]: http://oprofile.sourceforge.net/news/
[476]: http://libcork.readthedocs.io/en/0.14.0/
[477]: https://github.com/jppbsi/LibDEEP
[478]: https://github.com/xant/libhl
[479]: https://github.com/josephg/librope
[480]: https://github.com/miracl/MIRACL
[481]: https://github.com/RoaringBitmap/CRoaring
[482]: http://roaringbitmap.org/
[483]: https://github.com/cvxgrp/scs
[484]: https://github.com/powturbo/TurboRLE
[485]: https://github.com/trezor/trezor-crypto
[486]: https://github.com/NuxiNL/cloudlibc
[487]: https://en.wikipedia.org/wiki/Capability-based_security
[488]: https://github.com/NeonMercury/jfes
[489]: https://github.com/inikep/lizard
[490]: https://nullprogram.com/blog/2017/03/30
[491]: https://github.com/westes/flex
[492]: https://www.gnu.org/software/bison/
[493]: https://openquantumsafe.org/
[494]: https://github.com/sabotage-linux/netbsd-curses
[495]: https://github.com/lemire/clhash
[496]: https://github.com/dmw/caffeine
[497]: https://github.com/fredrik-johansson/arb
[498]: https://github.com/theck01/offbrand_lib
[499]: https://github.com/simplegeo/libgeohash
[500]: https://github.com/smackers/smack
[501]: http://cppcheck.sourceforge.net/
[502]: https://clang.llvm.org/docs/ClangCheck.html
[503]: https://github.com/bvdberg/ctest
[504]: https://github.com/antirez/linenoise
[505]: https://github.com/memononen/nanovg
[506]: https://github.com/centaurean/density
[507]: https://maciejczyzewski.github.io/retter
[508]: http://lz4.github.io/lz4/
[509]: https://github.com/spotify/sparkey
[510]: http://facebook.github.io/zstd/
[511]: https://libvips.github.io/libvips/
[512]: https://github.com/priitj/whitedb
[513]: http://paulbatchelor.github.io/proj/soundpipe.html
[514]: https://github.com/atomicobject/heatshrink
[515]: http://ebassi.github.io/graphene/
[516]: https://www.raylib.com
[517]: https://github.com/kkos/oniguruma
[518]: https://github.com/k-takata/Onigmo
[519]: https://github.com/lemire/simdcomp
[520]: https://github.com/kuba--/zip
[521]: https://www.scons.org/
[522]: http://cyan4973.github.io/xxHash
[523]: https://github.com/aubio/aubio
[524]: https://github.com/groonga/groonga
[525]: https://100.github.io/Cranium/
[526]: http://www.saphir2.com/sphlib/
[527]: https://github.com/google/highwayhash
[528]: http://nullprogram.com/blog/2017/08/20/
[529]: http://nullprogram.com/blog/2017/09/21/
[530]: https://github.com/leo-yuriev/t1ha
[531]: http://www.gii.upv.es/tlsf/
[532]: https://github.com/minad/tlsf
[533]: https://github.com/gildor2/fast_zlib
[534]: https://github.com/ferreiradaselva/mathc
[535]: https://github.com/ferreiradaselva/uastar
[536]: https://github.com/lieff/minimp3
[537]: https://github.com/adis300/fft-c
[538]: https://github.com/nbulischeck/list.h
[539]: https://github.com/shlomif/fc-solve
[540]: http://www.shlomifish.org/rwlock/
[541]: https://github.com/recp/ds
[542]: https://github.com/recp/cglm
[543]: https://github.com/recp/tm
[544]: https://igraph.org/
[546]: https://scientificc.github.io/cmathl/
[547]: https://github.com/benhoyt/inih
[548]: https://github.com/libarchive/libarchive
[549]: https://github.com/LiamBindle/MQTT-C
[550]: https://github.com/LeoVen/C-Macro-Collections
[551]: https://github.com/mysql/mysql-server
[553]: https://github.com/okuvshynov/b63
[554]: https://github.com/rxi/dyad
[555]: https://github.com/eerimoq/pbtools
[556]: https://wiki.videolan.org/LibVLC
[557]: https://github.com/SanderMertens/flecs
[558]: https://github.com/librg/librg
[559]: https://github.com/superjer/tinyc.games
[560]: https://github.com/eerimoq/nala
[561]: http://jstimpfle.de/projects/rb3ptr/rb3ptr.html
[562]: https://kristaps.bsd.lv/kcgi
[563]: https://github.com/christophercrouzet/rexo
[564]: https://github.com/ithewei/libhv
[565]: https://github.com/sakhmatd/rogueutil
[566]: https://github.com/the-tcpdump-group/libpcap
[567]: http://esbmc.org/
[568]: https://ejdb.org/
[569]: https://github.com/recp/xml
[570]: https://github.com/recp/cmt
[571]: https://github.com/recp/AssetKit
[572]: https://github.com/shiyanhui/libcsp
[573]: https://github.com/PJK/libcbor
[574]: https://git.sr.ht/~mcf/cproc
[575]: https://lvgl.io/
[576]: https://github.com/ianh/owl
[577]: https://github.com/zhaojh329/libuhttpd
[578]: http://zinjai.sourceforge.net/
[579]: https://github.com/silgy/silgy
[580]: https://github.com/small-c/obj.h
[581]: https://github.com/zeromq/libzmq
[582]: https://www.infradead.org/~tgr/libnl/
[583]: https://www.gnu.org/software/automake/manual/html_node/GNU-Build-System.html
[584]: https://github.com/msune/autotools-skeleton
[585]: https://msune.github.io/libcdada/
[586]: https://github.com/ariya/fastlz
[587]: https://github.com/maxim2266/str
[588]: https://github.com/saprykin/plibsys
[589]: https://github.com/Jorengarenar/libXDGdirs
[590]: https://github.com/sammycage/plutovg
[591]: https://duktape.org/
[592]: https://github.com/graphitemaster/incbin
[593]: https://libzip.org
[594]: https://github.com/tek256/astera
[595]: https://github.com/tezc/sc
[596]: https://github.com/damian-m-g/xlsx_drone
[597]: https://github.com/jart/cosmopolitan
[598]: https://github.com/cjwagenius/bfish
[599]: https://github.com/hnes/libaco
[600]: www.littlecms.com
[601]: https://github.com/smoked-herring/sail
[601]: https://sigrok.org/wiki/Libsigrok
[602]: https://github.com/zpl-c/zpl
[603]: https://github.com/Hirrolot/metalang99
[604]: https://github.com/Hirrolot/datatype99
[605]: https://codeforwin.org/2015/09/singly-linked-list-data-structure-in-c.html
[606]: https://www.learn-c.org
[607]: https://github.com/metacall/core
[608]: https://hirrolot.github.io/posts/compiling-algebraic-data-types-in-pure-c99.html
[609]: https://github.com/jasmcaus/tau
[610]: https://github.com/BayesWitnesses/m2cgen
[611]: https://sod.pixlab.io/
[612]: https://github.com/michaelrsweet/pdfio
[613]: https://github.com/rurban/ctl
[614]: https://github.com/nakst/luigi
[615]: https://github.com/helderman/htpataic
[616]: https://github.com/rxi/microui
[617]: https://github.com/Cogmasters/concord
[618]: https://github.com/solenum/exengine
[619]: https://projects.malikania.fr/bcc
[620]: https://github.com/pspdev/pspsdk
[621]: https://github.com/pspdev/pspsdk/blob/master/LICENSE
[622]: https://remove-to-waste.info
[623]: https://github.com/ashvardanian/StringZilla
[700]: https://viewsourcecode.org/snaptoken/kilo/
[701]: https://wiki.gnome.org/Projects/GLib
[702]: https://duckdb.org/
[703]: https://github.com/armink/FlashDB
[704]: https://github.com/taosdata/TDengine
[705]: https://nappgui.com/
[706]: https://github.com/armink/EasyLogger
[707]: https://github.com/JosefVesely/Image-to-ASCII
