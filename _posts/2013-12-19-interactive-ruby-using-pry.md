---
layout: post
title: "Interactive Ruby Using Pry"
description: "Presentation for Rails Girls"
category: "Rails Girls"
tags: [Ruby, Ruby on Rails, Gems, Public Speaking, Rails Girls]
---
{% include JB/setup %}

<div class="blog-photo">
	<img src="{{ site.url }}/assets/pictures/pry.png" />
</div>

Last night I gave a talk at [Rails Girls Atlanta meetup](http://www.meetup.com/Rails-Girls-Atlanta/events/147082012/) 
on the Pry gem.  My slides are available 
[here](https://docs.google.com/presentation/d/1RlBptG2n0lv7PFBjbrMsc4u8qXQ7IHgBx0w_zeC5bUY/pub?start=false&loop=false&delayms=3000).

I originally volunteered because I thought it would be a perfect opportunity to work with a 
deadline to learn about more Pry features. When I first learned about Pry, I mainly used it to use the 
`binding.pry` command to put breakpoints in my Rails apps.

It was actually kind of surprising to see how well documented the gem is.  I'm used to looking at documentation 
for other languages where the information is minimal, but the maintainers have a plentiful [list](http://pryrepl.org/) of videos, tutorials, and blog 
posts to explore created by the Ruby community.

Based on my experience with `binding.pry`, I expected Pry to be a tool for breakpoints, but working in the Pry REPL
has a lot of interesting commands to offer.  After my talk, I did some experimental live coding and tried using Pry
to explore a Rails project based on suggestions from the audience.  It was fun to `cd` into Rails models and other
classes including ones with database relationships and see what happened.  I think the main downside is keeping
track of where you are in the code, but it should get easier with more experience.

My next goal is becoming more familiar with pry-debugger.  The base Pry gem wasn't as helpful for plain debugging 
with breakpoints as I thought, but I learned about a bunch of commands and features that I didn't know existed, so
my time was well spent.  I'd also like to learn about other gems that extend Pry functionality.
