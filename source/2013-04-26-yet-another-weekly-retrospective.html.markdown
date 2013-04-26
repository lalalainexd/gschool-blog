---
title: Yet Another Weekly Retrospective
date: 2013-04-26 09:04 -06:00
tags:
---

###The Daugher of Store Engine
My group approached this project very differntly than other my groups have in
other projects...
  * We are doing REAL agile development. Previously, we were always handed the
    specs of a project and we'd implement each requirement one a time. It was an
    excellent waterfall process. For this project though, we've been meeting
    with our "client" to drill down the scope to something that is reasonable
    and doable.
  * We are switching roles. So far I've pretty much been igonring the frontend,
    but this time I decided I'd focus on the frontend, improve the views we
    inherited, and work on the UI. My other team members who have had more
    experience doing frontend, are now working on the backend. The process has
    been slow, and I feel we could get a lot more done much more quickly if we
    played our "usual" roles, but I think we're all really enjoy this
    experience.
  * This is the first group I've worked with where every member doesn't need to
    be told what to do. If a member is finished with task, he or she will
    immediately go clean up bugs, or help someone else with a task. It's been
    really great. I feel like the weight of the project is evenly
    distributed among all the group members.

###Working with Legacy Code
I actually find this project to be less challenging than the last. This might be
because I haven't bothered to look at the tests yet. Larua was awesome enough to
clean up the failing tests. Test coverage isn't great and the tests run kind of
slow, but all except a few are passing. Yes, it's not great that we still have
a few failing tests... actually I'm not sure why we haven't just deleted those
or marked them as pending... HRMM.. ANYWAY, We're just cleaning up code as we
see the problems.

###REAL Agile Development
The best thing about doing this agile process is that I don't feel overwhelmed
by the specifications. I focus on just the requirements for the current
iteration since I don't know the details for future steps. At the same time, we
keep possible future features in mind so that we can impelemnt our current
features in a way that allows for flexibility and change.

I love the agile approach so much more than the waterfall approach. I'm not
overwhelemed; the team gets regular feedback; I'm confident about each feature
we implement. **Confidence** in the product is something I was lacking in
all my previous projecs. I knew the code was bad and featuees were buggy
but I felt too much pressure and would just move on to the next features.

###The Rails Stack
I feel really comfortable with rails and the MVC paradigm. There are obviously
lots of things I don't know, but usually if a bug appears, I can quickly figure
out where and why it appeared. I'm weakest with frontend development. I'm
creating some pretty crappy views that need to be broken up into paritals,
templates, etc, but I'm learning and hoping to continue to improve.

I also still need to work on performance. Yesterday, Franklin talked about
making it easy to optimize by having the performance tools ready from the get
go. I really like this approach. My team added new relic to the project
immediately afterwards, and hopefully I remember to do that for future projects.
