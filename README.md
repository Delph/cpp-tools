# cpp-tools
A collection of utilities and tools for C++ (and C) code bases.

## cpp-includes
This tool scans a C or C++ codebase and builds a report on how large the translation units being sent to the compiler are.
This is useful for tracking down combinations of headers which explode the code size, increasing compilation time.

This tool was based on the description of a similar tool developed at Figma in their blog, [Speeding Up C++ Build Times](https://www.figma.com/blog/speeding-up-build-times/#measuring-our-codebase-includes-py)

## cpp-warnings
This tool processes the output of gcc recording any emitted warnings to form a summary at the end.
The summary allows developers to prioritize fixing specific files or categories of warnings without overloading them.
