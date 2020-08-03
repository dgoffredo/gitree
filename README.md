![](reee.jpg)

gitree
======
`gitree` copies a git tree into a specified directory.

Why
---
I want to compare all of the `*.proto` files in the current directory tree
to all of the `*.proto` files in a previous version of the git respository.
It would be convenient to have both trees on the same file system at the
same time for comparison.

What
----
`gitree` is a script that copies a specified git tree into a specified
directory. It recursively handles all submodules as well.

How
---
```console
$ mkdir /tmp/root
$ gitree HEAD~5 /tmp/root
```

More
----
### Dependencies
`gitree` requires [git][1] and [GNU Coreutils][2].

[1]: https://git-scm.com/
[2]: https://www.gnu.org/software/coreutils/
