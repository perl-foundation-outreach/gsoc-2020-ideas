Improving Open Food Facts architecture and code quality
==================================

Description
-----------
[Open Food Facts](https://world.openfoodfacts.org) is a Wikipedia for food products: a collaborative database of food products, with a backend written in Perl.

Over the last 8 years, the [Open Food Facts code base](https://github.com/openfoodfacts/openfoodfacts-server) has grown a lot organically, which makes contributing not very welcoming for developers, and that can also cause performance issues and bugs.

This project is to improve the architecture, performance, code quality, tests and documentation of an important project that badly needs it! 

Expected outcomes
-----------------

It's important to note that Open Food Facts is a running project with millions of users every month, so finding the right way to do things is only the beginning: it will also be necessary to find the right way to get there. In practice, it will be better to make small incremental changes that can be gradually deployed with minimal risk.

The project could include some of the following:

- Replacing the generation of HTML by a templating system like Template::Toolkit
- Extending the existing documentation in POD format
- Re-architecturing the Open Food Facts Perl modules and functions, possibly making some of them more generic and publishing them on CPAN.
- Extending the coverage of unit tests
- Making it easier to install a dev environment for Open Food Facts
- and more!

Required skills
---------------

The student should be familiar with Perl.

Rating
------

Medium

Possible mentors
----------------

Stéphane Gigandet stephane@openfoodfacts.org - the main developer of the Open Food Facts Perl backend and the person to blame for all the current mess! :)

