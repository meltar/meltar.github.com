---
layout: post
title: "January 2014 ATLRUG meeting"
description: ""
category: "ATLRUG"
tags: [Meetups, ATLRUG, Searching, Sunspot, OpenShift, Ruby on Rails]
---
{% include JB/setup %}

Last night was the monthly meeting of the Atlanta Ruby Users Group.  I've been involved 
the ATLRUG community for about a year now, and it's always fun to see all the nice people
in the area and hear about what they are working on. Each meeting, we eat pizza, listen to
a couple of presenters, then go to a bar and catch up on what everyone has been doing since
the last meeting.

The first presentation was on "Apache Solr and how to use it with the Sunspot gem" by Harold
Dorst.  There was a presentation last month on Asari/Active Asari that compared Asari to
some of the other search options, so I'd heard of [Sunspot](http://sunspot.github.io/) before
the talk started.  This presentaton was especially interesting becaue Harold talked about 
how he uses searches for the
benefit of the developers.  I've always thought of searching as something the application's
users would use, but there are many reasons for an app to need to search through data to 
prioritize it or present it to the user in the best possible way.  I also like the idea of
facets and nested searches to get relevant results.  I'm often frustrated when I'm using a 
retail site, and I can't look at a category of items that match what I'm looking for, but
now I know that searching is more complicated than I thought, and some fields may not be 
available for searching in specific contexts or are unavailable in general.  
(Harold's slides are available for download [here](http://www.raastech.com/raastech/library/Raastech_Jan2014_ATLRUG_SolrSunSpot.pdf).)

Next, we listened to Ernie Ellingson introduce [OpenShift](https://www.openshift.com/) by
Red Hat. I'd never heard of OpenShift, so I was happy to hear about another deployment
option.  Ernie said he chose OpenShift because he had an app using Ruby 1.8, so I don't
expect to be in that situaion, but it's interesting to compare the scaling options that
different companies offer.  Another notable thing about OpenShift is that it deploys new
code as soon as you push it to github.  That seems risky in production, and it doesn't make
sense to me for the developers to restart processes in the app during peak usage, but it 
would be convenient for a staging environment.

As usual, I'm looking forward to finding out what we'll be learning next month.
