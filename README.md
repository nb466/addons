[![Build status](https://api.travis-ci.com/undoio/addons.svg?master)](https://travis-ci.com/undoio/addons)

UDB Addons
==========

A collection of add-on scripts and configuration to enhance the functionality
provided by [UndoDB](http://undo.io/) (and, in some cases, also vanilla GDB).


Summary
-------

[**Backtrace with time**](backtrace_with_time/README.md)  
Adds a ubt command which adds basic block counts to frames within a backtrace.

[**Bookmarks recreate**](bookmarks_recreate/README.md)  
Save and restore bookmarks to and from a file.

[**Completion**](completion/README.md)  
Adds completion of udb command line parameters in bash.

[**Fancy prompt**](fancy_prompt/README.md)  
Enhanced prompt support for UndoDB.

[**Regs every bb**](regs_every_bb/README.md)  
Prints the values of all the registers at every basic block within a range.

[**Sample functions**](sample_functions/README.md)  
Samples the number of times the program is in each function.

[**What map**](what_map/README.md)  
Looks up a variable or address within the maps of the debuggee.


Development
-----------

Feel free to make a pull request against the project!

The [`master`](https://github.com/undoio/addons/tree/dev) branch supports the
latest release of UndoDB.
The [`dev`](https://github.com/undoio/addons/tree/dev) branch contains code
meant for the next future release of UndoDB.
