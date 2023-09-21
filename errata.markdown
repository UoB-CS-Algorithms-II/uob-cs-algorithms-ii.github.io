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