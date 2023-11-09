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