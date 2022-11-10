---
layout: default
title: Announcements
permalink: /announcements/
---
<details open markdown="block">
<summary>
Table of contents
</summary>
{: .text-delta}
1. TOC
{:toc}
</details>

# Announcements Page

## Quiz deadline change and response to mid-term feedback

Hi all,

The mid-term feedback is in! Thanks to everyone who responded, 60 people is a really good rate and it helps us make things better for future years. I'd rather not stick the feedback and my responses on the open Internet, and it's pretty long, so I've linked it on OneDrive [here](https://uob-my.sharepoint.com/:b:/g/personal/fz19826_bristol_ac_uk/Efg8TrhxpZBEqSo5iEjhv-kBqol4ebW0_5SWIF7bNJV-mw?e=bGtRU0). That said, there are a couple of things that I think are major enough to mention in this email.

**Quiz deadlines:**

Some people made the very reasonable point that having the quiz deadline on a Monday means people are pushed into working on it over the weekend, which besides being generally antisocial is also the time when there's least TA support available. As such, **quiz deadlines will be on Tuesdays from now on**. The quiz 6 deadline has been moved back a day accordingly.

**More examples:**

A lot of people have asked for more examples to be available. There's one really good and under-utilised source of this - the foundational problem classes! Adi is an excellent teacher and class sizes are currently very small (ten people or less). I've heard some concern via the Staff-Student Liaison Committee that going to them will leave you unprepared for the exam, or leave you needing to do perfectly to secure a pass, and this couldn't be further from the truth. If you've kept up with the quizzes (which are worth 10% of the overall mark), then you need a mark of 50/150 to pass the exam. I've written the exam now, and roughly speaking the mark breakdown is:

80 marks: A mix of pure bookwork questions ("Which of these five options is the definition of O-notation?"), questions that ask about a definition ("Is this graph bipartite?"), and questions that ask you to apply a given algorithm to a given input. 

55 marks: Questions asking you to do things like finding counterexamples for greedy algorithms, finding reductions, prove things by induction or come up with dynamic programming algorithms. About 20 marks of these are pitched at a level where you should be able to do them just from understanding the underlying concepts, without spending any time practising them in problem-based problem classes. Think of the past paper question that asks for a graph with a Hamilton cycle but no Euler walk as an example. The remaining 35 marks get steadily harder, and you'll probably want to have spent some time practising problem-solving to do well at them. 

15 marks: OK, these ones are hard, and are intended to distinguish between the very best candidates.

So if you've never been to the problem-based problem classes, and you don't try the harder quiz questions, and you don't try either problem sheet questions or practice exam questions when you're revising... you've still got a solid 100 marks available to you, and you need 50 of those to pass. Meanwhile, if you try to go into the exam without understanding the fundamentals, it's not going to be pretty even if your problem-solving skills are good. 

So... I would really strongly recommend you give the foundational problem classes a try! They're not a dastardly trap, they're the single best thing you can do to prepare for the exam if you're having trouble with the fundamentals. And you can always just go to one, and swap back to the problem-based stream next week - especially if there's something that week you're having trouble with.

There are also five past exam papers available (with full solutions) on the unit page [here](https://uob-cs-algorithms-ii.github.io/exam/#practice-questions) - they're a little harder than the actual exam will be, since in past years the exam was open-Internet and not just open-note. And of course, you can always ask on the Teams channel or in the daily drop-ins.

**Drop-in topic for week 8**

Lastly, Charlotte's focused drop-in session next week will be based on 2-3-4 trees.

Best wishes,

John

Cat of the day: [Here](http://i.redd.it/muxlsdbw3ux91.jpg)!

## Minor error in video 6-4

Hi all,

Just a quick heads-up that there's a minor error in the definition of a red-black tree in video 6-4, right at the end - a node can have a single child (rather than two or zero) if the node is black and its child is a red leaf. The slides are fixed, and I was planning to fix the video before it went up, but the last week has been a mad 80-hour sprint to get a 90-page paper finished and submitted to a conference before both the deadline hits and my co-authors go on parental leave...! The deadline is Monday evening, so hopefully it will be up on arXiv on Tuesday in all its terrible glory and you can see exactly why it took so long.

Best wishes,

John

Cat of the day: [Here](http://i.redd.it/4oglyc9t72q81.png)!

## Reading week arrangements

Hi all,

Congratulations on making it to reading week! As with most units, there won't be any dedicated teaching so you all have time to catch back up (and so that I can sprint for a conference deadline on my next paper!), but the normal support will still be running. This means:

* We'll still be answering questions on the Teams channel.
* Drop-ins will still be running (**except** the drop-in on Friday November 4th). Charlotte's focused office hour next week will focus on matchings.
* There won't be any Q&A or problem class.
* The week 5 quiz will be due on Monday of **week 7**, so you have all of reading week to do it.

Have fun, have a good rest, and see you all in week 7!

Best wishes,

John

Cat of the day: [Here](https://preview.redd.it/xuc50kxm7m581.jpg?width=640&crop=smart&auto=webp&s=5e9fea4afe5b55b7d89519fff8ec5efdc18192dc)!

## Foundational Stream and New Office Hour Format

Hi Guys,

I hope year 2 is going well!

Last week was the first week of the new foundational stream in the problem classes, and we think they went really well, so we’re going to continue them for the rest of term.

If you were already coming along, then that’s great!
However, attendance last week wasn’t as high as we’d hoped, so I’m gonna shamelessly advertise these some more :)

The foundational stream is intended to help students grasp the basics.
If you’ve been **challenged or confused by any of the \* or \*\* questions in the problem sheets**, then these are the sessions for you.

No prep is required, just show up, and we’ll walk you through everything you need to know.
Friday morning as usual in MVB 1.11.

Additionally, from tomorrow Charlotte will start running a ‘focussed office hour’.
This will be like a normal office hour, except now we will also encourage you to show up without questions, and each week there will be a different topic which Charlotte will go through.
These topics will be related to the material covered in that week.
These will continue to be on Thursdays at 2pm in Queens 1.59.

Historically, students who engage with the contact hours usually pass.
We **strongly** encourage you to come along to sessions - we want to help you understand this material as well :)

Thanks,
Adi

## Error in notes (weak connectedness)

Hi all,

I've realised there's a minor but important error in the notes and video for lecture 3-1: the definition of weak connectedness should say that G is weakly connected if for all vertices u and v, there's a path from u to v **ignoring edge directions**. (It previously required either a path from u to v or a path from v to u.) I've fixed this in the lecture notes now, and will upload a fixed version of the video later this week. There are no implications for Blackboard quiz marks, since the two definitions are equivalent for all the graphs in the quiz questions. 

To see the difference between these two definitions, think of the graph with V = {a,b,c} and E = {(a,b), (c,b)} - in other words, two edges, both pointing towards b. Under the old, incorrect definition of weak connectedness, this graph is not weakly connected, since there's no directed path from a to c and no directed path from c to a. But under the new, correct definition, this graph is weakly connected, since abc is a path from a to c ignoring edge directions. Conceptually, weak connectedness is exactly like connectedness in an undirected graph - it is saying that the graph is "all one lump" if you draw it out. 

I'd also like to shamelessly plug the new problem class format again. Right now we have very low numbers attending the foundational classes with Adi - which is absolutely great for everyone attending, since they're getting quality teaching in an incredibly small group size! But it's less great for all the people who would benefit from coming, but who are staying home. I can't stress this enough - no prep is required, Adi is a great teacher, and you will learn a hell of a lot. Barring illness, absolutely everyone taking the unit should be coming to either Adi's classes or mine.

Best wishes,

John

Cat of the day: [Here](https://imgur.com/dgTmhaI)!

## New problem class format from tomorrow!

Hi all,

From tomorrow onwards, we'll be experimenting with a **new format** for problem classes, which means **which group you're in might change** (although your time slot won't). So please read the rest of this email! 

Just about everyone finds this unit hard, but it became clear in the last class that different people find it hard in different ways. We’ve decided that going forward, we’ll split up the problem classes in each time slot according to these two areas people are struggling with most.

**Foundational class:** Run by **Adi** in **MVB 1.11** with an emphasis on helping with the definitions and algorithms themselves.

**Problem-based class:** Run by **John** in **MVB 1.11a** with an emphasis on using those definitions and algorithms to solve problems creatively.

As a general guide, if you find yourself having a lot of trouble with the \* and \*\* problems in a quiz in a given week, then you’ll probably get more out of Adi’s classes. These class will focus on questions like "what’s the difference between a path and a walk, or between isomorphism and equality, or between an induced subgraph and a subgraph?" "Is big O like less than or equals, or is it the other way round?" or "How would I implement Dijkstra’s algorithm?"

Other people find that the videos/quizzes/unit Team are enough to help them understand the definitions and algorithms introduced in the unit, but find it hard to see how to solve problems *using* these concepts. If that's you, then you'll probably get more out of my classes. These class will focus on questions like "How can you apply an exchange argument to a real greedy algorithm?" "How do you break a problem down into subproblems to apply induction or dynamic programming?" and "How would you come up with the proof of Dirac’s theorem for yourself?"

**This will replace your previous group assignments.** Whether you were originally assigned to my group or Adi's group for a given time slot, you can decide which class to go to on the day each week. This means that if you find the definitions or algorithms in a given week are unusually hard or unusually easy, then you can go to Adi’s class or my class accordingly. A TA will be standing outside with a whiteboard to point people to the right rooms. There won’t be anything examinable in either of our classes that’s not also covered in the lecture videos, so you don’t need to worry about missing out.

Also, one thing to ease people’s nerves a bit - while this is a very hard unit do well in, it’s not a very hard unit to pass. When I write the exam, I set up the mark distribution so that you can get a high 2.ii in this unit with just a solid grasp of the foundations. This means that if you understand the definitions and know the algorithms, then you have enough for a very comfortable pass. Getting a 2.i in the unit does require you to do some problem-solving as well, and this is genuinely difficult - normally about half the class manages it, and I have a lot of respect for everyone who does. But if you’re just worried about passing, then you can relax a little!

Best wishes,

John

Cat of the day: [Here](https://v.redd.it/b23c2pw5kvq91)!

## COVID cases rising, policy reminder

Hi all,

Unfortunately, fresher's flu season has become more sinister in recent years, and like this time last year, we've started to get reports of students in this unit testing positive for COVID... I'm not planning to move problem classes online - when it comes to small-group teaching, in-person is drastically better, and a good mask cuts out almost all the risk the risk to you (see the first video for an overview). But I wanted to flag that there are active cases for the benefit of people who might otherwise choose not to wear a mask - while the COVID-positive students I know about are doing the right thing and staying home, normally for every two people who know they have COVID there's one person spreading it asymptomatically.

Speaking of which, if you have COVID yourself, please don't come to problem classes! While the classes are very useful, they're also optional. We don't take attendance, and they're going to be recorded and made available on Re/Play, so you can catch back up afterwards. You're also much more likely to get a worse case of COVID if you push yourself while you've got it - so not only is it better to keep other people safe, it’s also in your own best interest to stay home and recover quickly rather than try to come in and end up recovering slowly.

Best wishes,

John

Cat of the day: [Here](https://img.freepik.com/premium-photo/cat-protective-medical-mask-protective-face-mask-animals-covid-19-coronovirus_36325-3303.jpg?w=2000)!

## Welcome and drop-in sessions

Hi all,

Welcome to Algorithms II! At this point you've hopefully already noticed that the main site is hosted on GitHub Pages [here](http://uob-cs-algorithms-ii.github.io) - last year Blackboard gave us a lot of trouble with file permission issues, and this should help to mitigate them. The first video gives a much more detailed introduction, but in short, this unit will cover material on a rolling basis. For example, for Week 1, I released video lectures this morning, we'll have an online Q&A on Thursday, there's a Blackboard quiz on the material with a deadline of next Monday (i.e. October 3rd), then we'll have a 90-minute in-person problem class on it the following Friday. Meanwhile, Week 2 will have its own material release and Q&A to match a quiz deadline and problem class in Week 3, and so on. 

**These weekly quizzes do count towards your unit mark, and are essentially free marks - don't let them slip by!** Again, the first quiz deadline is **noon on Monday October 3rd**.

Also, it looks like we'll also be able to run daily drop-in sessions with TAs this term. The final time slots and locations will appear in your calendars soon, but the draft version is:

* **Mondays 11:45-12:45**:  In-person, room TBD. Week 2 onwards.
* **Tuesdays 10:00-11:00**: In-person, room TBD. Week 2 onwards.
* **Wednesdays 15:00-16:00**: Online on the unit team. Week 2 onwards.
* **Thursdays 14:00-15:00**: In-person, room TBD. Week 2 onwards.
* **Fridays 13:00-14:00**: Online on the unit team. Week **\*1\*** onwards.

I know that not all of you will be able to make all these drop-in sessions, because free timetable slots are scarce, but I think we've managed to schedule things in such a way that most people have access to all of them and everyone has access to some of them.

I hope you all enjoy the unit - see you on Thursday for the first Q&A!

Best wishes,

John

Cat of the day: [Here](https://i.imgur.com/JLiyZa4.mp4)!