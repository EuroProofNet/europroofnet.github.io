---
title: "LFPSI'25 lecture: Second-Order Generalized Algebraic Theories"
layout: single
permalink: /LFPSI25-Ambrus/
author_profile: true
breadcrumbs: true
---

In the [International School on Logical Frameworks and Proof Systems Interoperability](../LFPSI25).

<img src="/_pages/schools/LFPSI25/ambrus.jpg"/>

**Lecturer:** [Ambrus Kaposi](https://akaposi.github.io/)

In this lecture series, we will study non-substructural programming
languages at a very high level of abstraction: a language is a
second-order generalised algebraic theory (SOGAT). The syntax of such
a language is its initial model, in which there are only well-typed
(intrinsic) terms quotiented by conversion, every operation is
automatically a congruence with respect to conversion and every
operation is stable under substitution. Planned schedule:

  1. Derivability and admissibility in GATs. We look at the following
  binder-free languages: monoids, pointed set with endofunction, a
  typed expression language, simply typed combinator calculus. For
  each language, we review the following notions: model, derivability,
  morphism, dependent model, dependent morphism, syntax, induction,
  admissibility, normal forms, normalisation.

  2. Derivability in SOGATs. We look at the following languages with
  binders: simply typed lambda calculus, PCF, first-order logic,
  System F, the lambda cube, Martin-Löf type theory, the language of
  SOGAT signatures. For each language, we look at derivable operations
  (programs) and equations (running programs).

  3. Converting SOGATs into GATs. Through examples, we learn how to
  make a language with binders first-order.

  4. Admissibility in SOGATs. We show how to prove properties about
  closed syntactic terms (easy), an example is canonicity for
  Martin-Löf type theory. We illustrate proofs about open syntactic
  terms (involves understanding presheaf internal languages), an
  example is normalisation for Martin-Löf type theory.

Related ideas are higher-order abstract syntax, logical frameworks,
two-level type theories, synthethic Tait computability. We will rely on
being able to work informally in type theory (informal
Agda/Coq/Idris/Lean). The first three lectures won't use any category
theory, the last lecture will introduce presheaf models of type theory
gently. We plan to have exercise sessions as well. We will rely directly
on two papers, but we won't assume the knowledge of these from the
participants:
  - Ambrus Kaposi, Szumi Xie: [Second-Order Generalised Algebraic Theories:
    Signatures and First-Order Semantics](https://doi.org/10.4230/LIPIcs.FSCD.2024.10). FSCD 2024:10:1-10:24.
  - Rafaël Bocquet, Ambrus Kaposi, Christian Sattler: [For the Metatheory of
    Type Theory, Internal Sconing Is Enough](https://doi.org/10.4230/LIPIcs.FSCD.2023.18). FSCD 2023:18:1-18:23.

[Course notes (under construction)](https://akaposi.github.io/sogat-paris.pdf).
