# Changelog

## [0.2] series

The 0.2 series of patches somewhat changes the focus and direction of this theme. Instead of trying to be as accurate to the vim version as possible, the focus is to reduce the number of colours used while maintaining consistency across languages.

Example of differences between Solarized Dark Vim (**SDV**) and Solarized Dark (**V**) in Vim:

- In SDV, Python functions are left in the regular colour, while in V they are coloured blue.
- In SDV, C++ visibility keywords are yellow and regular keywords green, where they are flipped in V.

- [0.2.5] Add syntax highlighting for markdown quote blocks.
- [0.2.4] Change visibility -> keyword instead of storage colour.
  - Tweak Rust colours.
  - Also changes git modified to blue to match gutter.
- [0.2.3] Update screenshots.
- [0.2.2] Tweak storage/keyword highlighting to be more accurate.
  - Added support for additional languages (+) indicates first-class support:
    - CMake
    - Go
    - Lua
    - PHP
    - Rust (+)
  - Many colour tweaks for unsupported languages (in the hopes they look a bit better).
- [0.2.1] Improve selection background readability.
- [0.2.0] Fix various issues with syntax highlighting in Python and JavaScript/TypeScript.
  - Added support for additional languages:
    - LaTeX/TeX
    - Java
  - Certain types were highlighted as blue in TypeScript React files. The colour has been removed.
  - Decorators were unhighlighted. Now they are highlighted orange. In V they are blue, but this does not stand out against other blue words like `self`.
  - Tweaked highlighting of `self`, `this`-type variables. The colour has been removed.
  - Fixed C++ macro syntax highlighting.

## [0.1] series

Initial development, expect small developmental fixes with fast turnaround times.

- [0.1.8] Fix class highlighting (revert to no special highlighting).
- [0.1.7] Fix keyword expression operators, e.g. `delete` operator in JavaScript.
- [0.1.6] Fix escaped entities, e.g. `&amp;`.
- [0.1.5] Fix templated string, debug bar text colours.
- [0.1.4] Tweak highlighting for operator keywords.
- [0.1.3] Add logo.
- [0.1.2] Add screenshot.
- [0.1.1] Theme the UI more extensively and flatten overall look.
- [0.1.0] Initial release, contains support for:
  - C/C++
  - JavaScript/TypeScript/React
  - Markdown
  - Python
  - Shell script
