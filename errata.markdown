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

## Week 5 video 4 (Kruskal's algorithm)

In the graph on slide 5, the weight-1 edge should be a weight-10 edge (so that the situation shown in the slides can actually happen).