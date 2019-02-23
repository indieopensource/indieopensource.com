---
title: Private Licenses for Public-Private Licensing
description:
permalink: /public-private/private-licenses
---

# {{page.title}}

Once you've [chosen a public license for your project](./public-licenses), you need to decide what the private licenses that you sell to customers will say.

{{site.title}} maintains a [form paid license agreement](/forms/paid-license) as a place to start.  But there are a few decisions you need to make, with your particular project and customers in mind.

## Licensing Models

### One-Time Licensing

You might choose to sell licenses for particular versions of your software, or particular versions and their updates, that last forever.  Customers make a one-time payment and receive permission to use your software.  That permission lasts forever, but may not cover new versions of the software that you release later.

### Subscription Licensing

You might choose to sell license subscriptions for your software.  Customers make several license payments over time, such as monthly or yearly.  As long as the customer pays, they can use your software.  When they stop paying, they have to stop using your software.

## Permitted Use

Your private license should make clear what paying customers may and may not do with your software.

Your private license should make clear that paying customers may do what they need to do with your software.  If you are doing [public-private licensing](/public-private/indies), your private license should allow customers to use your open source software to make closed.  If you are doing [open core](/open-core/indies), your private license should allow customers to use your closed software.

Your private license should make clear that paying customers can't offer your software to others in a way that significantly competes with your business of selling others private licenses.  If you are doing [public-private licensing](/public-private/indies), your private license should not allow customers to give others freedom to make closed software with your open source.  If you are doing [open core](/open-core/indies), your private license should not allow customers to pass their permission on to others who should buy their own private licenses.

These goals become a bit tricky when customers want to make your software part of software that the customers turn around and offer to _their_ customers.  The usual solution to that challenge is to allow customers to pass on permission for your software to their own customers, but only as part of a larger software or service offering that offers more or different functionality than your software does.

## Warranties

Unlike open source software, which usually comes without any promises that it will work well, or do what its documentation says, or not infringe others' intellectual property rights, paid software usually comes with warranties about all of those things.

In a typical paid software deal, you will need to promise that you have the right to license the software, the software will work, overall, as described.  [Handling contributions correctly](./contributions) will help you to keep the first kind of promise.

The toughest decision---and negotiation---about paid software warranties is usually responsibility for patent infringement.  Unlike copyrights, it's hard to know whether software infringes someone else's patent.  Customers usually want vendors to take responsibility for any patent claims against the software, by agreeing to pay their legal costs, and any legal damages, of patent suits.  The legal terms for these concepts are "patent noninfringement warranty", the promise that the software won't infringe any patents, and "indemnification", the promise to pay costs if it does.  Trouble is, costs of a patent claim can be extraordinarily high, even if the claim never goes to court.

Software vendors and customers often compromise on patent risk in a particular way.  The vendor will promise that as of the day when it sells the customer a license, the vendor's people aren't aware of any patent the software could infringe.  The vendor promises to cover the customer for costs of any claims about patents it did know about, but not any other patents.  But the vendor promises to cover the customer for costs of any claims about infringement of any other kinds of intellectual property, like copyrights, trade secrets, and trademarks.

## Hybrids

Software vendors often offer paid services along with paid licenses.  The most common by far are [support](/paid-support) and "maintenance", or [ongoing development](/paid-development).
