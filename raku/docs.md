Raku documentation tools
========================

Description
-----------

Raku documentation uses different tools to index, process and
generate HTML pages (and other formats). What can be said now about
the tooling is that it's working, but little else.

During Google Summer of Code of 2019, Antonio Gámiz did a good job of
overhauling the documentation system, which is now much faster and
efficient. At the same time, Joel changed the command line utility
p6doc so that it worked well with this new system. As a result,
[Documentable](https://github.com/perl6/Documentable), which is
currently used for generating and indexing the documentation, was
produced. There are a number of issues in that milestone that have not
been fulfilled: here's the
[roadmap](https://github.com/Raku/doc/issues/2983). 

Besides finishing that roadmap, and sometimes included with it, there
are many issues that need to be addressed.

* Web serving is still done ad hoc, following instructions. Web
  assets are still part of the old documentation repository, and have
  not been spun off.
* Document cache is not compatible with the module precomp
  repository. That means that if some documentation is installed via
  zef, it will have to be precompiled again using documentable to be
  used for generating documentation.
* Integration of p6doc as well as other documentation utilities
  (specially Pod::To::BigPage) still needs to be done.




Expected outcomes
-----------------

* Finishing the issues in the roadmap to the version 2.0 of the
  documentation.
* Integration of all document parsing and indexing utilities in a
  common backend.


Required skills
---------------

Required or prefered skills the student should have to be able to
tackle this project.

* Some experience with Raku is appreciated, but not really
  needed. Will to learn will be a requisite.
* Experience with grammars and language parsing.


Rating
------

Medium.


Possible mentors
----------------

- JJ Merelo (jjmerelo@gmail.com, [GitHub](https://github.com/JJ)),
  jmerelo on Freenode.


