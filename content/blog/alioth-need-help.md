---
date: 2017-06-18T19:06:13+02:00
description: alioth alternatives
title: alioth needs your help
best: true
tags: ["alioth", "debian"]
---

It may look that the decision for pagure as alioth replacement is already finalized, but thats not really true. I got a lot of feedback and tips in the last weeks, those made postpone my decision. Several alternative systems were recommend to meb, here are a few examples:

* [gitalib](https://gitlab.org)
* [kallithea](http://kallithea.readthedocs.io/en/latest/)
* [gogs](http://gogs.io)
* [gitblit](http://gitblit.com)

and probably several others. I won't be able to evaluate all of those systems in
advance of our [sprint](https://wiki.debian.org/Sprints/2017/Alioth). 
Thats where you come in: if you are familiar with one of those systems or want
to get familiar with. Please join us on our [mailinglist](https://lists.alioth.debian.org/mailman/listinfo/alioth-staff-replacement)
and create a wiki page below <https://wiki.debian.org/Alioth/GitNext> with a review of
your system. 

What do we need to know? 

* Featureset compared to current alioth
* Featureset compared to a popular system like github
* Some implementation designs
* Some information about scaling (expect something like 15.000 > 25.0000 repos)
* Support for other version control systems
* Advantages: why should we choose that system
* Disadvantes: why shouldn't we choose that system
* License
* Other interesting features
* Details about extensibility
* A really nice thing would be a working vagrant box / vagrantfile + ansible/puppet to test things

If you want to start on such a review, please announce it on the mailinglist.

If you have questions, ask me on IRC, [Twitter](https://twitter.com/formorer) or [mail](mailto:formorer@debian.org). Thanks for your help!
