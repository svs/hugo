---
title: "Tools Not Processes"
date: 2017-12-02T16:15:52+05:30
draft: true
---

There is always a perceived conflict between process and agility. A  process makes things easier to understand and help in coordination but they have some very important drawbacks. The most harmful one is that process is often designed to serve the manager, not the doer, and so on all the way up the heirarchy. This makes adherence to process a constant struggle as the process delivers little value to the person who has to follow it.

While it might even be possible to achieve adherence in letter, adherence to process in spirit is well nigh impossible - all processes are vulnerable to gaming and many end up becoming meaningless checkboxes.

As an engineering team, we do follow processes. Some of these take some effort and some of these are effortless. For example, JIRA takes effort but everyone derives value from it. On the other hand, git takes no effort and delivers awesome value to all. Marking attendance in HRIS is also a process but this seems pointless and an imposition. What's the difference?

The main difference between the three can be categorized into

* __how easy are they?__
* __Is the process part of the work?__
Git is a part of the development workflow - developers literally cannot get their work done without git. Developers can work without JIRA, but planning is valuable in larger teams and JIRA helps with that so while JIRA may not be a part of the actual work, it is a seamless part of the planning of the work. And for HRIS, one has to actively stop what one is working on and go check a checkbox somewhere. So processes that are part of the work are easy to use, processes that help to get the work done are a bit harder and processes that compete with work for time and attention are the hardest.
* Are they to be set up once or used continuously? The best tools are set up once and deliver value repeatedly (Rollbar). Next best are tools that deliver value each time they are used and also accrete the value over time (Basecamp, git). Then there are tools that are valuable while being used but don't grow in value over time (toilet paper, for example).
* __who derives the value?__
With JIRA, developers gain enough value individually to keep them invested in the process but the dev team gains a huge amount of value collectively. With git, every developer gains the value immeditaley upon using and then forever due to the history. With HRIS, HR gains the value and sometimes developers lose value.
* __When is the value derived?__
    * immediately and forever - git
    * immediately - linter
    * later - JIRA
    * never - HRIS

* __Does the value grow over time?__ Basecamp keeps getting more valuable the more it is used as a system of record. Git repositories get more useful over time. Also, they integrate well with many other tools and so the standardization definitely helps extract more value by making more tools available for use. A linter is useful temporarily.

So one way of adding more process without making it feel like an imposition is to make it

* deliver value immediately
* to the person performing the task
* while performing the task
* and continue to add value through accreting history, integration with the outside world and so on.

The best way I can think of doing this is to focus on tools, rather than processes.
Tools are great because they empower the doer. They allow certain actions and disallow others. They often grow in value the more they are used. They allow for integration with other tools, thus compunding the benefits from tool use. They reduce complexity while getting out of the way.

These are the characteristics of a good tool. We should care very, very deeply about the tools we use and the effect they have on our development methodologies.
