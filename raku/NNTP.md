# Create a Raku implementation of NNTP

## Description

NNTP (Network News Transfer Protocol) is a protocol used by USENET and mailing
lists such as https://www.nntp.perl.org. As of writing, there are no Raku
modules that offer a high-level interface for working with it.

In this project, the student would be expected to create and release to the
Raku ecosystem a `Net::NNTP` module for creating NNTP clients and servers,
along with documentation on how to use it and unit tests to ensure that it
works properly.

## Expected outcomes

- Functional release v0.1.0 of `Net::NNTP` released to the ecosystem. This
  doesn't need to be 100% compliant with
  [RFC 3977](https://tools.ietf.org/html/rfc3977), but should allow users to
  create a client with which to connect to an NNTP server and read articles
  from it.

## Required skills

- Will to learn is a must! There will be *a lot* of reading involved.
- Some experience with Raku, networking, and/or Unicode are appreciated, but
  are not strictly necessary.

## Rating

Medium-hard. Existing modules like `Net::Telnet` and `Net::SMTP` implement
layer 4 protocols similar to NNTP, but may or may not be of much help when
writing this module.

## Possible mentors

Ben Davies (kaiepi@outlook.com, [GitHub](https://github.com/Kaiepi/)), Kaiepi
on Freenode
