---
title: Home
layout: wikistyle
---

otrtool
=======
otrtool aims to provide an open source tool to deal with otrkey-files from [OnlineTvRecorder.com](http://onlinetvrecoder.com/). At the moment it is able to decrypt them, in the future a download manager and/or EPG could be added.

Packages
--------

### Arch Linux
* [AUR/otrtool](http://aur.archlinux.org/packages.php?ID=41577)
* [AUR/otrtool-git](http://aur.archlinux.org/packages.php?ID=40775)

*This projects needs package maintainers (=> you?)*

Dependencies
------------

* libmcrypt
* libcurl / curl

Building
--------

    $ make depend && make

After that, copy the following files to the places they belong:

* `./otrtool` (the main binary)
* `./otrtool.1.gz` (the gzip'ed manpage)
* `./LICENSE` (the (rights waiver) license)

Links
-----

* [github repository](http://github.com/pyropeter/otrtool)
* [bugtracker](http://github.com/pyropeter/otrtool/issues)

### Related projects:

* [lem's tk/perl GUI](http://github.com/Lem/otrtool-gui)

Contact
-------

    E-Mail:                 com.googlemail@abi1789
    IRC:                    PyroPeter at freenode

Reporting Bugs
--------------

For bug reports please run otrtool with the "-v"-option. Note that the output contains personal data like your email/password, and/or hashes of thiese.

History
-------

In April, 2010, eddy14 reverse-engineered the otrkey-file-format and OTRs Client-Server-protocol. [He described his work in a german blog post.](http://41yd.de/blog/2010/04/18/otrkey-breaker/) He also wrote a proove-of-concept tool to decrypt OTRKEY's. I rewrote it in proper C and without licensing issues.

License
-------

otrtool uses the CC0-license.
(This seems to place it into Public Domain in at least some countries, `disclaimer` but I am far from beeing a lawyer `/disclaimer`)

For the license text see the LICENSE file or [CC0 at creativecommons.org](http://creativecommons.org/publicdomain/zero/1.0/legalcode)