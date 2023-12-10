---
layout: post
title: Managers personal task management - discovery
tags: business task-management management productivity multi-part series
categories: projects
---

I recently started a new a job as executive in medium-sized B2B FinTech company. Though not my first rodeo, it is here where I finally achieved inbox zero for the first time, and, fingers crossed, may also sustain it.

Now I see the upcoming holiday slowdown could provide an opportunity to upgrade a quite related frenemy of mine: task management.

As this seems to be a topic of general concern for many people, and as there are hardly any secrets involved, I decided to create at least one post to let others share in my thoughts and hopefully the future fruits and less so the frustrations.

# Motivation & Problem

I think we can keep this light and straightforward, but folks it is a mess out there and if you work in an organisation that thinks it cracked task management in a way that is both efficient (eliminating tools and steps) and inclusive (works for all types of people, the managerial ones, the individual fighters, the disciplined and the others) then please tell me.

We could go into problem specifications, thinking backwards and success metrics but this is still a blog post, so lets keep it real.

# Context Discovery

However, as with any good design process, we begin with describing and maybe even structuring the relevant context, omiting any obvious things like, no, this wouldn't extend to grocery shopping or ticking off other private chores.

## Potential origins of tasks

* Task origin: **GSuite** comments (via assign to)
* Task origin: **Confluence** (via tagging)
* Task origin: **Jira**
* Task origin: **[fibery.io](fibery.io)** (love it, but its new and rare)
* Task origin: **slack** reminders
* Task origin: beeing mentioned in an **email** (🤦 lord give me strength)

## Potential types of tasks

I am not going to be even partially complete here, instead focusing on what I perceive to be different types of relation-defining tasks. 

* Task type: Owner/Driver/Accountable for an **objective** or a **key result** in OKR (🔺heirarchy detected)
* Task type: Personal **growth goal or task** (🔺heirarchy detected)
* Task type: recurring **meeting "pledges"**: Something agreed on and assigned during (sometimes recurring) meetings. These tasks should be done until the next same type of meeting, before a specified deadline or without a timeline (he-he). Examples of popular task-creating meetings:
  * Weekly check-ins between managers and their direct reports
  * Any other Group meetings
* Task type: [5-3-1 System](https://www.timedoctor.com/blog/1-3-5-rule/) (🔺heirarchy detected)

# Goals

And here the 🍹 juicy wishlist starts, prioritising according to the [MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method)

## Must have

* 👀 **Unified single source of truth** as read-only
* 🔗 Deep-link to the specific task origin

## Should have

* 📝 **Unified single source of truth** with limited write support for the task owner (e.g. set to done)
* 🔺 Represent hierarchy & dependencies in a good UI
* 🤝👀 Share a read-only single source of truth view with others
* 🤝💬 Load and display more meta-data like further comments from the origin
* ✨ Inspire collaborators to also adopt a structured and consolidated view for the tasks they interact with, maybe even via **[fibery.io](fibery.io)**
* ✅ pass compliance smell tests

## Could have

* 🔔 Unified notifications
  * Reminders for urgency or deadlines
  * New or changed tasks
* ⏰ Visualing deadlines well
* Sorting/ranking by some dimensions (importance, urgency, deadline, effort etc.)
* 🔒 Permission system that restrict which tasks are accessible to whom when sharing source of truth with others
* 🤝📝 Colaborators can add additional content, comments etc. towards the task origin but via the unified view (no context switches)


# Constraints

Omiting the "Won't have" of MoSCoW in the goals, instead I find it useful to focus on the harder and more flexible constraints that seem relevant to the problem and context.

## Hard constraints

* Cannot "just" migrate a whole organisation
* Cannot enforce complicated policies for (most) task origins
  * possible though: "allways tag a person"

## Soft constraints
* Avoid disruptive back-referencing from origin e.g. long ID-tags appearing next to human readable text.
* May not be able to guarantee intact back-referencing from origin i.e. users could overwrite "backlinks" or IDs
* Avoid extra license costs where possible
* Avoid steep learning curve

# Next steps

I will probably let these thoughts simmer for a little bit, while I explore the listed origin's possibilities and limitations in terms of interconnectivity.

I have the 🌠 wishful thinking that a low-code solution may be found. One that meets a good chunk of my design parameters while unifying towards **[fibery.io](fibery.io)**. 

I cannot avoid to point out my opinion that **If an organisation is already using fibery for everything™, this whole post would be likely irrelevant to them**. However, as migration is far-off in a scenario like mine, I must identify the baby steps first.

# AI disclaimer

* I asked ChatGPT which officially supported emojis best represent some of the concepts mentioned here. E.g for "hierarchy" it recommended 🔺 as a sort of pyramid.
* Slight grammar and style corrections were applied, ChatGPT had not much to complain.
