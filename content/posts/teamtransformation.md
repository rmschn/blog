+++ 
draft = false
date = 2026-03-16T11:59:43-04:00
title = "Team Transformation: From App Admins to DevOps"
slug = "" 
tags = []
categories = []
thumbnail = "images/tn.png"
description = "A Story of Team Transformation"
+++
## **Quick Note**

This post is about transformation. It isn’t a tech transformation story but a technical teams transformation from being specialized ‘application administrators’ to becoming ‘devops engineers.’ 
The names of individuals, companies, etc, have all be either changed or left out in order to protect their privacy, but the reader can understand that this is a story from my professional past in a leadership role.

A little background to give some industry contexts for these transformations is in order.
 
## **App Admin**

In the enterprise there are many contracts, professional relationships, proprietary technologies in place, and of course, over many years the specialization of the enterprise workforce. This is how things had been getting done for a long time. The industry started with system administrators which were not specialized roles, they were running all the systems. Over time the industry at least in the largest enterprises started to specialize the workforce and thus was born the Application Admin, or App Admin for short. This was / is essentially a systems admin for a single application used by the enterprise.

## **DevOps**

Then along came ‘Dev/Ops.’ Another but new specialization at the time, which essentially combined several related but different responsibilities. Related in the since that they were generally operating on the same tech stack, but different in the sense that one side was developing that tech stack, and the other was operating it. Thus DevOps is born. The idea that you built it you run it. You might still have individuals with specialization within the DevOps team, but it’s generally the case that these individuals are cross-trained within the team to operate across the tech. The industry adoption of this caused a transformation. 

## **Transformation**

So how does transformation happen? What do you do in order to encourage a group of people to adopt an entirely new mindset, operating model, and gain new skills? Not only that, but do it while they are all still making the same salaries, and must continue to run the same environments they are currently responsible for during the transition, all the while, transitioning everything to the new way?

While I am sure there are many ways to do it, the following describes how I did it for my teams at that time.

Lets briefly describe the team as it was in the beginning. This was a data center automation team. It essentially ran a piece of software called OpsWare (later called HPSA after its acquisition). They also ran another piece of software called SCCM. They were a team of App Admins. There were approximately a dozen.

What was the decider for the transformation? It was two-fold really, it had been decided that the proprietary software systems needed to be replaced by open source based systems. (A story for another post.) In order to facilitate that stack change, the organization either need to hire, or transform the team it had, or a little of both. 
These app admins at the time were also a ticket driven team. They ran like the usual ticket driven teams. Tickets came in, the addressed them in the order they arrived, and priority given. They served on an on-call, and so on. 

So how do you transform a team like that into DevOps Engineers? 

Here was the plan..

- **Transition team from ticket driven to sprint driven, in this case SCRUM**

This is simply a decision, and the beginnings of a mindset shift. I won’t go into why SCRUM or what SCRUM is. I’m sure you can read about that elsewhere. In general its the decision to stop being ticket driven that is key. 

- **Reserve sprint capacity for training**

Capacity is an amount of time each individual has for Sprint work. A good rule of thumb is that number should be approximately 80% of the total available normal working hours for any given week. From there in order to reserve capacity for training, you reduce that 80% number some more. This ensures there is no excuse to not have time to learn. 

In our case, in the beginning of the transition everyone had 20% of that 80% to train on the new technologies we were adopting. Also, as you learned something, you were asked to brown bag it to the team over lunch at the close of the sprint. Also, we asked people to write things up and post them for the team about what they learned especially if it might accelerate the other team members learning.

- **Cycle the duties of SCRUM Master through the team as they participate in the sprints.**

SCRUM Master can be a thankless role, and one that the individual sitting in it gets attacked by the team in the sprint since the SCRUM master is responsible for the sprints delivery. They may make decisions at every Standup that impact other team members. What better way to bake in empathy and understanding than to cycle that responsibility. 

In our teams the SCRUM Master had approximately 10% of their sprint capacity withheld to perform the duties of the SCRUM Master.
                                                                                                                                                 
- **Time box all activities**

In order to keep things from ballooning into sucking up all the oxygen and time in the sprint, any activities that could be reasonably time boxed was. If you ran out of time, well the story was still done for that sprint. You make notes of what happened, and status and it likely walks into the new sprint with a new time box. This must be paid attention to carefully. It can be abused.

- **Never create a story in a sprint dependent on another team to deliver**

Any story that starts with a dependency on the delivery of a team not managed by the Sprint is a set up for failure. They do not share your priorities and you do not know what theirs are. So.. never write a story that depends on some other team providing you something in the current sprint. Always start and plan your work after you have your prerequisites. Need something done by another team, put in a story to open a ticket with that team in your sprint, and document it, and who from that other team eventually takes ownership of that tickets deliverable to your team. Now you at least know who owes you something, but your sprint delivery is not subjected to the whims of another team.


- **Modify on-call system to be a Sprint Capacity Status for both a Primary (no Sprint capacity) and a Secondary (half of normal Sprint Capacity)**

Interruptions kill a sprint. If you are transitioning from a ticket driven team to devops, you need to get a handle on this and box it in so it doesn’t impact the entire team and ruin your sprints. The way we did this was simple. 

Identify a primary and a secondary oncall. Just like the team did before for after hours on-call, only this is for the duration of the sprint and both during work hours and after hours. So the primary has zero sprint capacity. If they happen to not get many calls or tickets, then good for them. They have  a lot of free time to learn new things. Always review what happened in on-call during Sprint Retro.

The secondary oncall, has at least 50% sprint capacity reduction. They are called on by the primary if the primary is being overwhelmed. They are also inline to be the next primary, so they are motivated to stay on top of whats happening in on-call. 

This protects the sprint. It worked very well.

- **Set delivery dates, and keep them.**

As you transition, and your team learns, it will learn very well, how long it takes them as a group to do anything. They will know this about each other as well due to serving as SCRUM Master at some point. Over time the teams ability to estimate will be very good. Others on the team will even be able to do reasonable estimations for other people on the teams work. 

This enables the team to set dates on deliverables and keep them. 

- **Review with team members the data about them and their sprints, and coach, and mentor**

If you operate like this as you transition the team members from App Admins to DevOps Engineers, you will be gathering data as a group about everyone and everything done. Reviewing this with each engineer is also key to the transition. 
                                                                                                                                           
In my case, I would review Monthly and Quarterly with each individual on the team. You learn a lot about people doing this. It will become evident to you if a team member bakes in extra time for themselves. Or if a team member is always right about their time estimates because they always deliver 100%. 

## **Team Transformation Benefit**

Adopting DevOps at the enterprise level delivers significant, measurable benefits. Here are the key advantages:

## **Speed & Efficiency**
- **50% faster feature delivery** – Organizations with mature DevOps practices can get new capabilities to market much quicker than traditional approaches
- **Quick feedback loops** between development, operations, business, and testing teams enable faster iteration and improvement
- **Containerization** enables rapid, secure, and efficient application building, testing, deployment, and maintenance

## **Reliability & Stability**
- **60% fewer production incidents** compared to organizations treating DevOps as optional or purely cultural
- **Faster recovery** when problems do occur – mature DevOps teams can detect and resolve issues quickly
- **Resilience without sacrificing velocity** – you can ship features confidently while maintaining system stability

## **Scalability**
- **Platform engineering** provides the internal tools and infrastructure that enable DevOps practices to scale across growing enterprise teams
- Delivery can scale as teams grow without proportional increases in incidents or downtime
- Standardized practices work across hybrid cloud environments and diverse technology stacks

## **Cultural & Operational Benefits**
- **Improved collaboration** – breaks down silos between development and operations
- **Better alignment** of funding, accountability, and operating models across the organization
- **Enhanced agility** – teams can respond more quickly to market changes and customer needs
- **Continuous improvement** of both products and processes through iterative feedback

## **Competitive Advantage**

As of 2026, DevOps has become a baseline expectation. You almost never see jobs posted for Application Admins anymore. Organizations that have mature DevOps practice are significantly outperforming those that haven't, particularly as the industry leans more into AI-assisted development and complex feature sets.

The key insight from recent research: organizations that pursue velocity *without* stability, or automation *without* governance, consistently underperform. The real benefit comes from implementing **mature, enterprise-grade DevOps** that balances speed with reliability.

## **Next Post**

Maybe in our next post we’ll address Tech Transformation, that this particular Team Transformation enabled. Until then.. Cheers.

