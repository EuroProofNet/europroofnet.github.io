---
title: "EuroProofNet Workshop on the development, maintenance, refactoring and search of large libraries of proofs"
layout: single
permalink: /wg4-meeting1-program/
author_profile: true
breadcrumbs: true
---

**Warning:** Time in Tbilisi (UTC+4)

## Friday 23 September

- 12:30 CLAS lunch time

- 14:00 [Claudio Sacerdoti](http://www.cs.unibo.it/~sacerdot/) (Universty of Bologna), The challenges of the EuroProofNet Working Group 4 on proof libraries <!--30'-->

- 14:30 Georges Gonthier (INRIA Saclay) [online], TBA <!--Friday only-->

- 15:00 [Enrico Tassi](http://www-sop.inria.fr/members/Enrico.Tassi/) (INRIA Sophia Antipolis), [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder), algebraic hierarchies made easy (in Coq) [online] <!--30'--> <!--Friday only-->

It is nowadays customary to organize libraries of machine checked
proofs around hierarchies of algebraic structures. One influential
example is the Mathematical Components library on top of which the long
and intricate proof of the Odd Order Theorem could be fully formalized.
Still, building algebraic hierarchies in a proof assistant such as Coq
requires a lot of manual labor and often a deep expertise in the
internals of the prover. Moreover, according to our experience, making
a hierarchy evolve without causing breakage in client code is equally
tricky: even a simple refactoring such as splitting a structure into
two simpler ones is hard to get right.
In this talk we describe HB, a high level language to build hierarchies
of algebraic structures and to make these hierarchies evolve without
breaking user code. The key concepts are the ones of factory, builder
and abbreviation that let the hierarchy developer describe an actual
interface for their library. Behind that interface the developer can
provide appropriate code to ensure retro compatibility.
We make a demo the HB language using the hierarchy-builder addon for
the Coq system.

- 15:30 CLAS coffee break

- 16:00 [Geoff Sutcliffe](https://www.cs.miami.edu/home/geoff/) (University of Miami), The TDTP library - Tons of Data for Theorem Provers [online] <!--30'--> <!--Friday after 14:00-->

- 16:30 [Marco Maggesi](https://sites.google.com/unifi.it/maggesi/), The HOL Light library of formalized mathematics

- 17:00 Roland Coghetto and [Julien Narboux](https://dpt-info.di.unistra.fr/~narboux/) (University of Strasbourg) [online], The GeoCoq library and its porting to Isabelle

GeoCoq is a formal proof library consisting in a formalization of foundations of geometry. It is based on several different axiom systems by Euclid, Hilbert and Tarski, and includes the arithmetization of geometry, i.e. the link between synthetic and analytic geometry. 
After giving a quick overview of the library, we will discuss how automation and logical foundations are used in each part of the library and the potential impact on porting the library to other proof assistants. Then, we will report on the porting of the library to Isabelle/HOL by Roland Coghetto.

- 17:30 [Florian Rabe](https://kwarc.info/people/frabe/) <!--and [Michael Kohlhase](https://kwarc.info/people/mkohlhase/)--> (University of Erlangen), Experiences from Exporting Major Proof Assistant Libraries <!--(online?)--> <!--30-60'-->

The interoperability of proof assistants and the integration of their libraries is a highly valued but elusive goal in the field of theorem proving.
As a preparatory step, in previous work, we translated the libraries of multiple proof assistants, specifically the ones of Coq, HOL Light, IMPS, Isabelle, Mizar, and
PVS into a universal format: OMDoc/MMT.
Each translation presented great theoretical, technical, and social challenges, some universal and some system-specific, some solvable and some still open.
In this talk, we survey these challenges and compare and evaluate the solutions we chose.
We believe similar library translations will be an essential part of any future system interoperability solution and our experiences will prove valuable to others undertaking such efforts.

- 18:00 end

- 19:00 dinner together in some restaurant for those who want (suggestions are welcome)

## Saturday 24 September

- 09:00 CLAS invited speaker slot (TBA)

- 10:00 [Fabian Huch](https://www21.in.tum.de/team/huch/) (Technical University of Münich), Finding facts in large formalization libraries: two Isabelle/AFP attempts <!--30'-->

- 10:30 CLAS coffee break

- 11:00 [Yiannis Stathopoulos](https://www.cl.cam.ac.uk/~yas23/) (University of Cambridge), TBA

- 11:30 [Artur Korniłowicz](http://math.uwb.edu.pl/~arturk/) (University of Bialystok), XML-based representation of Mizar Mathematical Library [online] <!--60'-120'-->

The Mizar Mathematical Library is a collection of mathematical papers written in the Mizar language and fully computer-verified by the Mizar proof checker.
From many years the Mizar Mathematical Library is a subject of translation into other systems for its cross-verification or representing its content in various formats.
To facilitate this task several internal XML-based formats have been designed to be processable by generic tools independent from the Mizar system.
These formats represent various syntactic-semantic information accessible at various stages of proof verification by the Mizar checker.
In this talk we present constructions of the Mizar language and describe how they are represented in the XML formats.
We also present the content of the Mizar Mathematical Library with a focus on its initial articles and discuss the management model of the library.

- 12:30 CLAS lunch time

- 14:00 [Anne Baanen](https://www.cs.vu.nl/~tbn305/) (Vrije Universiteit Amsterdam), Bundling in Dependent Type Theory <!--45'-60'-->

Dependent type theories allow us to bundle proofs and data in the same structure, which can be a great help for automation. On the other hand, unbundled definitions can allow greater flexibility. I discuss my experiences with refactoring between unbundled and bundled definitions in the Lean mathematical library mathlib, especially focusing on the implementation of typeclasses.

- 14:45 [Alexander Best](https://alexjbest.github.io/) (Vrije Universiteit Amsterdam), Metaprogramming for Automation of Library Maintenance <!--30'-45'-->

Large libraries of formal proofs are becoming increasingly common, and
pose several challenges for the maintenance and upkeep if they are to
be widely useful and remain so.
Specific issues for maintenance include problems such as: ensuring
content is not duplicated, it is organised appropriately, it is
sufficiently general to be useful in other developments, or that a
large library is coherent so different parts can be used together.
Ensuring these properties hold is mostly done by human review, which
while always a useful component can be a limiting factor of
maintenance.
We describe several specific problems that can be addressed with
automated tooling, and give some case studies showing how automation
can help humans review things they may not have the time to look into,
and also help us spot difficult to notice issues.

- 15:30 CLAS coffee break

- 16:00 [Riccardo Brasca](https://webusers.imj-prg.fr/~riccardo.brasca/) (University of Paris Cité), Maintenance of Lean's mathlib and the Liquid tensor experiment <!--30'-60'-->

- 17:00 [Reuben Rowe](https://www.cs.rhul.ac.uk/home/rrowe/) <!--30'-60'--> (Royal Halloway University of London), Refactoring OCaml

- 17:30 [André Freitas](http://andrefreitas.org/) (University of Manchester), Natural Language & Proofs: A Neuro-symbolic Perspective <!--30'-40'-->

This talk provides an overview of emerging methods and representation paradigms in Natural Language Processing (NLP) to support the interpretation of proofs. We will aim for a synthesis of the increasing dialogue between the neural perspective (e.g. large-scale neural language models) and symbolic inference, looking into specific architectural devices which are used to integrate the properties of both types of representation. We will finalize with an argument of how these methods can support the core aims of EuroProofNet: to improve the interoperability and usability of proof systems.

- 18:10 end

- 19:00 dinner together in some restaurant for those who want (suggestions are welcome)
