---
layout: post
title:  "Seminar by Henning Basold: Modelling Coinductive and Higher-Order Stochastic Systems"
date:   2019-09-09 14:00:00 +0200
categories: seminar
---

Modelling Coinductive and Higher-Order Stochastic Systems
=======================================================

In stochastic modelling, as it appears in artificial intelligence,
biology or physics, one often encounters the question of how to
model a probabilistic process that may run indefinitely. Such processes
have been described in non-probabilistic programming successfully by
using coinductive types and coiteration. Vákár et al. recently
introduced semantics for a higher-order probabilistic programming
language with full recursion in types and programs based quasi-Borel
spaces. Full recursion allows the introduction of coinductive types,
but this comes at the price of losing termination and productivity.

In this seminar, I would like to briefly show a language for stochastic
modelling of processes that run potentially indefinitely, like random
walks, and for distributions that arise from indefinite runs, like
geometric distributions. Such processes and distributions will be
described as so-called coinductive types and programmed via so-called
guarded recursion, which will make sure that the programs describing
random walks etc. are terminating. This eases reasoning about such
processes, while the recursion offered by the language is still
convenient to use. At the end, we will discuss open questions
concerning the presented programming language.

The language appeared in the paper
[Coinduction in Flow — The Later Modality in Fibrations](https://liacs.leidenuniv.nl/~basoldh/publications/2019/coinduction-in-flow.html)
that I presented at CALCO this year.
