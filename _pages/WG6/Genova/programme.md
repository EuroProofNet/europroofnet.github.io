---
title: "WG6 meeting in Genoa in April 2025"
layout: single
permalink: /wg6-genoa/programme/
author_profile: true
breadcrumbs: true
---

### Programme

TBA



### Invited talks


###### Francesco Gavazzo: A Mathematical Theory of Term Relations {#fgavazzo}

Syntactic methods play a central role in many fields of Logic and Theoretical Computer Science, including type theory, programming language semantics, proof theory and its computational interpretations, algebra, and rewriting systems. These methods characterise various behaviours resting solely on syntax, thereby avoiding the (notoriously difficult) introduction of `extra-linguistic' semantic objects such as term meanings. Unfortunately, their inherent syntax-dependence prevents syntactic methods to scale from a collection of application-specific methodologies to a an abstract mathematical theory readily  applicable across diverse logical and computational formalisms: how frequently must critical properties—such as confluence, termination, type safety, cut-elimination, congruence, and compositionality—be proven anew?

A recurring concept within syntactic methodologies is that of a \emph{term relation}, a relation, broadly intended, between syntactic terms (programs, proofs, types, agents, formulas, etc.): examples of term relations include rewriting and conversion, program equivalences and metrics, bisimulation, logical relations, and type elaboration. However, despite their pervasiveness, term relations have rarely been studied systematically, and never as an abstract and (language-)independent mathematical object.

In this talk, we present the foundations for a general mathematical theory of term relations. We begin by illustrating how term relations emerge naturally as a relational counterpart to the categorical theory of syntax interpretation, as exemplified by the initial algebra semantics paradigm. We then explore the algebraic structure inherent in the space of term relations, revealing how this structure underpins a synthetic theory that abstracts away from specific  syntax structures. Accordingly, we axiomatically define term relations through suitable extensions of relation algebras, dubbed \emph{Term Relation Algebras} (TRAs).

Remarkably, TRAs allow numerous operational and syntactic properties to be proven abstractly, independent of specific languages or syntactic notions, transforming typically cumbersome and error-prone syntactic proofs into concise algebraic calculations. Among those results, we will mention confluence theorems (e.g. Tait and Martin-Löf confluence techniques), theories of program dynamics, and congruence results for various notions of program equivalence (e.g. applicative bisimilarity).

###### András Kovács: A generalized logical framework {#akovacs}

Logical frameworks and the closely related two-level type theories let us work in a mixed syntax of a metatheory and a chosen object theory. Here, we have a second-order view on the object theory, where contexts, variables and substitutions are implicit, and binders are represented as meta-level functions. We generalize this to a setup where we can work with multiple models of multiple object theories at the same time, and we can also switch between "external" first-order views and "internal" second-order views of the same model. An important feature of the framework is that it's fully structural as a type theory; in particular it does not have any modalities. The main semantic idea is to have a universe hierarchy of "iterated internal presheaves". In the empty context, we have PSh 1 as the universe of presheaves over 1, i.e. sets. Internally to PSh 1, we can define a category C, from which we can obtain a universe of presheaves over C. In this universe, we can define another category D and get a universe of internal presheaves over D, and so on.

###### Thomas Lamiaux: A unified Framework for Initial Semantics, and it is 2 functorial {#tlamiaux}

We focus on the initial semantics aiming to model the syntax and substitution structure of programming languages with variable binding as initial objects. Three distinct yet similar approaches to initial semantics have been proposed. An initial semantics result was first proved by Fiore, Plotkin, and Turi using {\Sigma}-monoids in their seminal paper published at LICS'99. Alternative frameworks were later introduced by Hirschowitz and Maggesi using modules over monads, and by Matthes and Uustalu using heterogeneous substitution systems. Since then, all approaches have been significantly developed by numerous researchers. While similar, the links between this different approaches remain unclear. This is especially the case as the literature is difficult to access, since it was mostly published in (short) conference papers without proofs, and contains many technical variations and evolutions.
In [A Unified Framework for Initial Semantics](https://urlsand.esvalabs.com/?u=https%3A%2F%2Farxiv.org%2Fabs%2F2502.10811&e=ed7a584b&h=456504aa&f=y&p=y), we introduce a framework based on monoidal categories that unifies these three distinct approaches to initial semantics, by suitably generalizing and combining them. Doing so we show that modules over monoids provide an abstract and easy to manipulate framework, that {\Sigma}-monoids and strengths naturally arise when stating and proving an initiality theorem, and that heterogeneous substitution systems enable us to prove the initiality theorem modularly. Moreover, to clarify the literature, we provide an extensive related work.
In this talk, we will give an account of this work, introducing the different concepts with examples and explaining how they assemble. Doing so, we hope to make it more accessible to newcommers to the field. If times permits, we will also discussed more recent work where we show that models can be computed by a 2-functor, and how it can be used to further relate different instantiations and design generalized recursion principles for typed languages.

###### Paige Randall North: Comparing semantic frameworks for dependently-sorted algebraic theories {#prnorth}

Algebraic theories with dependency between sorts form the structural core of Martin-Löf type theory and similar systems. Their denotational semantics are typically studied using categorical structures such as contextual categories, categories with families, display map categories, comprehension categories, and many others. While comparisons between specific models appear in the literature, a unified analysis of this zoo of categorical structures has been lacking.

In this talk, I will describe our work in which we aim to give a clear 2-categorical analysis of this zoo. We use comprehension categories as a unifying language. We show that almost all established notions embed as sub-2-categories (usually full) of the 2-category of comprehension categories. The frameworks naturally divide into two groups: those representing types as certain (display) maps, and those treating types as primitive. We give 2-functors between all notions and describe when they are adjunctions and when they are equivalences. The analyses that we give are often well-known or folklore, or only discussed in the literature at a 1-categorical level (which we see as inadequate for certain purposes). This work aims to give a clear reference point for the organization of this zoo of categorical structures.

This is joint work with Benedikt Ahrens and Peter LeFanu Lumsdaine.

### Contributed talks

TBA
