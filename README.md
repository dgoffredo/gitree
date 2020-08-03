![](reee.jpg)

gitree
======
`gitree` copies a filtered version of a git tree into a specified directory.

Why
---
I want to compare all of the `*.proto` files in the current git tree to all
of the `*.proto` files in a previous version of the git respository. It
would be convenient to have both trees on the same file system for
comparison, without having to clone the respository anew.

What
----
`gitree` is a script that copies a specified git tree into a specified
directory, omitting all leaves that do not satisfy a specified
Perl-compatible regular expression. It recusively handles all submodules as
well.

How
---
TODO

More
----
### Dependencies
`gitree` requires [git][1] and [GNU Coreutils][2].

[1]: TODO
[2]: TODO
