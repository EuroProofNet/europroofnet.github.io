---
title: "LFPSI'25 lecture: λΠ-calculus modulo rewriting: theory and application to proof systems interoperability"
layout: single
permalink: /LFPSI25-Frédéric/
author_profile: true
breadcrumbs: true
---

In the [International School on Logical Frameworks and Proof Systems Interoperability](../LFPSI25).

<img src="https://blanqui.gitlabpages.inria.fr/img/photo.jpg">

**Lecturer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

In this course, we are going to see how dependent types and rewriting rules (aka oriented equations) can be used to represent the proofs of various logical systems, so as to facilitate their exchange between provers. In a practical session, we will learn how to use the interactive logical framework [Lambdapi](https://github.com/Deducteam/lambdapi), which implements the λΠ-calculus modulo rewriting. Finally, we will see how to try to automatically check some important properties of the rewrite systems one can define in Lambdapi.

**Outline:**

1. Introduction to proof systems interoperability, λ-calculus and
   dependent types. [[slides](https://files.inria.fr/blanqui/lfpsi25/1.pdf)]

    (To prepare the practical session tomorrow, please install [Lambdapi](https://github.com/Deducteam/lambdapi) on your machine.)

2. Introduction to pure type systems, rewriting, λΠ/R and the Lambdapi proof assistant. Practical session on Lambdapi.

3. Encoding logics in λΠ/R: first-order logic, polymorphism, higher-order logic, pure type systems, …

4. Properties of λΠ/R: decidability of type-checking, subject-reduction, confluence, termination, dependencies between these properties.
