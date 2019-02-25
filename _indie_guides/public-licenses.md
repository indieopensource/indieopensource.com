---
title: Choosing a Public License for Public-Private Licensing
description: a guide to good options
permalink: /public-private/public-licenses
layout: default
---

# {{page.title}}

The hardest part of [public-private licensing](/public-private/) is picking the right public license.  That is to say, the legal terms that go in the `LICENSE` file, header comments, and package metadata for your project.

That license needs to balance three goals:

1.  Make your project open source.

2.  Make clear that enough people can use and contribute back to your project under the public license, for free.

3.  Make clear that potential customers can't do what they want under the public license, and need to buy a private license.

In more personal terms:

1.  You want people looking at the license for your project to think, "This is an open source project."

2.  You want people and companies that you don't want to turn into customers, or folks that you hope will contribute back, to think, "This public license gives me all the permission I need to do what I want."

3.  You want people and companies that you _do_ want to charge for private licenses to think, "This public license doesn't let me do what I want.  I guess I need to buy a private license."

This guide can help you find that public license.  However, that is a pretty complex, nuanced challenge, and a guide can only do so much.  If you can afford the help of a lawyer familiar with open source, this is a good conversation to have with them.

## Decision Tree

### Start here.

Will potential customers send copies of your software outside their companies, in physical products, as part of installable software, or as client-side scripts?

Yes: [Continue here.](#customers-will-distribute-copies)

No:  [Continue here](#customers-will-not-distribute-copies)

### Customers will distribute copies.

Will potential customers make changes or extensions to your software?

Yes: Consider [MPL 2.0](#MPL-2.0).

No: Consider [GPL 3.0](#GPL-3.0).

### Customers will not distribute copies.

Will potential customers build your software into websites or other network services for use outside their companies?

Yes: [Continue here.](#customers-will-build-into-network-services)

No:  [Continue here.](#customers-will-not-build-into-network-services)

### Customers will build into network services.

Is your project a database?

Yes: Consider [SSPL](#SSPL).

No:  [Continue here.](#your-project-is-not-a-database)

### Your project is not a database.

If your project a web framework?

Yes: Consider [RPL-1.5](#RPL-1.5).

No: Consider [AGPL-3.0](#AGPL-3.0).

### Customers will not build into network services.

Will potential customers use your software as a developer tool to build other software?

Yes: Consider [Parity](#parity).

No:  [Continue here.](#no-open-source-option)

### No open source option.

Nearly everyone's working definition of "open source" excludes licenses that flat out prohibit use of the software in any particular way.  That doesn't mean you can't do public-private licensing, but the good public licenses that could work for you will make your software "source available" instead of "open source".

Consider a source-available license like [Prosperity](https://licensezero.com/licenses/prosperity), a public software license inspired by [Creative Commons' NonCommercial license](https://creativecommons.org/licenses/by-nc/4.0/).  If making your project open source is important to you, consider other business models, like [open core](./open-core/indies).

## Public License Options

### <a id="AGPL-3.0"></a>GNU Affero General Public License, Version 3

<https://www.gnu.org/licenses/agpl-3.0.en.html>

In simplified terms, AGPL 3.0 says:

> Do whatever you want with my software, but if you make changes or build my software into bigger programs and share that work with others outside your company, give them source code and license your work the same way.
>
> In addition, if my software is a network service and you make changes, then let other people use your changed version, offer them source code, and license your work the same way I have mine.

AGPL was written to close the "loophole" in [GPL](#GPL-3.0) that only requires others to share and license source code when the distribute copies.  That doesn't happen when users run code to provide network services.

Like the GPL, the AGPL was written for "software freedom" activist purposes, not business purposes.  It only happens to work for public-private licensing.  You may or may not agree with the purpose in AGPL's long preamble.

The Free Software Foundation, the Open Source Initiative, and the Debian Project have all approved AGPL 3.0, but it remains highly controversial.  Many companies ban use of AGPL software, and some hackers don't think it counts as "open source" or "free software".

### <a id="GPL-3.0"></a>GNU General Public License, Version 3

<https://www.gnu.org/licenses/gpl-3.0.en.html>

In simplified terms, GPL 3.0 says:

> Do whatever you want with my software, but if you make changes or build my software into bigger programs, and share that work with others outside your company, give them source code, build scripts, and other code needed to develop your work, and license it all the same way I have mine.

The GPL was written for "software freedom" activist purposes, not business purposes.  It only happens to work for public-private licensing.  You may or may not agree with the purpose in GPL's long preamble.

The Free Software Foundation, the Open Source Initiative, and the Debian Project have all approved GPL 3.0.  GPL 3.0 remains somewhat controversial, but not nearly as much as AGPL 3.0.

### <a id="MPL-2.0"></a>Mozilla Public License 2.0

<https://www.mozilla.org/en-US/MPL/2.0/>

In simplified terms, MPL 2.0 says:

> Do whatever you want with my software, but if you make changes or extensions and share them with others outside your company, give them source code and license your work the same way.

MPL 2.0 was written for the [Mozilla Foundation](http://mozilla.org/), to replace old version 1.0, which was used for the open source release of Netscape Navigator, which became [Firefox](https://getfirefox.com).

MPL 2.0 does _not_ require users to release source code for all of a new program that uses MPL 2.0 code as a library, framework, or plugin.  Nor does MPL 2.0 require users to release plugins for MPL 2.0 licensed programs.  It focuses only on requiring release of changes and extensions.

The Free Software Foundation, the Open Source Initiative, and the Debian Project have all approved MPL 2.0.

### <a id="OSL-3.0"></a>Open Software License 3.0

<https://opensource.org/licenses/OSL-3.0>

In simplified terms, OSL 3.0 says:

> Do whatever you want with my software, but if you make changes or build my software into bigger programs and share that work with others outside your company, give them source code and license your work the same way.
>
> In addition, if my software is a network service and you let other people use it, offer them source code, and license your work the same way I have mine.

OSL 3.0 is much like AGPL 3.0.  OSL 3.0 is less popular than AGPL 3.0, but easier to read and apply, and in many ways simpler and more consistent.

As compared to GPL 3.0 and AGPL 3.0, OSL 3.0 may require users to release less source code, in particular build scripts and other code that counts as "Corresponding Source" under GPL 3.0 and AGPL 3.0. 

The Free Software Foundation, the Open Source Initiative, and the Debian Project have all approved OSL 3.0, but its open source status remains highly controversial.  Many companies ban use of OSL software, and some hackers don't think it counts as "open source" or "free software".

### <a id="Parity"></a>Parity

<https://paritylicense.com/>

In simplified terms, Parity says:

> This software is free for open source.
>
> Do whatever you want with my software, but if you use it to make other software in any way, release source code and license your work under the same or more permissive terms.

Parity's open source status remains highly controversial.  It was first published in late 2017, and no outside organizations have approved it.  Controversy mostly focuses on Parity's rule that requires users who make other software with Parity-licensed development tools to release that software.

### <a id="RPL-1.5"></a>Reciprocal Public License 1.5

<https://spdx.org/licenses/RPL-1.5.html>

In simplified terms, RPL 1.5 says:

> Do whatever you want with my software, but if you make changes or build my software into bigger programs, release source code and license your work the same way, whether you share copies outside your company or not.
>
> In addition, if you use my framework as part of a network service, release source code for your whole application, and license your work the same way I have mine.

The Open Source Initiative approved RPL 1.5, but the Free Software Foundation [rejected](https://www.gnu.org/licenses/license-list.en.html#RPL) it for several reasons.  RPL 1.5's open source status remains somewhat controversial.  Many companies ban use of RPL software, and some hackers don't think it counts as "open source" or "free software".

### <a id="SSPL"></a>Server Side Public License

<https://www.mongodb.com/licensing/server-side-public-license>

In simplified terms, SSPL says:

> Do whatever you want with my software, but if you make changes or build my software into bigger programs, release source code and license your work the same way, whether you share copies outside your company or not.
>
> In addition, if you offer my program as a service, release source code for your whole service, and license your work the same way I have the program.

SSPL was written by MongoDB for its Mongo database, to close potential loopholes in [AGPL](#AGPL-3.0).  If you are considering SSPL for your own project, you should also read [Mongo's FAQ](https://www.mongodb.com/licensing/server-side-public-license/faq).

SSPL's open source status remains highly controversial.  It was first published in late 2018, and no outside organizations have approved it.  Controversy mostly focuses on SSPL's rule that requires users who offer SPPL-licensed programs as a service to others release all the code used to do so.
