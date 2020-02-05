Raku Enterprise Tools
=====================

Raku is designed along the same lines as Perl, letting you write code
the way you want to. Corporations sometimes have a different mindset,
and want code written by different people to look the same. This way
new people can be brought up-to-speed on a given code base quicker.

We propose a set of CLI tools that will let users:

* Parse Raku code into an AST and reconstruct the original code
  from that tree.
* Walk said AST tree to make certain that the parsed code meets
  corporate standards as specified in a configuration file.
* Edit said AST tree in order to make the code compliant with
  the corporate standards.

Expected outcomes
-----------------

* Command-line script to parse and "dump" AST of a small
  Raku file to the terminal, formatting optional.
* Modules will compile and be at least of alpha (v0.1) quality.
* Modules will have at least non-trivial documentation.
* Modules will be built with App::Mi6 and will be released to
  the CPAN ecosystem.
* Modules will have a non-trivial test suite which parses basic
  Raku expressions

Preferred skills:
-----------------

* Familiarity with Raku and its grammars.
* Ability to learn on-the-fly appreciated.

Required skills:
----------------

* Experience writing at least one of:
  * Python
  * Perl
  * Ruby
  * Bash
* Experience with at least one of:
  * flex / bison
  * lex / yacc
  * ANTLR

Rating
------

Medium to Advanced


Possible mentors
----------------

- Jeffrey Goff (drforr@gmail.com, [GitHub](https://github.com/drforr/)),
  DrForr on Freenode, irc.perl.org

