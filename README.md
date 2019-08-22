# About

A collection of resources (books, articles, talks...) about programming
languages theory, compilers construction and other related topics
(interpreters, lexers/parsers, VM's, JIT-compilation, GC implementations etc,.)


Unlike awesome-* repositories, my goal is to only add resources:
- That I've fully read (thus, I won't be adding SICP yet ;))
- Which I found to be of good quality (Concise explanations, challenging
  problem sets, new ideas etc,.)

Where applicable, I provided links to coding solutions/projects that I've written for that entry.

Propositions are welcome, but it may take me some time to add them if ever, due to the reasons cited above.

# Books
- [Writing an Interpreter in Go](https://interpreterbook.com/): This book is light on theory, but heavy on practice. At 200 pages, this is a quick read, and you can learn Go along the way (or use your favorite language) [to implement the Monkey language](https://github.com/kroosec/magot).

# Articles
- [Baby's First Garbage Collector](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/): A great introduction to implementing a mark-and-sweep Garbage Collector in C.
- [What To Know Before Debating Type Systems](https://cdsmith.wordpress.com/2011/01/09/an-old-article-i-wrote/):
  A well-written lengthy article about type systems.
- [Why Go Is Not Good](http://yager.io/programming/go.html): A nice article
  about missing/insufficient features in Go programming language, and their
  counterparts in Rust and Haskell.
- [A look at the Design of Lua](https://cacm.acm.org/magazines/2018/11/232214-a-look-at-the-design-of-lua/fulltext):
  A high-level look at the design goals of Lua and how these are reached by
  building various mechanisms on top of Lua's tables and functions.
- [Bytecode compilers and interpreters](https://bernsteinbear.com/blog/bytecode-interpreters/):
  An easy-to-follow introduction to writing a bytecode interpreter in Python.
- [Why Generics [in Go]](https://blog.golang.org/why-generics): An article
  explaining the need for generic types in Go, and the proposed implementation in Go 2.

# Courses
- [Programming Languages, by Dan Grossman](https://github.com/kroosec/pl-course):
  A great course teaching the fundamentals of programming languages theory,
  with a strong emphasis on functional programming.
  [Here are my solutions to the coding tasks](https://github.com/kroosec/pl-course).
    - [Part1](https://www.coursera.org/learn/programming-languages): Focuses on
      functional programming and related concepts (Recursion, higher-order
      functions, pattern-matching, type inference etc,.) using Standard ML,
      a statically-typed functional programming language.

# Talks/Videos
- [Lexical Scanning in Go](https://www.youtube.com/watch?v=HxaD_trXwRE): A nice
  talk by Rob Pike, about writing a lexer and a parser for Go's template
  system, using a functional style and leveraging Go's concurrency support.
