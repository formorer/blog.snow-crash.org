---
author: "Alexander wirt"
date: 2017-06-07
title: Upcoming Alioth Sprint
best: true
tags: ["alioth", "debian"]
categories: ["debian"]
---

As some of you already know we do need a replacement for [alioth.debian.org](https://alioth.debian.org). It is based on wheezy and a heavily modified version of 
[Fusionforge](https://fusionforge.org/). Unfortunately I am the last admin left for alioth and I am not really familiar with fusionforge. After some chatting with a bunch of people we decided that we should replace alioth with a stripped down version of new services. 

We want to start with the basic things, git and and identity provider.
For git there are two candidates: [gitlab](https://gitlab.org) and [pagure](https://pagure.io). Gitlab is really nice, but has a big problem: it is Opencore, which
that it is not entirely opensource. I don't think we should use software licensed under such a model for one of our core services.
That brings us to the last candidate: pagure.

Pagure is a nice project based on gitlab, it is developed by the fedora project which use it
for all their repos.

Pagure isn't packaged for Debian yet, but that is work in progress ([#829046](https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=829046)). If you can lend a helping hand 
to the packager, please do so. 

To get things started we will have a [Alioth Sprint](https://wiki.debian.org/Sprints/2017/Alioth) from 18th to 20th August 2017 in Hamburg, Germany. If you want to join us, add yourself to the [wikipage](https://wiki.debian.org/Sprints/2017/Alioth).

For further discussions I created a mailinglist on [alioth](https://lists.alioth.debian.org/mailman/listinfo/alioth-staff-replacement). Please subscribe if you are interested in that topic.