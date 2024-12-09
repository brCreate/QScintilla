# QScintilla - Python Bindings for the QScintilla Programmers Editor Widget

QScintilla is a port to Qt of the Scintilla programmers editor widget.  It
supports the traditional low-level Scintilla API and implements a high-level
API covering such things as auto-completion, code folding and lexer
configuration.

These Python bindings implement a single extension module that sits on top of
PyQt5 and wraps both the low-level and high-level APIs.


## Author

QScintilla is copyright (c) Riverbank Computing Limited.  Its homepage is
https://www.riverbankcomputing.com/software/qscintilla/.

Support may be obtained from the QScintilla mailing list at
https://www.riverbankcomputing.com/mailman/listinfo/qscintilla/.


## License

QScintilla is released under the GPL v3 license and under a commercial license
that allows for the development of proprietary applications.


## Documentation

The documentation for the latest release can be found
[here](https://www.riverbankcomputing.com/static/Docs/QScintilla/).


## Installation

The GPL version of QScintilla can be installed from PyPI:

    pip install QScintilla

The wheels include a statically linked copy of the QScintilla C++ library.

`pip` will also build and install the bindings from the sdist package but Qt's
`qmake` tool must be on `PATH`.

The `sip-install` tool will also install the bindings from the sdist package
but will allow you to configure many aspects of the installation.
