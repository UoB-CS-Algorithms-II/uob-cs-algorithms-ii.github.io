---
layout: default
title: Main hub
nav_order: 1
permalink: /
---

<details open markdown="block">
<summary>
Table of contents
</summary>
{: .text-delta}
1. TOC
{:toc}
</details>

## Welcome

Welcome to Algorithms II! This unit is a direct continuation of the algorithms part of Object-Oriented Programming and Algorithms from last year. The focus will be on three key algorithm design skills, which will be useful to you no matter which language or programming paradigm you end up working with:

* **Greedy algorithms.** In other words, when can you replace a complicated algorithm that carefully considers the whole situation with a simple algorithm that just repeatedly does whatever seems like a good idea at the time?
* **Graphs and networks.** You were briefly introduced to these in Imperative Programming last year, and perhaps in school before that, but in this unit you will learn to use them effectively to model and solve unfamiliar problems.
* **Reductions.** In other words, rather than writing your own algorithm to solve a problem, either making clever use of a library function or proving that no fast algorithm exists. This will include learning how to apply dynamic programming techniques, which you were introduced to in Algorithms last year, to unfamiliar problems.

## Schedule and links to materials

| Week 1 | **Monday 2022/09/26**<br>Videos released | _1-1: Unit introduction_<br> ([Video](https://web.microsoftstream.com/video/70f4313b-bde0-44a0-9eb5-2e0f1190d944), [slides](slides/video-1-1-verbose.pdf), [handout](slides/video-1-1-handout.pdf)) | _1-2: Induction_<br>([Video](https://web.microsoftstream.com/video/f9b002c0-ee53-439e-9d2b-93b146378cf3), [slides](slides/video-1-2-verbose.pdf), [handout](slides/video-1-2-handout.pdf)) |
| | [Optional resources](../readings/#week-1) | _1-3: Defining O-notation_<br> ([Video](https://web.microsoftstream.com/video/f7a2f3f6-b468-4ca6-b802-55cdd0a93f67), [slides](slides/video-1-3-verbose.pdf), [handout](slides/video-1-3-handout.pdf)) | _1-4: Using O-notation_<br> ([Video](https://web.microsoftstream.com/video/71184484-ac02-47be-8725-18c7d99aaf8c), [slides](slides/video-1-4-verbose.pdf), [handout](slides/video-1-4-handout.pdf)) |
| | **Monday 2022/10/03**<br>[Quiz 1](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_252983_1&content_id=_7306183_1&mode=cpview) due | **Thursday 2022/09/29**<br>Q&A 1 ([Padlet](https://uob.padlet.org/johnlapinskas1/dxcagumjlt89qhrm), recording) | **Friday 2022/10/05**<br> Problem class 1<br> Sheet coming week 2 |
| | (**Optional:** [Dummy quiz](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_252983_1&content_id=_7352533_1&mode=cpview)<br> to test your browser works.) | |

## What's in the unit

For more details on any of this, take a look at the first lecture video above.

**Video lectures** will be released every Monday at 10am, at a rate of four 15-25 minute videos per week. Everything in these lectures will be examinable unless explicitly stated otherwise, so you should watch them all carefully and make sure you understand them well. You should aim to watch all of them before the quiz deadline on the following Tuesday. Please do actually watch them rather than just skimming through the slides - some things are much easier to understand when someone's talking through them!

**Textbook readings** will be released at the same time as the video lectures, if you'd like more information or more detailed proofs. They are all completely optional and non-examinable, but they're a good place to try if you want another explanation of something.

**Blackboard quizzes** are weekly summative exercises covering that week's material. Each quiz will be released on Monday at 10am, and due the following week. They will be automatically marked as soon as you submit them, and you will immediately be able to see what you got wrong and why. Together, they will account for 10% of your unit mark. However, any mark of 50% or more on a quiz will count as 100% in this calculation - in other words, everyone who makes a reasonable attempt will receive full marks. All the material you need for these quizzes will be covered in the video lectures, but you are encouraged to use any other resources you find helpful, and to work on them together with your friends. They're not timed, and you can leave the page after starting and come back later. In addition to being worth marks in and of themselves, these quizzes will be good preparation for the short-answer portion of the exam.

**Q&A sessions** are weekly hour-long sessions in which I answer any questions about the unit you might have - for example, questions about the video lectures, the problem classes, the Blackboard quizzes or the exam. These will be run online with Padlet and Teams, allowing you to ask questions anonymously or in advance (with TA moderation). I'm running them online not because of covid, but because I've tried running them both online and in-person and I sincerely think they work better online. Attendance is optional, but encouraged if you're having difficulty with any part of the week's material.

**Drop-in sessions** with TAs will run several times per week. These are similar to "office hours" - you can come along without booking in advance to talk to someone one-on-one. These will take place at the following times and locations:

* **Mondays 11:45-12:45**:  In-person, room TBD. Week 2 onwards.
* **Tuesdays 10:00-11:00**: In-person, room TBD. Week 2 onwards.
* **Wednesdays 15:00-16:00**: Online on the unit team. Week 2 onwards.
* **Thursdays 14:00-15:00**: In-person, room TBD. Week 2 onwards.
* **Fridays 13:00-14:00**: Online on the unit team. Week **\*1\*** onwards.

**Problem sheets** are weekly formative exercises covering the previous week's material. Each sheet will be discussed in an in-person **problem class** the week after it is released. These will be ~50-person classes led by either John or Adi, and they won't follow the typical model of students doing problems while TAs wander around helping people. You **don't** have to try the sheet before the class, or even look at it. You **do** have to bring a copy of the sheet and make an effort to understand the previous week's material via the videos, Blackboard quizzes, Q&A, and asking questions on the unit team. The classes will then be a split between interactive lectures and group work, focusing mostly not on the material itself but on how to apply it to solve problems. 

It's also worth noting that you should **not** try to finish the problem sheets! They contain far too much work to finish them in a week without neglecting your other units, and normally we'll only pick out a few questions to discuss during problem classes. The reason there are so many questions is that they'll also be good preparation for the long-answer portion of the exam, so you can double back later on and use them for practice while you're revising.

While I can't require that you wear a mask, I would still ask you to do so. As of July 31st, 3% of the UK population are experiencing long COVID symptoms according to [the official data](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/articles/coronaviruscovid19latestinsights/infections), and about 1.5% of the population have been experiencing them for a year or more. It is true that being vaccinated reduces the risk of long COVID, but "only" by about half. My own anecdotal experience agrees with this - most people I know have had COVID, and a few of them do indeed still have long-lasting symptoms despite having contracted omicron rather than delta and despite being fully vaccinated and boosted. It's just not a smart risk to take when you can avoid it by wearing a good mask. Unfiltered or poorly-fitting cloth masks and surgical masks are a nice gesture to protect others, but will do very little to protect you. I'll be wearing one of [these](https://www.airinum.com/products/lite-air-mask) - a decently-fitting cloth mask with insertable KN95 filters. It's not perfect protection, but it's good enough to massively cut your risk without being overly bulky, expensive or muffling. If you are very worried about COVID and would otherwise not come to the problem classes, I would recommend one of [these](https://www.3m.co.uk/3M/en_GB/worker-health-safety-uk/safety-solutions/respiratory-protection-centre/secure-click-respirators/) masks with [these](https://www.3m.co.uk/3M/en_GB/p/d/v100801892/) FFP3 filters - they have a perfect seal and will give you absolutely perfect protection, at the cost of making you look and sound ridiculous.

I don't take attendance at problem classes, and I'd encourage anyone who is feeling ill or who has tested positive not to attend - recordings will be made available on the unit page after the fact, so you can catch up easily.

## Planning your time

The baseline expectation is that as a Bristol student, you should be spending **40 hours per week** on your course, i.e. the same amount of time you'd spend with a full-time job. This unit is worth 10 credit points out of 60 for the term, so you should aim to spend about 7 hours per week on it. Roughly speaking, that will divide into:

* 2 hours per week on video lectures;
* 2.5 hours per week on self-study getting to grips with the material;
* 1 hour per week on the Blackboard quiz; and 
* 1.5 hours per week on attending the problem classes. 

The self-study might involve e.g. going back over the lecture notes, or attending the Q&A, or looking at the textbook readings, or asking questions on the unit team, or trying questions from the problem sheet - the important thing is that you put the time in, and that you work in the way that suits you best.