# py_jsonparser
A Python JSON parser

This is a JSON parser written in pure Python.

It is intended to be used as a component in a bigger system.

It has zero external depenencies.

An embedded version of PLY and YPLY (Python Lex Yacc and Y-Python Lex Yacc) is included
so that a Yacc grammar can be used to specifiy the JSON syntax.

The JSON parser is stream based, and as such works like SAXP does for XML processing.

This is (or will be) wrapped by my generic path-based parsers linked below, 
so that you can transparrently change an app between XML, HTML and JSON parsing and
still use the same path-based handlers to specify which hierarchical nodes you wish to
extract and process.

https://github.com/whaleygeek/pyparsers

David Whale

@whaleygeek

March 2016

