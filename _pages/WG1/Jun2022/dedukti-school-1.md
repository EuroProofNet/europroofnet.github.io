---
title: "1st Dedukti school"
layout: single
permalink: /dedukti-school-2022/
author_profile: true
breadcrumbs: true
---

Colocated with [TYPES 2022](https://types22.inria.fr/).

**Place:** LS2N, Université de Nantes, Faculté des Sciences et Techniques (FST), Bâtiment 34, 2 Chemin de la Houssinière, 44322 Nantes, France.

The Dedukti school is preceded by the [Women in EPN workshop](../women-epn-2022) from 9:00 to 13:30.

Program:

**June 24, 2022:**

- 14:30-15:30 [Dedukti](https://deducteam.github.io/) & [Lambdapi](https://github.com/Deducteam/lambdapi), [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) will present the language Dedukti and the available tools for checking Dedukti files. He will also present Lambdapi, a new interactive proof assistant which can be used as an higher-level intermediate language for generating Dedukti files.

- 15:30-15:45 break

- 15:45-16:45 How to express a theory in Dedukti? [Gilles Dowek](http://www.lsv.fr/~dowek/) will present how simple theories, such as Predicate logic, Simple type theory, and the Calculus of constructions can be expressed in Dedukti, these expressions being the basis of the expression of more advances theories, such as the Calculus of constructions with universes and universe polymorphism, or cubical type theory can be expressed.

- 16:45-17:15 The case of cubical type theory, [Bruno Barras](http://www.lix.polytechnique.fr/~barras/)

- 17:30-19:00 WG 1 & 4 meeting

- 20:00 dinner

**June 25, 2022:**

- 9:00-10:30 How to write a translator to Dedukti? The case of [Agda](https://github.com/Deducteam/Agda2Dedukti). [Jesper Cockx](https://jesper.sikanda.be/) and [Thiago Felicissimo](https://lmf.cnrs.fr/Perso/ThiagoFelicissimo) will go over the basics of how to implement a translator from a proof assistant to Dedukti. We will start with the basic principles that can be applied in general for all proof assistants, before diving into our specific example: the case of the Agda translator, [Agda2Dedukti](https://github.com/Deducteam/Agda2Dedukti). We will then look into three general features that exist in Agda as well as in other proof assistants based on type theory: inductive types with dependent pattern matching, universe polymorphism, and type-directed conversion rules for eta-equality and definitional proof irrelevance. For each of these features, we will look into different ways to encode them and their respective benefits and downsides.


- 10:30-10:45 break

- 10:45-11:45 How to handle systems using automated theorem provers? [Guillaume Burel](http://web4.ensiie.fr/~guillaume.burel/) will show how automated theorem provers (ATPs) can be used to obtain proofs for Dedukti. First, he will present how existing ATPs, namely [Zenon Modulo](https://github.com/Deducteam/zenon_modulo), [ArchSAT](https://github.com/Gbury/archsat) and [iProverModulo](https://github.com/gburel/iProverModulo), were instrumented to produce Dedukti proofs directly. Then, he will talk about systems that do not produce complete Dedukti proofs, but only traces describing coarse-grain steps like in the [TSTP format](http://www.tptp.org/TSTP/). Complete Dedukti proofs can be reconstructed from such traces, using a tool like [Ekstrakto](https://github.com/Deducteam/ekstrakto) and Dedukti-producing ATPs to fill out the missing details. 

- 11:45-12:15 Predicate subtyping with proof irrelevance, [Gabriel Hondet](http://www.lsv.fr/~hondet/) will present an approach to push further the automation
provided by Lambdapi to generate Dedukti specifications. In particular,
we will see how user-input terms can be completed by the framework so
that they are well typed. We will then consider this method to implement
implicit predicate subtyping à la PVS in the framework.

- 13:30-14:30 Libraries, the case of Isabelle, [Michael Färber](http://cl-informatik.uibk.ac.at/users/mfaerber/)

- 14:30-15:30 Programming language semantics in Dedukti, [Catherine Dubois](http://web4.ensiie.fr/~dubois/) and [Amélie Ledein](http://www.lsv.fr/~ledein/). Most systems that are translated into Dedukti are logical systems. This lecture will deviate a little from this type of systems and address the encoding in Dedukti of 1) some programming languages features like structural object subtyping, inheritance, method redefinition and late binding; 2) semantics definitions as they are provided by the K framework.

- 15:30-15:45

- 15:45-16:45 Translating proofs from one theory to another within Dedukti, and exporting a library from Dedukti, François Thiré will present a methodology to write proof translations in Dedukti based around two tools: Dkmeta allows to use the Dedukti language as a meta-language to write term transformations that can be easily maintained; [Universo](https://github.com/Deducteam/universo) allows to rewrite universes in a term, in particular, to map universes from one logic to another (when it is possible).

**Registration:** on [TYPES 2022](https://types22.inria.fr/)

**Funding application deadline: May 22.**
EuroProofNet can fund the travel to Nantes and the accommodation for
June 24-25 of about 40 participants with a daily allowance fixed at
120 euros. If you want to attend the Dedukti school and be reimbursed,
you need to provide an estimation of your travel cost to
**frederic.blanqui(a)inria.fr**. The action members who
will be reimbursed will be chosen by taking into account the following
criteria in order: importance wrt the research coordination
objectives; inclusive target countries; age; gender; team with low
resources; balance over the action life time between people, teams,
countries and working groups.

**Organizers:** [Gilles Dowek](http://lsv.fr/~dowek/), [Jesper Cockx](https://jesper.sikanda.be/), [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)
