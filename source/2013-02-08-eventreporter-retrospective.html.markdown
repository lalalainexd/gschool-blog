---
title: EventReporter Retrospective - Completely Shamed.
date: 2013-02-08 09:05 -07:00
tags:
---

This past week, we were tasked to implement a program called EventReporter. The
rules were to implement a command line tool that would allow a user to load a
csv file and perform queries on this file. Those queries would be saved into a
cache or sorts and the user could print or save the queries to a new csv. There
were some basic commands we had to implement and afterwards, if we felt
adventurous, we could try out implementing some extensions.

I bombed it. I totally and completely bombed this project. As someone who has
been programming for a while now, "embarassed" does not even begin to express
how the total shame I felt when it was time to turn in the project.

After looking at the prompt, I immediately thought "Oh dear god.. this feels
all too much like the CS125" (an introductory programming class that was
offered at my university). I wanted to impress myself by going above and beyond
by doing more than what was asked.

I wasted my first day and a half attempting to get ActiveRecord to work in a
standalone ruby application. You may be thinking, "A day and a half?? That
should have taken very little time!" Yeah well.. it's what happened. woops.
Then I was informted that using ActiveRecord or any type of ORM was not
allowed. So with that bomb dropped, I promptly started to get to work.

I actually started working on EventReporter on Tuesday afternoon and worked
until 11:30pm. I also spent about half a day working on it on Wednesday, and
two more hours on Thursday. So in total, I spent approximately one full day
working on EventReporter.

So this is what I ended with: [lalalainexd/event-report](https://github.com/lalalainexd/event-reporter).

You can tell right away that I was trying to go above and beyond by using TDD.
For a while I was telling people "oh yeah, I'm taking a while because I'm doing
TDD" but deep down I knew that wasn't why. I was trying to be fancy by learning
some things about ruby such creating methods with optional parameters. I was
spending too much time with the details and forgot about the project. 

So when it was time to turn in the project, the most my program could do well
was run and quit. Nothing else.


