
# System Overview

## Data Structures
This should include all the primitives found in the C++ Standard Template Library 2014 plus a few additions:

1. Compile-time type identification that makes run-time type information optional
1. Mandatory hash functions for all wrappers to the primitive types
1. Singly-linked lists for when there is just no need to walk backwards

## User Interface
MUI and its open-source counterpart, Zune, will be the basis for the graphical portion of the user interface.

## Media Playback
Datatypes will be the basis for all media playback.

## Compiler Infrastructure
The compiler will be decoupled from the parser and will either be implemented via datatypes or be simply converted to use a central compiler framework such as LLVM, GCC, or some similar technology.
