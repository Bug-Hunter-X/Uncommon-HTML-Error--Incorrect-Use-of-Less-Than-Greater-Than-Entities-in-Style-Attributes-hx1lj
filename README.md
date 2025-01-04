# Uncommon HTML Error: Incorrect Use of Less Than/Greater Than Entities in Style Attributes

This repository demonstrates an uncommon HTML error involving the incorrect use of less than (&lt;) and greater than (&gt;) symbols within style attribute values.  While frequently, the symbols are used as entities (&lt; and &gt;) for correct display, this can lead to unexpected behavior, especially when used directly within CSS style attributes within HTML.

## The Problem

The issue occurs when you attempt to use these symbols directly, causing parsing errors.

## The Solution

The solution lies in understanding how the browser parses CSS and that such direct use is not permitted within HTML attributes. The proper approach is to correctly escape these characters or to place the style definitions within an external stylesheet.