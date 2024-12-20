---
layout: default
title: Readings and resources
permalink: /readings/
---

<details open markdown="block">
<summary>
Table of contents
</summary>
{: .text-delta}
1. TOC
{:toc}
</details>

## Generally-useful textbooks

The books below are all freely available in electronic format either from the University of Bristol library or (in the case of Erickson) from the author's website [here](https://jeffe.cs.illinois.edu/teaching/algorithms/). None of them are compulsory, but if you're having a hard time following something from lectures, it might help you to see the same thing presented in a different way. Many of the exercises in the course have also been taken from these books.

**Introduction to Algorithms (Cormen, Leiserson, Rivest and Stein):** This book is a truly excellent reference, and is generally considered the "standard" algorithms text. When I was learning this material for the first time, though, I found it quite dry and difficult to understand. 

**Algorithm Design (Kleinberg and Tardos):** This book is the one I wish I'd had as an undergraduate. It moves much more slowly and spells things out in far more detail than Cormen, while being very careful not to lose sight of the overall motivation. Highly recommended.

**The Algorithm Design Manual (Skiena):** When I say Kleinberg and Tardos is the book I wish I'd had as an undergraduate, bear in mind that I did my undergraduate degree in maths! This book is written from a more "engineering" point of view, and assumes less ability to prove things, than either of the books above. I particularly like the "war stories" in each chapter, which give examples of how the techniques we cover in this course can be used in practice.

**Algorithms (Erickson):** Frankly I don't know much about this book - I've only looked at the chapter on spanning trees in any detail - but that chapter talks about both Borůvka's algorithm and [Hyperbole and a Half](http://hyperboleandahalf.blogspot.com/2013/10/menace.html), a combination which instantly won my respect. The book opens by quoting Skiena: _"It is traditional for the author to magnanimously accept the blame for whatever deficiencies remain. I don't. Any errors, deficiencies, or problems in this book are somebody else's fault, but I would appreciate knowing about them so as to determine who is to blame." It then warns the reader that it contains "several mistakes, bugs, gaffes, omissions, snafus, kludges, typos, mathos, grammaros, thinkos, brain farts, poor design decisions, historical inaccuracies, anachronisms, inconsistencies, exaggerations, dithering, blather, distortions, oversimplifications, redundancy, logorrhea, nonsense, garbage, cruft, junk, and outright lies, all of which are entirely Steve Skiena's fault"._ A much more light-hearted approach to the subject than the other options on the list.

Sometimes I will also recommend parts of other books, generally when none of the above four books cover a topic well enough.

## Resources for specific weeks

### Week 1

* **Cormen et al.:** Chapters 3.1 and 3.2 cover O-notation.
* **Kleinberg and Tardos:** Chapters 2.1 and 2.2 cover O-notation.
* **Skiena:** Chapter 1.3 covers proof in general, with 1.3.4 dedicated to induction in particular. Chapters 2.1 to 2.5 cover O-notation.

### Week 2

* **Cormen et al.:** 16.1 covers interval scheduling, 16.2 discusses greedy algorithms more generally.
* **Erickson:** 4.2-4.3 covers interval scheduling, 5.1 covers the history of graphs and Eulera walks, and 5.2 covers some basic definitions.
* **Kleinberg and Tardos:** 4.1 covers interval scheduling and greedy algorithms and 3.1 covers graphs.
* **Skiena:** 1.2 covers interval scheduling, 5.1 covers graphs, and 15.7 covers Euler walks.
* **Bondy and Murty, Graph Theory with Applications:** 4.1 covers Euler walks.

### Week 3

* **Kleinberg and Tardos:** 3.1 covers trees (though not in much detail).
* **Bondy and Murty, Graph Theory with Applications:** 1.5 covers the handshaking lemma, and 4.2 covers Hamilton cycles and Dirac's theorem.
* **Harris, Hirst and Mossinghoff, Combinatorics and Graph Theory:** 1.3.1 and 1.3.2 covers trees in more detail than Kleinberg and Tardos, giving alternative proofs of the first few results proved in the video.
* **Even, Graph Algorithms:** 2.1 proves an analogue of the fundamental lemma of trees.

Back to CS books next week, honest!

### Week 4

* **Cormen et al.:** 22.1 covers graph representations, 22.2 covers breadth-first search, 22.3 covers depth-first search, and 24.3 covers Dijkstra's algorithm.
* **Kleinberg and Tardos:** 3.2 and 3.3 cover graph representations, breadth-first search and depth-first search, and 4.4 covers Dijkstra's algorithm.
* **Skiena:** 5.2 covers graph representations, 5.6 covers breadth-first search, 5.8 covers depth-first search, and 6.3.1 covers Dijkstra's algorithm.
* **Erickson:** 5.3 and 5.4 cover graph representations, and 5.5, 5.6 and 8.6 cover breadth-first search, depth-first search, and Dijkstra's algorithm.

### Week 5

* **Cormen et al.:** 23.1 and 23.2 cover Prim's algorithm and Kruskal's algorithm, although the section on Kruskal's algorithm won't make much sense until next week.
* **Kleinberg and Tardos:** 4.5 covers Prim's algorithm and Kruskal's algorithm.
* **Skiena:** 6.1.1 covers Prim's algorithm, and 6.1.2 covers Kruskal's algorithm.
* **Erickson:** 7.1, 7.2, 7.4 and 7.5 cover Prim's algorithm and Kruskal's algorithm.
* **Bondy and Murty, Graph Theory with Applications:** 5.1 covers matchings and augmenting paths. (Matchings are covered in all four other books as well, but from a different perspective that we will come to later in the unit.)

### Week 7

* **Cormen et al.:**  21.1-21.3 cover the union-find data structure. 13.1-13.4 cover red-black trees and are an amazing advertisement for never thinking of 2-3-4 trees as red-black trees unless you're implementing them. 18.1-18.3 cover B-trees, which are a slight generalisation of 2-3-4 trees and include 2-3-4 trees as a special case.
* **Kleinberg and Tardos:** 4.6 covers the union-find data structure.
* **Skiena:** 6.1.3 covers the union-find data structure. 3.4.3 discusses balanced trees, and 12.1 gives a detailed comparison of 2-3-4 trees to other data structures with similar purposes and complexities, but the book doesn't go into any detail on implementation.
* **Erickson:** The union-find data structure is covered in the "Director's cut" [here](https://jeffe.cs.illinois.edu/teaching/algorithms/notes/11-unionfind.pdf).

### Week 8

* **Cormen et al.:** 29.1 and 29.2 give an overview of linear programming. Avoid sections 29.3-5, which discuss the simplex algorithm, unless you are morbidly curious about how it's possible to spend 28 pages discussing it in detail without once mentioning the geometric intuition behind it. 26.1 covers flow networks, and 26.2 covers Ford-Fulkerson.
* **Kleinberg and Tardos:** 11.4 gives an overview of linear programming and goes into detail about the application to vertex cover. 7.1 and 7.2 cover flow networks and Ford-Fulkerson.
* **Skiena:** 13.6 discusses linear programming from a high-level "how do I use/solve this?" perspective. Their coverage of flow networks and Ford-Fulkerson in 6.5 is bound up with their coverage of bipartite matchings, for reasons that will become clear next week.
* **Erickson:** Network flows and Ford-Fulkerson are covered in 10.1-10.4.
* A pleasant song to listen to while you reflect on how the details of the simplex algorithm are non-examinable: [Here](https://www.youtube.com/watch?v=pg9l7Mx27t8).

### Week 9

* **Cormen et al.:** 26.3 covers maximum matchings in bipartite graphs from a flow perspective. 34-34.3 covers the definitions of NP-completeness, and 34.4 and 34.5 give examples of NP-completeness proofs.
* **Kleinberg and Tardos:** 7.5 covers maximum matchings in bipartite graphs from a flow perspective, and 7.7 covers circulations. 8.1 and 8.3 cover the definition of NP-completeness, and 8.2 covers the proof that 3SAT is NP-complete.
* **Skiena:** 9.1-9.3 cover the idea of a reduction, with several examples. 9.4 covers the proof that 3-SAT is NP-complete. 9.5 gives some more examples of reductions, 9.6 gives some general advice for coming up with reductions, and 9.9 discusses the philosophy of P versus NP.
* **Erickson:** 11.2 covers vertex capacities and 11.3 covers maximum matchings in bipartite graphs from a flow perspective. 12.1-12.3 and 12.5 set out the key definitions for NP-completeness.

### Week 10

* **Cormen et al.:** 34.3 proves an alternative form of the Cook-Levin theorem, proving directly that "Circuit-SAT" is NP-complete. 34.5 gives an alternative NP-completeness proof for vertex cover.
* **Kleinberg and Tardos:** 8.2 gives a slicker reduction from 3-SAT to independent set, and 8.4 proves the alternative form of the Cook-Levin theorem. 8.9 defines Co-NP. 8.10 gives a nice taxonomy of NP-hard problems for use in reductions. Chapter 10 gives a detailed treatment of treewidth, and chapter 11 gives a detailed treatment of approximation algorithms.
* **Skiena:** 9.5.2 gives an alternative proof that vertex cover is NP-hard. 9.6-9.8 give a nice set of heuristics for coming up with hardness proofs in general. 9.10 discusses how to deal with NP-complete problems.
* **Erickson:** 12.7 gives a slicker reduction from 3-SAT to independent set, 12.8 discusses how to come up with hardness proofs in general, 12.9 and 12.14 gives a reduction from independent set to vertex cover, and 12.13 gives a nice taxonomy of NP-complete problems for use in reductions.
* **Arora and Barak, Computational Complexity:** 2.3 gives the full version of the proof of Cook-Levin I sketched in video 10-2, and 2.6 and 2.7 feature a good discussion of NP versus Co-NP.
* [The most accurate (and funniest) pop-culture exposition of quantum computing I've ever seen.](https://www.smbc-comics.com/comic/the-talk-3)

### Week 11

* **Cormen et al.:** Dynamic programming as a concept is covered in chapter 15 with many of the same examples given in Object-Oriented Programming and Algorithms last year (e.g. pole-cutting is 15.1). Weighted interval scheduling is demoted to an exercise in 16.1, which focuses on unweighted interval scheduling. Bellman-Ford is covered in 24.1, but only the "final version" covered in video 11-4 and not from the same dynamic programming perspective used in the unit. Cormen isn't very useful here.
* **Kleinberg and Tardos:** Dynamic programming as a concept is covered in chapter 6. Weighted interval scheduling is covered in 6.1, and Bellman-Ford is covered in 6.8 in a very similar way to how we cover it. The rest of chapter 6 consists of a whole lot more examples of dynamic programming algorithms with an emphasis on how you would come up with them, and with a very good collection of exercises at the end of the chapter. Very strongly recommended.
* **Skiena:** Dynamic programming as a concept is covered in chapter 8. The coverage is good and worth reading, but the examples used are completely different - weighted interval scheduling does not appear in the book, and Bellman-Ford is only mentioned in passing in 15.4.
* **Erickson:** Dynamic programming as a concept is covered in chapter 3. Again, good and worth reading (although I strongly disagree with the man about the value of greedy algorithms), but uses different examples to those covered in the course. As with Kleinberg and Tardos, has a very large and very good selection of exercises at the end of the chapter, but they seem to be a fair bit harder.