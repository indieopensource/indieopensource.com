---
title: Licensing Outside Contributions to Public-Private Licensing Projects
description: practical steps and resources
permalink: /public-private/contributions
---

# {{page.title}}

In a typical open source software project, everyone agrees to give their own contributions away under the same public license, like The MIT License or the GNU General Public License.  On the receiving side, everyone gets a license for all contributions to the project under just one set of terms: those of the public license.

When [public-private licensing](/public-private/indies), the developer selling private licenses needs to be able to license all contributions to the project under two different sets of terms: those of the [public license](./public-licenses), and those of the [private license](./private-licenses).

When there is just one contributor the project, or all contributors work for the same company, that's no problem.  The contributor or company isn't going to sue itself for failing to follow the rules of its own public license.  As long as they doesn't use copyleft software _from others_ to build their project, it's up to them how to license their own, original work.  That includes offering their work under different public and private terms at the same time.

When there is more than one contributor to a copyleft project, and they aren't all working for the same company, problems can arise.  If the public license for outside contributions prohibits building closed software, inside contributors can't turn around and sell licenses for those contributions that allow building closed software.

Indie developers doing [public-private licensing](/public-private/indies) can solve this problem in two straightforward ways.

1.  Ask outside contributors to license their contributions under a permissive open source license, rather than a copyleft open source license:

    > Do you license your contributions under The MIT License?

2.  Ask outside contributors to give them a private license, usually called a "contributor license agreement", that gives them permission  to sell private licenses on whatever terms they like.

    {{site.title}} has a [tiny form contributor license agreement](/forms/cla) you can use.

In the past, projects from foundations and large corporations often used formal, cumbersome processes to receive contributor license agreements, for various reasons.  You can take a much simpler approach.  Handling outside contributions can be as simple as asking outside contributors to license their work in one of the ways above in a comment to their pull request, only merging if they agree, and saving a record of their response.
