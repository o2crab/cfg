# cfg
## a context-free grammer library

This library implements context-free grammer.

You can:
* define a context-free language in the form of (V, T, R, S), where
  * V is a set of variables
  * T is a set of terminals
  * R is a set of production rules
  * S is a start symbol
* determine if an array of alphabets belongs to a language
* construct a parse tree from a sentence (an array of alphabets) using CYK algorithm
* convert a parse tree into a sentence
