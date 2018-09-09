# godot-yarn-importer
A Yarn Importer for Godot 3+

![Screenshot](https://i.imgur.com/WRtQUJl.png)

# Yarn / Twine

Based on:
- Yarn: https://github.com/InfiniteAmmoInc/Yarn
- Twine: http://twinery.org/

The focus of this is to provide a GDScript library that reads ".yarn.txt" files from Yarn, then imports it into a data structure useful for Godot.  Convienience functions are included but the GUI portion of the import is up to *you*, the developer.  Whether you want basic 2D, custom 2D, 3D controls, or whatever, you are responsible for the look and feel and you must choose the components used to create the GUI. A basic vanilla dialog+choice GUI is provided merely as an example.

# GDScript

This is currently only compatible with standard GDScript versions of Godot.  

There are some non-standard Yarn features such as running GDScript code from a node, a settings node, and preliminary support for logical statements.

# Todo

- Support for Yarn Shortcut Options
- Explicit Support for Multiple Characters
- Increased Parsing of Code, Logic, Conditionals, and basic Math Operations
- Ability to jump to another Yarn file
- Improve Demo with Advanced Dialog Widgets
- Improve GDScript Export Feature
