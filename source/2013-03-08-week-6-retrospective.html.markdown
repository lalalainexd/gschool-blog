---
title: Week 6 Retrospective
date: 2013-03-08 09:02 -07:00
tags:
---

##TrafficSpy

This week we finished the TrafficSpy project. This was by far, the most fun
project we've had so far. I really appreciate building the web app with sinatra
and sequel. The experience helped me get a better feel, deeper understanding,
and appreciation of how web frameworks work in general. I've built some itty
bitty web apps with django and rails, but a lot of the time I wasn't quite sure
what was going on in the background. With the combination of sinatra and sequel,
we had to build a lot of the things I've taken forgranted with more complex
frameworks. I now have a better understanding of migrations, structuring my
projects to be more MVC-like, how routes work, and databases.

My wone issue about the project is that there were times
when I was extremely frustrated with sequel because there's not a lot of
documentation or support for it so I had trouble figuring out the right method
calls to do what I needed. As our queries became more complex, Aimee and I ended
up falling `fetch` and passing in SQL straigt up.

I realy enjoyed this project, and even though it's done, I don't feel done with
it so I'm going to refactor and try to improve it, do some of the extensions,
and improve the view. We started off the project by building all the models and
setting up the database which I kind of regret. A top-down approach, where we
start with the views and see what models and methods we needed, would have been
better and easier. On the one hand, implementing the views was pretty quick and
easy because we had all *most* of the methods we nedded. On the other, before we
started on the views, there was a constant feeling of "I don't know if I have
exactly what I need for later" which made me a bit uneasy. When I refactor and
improve TrafficSpy, I'm going to take a more BDD approach and get practice in
thinking in the mindset of my user and clients. I'm getting comfortable with TDD
so it seems natural to try out BDD.

##Obama for America

Yesterday, the tech leads of Obama for America had a Q&A session at Galvanize.
What stuck out the most to me is all the effort they put into testing. They
really pushed their applications to the limit so that there wouldn't be any
failures at the most crucial times... and there weren't any. This is a HUGE
lesson to learn and apply in real life, professional situations. Poke all the
holes you can in your application, find all the failing points, and figure out
how to deal with them. That way, when it actually matters, you and your team
won't be freaking out and madly rushing to find a patch while losing business.

##Big Picture

###Project Management
This time around, my group wasn't as good with using pivotal, which is kind of
sad considering that we basically had all the stories listed out so it should
have been *easy* to use it. For the future projects, I'm going to try and push
my group to use it effectively and write better stories.

###Open Source
I'm still iffy about working on open source projects. I haven't seen any that
I would really like to contribute too, but then again I haven't really looked
into any either. I wonder if Jeff would let me work on my own little gem...
HRMMM....
