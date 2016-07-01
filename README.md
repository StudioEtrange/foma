# foma

Unofficial foma repo

* https://code.google.com/archive/p/foma
* https://github.com/jrwdunham/foma 
* https://bitbucket.org/mhulden/foma
* https://github.com/hfst/hfst/tree/master/back-ends/foma

NOTE : the original official site on google code is broken.

# Summary

Foma is a compiler, programming language, and C library for constructing finite-state automata and transducers for various uses. It has specific support for many natural language processing applications such as producing morphological analyzers. Although NLP applications are probably the main use of foma, it is sufficiently generic to use for a large number of purposes.

The foma interface is similar to the Xerox xfst interface, and supports most of the commands and the regular expression syntax in xfst. Many grammars written for xfst compile out-of-the-box with foma.

The library contains efficient implementations of all classical automata/transducer algorithms: determinization, minimization, epsilon-removal, composition, boolean operations. Also, more advanced construction methods are available: context restriction, quotients, first-order regular logic, transducers from replacement rules, etc.

# Features

* Xerox-compatible regular expression and scripting syntax (xfst/lexc)
* Separate C API for constructing and handling automata
* Import/export from Xerox/AT&T/OpenFST tools
* Separate utility (flookup) for applying automata with various strategies
* Supports flag diacritics
* Contains functions for constraining reduplication (_eq())
* Supports first-order regular logic expressions


# License

* Copyright © Mans Hulden 
* Apache License 2.0
