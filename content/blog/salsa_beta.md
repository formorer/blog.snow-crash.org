---
date: 2017-12-25T11:46:51+01:00
description: salsa.debian.org beta
best: true
tags: ["alioth", "debian"]
title: salsa.debian.org (git.debian.org replacement) going into beta
---

Since summer we have worked on our git.debian.org replacement based
on GitLab. I am really happy to say that we are launching the beta of our service
today. Please keep in mind that it is a beta, we don't expect any database
resets, but under unexpected circumstances it might still happen.

The new service is available at https://salsa.debian.org. Every active Debian
Developer already has an account. Please request a password reset via https://salsa.debian.org/users/sign_in
-- your login is either your Debian login or Debian e-mail address.

Guest users
-----------

External users are invited to create an account on salsa. To avoid clashes with
future Debian Developers, we are enforcing a '-guest' suffix for any guest username.
Therefore we developed a self-service portal which allows non-Debian Developers to sign up,
available at https://signup.salsa.debian.org.
Please keep in mind that your username will have '-guest' appended.

Project creation
----------------

Every user can create projects in their own namespace (similar to GitHub).

Teams
-----

For larger projects you can also create a group to host your projects.
To avoid clashes with usernames (that share the same namespace as groups) we are requiring
groups to have a '-team' suffix to their name.
Groups can be created using the same self-service portal https://signup.salsa.debian.org.
For larger, already-established teams it is also possible to ask us to create the group with a
name not conforming to the normal team namespace. Examples are teams like *debian-qa*.
Please create an issue in the support[1] project.

Collab-maint
------------

If you want to allow other Debian Developers to work on your packages or software, you can create projects within the
**Debian** group. Every Debian Developer has write access to projects created in this group.
If you create a project within the Debian group, you are implicitly welcoming all DDs to contribute directly to the project.

Guest users can only be added to individual projects with the Debian group, but not to the entire Debian group. This is different to the policy for the collab-maint group on Alioth.

GitLab runners
--------------

We won't provide any shared Gitlab runners for now. If you want to sponsor resources for such runners please contact us.


Gitlab pages
------------

We will support Gitlab pages in the future, but more work is needed first. We will post an update when they
are ready.

Migration of repositories
-------------------------

We don't plan to do any automatic migration of alioth repositories. If you use a repository and think it is important (!)
migrate it on your own. We will provide a read-only export of all repositories that weren't exported after disabling
alioth.

Timeline
--------

We want to run this beta at least for four weeks. If everything goes well we intend to leave beta around the end of January.

Documentation
-------------

Documentation of the service will happen in the Debian Wiki [2]. Please feel free to enhance the documentation.
See also the upstream GitLab docs [3].

Getting help
------------

If you have problems with the service you can reach us:

- IRC: #alioth@irc.debian.org
- Mailing list: https://lists.alioth.debian.org/mailman/listinfo/alioth-staff-replacement
- Issue tracker: https://salsa.debian.org/salsa/support/issues

Don't expect us to be responsive during the holidays, so be patient :).


Request for help
----------------

If you want to take part in salsa administration please get in touch with us. We want to have at least two more administrators
for the Gitlab instance.

[1] https://salsa.debian.org/salsa/support
[2] https://wiki.debian.org/Salsa/Doc
[3] https://docs.gitlab.com/ee/README.html
