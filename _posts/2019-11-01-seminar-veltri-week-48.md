---
layout: post
title:  "Niccolò Veltri: Formalizing π-calculus in Guarded Cubical Agda"
date:   2019-11-25 14:00
categories: seminar
room: "Snellius 176"
---

[Niccolò Veltri](https://niccoloveltri.github.io/ "Homepage of Niccolò")
will visit us 18 - 26 November, during which we will be working on
coinductive types and extensions of dependent type theory.
He will give a short talk of about 30 minutes this day, but please feel
free to approach him at any time.

## Title: Formalizing π-calculus in Guarded Cubical Agda

Dependent type theories with guarded recursion have shown
themselves suitable for the development of denotational semantics
of programming languages. In particular Ticked Cubical Type
Theory (TCTT) has been used to show that for guarded labelled
transition systems (GLTS) interpretation into the denotational
semantics maps bisimilar processes to equal values. In fact the
two notions are proved equivalent, allowing one to reason about
equality in place of bisimilarity.
We extend that result to the π-calculus, picking early
congruence as the syntactic notion of equivalence between
processes, showing that denotational models based on guarded
recursive types can handle the dynamic creation of channels that
goes beyond the scope of GLTSs.
Hence, we present a fully abstract denotational model for the
early π-calculus, formalized as an extended example for Guarded
Cubical Agda: a novel implementation of Ticked Cubical Type
Theory based on Cubical Agda.

This is joint work with Andrea Vezzosi.
