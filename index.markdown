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

Welcome to Algorithms and Data! In TB1 we'll be in the algorithms half of the unit, which is a direct continuation of the algorithms part of Object-Oriented Programming and Algorithms from last year. The focus will be on three key algorithm design skills, which will be useful to you no matter which language or programming paradigm you end up working with:

* **Greedy algorithms.** In other words, when can you replace a complicated algorithm that carefully considers the whole situation with a simple algorithm that just repeatedly does whatever seems like a good idea at the time?
* **Graphs and networks.** You were briefly introduced to these in Imperative Programming last year, and perhaps in school before that, but in this unit you will learn to use them effectively to model and solve unfamiliar problems.
* **Reductions.** In other words, rather than writing your own algorithm to solve a problem, either making clever use of a library function or proving that no fast algorithm exists. This will include learning how to apply dynamic programming techniques, which you were introduced to in Algorithms last year, to unfamiliar problems.

## Schedule and links to materials

Most of the material below (especially recordings of Q&As and problem classes) will require you to log in to University of Bristol systems. In any given week, you should:

1. Watch the videos. (Don't just skim the slides!)
1. Do the weekly quiz to check your understanding of the basic material.
1. Come to the problem class the following week to learn how to apply the material to unfamiliar problems - these are half-lecture half-lab, not just a place to work on the problem sheet.

If (and only if!) there's part of the material you're having trouble with in steps 2 or 3, first make sure this isn't a mistake in the video other people have already noticed - if it is, it will be posted as [errata](errata) and linked directly from the video below. After that, your best options are:

* Come to the weekly Q&A, where you can ask the lecturer questions either directly or anonymously via Padlet (linked below).
* Come to the drop-in sessions, which will hopefully be near-daily Monday to Friday, to ask a TA.
* Ask on the unit Team, which is monitored by both TAs and the lecturer and should get a response within a day.
* Check out the [recommended reading](readings) for another perspective on the same material.

| Week 1 | **Monday 2023/09/16**<br>Videos released | _1-1: Unit introduction_<br> ([Video](https://uob-my.sharepoint.com/:v:/g/personal/fz19826_bristol_ac_uk/EbkMSWQvKypLlZL5WRHa5hsBAXWIAujTQLdQwE9ntotuGg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SSdhXe), [slides](slides/video-1-1-verbose.pdf), [handout](slides/video-1-1-handout.pdf)) | _1-2: Induction_<br>([Video](https://web.microsoftstream.com/video/f9b002c0-ee53-439e-9d2b-93b146378cf3), [slides](slides/video-1-2-verbose.pdf), [handout](slides/video-1-2-handout.pdf)) |
| | [Optional resources](../readings/#week-1) | _1-3: Defining O-notation_<br> ([Video](https://uob-my.sharepoint.com/:v:/g/personal/fz19826_bristol_ac_uk/EWHDxKRJW0VHrBfW4SdEZXEB_R_9u5JZrD_KMyoVyDoxvg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dw3Z4L), [slides](slides/video-1-3-verbose.pdf), [handout](slides/video-1-3-handout.pdf)) | _1-4: Using O-notation_<br> ([Video](https://web.microsoftstream.com/video/71184484-ac02-47be-8725-18c7d99aaf8c), [slides](slides/video-1-4-verbose.pdf), [handout](slides/video-1-4-handout.pdf))<br>**Errata [here](errata/#week-1-video-4-using-o-notation)!** |
| | **Monday 2023/09/23**<br>[Quiz 1](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_260090_1&content_id=_9196068_1) due | **Friday 2023/09/20**<br>Q&A 1<br>([Padlet](https://uob.padlet.org/johnlapinskas1/coms20017-algorithms-and-data-q-a-1-zz7arww7ox6d1cyc), [recording](https://mediasite.bris.ac.uk/Mediasite/Play/745ebe6f53f944938d47e9dd2ca184731d)) | **Monday 2022/09/23**<br> Problem class 1<br> ([Sheet](sheets/sheet-1-questions.pdf), [solutions](sheets/sheet-1-solutions.pdf),<br> recordings [1](https://mediasite.bris.ac.uk/Mediasite/Play/28d2554516874da9b2a3a7506c7997dd1d), [2](https://mediasite.bris.ac.uk/Mediasite/Play/fe0b8e97e03547afb05f737816e2a8091d)) |
| | (**Optional:** [Dummy quiz](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_260090_1&content_id=_9187072_1)<br> to test your browser works.) | |
| Week 2 | **Monday 2023/09/23**<br>Videos released | _2-1: Greedy algorithms<br> and interval scheduling_<br> ([Video](https://web.microsoftstream.com/video/29d25fdb-e1ad-465c-add0-fed869967334), [slides](slides/video-2-1-verbose.pdf), [handout](slides/video-2-1-handout.pdf)) | _2-2: Correctness proofs <br>for interval scheduling_<br>([Video](https://web.microsoftstream.com/video/be5ba104-5fc1-4411-99a3-11c16bdce8a2), [slides](slides/video-2-2-verbose.pdf), [handout](slides/video-2-2-handout.pdf)) |
| | [Optional resources](../readings/#week-2) | _2-3: The bridges of Königsberg_<br> ([Video](https://web.microsoftstream.com/video/ecc0634a-c6e4-4d75-a7f0-22dcc38f8ab5), [slides](slides/video-2-3-verbose.pdf), [handout](slides/video-2-3-handout.pdf)) | _2-4: When does a<br> graph have an Euler<br> walk?_<br> ([Video](https://web.microsoftstream.com/video/6bddb899-7fed-4618-a25a-af0ac77069aa), [slides](slides/video-2-4-verbose.pdf), [handout](slides/video-2-4-handout.pdf)) |
| | **Monday 2023/09/30**<br>[Quiz 2](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_260090_1&content_id=_9209866_1&mode=cpview) due | **Friday 2023/09/27**<br>Q&A 2<br>([Padlet](https://uob.padlet.org/johnlapinskas1/coms20017-algorithms-and-data-q-a-2-r1zrrnis1gkyvc3b), [recording](https://mediasite.bris.ac.uk/Mediasite/Play/86f957442ada4ed3a3fd259312f8c0111d)) | **Monday 2023/09/30**<br> Problem class 2<br> ([Sheet](sheets/sheet-2-questions.pdf), [solutions](sheets/sheet-2-solutions.pdf), <br>recordings [1](https://mediasite.bris.ac.uk/Mediasite/Play/37c4e55e4b894a8db33deba63d9ddc351d), [2](https://mediasite.bris.ac.uk/Mediasite/Play/7e902bd5513a4a8daa462d7ed05cd2dc1d)) |
| Week 3 | **Monday 2023/09/30**<br>Videos released | _3-1: Directed Euler walks_<br> ([Video](https://uob-my.sharepoint.com/:v:/g/personal/fz19826_bristol_ac_uk/EQ5TUbxjCPdZv2wS8xfrBSwBCyZb-uqmbkcWhNOfBnIqoQ?e=E83dXZ), [slides](slides/video-3-1-verbose.pdf), [handout](slides/video-3-1-handout.pdf))<br> | _3-2: Hamilton cycles_<br>([Video](https://web.microsoftstream.com/video/f756ccf9-7cea-44e1-8c26-fa2eedcf490e), [slides](slides/video-3-2-verbose.pdf), [handout](slides/video-3-2-handout.pdf)) |
| | [Optional resources](../readings/#week-3) | _3-3: Shaking hands_<br> ([Video](https://web.microsoftstream.com/video/ce5aaf13-6c85-4b69-b7b7-489abe2676ee), [slides](slides/video-3-3-verbose.pdf), [handout](slides/video-3-3-handout.pdf)) | _3-4: Trees_<br> ([Video](https://uob-my.sharepoint.com/:v:/g/personal/fz19826_bristol_ac_uk/EXnSFqUtFmNXa-a4sxkt8vUBKWziIhJonS75BPwNACG6OA?e=yY5CbX), [slides](slides/video-3-4-verbose.pdf), [handout](slides/video-3-4-handout.pdf)) |
| | **Friday 2023/10/07**<br>[Quiz 3](https://www.ole.bris.ac.uk/webapps/blackboard/content/launchAssessment.jsp?course_id=_260090_1&content_id=_9214762_1&mode=cpview) due | **Friday 2023/10/04**<br>Q&A 3<br>(Padlet link in Team) | **Monday 2023/10/07**<br> Problem class 3<br>([Sheet](sheets/sheet-3-questions.pdf)) |

## What's in the unit

For more details on any of this, take a look at the first lecture video above.

**Video lectures** will be released every Monday morning, at a rate of four 15-25 minute videos per week. Everything in these lectures will be examinable unless explicitly stated otherwise, so you should watch them all carefully and make sure you understand them well. You should aim to watch all of them before the quiz deadline that Friday. Please do actually watch them rather than just skimming through the slides - some things are much easier to understand when someone's talking through them!

**Textbook readings** will be released at the same time as the video lectures, if you'd like more information or more detailed proofs. They are all completely optional and non-examinable, but they're a good place to try if you want another explanation of something.

**Blackboard quizzes** are weekly summative exercises covering that week's material. Each quiz will be released by Monday morning, and due at noon the following Monday. They will be automatically marked as soon as you submit them, and you will immediately be able to see what you got wrong and why. Together, they will account for 10% of your unit mark. However, any mark of 50% or more on a quiz will count as 100% in this calculation - in other words, everyone who makes a reasonable attempt will receive full marks. All the material you need for these quizzes will be covered in the video lectures, but you are encouraged to use any other resources you find helpful, and to work on them together with your friends. They're not timed, and you can leave the page after starting and come back later. In addition to being worth marks in and of themselves, these quizzes will be good preparation for the short-answer portion of the exam.

**Q&A sessions** are weekly hour-long sessions in which I answer any questions about the unit you might have - for example, questions about the video lectures, the problem classes, the Blackboard quizzes or the exam. These will be run in-person, but supported by Padlet, allowing you to ask questions anonymously during the session or or in advance before it (with TA moderation). Attendance is optional, but encouraged if you're having difficulty with any part of the week's material.

**Drop-in sessions** with TAs will run several times per week. These are similar to "office hours" - you can come along without booking in advance to talk to someone one-on-one. The times will be determined later, and we expect to announce them in week 1.

**Problem sheets** are weekly formative exercises covering the previous week's material. Each sheet will be discussed in an in-person **problem class** the week after it is released. These will be ~100-person classes led by John, and they won't quite follow the typical model of students doing problems while TAs wander around helping people. You **don't** have to try the sheet before the class, or even look at it. You **do** have to bring a copy of the sheet and make an effort to understand the previous week's material via the videos, Blackboard quizzes, Q&A, and asking questions on the unit team. The classes will then be a split between interactive lectures on how to solve problems and trying the ideas out for yourselves (either on your own or with your friends).

It's also worth noting that you should **not** try to finish the problem sheets! They contain far too much work to finish them in a week without neglecting your other units, and normally we'll only pick out a few questions to discuss during problem classes. The reason there are so many questions is that they'll also be good preparation for the long-answer portion of the exam, so you can double back later on and use them for practice while you're revising.

## Planning your time

The baseline expectation is that as a Bristol student, you should be spending **40 hours per week** on your course, i.e. the same amount of time you'd spend with a full-time job. This unit is worth 10 credit points out of 60 for the term, so you should aim to spend about 7 hours per week on it. Roughly speaking, that will divide into:

* 2 hours per week on video lectures;
* 2.5 hours per week on self-study getting to grips with the material;
* 1 hour per week on the Blackboard quiz; and 
* 1.5 hours per week on attending the problem classes. 

The self-study might involve e.g. going back over the lecture notes, or attending the Q&A, or looking at the textbook readings, or asking questions on the unit team, or trying questions from the problem sheet - the important thing is that you put the time in, and that you work in the way that suits you best.

## COVID policy

While I can't require that you wear a mask, I would still ask you to do so. When the government stopped bothering to keep track in March 2023, 2.9% of the UK population (1.9 million people) were experiencing long COVID symptoms according to [the official data](https://www.ons.gov.uk/peoplepopulationandcommunity/healthandsocialcare/conditionsanddiseases/articles/coronaviruscovid19latestinsights/infections), over 90% of them for 12 weeks or more. It is true that being vaccinated reduces the risk of long COVID, but "only" by about half, and there's not much protection from having been infected in the past. My own anecdotal experience agrees with this - five of my friends have life-altering symptoms from long COVID, including four who caught omicron while fully vaccinated. In my opinion, it's just not a smart risk to take when you can mostly avoid it by wearing a good mask. Unfiltered or poorly-fitting cloth masks and surgical masks are a nice gesture to protect others, but will do very little to protect you. I'll be wearing one of [these](https://www.airinum.com/products/lite-air-mask) - a decently-fitting cloth mask with insertable FFP2 filters. It's not perfect protection, but it's good enough to massively cut your risk without being overly bulky or muffling. 

I don't take attendance at problem classes, and I'd encourage anyone who is feeling ill or who has tested positive not to attend - recordings will be made available on the unit page after the fact, so you can catch up easily.