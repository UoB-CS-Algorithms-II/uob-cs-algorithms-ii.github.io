---
layout: default
title: Exam and unit mark info
permalink: /exam/
---
<details open markdown="block">
<summary>
Table of contents
</summary>
{: .text-delta}
1. TOC
{:toc}
</details>

Your unit mark will be split into two parts. 10% will come from Blackboard quizzes, which are called "in-class tests" on eVision but are neither in-class nor tests. The remaining 90% will come from an exam in January.

## Blackboard quizzes

* There are 10 quizzes in total, one per week, and they are equally weighted (so each quiz counts for 10% of your "in-class tests" mark and 1% of your unit mark).
* Quizzes are always due at midday on Tuesday the week after release. The university standard late penalties will apply.
* The quizzes are not tests. There is no time limit, you can leave the page and come back, you can (and should!) work on quizzes together with your friends, and you are free to use any online or offline resources you want.
* If your raw mark on a quiz is greater than 50%, then it will be set to 100% in the final grade calculation. Otherwise, it will remain unchanged. For example, a student who gets 55% in nine quizzes and 45% in one quiz will get a total mark of 94.5%.
* The intention is that thanks to the "rounding" above, almost everyone will get full marks on almost every quiz. They are explicitly intended not to gauge your ability, but to nudge you into keeping up with the unit.
* Immediately after you've submitted your quiz, you can (and should!) check to see exactly what you got wrong and why.

## Exam

**Everything below is currently subject to change, and is unlikely to be finalised until mid-TB1.** 

### Format and rules

* The exam will be in-person. 

* The exam will be two hours long.

* The exam will be open-note. This means you will be allowed to bring some number (TBD) of pages of handwritten or printed A4 notes with you to the exam room. You will not be allowed to access the unit lecture notes or any other resources, and you will not be allowed to work with others.

* Calculators are allowed, although you probably won't need one.

* The exam will be split into two sections, one short-answer and one long-answer. The exact format is still TBD - it is possible that the short-answer format will run as a Blackboard quiz, supervised in our computer labs, or that it will all be a paper exam.

* The exam will be divided into two sections. 
   * The first section will contain short-answer questions worth a total of 75 marks, in a similar format to the Blackboard quizzes. For these questions, you won't need to show any working, and any working you do show won't be taken into account --- you'll just need to choose an option, fill in blanks, write down a number, or give some similarly short answer. If you do show working, it's important that you circle your final answer or otherwise make it very clear what it is.
   * The second section will contain long-answer questions worth a total of 75 marks, in a similar format to the problem sheets. For these questions, you should show your working as you will be able to get partial credit even for an incorrect answer.

* Not all the questions will be of equal difficulty. I subscribe to the idea that a unit mark of 40 should be attainable by everyone in the class who's willing to put effort in, a mark of 70 should show genuinely impressive understanding of the material, and a mark of 90 or more should be a huge achievement that comes round once per year or less. This means the questions will start out relatively easy, to make sure it's not too hard to pass, and then get progressively harder, to make sure it's not too easy to get a high mark. To help you plan your time, each question (and each part of multi-part questions) will be tagged "short", "medium" or "long". In total, 80 marks will be available from short questions, 50 marks will be available from medium questions, and 20 marks will be available from long questions, for a total of 150. 
   * Short questions will correspond to questions rated [\*] or to the easier questions rated [\*\*] on the quizzes and example sheets.
   * Medium questions will correspond to the harder questions rated [\*\*] on the quizzes and example sheets, or to the easier [\*\*\*] questions. Some of them will require you to prove results or come up with new algorithms, and some of them will be similar to "short" questions but be more involved and require more time and effort for the same amount of marks.
   * Long questions will correspond to questions rated [\*\*\*] and [\*\*\*\*] on the quizzes and example sheets. They are intended to push the very best students, and you should not attempt them unless you have already tried all the short and medium questions.

* I won't "curve" marks, but I will make sure that I didn't accidentally make the exam too hard. For transparency, this is the procedure I use.
   * For each grade boundary (i.e. 40, 50, 60, 70) in the unit, I look at a couple of randomly-chosen anonymised students whose final mark is just below it (i.e. with marks 39, 49, 59, 69).
   * I look at those students’ exam scripts in detail and decide whether it’s correct that they should fail to attain the relevant grade, given the questions they’ve been able to answer relative to the unit ILOs. Let’s take the specific case of 40 as an example. In this case, the question I’m asking is: is it correct that this should fail rather than narrowly passing?
   * If I think it is correct that these scripts should fail, I define f(39) = 39.
   * Otherwise, i.e. if I think these scripts actually should be passes, then I define f(39) to be the mark I think they should have got – e.g. f(39) = 40 if I think they should be bare passes, or 42 if I think they should be passes with a bit of room to spare. 
   * So now I have four numbers f(39), f(49), f(59) and f(69). Together with f(0) = 0 and f(100) = 100, this defines a piecewise linear function f:[0,100] &rarr; [0,100] with five linear segments. Everyone’s raw mark then gets mapped to f(raw_mark) via scripts and spreadsheets, and I upload f(mark) to Blackboard (and it goes from there to eVision).
   * The end result is that your final mark **might** be higher than the sum of your marks for individual questions. It will never be lower.
   * The difference between this profcess and curving is that I'm not doing it to achieve a specific number of people passing or getting Firsts. In the incredibly unlikely event that half the class fails, I will not automatically drop the pass mark - I'll instead be trying to decide whether half the class _should_ have failed, and I'll make my decision based on that.

### Practice questions

* The exams in past years will be a little harder than the exam this year, because they were entirely open-note exams that allowed full access to the lecture notes - as such, it didn't really make sense to ask any pure bookwork questions like "define NP". That said, the material covered in the unit is exactly the same, and they're still the best source of practice. The following papers are available, with answers:
  * [Mock exam](mock-exam-questions.pdf) ([answers](mock-exam-solutions.pdf))
  * [August 2021-22](2022-resit-questions.pdf) ([answers](2022-resit-solutions.pdf))
  * [January 2021-22](2022-original-questions.pdf) ([answers](2022-original-solutions.pdf))
  * [August 2020-21](2021-resit-questions.pdf) ([answers](2021-resit-solutions.pdf))
  * [January 2020-21](2021-original-questions.pdf) ([answers](2021-original-solutions.pdf))
* Towards the end of term, I'll be making new copies of the Blackboard quizzes which you can take as often as you like for revision purposes, to help you practice for short and medium questions.
* The problem sheet questions you didn't go through in the example class are a great source of practice for medium and long questions.
*The exercises given in the relevant chapters of the unit's recommended textbooks (see [here](../readings)) are great practice for short, medium _and_ long questions.
* I'm not making past papers from before 2020-21 available, because the unit has changed a huge amount since then. In 2019--20, the unit was 20cp instead of 10cp, taught quite different material, and the exam did not allow access to notes. You can probably get copies from the Bristol library, but I wouldn't bother if I were you --- I already repurposed the most useful stuff for the mock exam anyway, and they won't come with detailed answers.

### Examinability

* All material appearing in video lectures and on Blackboard quizzes is examinable, with the following exceptions:
  * If a result is stated in lectures but not proved, then the proof is non-examinable. For example, you won't be expected to know how to prove the worst-case running time of the Edmonds-Karp algorithm, but you will be expected to know what that running time is.
  * Anything stated verbally in a lecture but not written on the slides is non-examinable.
  * All historical asides, industrial applications, and jokes are non-examinable.
  * Anything intrinsic to the way the material is presented is non-examinable. For example, I'd never ask you to state "Lemma 1 of Lecture 23", but you may be asked a question which requires you to know that statement. If a result has a standard name, then that name is examinable - for example, I might ask you to state Dirac's theorem or the Cook-Levin theorem. 
  * Anything specifically flagged as non-examinable is non-examinable. (Duh.)
* Anything in the following materials is non-examinable unelss it also appears in a video lecture or Blackboard quiz:
  * Anything specific to the problem sheets. The general techniques they teach are examinable --- for example, how to prove that a problem is NP-hard, or how to find a counterexample to a proposed greedy algorithm --- but the specific questions and answers are not.
  * Anything linked on the unit pages under readings and resources. They're just intended as alternative sources if you're having trouble understanding the lectures or if you'd like more detail on something.

### Strategy tips

* Remember that the exam will count for 90% of the unit marks, and the Blackboard quizzes will count for 10%. So if you have half-marks or more in every quiz (which counts as full marks), then you need 34% in the exam to pass, 45% in the exam for a II.ii, 56% for a II.i, and 67% for a First. Every little helps! 
* Being able to bring notes into the exam is incredibly powerful, and you should prepare them carefully. You don't have anywhere near enough space to just print out the lecture notes and bring them in. Instead, you should try to distill the concepts down to the very basics, to the point where you can reconstruct them from just a few reminder notes. In doing so, you will not only get an immediate advantage in the exam, you will also have made an excellent start on understanding and revising the material. 
* If you have been struggling with the unit and have limited time to revise, you should try to get a shallow understanding of the entire unit rather than a deep understanding of one or two areas. Being able to answer almost all the short questions and some of the medium questions is a perfectly viable path to a II.i, and being able to answer a decent proportion of the short questions and no medium questions is a perfectly viable path to a pass. By contrast, being able to answer almost all the short, medium and long questions on half of the unit but not being able to answer anything on the other half will lead to a II.ii or worse while taking much more work to achieve. There is also no guarantee that any particular topic will come up in the exam.
* If I ask you to prove something on the exam, the standard of rigour I'll be looking for is: would this convince your boss that the statement is true? In other words, I know most of you aren't mathematicians, so I'm not testing your ability to write rigorous symbol-heavy proofs like a mathematician would. (Even though I tend to write proofs that way myself in e.g. the problem sheet answers...) I'm testing your ability to see why something has to be true, and to communicate that argument clearly enough to be understood by others and to convince others. If you've done that, then you'll get full marks on the question. 