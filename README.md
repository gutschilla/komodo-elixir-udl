# komodo-elixir-udl
*VERY* basic UDL file for the Elixir language. Includes built XPI extension for Komodo-Edit and Komodo-IDE

Just install the latest .xpi fuile in your Komodo

To build (assuming Komodo-IDE in ~/Komodo-IDE-9), run

  ~/Komodo-IDE-9/lib/sdk/bin/koext build
  
in project directory.

TODO
====
- fix calls to erlang :module.function(..) 
- distinguish between module names and atoms
- respect do: <EXPRESSION> one-liners
- code intelligence would be awesome
 
