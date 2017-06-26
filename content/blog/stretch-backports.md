---
date: 2017-06-26T22:48:05+02:00
description: stretch backports
title: Stretch Backports available
best: true
tags: ["debian"]
categories: ["debian"]
---

 With the release of stretch we are pleased to open the doors
for stretch-backports and jessie-backports-sloppy. \o/

As usual with a new releasewe will change a few things for 
the backports service. 

## What to upload where ##

 As a reminder, uploads to a release-backports pocket are to be taken
from release + 1, uploads to a release-backports-sloppy pocket are to be
taken from release + 2.  Which means:

 Source Distribution | Backports Distribution | Sloppy Distribution
---------------------|------------------------|------------------------
 buster             | stretch-backports       | jessie-backports-sloppy
 stretch            | jessie-backports        | - 

## Deprecation of LTS support for backports ##

We started supporting backports as long as there is LTS support as an 
experiment. Unfortunately it didn't worked, most maintainers didn't 
wanted to support oldoldstable-backports (squeeze) for the lifetime
of LTS. So things started to rot in squeeze and most packages didn't
received updates. After long discussions we decided to deprecate LTS 
support for backports. From now on squeeze-backports(-sloppy) is closed
and will not receive any updates. Expect it to get removed from the
mirrors and moved to archive in the near future.

## BSA handling ##

We - the backports team - didn't scale well in processing BSA requests.
To get things better in the future we decided to change the process a
little bit. If you upload a package which fixes security problems
please fill out the BSA template and create a ticket in the rt tracker
(see https://backports.debian.org/Contribute/#index3h2 for details).

## Stretching the rules ##

From time to time its necessary to not follow the backports rules, like
a package needs to be in testing or a version needs to be in Debian. 
If you think you have one of those cases, please talk to us on the list **before** upload the package.

## Thanks ##

 Thanks have to go out to all people making backports possible, and that
includes up front the backporters themself who do upload the packages,
track and update them on a regular basis, but also the buildd team
making the autobuilding possible and the ftp masters for creating the
suites in the first place.

 We wish you a happy stretch :)
Alex, on behalf of the Backports Team
