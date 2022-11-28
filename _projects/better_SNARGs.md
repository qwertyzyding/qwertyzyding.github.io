---
title: "Towards better SNARGs for P from Fiat-Shamir"
collection: projects
permalink: /project/2022-08-29-better_SNARGs
excerpt: 'This project is mainly about SNARG constructions using Fiat-Shamir in recent years. We make some attempts to generalize some techniques used in the constructions.'
date: 2022-08-29
venue: 'Research Immersion Training'
paperurl: 'http://qwertyzyding.github.io/files/Towards_better_SNARGs_for_P_from_Fiat-Shamir.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

We study the problem of constructing succinct non-interactive arguments ($\mathrm{SNARG}$s), an important tool in cryptography for delegating computations. In recent years, several results related to $\mathrm{SNARG}$s have appeared due to the progress in provably instantiating the Fiat-Shamir transformation. In this note, we show that some techniques used in constructing $\mathrm{SNARG}$s can be improved to work in more general settings, which may be useful in constructing better $\mathrm{SNARG}$s (e.g., a $\mathrm{DDH}$-based $\mathrm{SNARG}$) or in some other applications in cryptography.

See the report [here](http://qwertyzyding.github.io/files/Towards_better_SNARGs_for_P_from_Fiat-Shamir.pdf).

UPD: the problem of $\mathrm{SNARG}$s based solely on $\mathrm{DDH}$ mentioned in the report has been solved by a recent work (see [2022/1486](https://eprint.iacr.org/2022/1486)). The main technique is rougly $\mathrm{DDH}$ based correlation-intractable hash for product relations, which was only known from $\mathrm{LWE}$ before.