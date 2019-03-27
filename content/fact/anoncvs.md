---
title: "AnonCVS and open source repos"
---

OpenBSD was the first open source OS project, and probably the first open source project, to make its
source code available for all to see in real time - no tarball downloads, no user accounts needed.

```
In the Fall of 1995 when we started our own open source operating system project called OpenBSD,
we decided to use CVS to manage the OpenBSD source tree. Based on our experiences with the previous open 
source project we were involved with, we recognized the inherent conflict between trying to maintain an open
environment while maintaining a private CVS source repository that only privileged users could access.
To resolve this conflict we created Anonymous CVS — a mechanism that lets anonymous Internet users access
a source repository without compromising its security.
```

OpenBSD continues to use AnonCVS to this day.

Details:

* [Opening The Source Repository With Anonymous CVS](https://www.openbsd.org/papers/anoncvs-paper.pdf)
* [cvs man page](https://man.openbsd.org/man1/cvs.1)
* [AnonCVS webpage with mirrors](http://anoncvs.openbsd.org/anoncvs.html)
* [Browse source code online](https://cvsweb.openbsd.org/)
