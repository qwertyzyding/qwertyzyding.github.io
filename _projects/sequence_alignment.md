---
title: "Hardness of sequence alignment from fine-grained complexity"
collection: projects
permalink: /project/sequence_alignment
excerpt: 'This project is about the hardness of sequence alignment, a fundamental problem in computational biology. We show that the online version of this problem is hard assuming Orthogonal Vectors Conjecture.'
date: 2022-01-08
venue: 'Computational Biology'
paperurl: 'http://qwertyzyding.github.io/files/Hardness_of_sequence_alignment_from_fine_grained_complexity.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

We study the hardness of sequence alignment problem in the context of data structure lower bounds. In particular, the problem is given a database of many sequences, and on each query sequence, find the sequence from the database that best aligns to the query. This characterizes the task of finding similar species from a huge biological database. We show that assuming Orthogonal Vectors Conjecture in fine-grained complexity, even approximately finding the optimal answer is very hard, in the sense that there could not be a data structure that simultaneously achieves $\mathrm{poly}(n)$ space and $n^{1-\epsilon}$ query time, where $n$ is the length of the database. This
means that essentially we need to enumerate over the whole database to get the answer.


See the report [here](http://qwertyzyding.github.io/files/Hardness_of_sequence_alignment_from_fine_grained_complexity.pdf).
