---
title: "Daily Planner"
date: 2025-11-09
layout: post
---

### Premise
I have been looking into productivity tools for a long time already and somewhat optimized my setup towards a state that I can work with.
Recently I looked into daily planning as this is still an area I would like to improve.
In this context, daily planning just means taking tasks and events from your other tools and structuring them for the current day.
#### Timeblocking
There are many apps that hope to solve daily planning for you. Most of them implement a form of [timeblocking](https://en.wikipedia.org/wiki/Timeblocking).
I had a shot at [Structured](https://structured.app/) and while I like the polish and presentation of the app, I found myself falling behind, even when the timeblocked tasks should be simple to start.

### Working Theory
I found that timeblocking doesn't work for me as I often don't *feel like it* in the *planned* moment of action. I don't like too much structure, so the tools have to cater to that if I want to be productive.
This means that I need something other than timeblocking to structure my day. A simple list of ToDos for the day already works OK in most cases. But what this list lacks is **commitment and gratification**.
A lot of posts and blogs mention [Sunsama](https://www.sunsama.com/) and how it transformed their daily planning, prompting people to content themselves with a steep pricetag of 20€/month.
After briefly testing the app I found for myself why it may be interesting. However, I can't make use of any of the tool integrations, where a lot of the cost stems from, I assume.
During my brief testing, I found that *assigning a planned duration* and then also *commiting* to the task and *recording an actual duration* for it really helps.
My understanding is, that the **act of commiting** and recording the time taken **helps engaging with the task**, as it's a simple low-barrier entry that builds momentum.
Sunsama also gives you a break-down of all tasks completed which is really neat and probably helps with the *gratification* aspect, that my ToDo list approach lacks.

### Iterating
I am not willing to pay 20€/month or even 10€/month for a feature set that barely expands on my todo app. That's why I vibe coded a quick [daily planner](https://constwerk.com/planner.html) myself, to test what works and what doesn't. 
As the devs of Sunsama and Structured point out, their tools are an extension on top of an existing calendar and todo list. So my solution for now is that this extension can be simple and ephemeral.
The daily planner prototype is just a static HTML site that lets you put in tasks, their duration and when to do them. Each task has a *commit* button called "Do". 
Pressing this button places the start of the task at the current time. When you press the "Done" button, the task updates with the actual time taken. 
This way, I get the benefit of commitment in my daily planner and hopefully no stress from not completing tasks in their designated timeslot, as I can just move them around and the tool doesn't nag me about it.
A neat feature of this simple implementation is that I can add the website as a [web app](https://www.macrumors.com/how-to/use-web-apps-iphone-ipad/) on the homescreen of my phone and it retains the task information! So I got a simple app really quickly.
I will probably iterate on this idea further but for now I'm happy to have a basic working version that I can test. What's definitely still missing is the *gratification* aspect and I'm not sure I want my tasks in a calendar-like view in the first place.
