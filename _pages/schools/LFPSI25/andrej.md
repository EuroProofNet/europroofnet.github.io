---
title: "LFPSI'25 lecture: Programming language techniques for proof assistants"
layout: single
permalink: /LFPSI25-Andrej/
author_profile: true
breadcrumbs: true
---

In the [International School on Logical Frameworks and Proof Systems Interoperability](../LFPSI25).

<img src="/_pages/schools/LFPSI25/andrej.jpg" style="width: 35%;"/>

**Lecturer:** [Andrej Bauer](https://www.andrej.com/)

To someone wielding the hammer of programming language design, a proof assistant can look very much like a nail: it parses source code, processes it through an elaborator, and validates it with a type-checking procedure.
In fact, several mainstream proof assistants advertise themselves as programming languages.
However, a proof assistant is a peculiar kind of programming language — one that supports interactive development and automation through meta-level techniques such as tactics, type-class mechanisms, coercions, meta-variables, unification, and more. Can these, too, be shaped by the same hammer?

In this lecture series, we will design a simple proof assistant using programming language techniques. We will start with a basic type checker, progressively extend its capabilities, and then apply algebraic effects and handlers to give a unifying picture of these mechanisms. Finally, we will explore how algebraic effects and handlers enable further development.

Lecture 1 – The anatomy of a proof assistant
: We review the implementation of a rudimentary type checker for a dependent type theory, based on bidirectional type checking and type-directed equality checking.

Lecture 2 – Implicit arguments, meta-variables and unification
: We extend the rudimentary type checker with implicit arguments, requiring meta-variables and unification.

Lecture 3 – Algebraic effects and handlers
: After reviewing the basics of algebraic effects and handlers, we redesign our proof assistant and re-implement implicit arguments, meta-variables, and unification as computational effects.

Lecture 4 – Effects in proof assistants
: We further explore the possibilities of algebraic effects. Implicit coercions, tactics, and type classes can be expressed as effects, allowing the type-checking core to interact safely with user code.
