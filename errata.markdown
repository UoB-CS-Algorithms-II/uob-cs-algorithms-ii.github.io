---
layout: default
title: Errata for videos
permalink: /errata/
---

<details open markdown="block">
<summary>
Table of contents
</summary>
{: .text-delta}
1. TOC
{:toc}
</details>



## Week 1 video 3 (Defining O-notation)

New slide added at the end: we only care about O-notation for functions that are eventually non-negative.

Also, not a mistake but a common point of confusion: the reason we can say n! &ge; 4<sup>n-3</sup> on slide 6 is that we can write n! = n * (n-1) * ... * 4 * 3 * 2 * 1, where all but three of the n terms in the product are at least 4.

## Week 3 video 1 (Directed graphs)

The definition for weak connectedness stated in the video is subtly wrong. A directed graph is weakly connected when for all vertices u and v, there is a path from u to v **ignoring edge directions**, not when there is a path from u to v or from v to u (but maybe not both). For example, the graph with vertex set {1,2,3} and edge set {(1,2), (3,2)} is weakly connected under the first (correct) definition, but not under the second (incorrect) definition.

## Week 3 video 4 (Trees)

At the end of slide 6, the definition of a leaf as a degree-1 vertex is correct for unrooted trees. For rooted trees, the definition is the same except that the root cannot be a leaf, even if it has degree 1.

## Week 5 video 3 (Prim's algorithm)

The proof of correctness of Prim's algorithm contains a subtle bug in the definition of f on slide 7. Starting from just after the statement that 2 <= I <= \|V\| on slide 7, the definition should read as follows:

"Let v be the vertex added to T<sub>I-1</sub> by Prim's algorithm, so that V(T<sub>I</sub>) = V(T<sub>I-1</sub>) U {v}. Let C be the component of S - V(S<sub>I-1</sub>) containing v.

Since S is a tree, it's connected, so there must be an edge f from C to S<sub>I-1</sub>. Also, S has no cycles, so f must be the only edge from C to S<sub>I-1</sub>."

The proof should then continue as before, removing f from S and replacing it with e<sub>I-1</sub>. As before, after doing this, S is still a tree with w(S) <= w(T), and now S<sub>I</sub> = T<sub>I</sub>.

## Week 5 video 4 (Kruskal's algorithm)

In the graph on slide 5, the weight-1 edge should be a weight-10 edge (so that the situation shown in the slides can actually happen).

## Week 7 video 4 (Red-black trees)

The 2-3-4 tree in the transferring example of slide 3 in the video isn't valid, as it shows a 3-node with values (2,5) and a middle child (1,3). This doesn't matter for the example, but these 3-nodes should be (1,5) and (2,3) respectively.

There's one exception to the rule on slide 7: in a red-black tree, a black node with a single child is OK if that child is a red leaf (corresponding to a 3-node leaf in a 2-3-4 tree).

## Week 8 video 1 (Linear programming)

Added a slide to the end saying in writing what I said in the video - that this is a general technique for reducing the problem of solving an arbitrary linear program to the problem of solving a linear program in standard form.

## Week 8 video 3 (Flow networks)

In slides 5 and 6 in the video, where the definition of a flow is recalled, f<sup>+</sup>(v) and f<sup>-</sup>(v) are the wrong way around. As in the original definition on slide 4, f<sup>+</sup>(v) should be the sum of f(v,w) over all vertices w in v's out-neighbourhood, and f<sup>-</sup>(v) should be the sum of f(u,v) over all vertices u in v's in-neighbourhood.

## Week 8 video 4 (Ford-Fulkerson)

In slide 4 in the video the same typo appears again, with f<sup>+</sup>(v) and f<sup>-</sup>(v) the wrong way around when the definition of a flow is recalled.

## Week 9 video 1 (Ford-Fulkerson redux)

In slide 2 the same typo appears yet again, with f<sup>+</sup>(v) and f<sup>-</sup>(v) the wrong way around when the definition of a flow is recalled. (Don't copy-and-paste your code, kids!)

On slide 5, the correct capacity of the middle edge is 1.5\*6 = 9, not 18.

Also on slide 5, "iff" in the video is actually not a typo - it's a standard abbreviation for "if and only if". But it's not used elsewhere in the unit, so I've replaced it with an arrow in the video.

## Week 9 video 3 (SAT and NP)

You do not, under any circumstances, gotta hand it to JK Rowling. That Harry Potter reference dates back to 2019, it should not be there, and I wish I had time to re-record and remove it. :-(

## Week 10 video 1 (Independent sets and vertex covers)

In the recapped definition of VC in slides 9 and 10, the problem should ask: "Does G contain a vertex cover of size at most k?" rather than "at least k".

## Week 11 video 3 (The Bellman-Ford algorithm)

The version of GoodPath in the video has a subtle bug in the base case. Lines 2-3 should read:

**if** s = t **then**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Return the empty walk.<br>	
**else if** k = 0 **then**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Return None.
	
The rest of the algorithm is correct.