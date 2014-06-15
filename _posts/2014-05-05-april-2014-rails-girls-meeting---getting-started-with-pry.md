---
layout: post
title: "April 2014 Rails Girls Meeting   Getting Started With Pry"
description: "Lightning Talk for Rails Girls Atlanta"
category: "Rails Girls"
tags: [Meetups, Public Speaking, Rails Girls, Pry, Gems]
---
{% include JB/setup %}

<div class="blog-photo">
	<img src="{{ site.url }}/assets/pictures/pry2.png" />
</div>

I wasn't initially planning to give a talk at this meetup, but I was asked to give a lightning talk on
Pry since my last talk was six months ago, and we had a smaller group than usual since it was scheduled
around the holidays.  I'm glad I agreed because I was able to think about what I should talk about
with the time constraint due to it being a lightning talk. Pry is really awesome, but developing in a
Pry session is a big jump for new developers.

I decided to focus on a few uses that would help
everyone now. The first one was the `view-source` method.  Being able to view source code while inside
a REPL is really cool and helpful.  Sometimes when I'm experimenting with code, I don't remember which
method to use or what it is actually doing (compared to the behavior I'm seeing).  The second usage is
related - `gist` allows me to grab the code I wanted to see with `view-source` and save it in a gist on
[Github.com](github.com) to view later or share with someone.  The third topic I wanted to cover was
placing `binding.pry` in the code to make a breakpoint. This one is pretty different, but it's more 
important and complicated than the first two commands.  When I first heard about `binding.pry` it changed
my life.  Being able to debug my Rails servers is **so** helpful, and most of the people at the meetup
had never heard of it.  I hope it saves everyone a lot of frustation and time, and at some point
encourages them to learn about more Pry features as well as other interactive debugging gems.


