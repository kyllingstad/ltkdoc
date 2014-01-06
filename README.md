LTKdoc
======

LTKdoc is a very simple DDOC theme, and is a work in progress.
Currently, it may be used to format the documentation of individual modules
as HTML5 with embedded CSS.  It does not use JavaScript or other scripting
languages.  It does not provide a way to browse and move between different
modules.

To use it, simply provide the compiler with the path to the `ltk.ddoc` file
when compiling the module(s) you'd like to document, like this:

    dmd -D my_module.d /path/to/ltk.ddoc

LTKdoc was created by [Lars T. Kyllingstad](https://github.com/kyllingstad),
and placed in the public domain.
