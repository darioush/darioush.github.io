---
layout: page
title: Projects
permalink: /projects/
---

* [Defects4J][defects4j]
    : Software engineering research needs a database of reliably reproducable real faults for many reasons.
    What research doesn't have is time for is actually collecting this database. So I spent
    far too much time dealing with idiosyncrasies of build systems, library version compatibility,
    and the dreaded `CLASSPATH` setting, with my collegue [René Just][rene]. Unfortunately for you, we did
    it in Perl. It still beats dealing with `maven`, `ant`, and `git` commit SHAs though, so enjoy
    using it.
    : [[paper]][issta14-1]

* [Dependent test detector][dtd]
    : Have you ever run your tests in a different order and got different results? No? Well, that's because
    you aren't a practicioner -- you should go ask one. I spent some time on [Sai Zhang][sai]'s tool and
    added a program analysis that eliminated the need to check every order to determine whether
    running a certain reordering of tests may change the results from the original order.

[issta14-1]: ../papers/issta-2014-1.pdf
[issta14-2]: ../papers/issta-2014-2.pdf
[defects4j]: https://github.com/uw-plse/defects4j
[rene]: http://homes.cs.washington.edu/~rjust
[dtd]: https://code.google.com/p/testisolation/
[sai]: http://zhang-sai.github.io/
