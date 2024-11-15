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


## Week 1 video 4 (Using O-notation)

In slide 4 on L'Hôpital's rule, the statement that n &isin; o(b<sup>n</sup>) for all b > 0 should instead require b > 1.

## Week 5 video 4 (Kruskal's algorithm)

In the graph on slide 5, the weight-1 edge should be a weight-10 edge (so that the situation shown in the slides can actually happen). This does not substantively affect the discussion.

## Week 7 video 4 (Red-black trees)

The 2-3-4 tree in the transferring example of slide 3 in the video isn't valid, as it shows a 3-node with values (2,5) and a middle child (1,3). This doesn't matter for the example, but these 3-nodes should be (1,5) and (2,3) respectively.

There's one exception to the rule on slide 7: in a red-black tree, a black node with a single child is OK if that child is a red leaf (corresponding to a 3-node leaf in a 2-3-4 tree).

## Week 8 video 1 (Linear programming)

Added a slide to the end saying in writing what I said in the video - that this is a general technique for reducing the problem of solving an arbitrary linear program to the problem of solving a linear program in standard form.

In slide 9, the explanation for how to put equality constraints into standard form should say that &Sigma;<sub>j</sub>a<sub>ij</sub>x<sub>j</sub> = b<sub>i</sub> if and only if &Sigma;<sub>j</sub>a<sub>ij</sub>x<sub>j</sub> &ge; b<sub>i</sub> and **&Sigma;<sub>j</sub>a<sub>ij</sub>x<sub>j</sub> &le; b<sub>i</sub>**, not &Sigma;<sub>i</sub>a<sub>i</sub>x<sub>i</sub> = b<sub>i</sub>.

## Week 8 video 3 (Flow networks)

In slides 5 and 6 in the video, where the definition of a flow is recalled, f<sup>+</sup>(v) and f<sup>-</sup>(v) are the wrong way around. As in the original definition on slide 4, f<sup>+</sup>(v) should be the sum of f(v,w) over all vertices w in v's out-neighbourhood, and f<sup>-</sup>(v) should be the sum of f(u,v) over all vertices u in v's in-neighbourhood.

## Week 8 video 4 (Ford-Fulkerson)

In slide 4 in the video the same typo appears again, with f<sup>+</sup>(v) and f<sup>-</sup>(v) the wrong way around when the definition of a flow is recalled.

## Week 9 video 1 (Ford-Fulkerson redux)

In slide 2 the same typo appears yet again, with f<sup>+</sup>(v) and f<sup>-</sup>(v) the wrong way around when the definition of a flow is recalled. (Don't copy-and-paste your code, kids!)

On slide 5, the correct capacity of the middle edge is 1.5\*6 = 9, not 18.

Also on slide 5, "iff" in the video is actually not a typo - it's a standard abbreviation for "if and only if". But it's not used elsewhere in the unit, so I've replaced it with an arrow in the video.

## Week 10 video 1 (Independent sets and vertex covers)

In the recapped definition of VC in slides 9 and 10, the problem should ask: "Does G contain a vertex cover of size at most k?" rather than "at least k".