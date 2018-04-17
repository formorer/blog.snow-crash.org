---
date: 2018-04-17T22:19:52+02:00
description: alioth deprecation - next steps
tags: ["alioth", "debian"]
title: alioth deprecation - next steps
best: true
---

As you should be aware, alioth.debian.org will be decommissioned with
the EOL of wheezy, which is at the end of May. The replacement for
the main part of alioth, git, is alive and out of beta, you know it
as salsa.debian.org. If you did not move your git repository yet,
hurry up, time is running out.

The other important service from the alioth set, lists, moved to a
new host and is now live at https://alioth-lists.debian.net
with the lists which opted into migration. All public list archives
moved over too and will continue to exist under the old URL.

## decommissioning timeline

**2018-05-01**  DISABLE registration of new users on alioth. Until an improved SSO ([GSOC Project](https://wiki.debian.org/SummerOfCode2018/Projects#SummerOfCode2018.2FProjects.2FNewDebianSSO.Successor_of_the_Debian_SSO_Service)) is ready, new user registrations needed for SSO services will be handled manually. More details on this will follow in a seperate announcement.<br/>
**2018-05-10 - 2018-05-13** darcs, bzr and mercurial repositories will be exported as tarballs and made available readonly from a new archive host, details on that will follow.<br/>
**2018-05-17 - 2018-05-18** During the Mini-DebConf Hamburg any existing cron jobs will be turned off, websites still on alioth will be disabled.<br/>
**2018-05-31** All remaining repositories (cvs, svn and git) will be archived similar to the ones above.
          The host moszumanska, the home of alioth, will go offline!
