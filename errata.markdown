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