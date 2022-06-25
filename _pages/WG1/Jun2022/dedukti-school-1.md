---
title: "1st Dedukti school"
layout: single
permalink: /dedukti-school-2022/
author_profile: true
breadcrumbs: true
---

Colocated with [TYPES 2022](https://types22.inria.fr/).

**Place:** LS2N, Université de Nantes, Faculté des Sciences et Techniques (FST), Bâtiment 34, 2 Chemin de la Houssinière, 44322 Nantes, France.

<img src="/_pages/WG1/Jun2022/group_with_frederic.jpg"/>

The Dedukti school is preceded by the [Women in EPN workshop](../women-epn-2022) from 9:00 to 13:30.

Program:

**June 24, 2022:**

- 14:30-15:45 **[Dedukti](https://deducteam.github.io/) & [Lambdapi](https://github.com/Deducteam/lambdapi)**, [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) will present the language Dedukti and the available tools for checking Dedukti files. He will also present Lambdapi, a new interactive proof assistant which can be used as an higher-level intermediate language for generating Dedukti files. [slides](frederic.pdf)

- 15:45-16:00 break

- 16:00-17:00 **How to express a theory in Dedukti?** [Gilles Dowek](http://www.lsv.fr/~dowek/) will present how simple theories, such as Predicate logic, Simple type theory, and the Calculus of constructions can be expressed in Dedukti, these expressions being the basis of the expression of more advances theories, such as the Calculus of constructions with universes and universe polymorphism, or cubical type theory can be expressed. [slides](gilles.pdf)

- 17:00-17:30 **The case of cubical type theory**, [Bruno Barras](http://www.lix.polytechnique.fr/~barras/) will describe a partial encoding of Cubical Type Theory in Dedukti. Beyond the mere interest of representing the features of that formalism, it is an example of a logic which definitional equality  may not be representable as rewrite rules. We propose a general method to deal with issue. [slides](bruno.pdf)

- 17:30-17:45 break

- 17:45-19:15 **WG 1 & 4 meeting**: [Introduction to WG4 on libraries](claudio.pdf). [Activities for November 2022 - October 2023 ?](discussion.pdf)

**June 25, 2022:**

- 9:00-10:30 **How to write a translator to Dedukti? The case of [Agda](https://github.com/Deducteam/Agda2Dedukti)**. [Jesper Cockx](https://jesper.sikanda.be/) and [Thiago Felicissimo](https://lmf.cnrs.fr/Perso/ThiagoFelicissimo) will go over the basics of how to implement a translator from a proof assistant to Dedukti. We will start with the basic principles that can be applied in general for all proof assistants, before diving into our specific example: the case of the Agda translator, [Agda2Dedukti](https://github.com/Deducteam/Agda2Dedukti). We will then look into three general features that exist in Agda as well as in other proof assistants based on type theory: inductive types with dependent pattern matching, universe polymorphism, and type-directed conversion rules for eta-equality and definitional proof irrelevance. For each of these features, we will look into different ways to encode them and their respective benefits and downsides. [slides](thiago_and_jesper.pdf)

- 10:30-10:45 break

- 10:45-11:45 **How to handle systems using automated theorem provers?** [Guillaume Burel](http://web4.ensiie.fr/~guillaume.burel/) will show how automated theorem provers (ATPs) can be used to obtain proofs for Dedukti. First, he will present how existing ATPs, namely [Zenon Modulo](https://github.com/Deducteam/zenon_modulo), [ArchSAT](https://github.com/Gbury/archsat) and [iProverModulo](https://github.com/gburel/iProverModulo), were instrumented to produce Dedukti proofs directly. Then, he will talk about systems that do not produce complete Dedukti proofs, but only traces describing coarse-grain steps like in the [TSTP format](http://www.tptp.org/TSTP/). Complete Dedukti proofs can be reconstructed from such traces, using a tool like [Ekstrakto](https://github.com/Deducteam/ekstrakto) and Dedukti-producing ATPs to fill out the missing details.

- 11:45-12:15 **Embracing predicate subtyping within Dedukti**. [Gabriel Hondet](http://www.lsv.fr/~hondet/) will present how predicate subtyping à la PVS can be encoded into Dedukti. Proof irrelevance for inhabitants of predicate subtypes of the form `{ x : A | P }` will be discussed. Finally, he will give a method to implement implicit predicate subtyping by allowing the framework to complete user-input terms through a generic coercion insertion algorithm. [slides](gabriel.pdf)

- 12:15-13:30 lunch

- 13:30-14:30 **How I Learned to Stop Trusting and Implement Dedukti Myself?** [Michael Färber](http://cl-informatik.uibk.ac.at/users/mfaerber/) You should not need to trust the Dedukti developers in order to convince yourself that a Dedukti theory is correct. Michael Färber will give an overview of how Dedukti works internally and how to re-implement relevant parts of it yourself. In particular, he will touch upon parsing, terms, sharing, rewriting, and type checking. The goal of this talk is to empower anyone to write their own checker for Dedukti.

- 14:30-15:30 **Programming language semantics in Dedukti**, [Catherine Dubois](http://web4.ensiie.fr/~dubois/) and [Amélie Ledein](https://lmf.cnrs.fr/AmelieLedein/). Most systems that are translated into Dedukti are logical systems. This lecture will deviate a little from this type of systems and address the encoding in Dedukti of 1) some programming languages features like structural object subtyping, inheritance, method redefinition and late binding; 2) semantics definitions as they are provided by the K framework.

- 15:30-15:45 break

- 15:45-16:45 **Translating proofs from one theory to another within Dedukti, and exporting a library from Dedukti**, François Thiré will present a methodology to write proof translations in Dedukti based around two tools: Dkmeta allows to use the Dedukti language as a meta-language to write term transformations that can be easily maintained; [Universo](https://github.com/Deducteam/universo) allows to rewrite universes in a term, in particular, to map universes from one logic to another (when it is possible).

**Registration:** on the [TYPES 2022 website](https://types22.inria.fr/)

**Funding applications:** [here](../funding-June-2022) (deadline: May 22)

**Scientific organizers:** [Gilles Dowek](http://lsv.fr/~dowek/), [Jesper Cockx](https://jesper.sikanda.be/), [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Local organizers:** Matthieu Sozeau and Nicolas Tabareau

<img src="/_pages/WG1/Jun2022/amphi1.jpg"/>

<img src="/_pages/WG1/Jun2022/gilles2.jpg"/>

<img src="/_pages/WG1/Jun2022/thiago.jpg"/>

<img src="/_pages/WG1/Jun2022/guillaume.jpg"/>

<img src="/_pages/WG1/Jun2022/michael.jpg"/>

<img src="/_pages/WG1/Jun2022/catherine.jpg"/>
