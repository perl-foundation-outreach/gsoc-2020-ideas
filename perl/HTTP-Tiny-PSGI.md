PSGI protocol for HTTP::Tiny
============================

Description
-----------

Add PSGI support for HTTP::Tiny which would allow ease of testing for code using the module.

Expected outcomes
-----------------

The https://metacpan.org/pod/LWP::Protocol::PSGI module allows you to provide code that will called to respond to requests you make with LWP, rather than them going off to a server. LWP is multiprotocol, so lends itself to having PSGI added.

A GSoC student would author something analogous, but for HTTP::Tiny.

The pod of LWP::Protocol::PSGI has a good example, where a trivial dancer app is loaded to respond to LWP requests to google.com. In a test file, an author can mock a web service without having to start up a http daemon of some sort, and doesnt need to insert shims in their code either. Another example from the real world is https://metacpan.org/source/HAKOBE/WebService-SyoboiCalendar-0.02/t/lib/SyobocalMock.pm. The code being tested in entirely unaware of the subterfuge.

See also Furl::PSGI

A version for HTTP::Tiny would do something very similar. Authors of code using HTTP::Tiny could use this new HTTP::Tiny w/ PSGI in their test suites to mock web services they want to test against.


For HTTP::Tiny to speak to something via PSGI, the Student would study and decide upon:

 - Faking HTTP::Tiny entirely, with a module that would be loaded prior to HTTP::Tiny and trick perl in to not loading it

- Add hooks in HTTP::Tiny, so that PSGI can be used

- Sub-class HTTP::Tiny and override necessary functions, similar to Furl::PSGI

- Other, as suggested by more creative perl people

Having made an informed decision, proceed to author the module and release it to the CPAN.

Required skills
---------------

Reasonable understanding of Perl and testing in Perl.

Rating
------

Medium.

Possible mentors
----------------

 - Dean H (dean@fragfest.com.au / [CPAN](https://metacpan.org/author/DJZORT) / [GitHub](https://github.com/djort))
 - Kieran D (diment@gmail.com / [CPAN](https://metacpan.org/author/ZARQUON) / [GitHub](https://github.com/singingfish))
 - Tom M (tmetro@cpan.org / [CPAN](https://metacpan.org/author/TMETRO) / [GitHub](https://github.com/tmetro))
