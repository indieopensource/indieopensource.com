---
title: Open Core Allocation
description: deciding what is open core and what is closed shell
permalink: /open-core/allocation
layout: default
---

# {{page.title}}

Perhaps the hardest part of [open core](/open-core/indies) is deciding what you will give away as open core, what you will sell as closed shell, and how to communicate that allocation to users and potential customers.

Do this well, and your open core can create scores of users who contribute patches back and graduate naturally to paying for licenses to use your closed shell.  Do this poorly, and you will have neither, with lots of complaints that your project is not truly open source.

A good open core allocation achieves several goals:

1.  Offer a useful enough open core to attract large numbers of free users.

2.  Offer enough reasons to buy closed shell licenses to earn revenue.

3.  Preserve the good name of your open core as a bona fide open source software project attracting outside contributions.

4.  Prevent others from outcompeting your closed shell, even though they don't have to contribute to your open core.

That is a lot of goals.   Obvious means to achieving one goal work against others.  In fact, every goal connects to every other goal.  If you put nearly all good functionality in your closed shell, there will be lots of incentive to buy licenses, and it will be difficult with others to offer competing software, but there may not be enough left to your open core to inspire adoption, and developers may criticize the project as crippleware, rather than true open source.

Rather than set out a step-by-step guide to deciding on and messaging an open core allocation, this guide provides some case studies.  First come sketches of relatively large, VC-funded companies developing databases.  Compare and contrast their approaches.  Then comes an example of a classic indie dev shop, to compare and contrast.

## Database Companies

As of February, 2019, many companies offering databases are running open core.  All of the following companies are either venture capital financed or public.  But their approaches, and the differences between them, can teach a lot about open core allocation.

### Elastic

[Elastic](https://www.elastic.co/)'s open core is the Apache 2.0-licensed [ElasticSearch](https://www.elastic.co/products/elasticsearch), which is based in turn on [Apache Lucene](https://lucene.apache.org/).

Elastic offers security, alerting, management, machine learning, and other features as part of its closed shell.  Elastic also offers hosting of both open core and hosted-only closed shell features.

Some parts of Elastic's closed shell, like [X-Pack](https://www.elastic.co/products/x-pack/open), are released as source available software under its [Elastic License Agreement](https://github.com/elastic/elasticsearch/blob/0d8aa7527e242fbda9d84867ab8bc955758eebce/licenses/ELASTIC-LICENSE.txt).

### Redis Labs

[Redis Labs](https://redislabs.com)'s open core is the BSD-licensed [Redis](https://redis.io) database.

Redis Labs offers an enterprise version of Redis with a variety of additional features, including multi-tenant support, as well as plugins for search, graphs, JSON, filtering, and machine learning, called modules, as part of its closed shell.  Redis Labs also offers hosting of both open core and closed shell features.

Redis Labs originally licensed Redis modules in its closed shell under the GNU Affero General Public License.  In 2018, Redis Labs [pioneered](https://redislabs.com/blog/redis-license-bsd-will-remain-bsd/) the use of [Commons Clause](https://commonsclause.com), a license rider for turning open source software licenses into source-available licenses that restrict offering the project as a service. In 2019, Redis Labs [changed the terms for its modules again](https://redislabs.com/blog/redis-labs-modules-license-changes/), to a new Redis Source Available License, to avoid confusion created by Commons Clause.

### Cockroach Labs

[Cockroach Labs](https://www.cockroachlabs.com/)'s open core is the Apache 2.0-licensed [CockroachDB](https://github.com/cockroachdb/cockroach) database.

Cockroach Labs offers an enterprise version of CockroachDB with additional backup, access-control, partitioning,  and other features.  Cockroach Labs also offers hosting of both open core and closed shell features.

Cockroach Labs makes source code for its enterprise features available behind feature flags.  While Cockroach Labs publishes license terms for its closed-shell features, the CockroachDB Community License, that license requires payment.

### MongoDB

[MongoDB](https://www.mongodb.com)'s open core is the MongoDB database.

MongoDB offers management, visualization, backup, security, analytics, and other functionality as part of its closed shell.  MongoDB also offers hosting of open core, closed shell, and service-only closed shell features.

Earlier versions of MongoDB were released under the GNU Affero General Public License.  In 2019, newer versions of MongoDB [transitioned to the Sever Side Public License](https://www.mongodb.com/licensing/server-side-public-license), written to address loopholes in AGPL that MongoDB claimed allowed large cloud infrastructure providers, especially Amazon Web Services, to compete in MongoDB hosting without releasing any of their code.

## Metafizzy

In stark contrast to those database companies, [Metafizzy](https://metafizzy.co) is an indie shop of just of one man, [Dave DeSandro](https://desandro.com/).

Metafizzy's open core is the MIT-licensed [Masonry](https://masonry.desandro.com/) JavaScript grid-layout library.  Metafizzy's primary paid product is [Isotope](https://isotope.metafizzy.co/), which adds filtering and sorting functionality to Masonry.  Metafizzy also offers [Packery](https://packery.metafizzy.co/), a grid-layout library with draggable features that Masonry can't well support, and a few other front-end libraries.

Isotope itself is [public-private licensed](/public-private).  Metafizzy releases Isotope under the GNU General Public License, version 3, and [sells licenses](https://isotope.metafizzy.co/license.html) to build Isotope into closed-source software.

## Hybrids

Developers doing open core often blend a number of business models at once.  For example, many open core companies, especially large and venture capital-financed companies, bundle licenses for their closed shells with [support](/paid-support), [custom development](/paid-development), [permission to build closed software](/public-private), and [hosting](/hosting).
