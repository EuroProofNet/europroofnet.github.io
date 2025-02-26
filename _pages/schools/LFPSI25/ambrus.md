---
title: "LFPSI'25 lecture: Second-Order Generalized Algebraic Theories"
layout: single
permalink: /LFPSI25-Ambrus/
author_profile: true
breadcrumbs: true
---

In the [International School on Logical Frameworks and Proof Systems Interoperability](../LFPSI25).

<img src="/_pages/school/LFSPI25/ambrus.jpg"/>

**Lecturer:** [Ambrus Kaposi](https://akaposi.github.io/)

In this lecture series, we will study non-substructural programming
languages at a very high level of abstraction: a language is a
second-order generalised algebraic theory (SOGAT). The syntax of such
a language is its initial model, in which there are only well-typed
(intrinsic) terms quotiented by conversion, every operation is
automatically a congruence with respect to conversion and every
operation is stable under substitution. Planned schedule:

  1. Examples of languages as SOGATs and programming in a language. We
  will cover some of the following: Simply typed lambda calculus, PCF,
  first-order logic, System F, the lambda cube, call by value lambda
  calculus, Martin-Löf type theory, the language of SOGAT signatures.
  2. What is a model of a SOGAT? Translation from SOGATs to GATs through
  examples. Notion of syntax.
  3. Proofs about closed syntactic terms (such as canonicity) staying at
  the SOGAT level of abstraction.
  4. Proofs about open syntactic terms (such as normalisation) staying
  at the SOGAT level of abstraction.

Related ideas are higher-order abstract syntax, logical frameworks,
two-level type theories, synthethic Tait computability. We will rely on
being able to work informally in type theory (informal
Agda/Coq/Idris/Lean). The first two lectures won't use any category
theory, the third lecture will introduce presheaf models of type theory
gently. We plan to have exercise sessions as well. We will rely directly
on two papers, but we won't assume the knowledge of these from the
participants:
  - Ambrus Kaposi, Szumi Xie: [Second-Order Generalised Algebraic Theories:
    Signatures and First-Order Semantics](https://doi.org/10.4230/LIPIcs.FSCD.2024.10). FSCD 2024:10:1-10:24.
  - Rafaël Bocquet, Ambrus Kaposi, Christian Sattler: [For the Metatheory of
    Type Theory, Internal Sconing Is Enough](https://doi.org/10.4230/LIPIcs.FSCD.2023.18). FSCD 2023:18:1-18:23.
