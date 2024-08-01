---
title: "EuroProofNet meeting on proof libraries"
layout: single
permalink: /wg4-tbilisi24/
author_profile: true
breadcrumbs: true
---

**Date:** 13-14 September 2024

**Venue:** [Tbilisi State University, Chavchavadze ave. 1, 0179 Tbilisi, Georgia](https://www.viam.science.tsu.ge/itp2024/venue)

This meeting includes several sessions shared with other co-located events. Registration to these other events is mandatory (see the ITP web page for this).

**September 13:**

- **[15th Conference on Interactive Theorem Proving](https://www.viam.science.tsu.ge/itp2024/)** (ITP'24)

  |time|title, authors|
  |--|--|  
  |09:00|Invited talk: Translating libraries of definitions and theorems between proof systems, Frédéric Blanqui|
  |10:00|Graphical rewriting for diagrammatic reasoning in monoidal categories in Lean4, Sam Ezeh|
  |10:15|Formalising Half of a Graduate Textbook on Number Theory, Manuel Eberl, Anthony Bordg, Lawrence Paulson and Wenda Li|
  |10:30|break|
  |11:00|An Isabelle/HOL formalization of narrowing and multiset narrowing for E-unifiability,  reachability and infeasibility, Dohan Kim|
  |11:30|A Modular Formalization of Superposition in Isabelle/HOL, Martin Desharnais, Balazs Toth, Uwe Waldmann, Jasmin Blanchette and Sophie Tourret|
  |12:00|A Proof-Producing Superposition Theorem Prover for Dependent Type Theory, Joshua Clune, Yicheng Qian, Alexander Bentkamp and Jeremy Avigad|
  |12:30|lunch|
  |14:00|Mechanized HOL Reasoning in Set Theory, Simon Guilloud, Sankalp Gambhir, Andrea Gilot and Viktor Kuncak|
  |14:30|End-to-End Formal Verification of a Fast and Accurate Floating-Point Approximation, Florian Faissole, Paul Geneau de Lamarlière and Guillaume Melquiond|
  |15:00|Distributed Parallel Build for the Isabelle Archive of Formal Proofs, Fabian Huch and Makarius Wenzel|
  |15:30|break|

- **2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs**

  |time|title, authors|
  |--|--|  
  |16:00|Exploring the benefits of a general abstract formalization, Thaynara Arielly de Lima|
  |16:30|Post-processing Coq Proof Scripts to Make Them More Robust, Titouan Lozac’h and Nicolas Magaud|
  |17:00|Verifying Nominal Equational Reasoning Modulo Algorithms, Mauricio Ayala-Rincón|
  |17:30|An Indexer and Query Language for Libraries written in LambdaPi/Dedukti, Claudio Sacerdoti Coen|

<!--Post-processing Coq Proof Scripts to Make Them More Robust, Titouan Lozac’h and Nicolas Magaud: Proof assistants like Coq are increasingly popular to help mathematicians carry out proofs of the results they conjecture. However, formal proofs remain highly technical and are especially difficult to reuse. In this paper, we present a framework to carry out a posteriori script transformations. These transformations are meant to be applied as an automated post-processing step, once the proof has been completed. We implemented two transformations so far:  the first one takes an arbitrary large proof script and produces an equivalent single-line proof script, which can be executed by Coq in one single step. 
The second example implements the converse operation, fully expanding a proof script into atomic proof steps. Other applications can be envisioned : removing all named hypotheses, increasing automation, removing some pre-defined proof patterns, etc. We apply our tool to various Coq proof scripts, including rather large ones from the GeoCoq library.-->

<!--Verifying Nominal Equational Reasoning Modulo Algorithms, Mauricio Ayala-Rincón: The PVS library on nominal equational reasoning includes
formalizations of syntactic unification and the formalization of the
long-standing Stikel(-Fages) AC-unification algorithm. Our research on
nominal equational reasoning has uncovered significant disparities
compared to the first-order unification approach. Specifically, it has
highlighted differences in the unification type of nominal unification
modulo regarding first-order standard unification. The talk will
deeply delve into the mechanization of various unification algorithms
in the PVS nominal library, focusing on nominal equality-check,
matching, and unification modulo associativity and commutativity, in
order to emphasize the observed differences, address pertinent
questions, and present the current progress on the mechanization of
anti-unification modulo algorithms.-->

<!--Exploring the benefits of a general abstract formalization, Thaynara Arielly de Lima: One of the main challenges in formal methods is the reuse of formal
proofs in several contexts.  With this in mind, the recent PVS
developments regarding abstract algebra have been mechanized as
generally as possible, allowing their application to different
algebraic structures. For example, recently, a Euclidean gcd algorithm
for Euclidean domains was specified in PVS and its correctness was
formalized. Thus verifying that the rings of integers and the Gaussian
integers are Euclidean domains provides a straightforward manner to
infer the correctness of this algorithm for both structures.  Another
example concerns quaternions. It is well known that Hamilton's
quaternions mimic any 3D rotation.  However, specifying quaternion
structures using any arbitrary field as a parameter allows not only
the verification of the completeness of three-dimensional rotations
but also a simple specification of Hurwitz quaternions, which can be
used to give an alternative proof of the well-known Lagrange's
four-square theorem.  This talk will discuss the main recent
developments of the PVS theory algebra, highlighting the benefits of
its general abstract discipline of formalization by exploring as a
case study the use of Hurwitz Rings, the First Isomorphism Theorem for
rings and the characterization of algebraic properties that lead to
constructing quaternions as division rings to establish Lagrange's
four-square theorem.-->

<!--An Indexer and Query Language for Libraries written in
LambdaPi/Dedukti, Claudio Sacerdoti Coen: The libraries exported from
various mathematical tools to Dedukti/LambdaPi poses peculiar
challenges to indexing and retrieval. In particular the libraries are
heterogeneous because "the same" statements and definitions can be
encoded in different ways according to the encoding of the logic they
are written in. Moreover the same statement can appear in various
forms because of user defined rewriting rules. We will present an
indexing tool and query language integrated in LambdaPi that addresses
the previous challenges and also allows limited search up-to
alignments. -->

**September 14:**

  - session with the [Coq workshop](https://coq-workshop.gitlab.io/2024/)
  
  |time|title, authors|
  |--|--|  
  |9:40|On the Potential of Coq as the Platform of Choice for Hardware Design, Sebastian Ertel, Max Kurze and Michael Raitza|
  |10:00|A Development Process for Coq Projects Permitting Invalid Proofs, Hendrik Tews|
  |10:30|break|
  |11:00|CoqPilot, a plugin for LLM-based generation of proofs, Andrei Kozyrev, Gleb Solovev, Nikita Khramov and Anton Podkopaev|
  |11:30|Blueprints for formalisation in Coq, Peter Lefanu Lumsdaine|
  |11:50|Coq Platform docs: A Compilation of Short Interactive Tutorials and How-To Guides for Coq, Thomas Lamiaux, Pierre Rousselin and Théo Zimmermann|
  |12:20|lunch|
  |14:00|Shared invited talk TBA|
  |15:00|Lessons from Formalizing (Higher) Category Theory, Benedikt Ahrens and Niels van der Weide|
  |15:30|break|
  |16:00|Towards Formalising the Guard Condition of Coq, Yee Jian Tan and Yannick Forster|
  |16:25|Turning the Coq Proof Assistant into a Pocket Calculator, Guillaume Melquiond|
  |16:45|Discussion with Coq developers|
  |18:00|end|

  - session with the [Isabelle workshop](https://sketis.net/isabelle/isabelle-workshop-2024)

<!--
  |time|title, authors|
  |--|--|
  |09:00||
  |09:30||
  |10:00||
  |10:30|break|
  |11:00||
  |11:30||
  |12:00||
  |12:30|lunch|
  |14:00||
  |14:30||
  |15:00||
  |15:30|break|
  |16:00||
  |16:30||
  |17:00||
-->

**Call for talk proposals:** If you are interested in giving a talk at
the 2nd Workshop on the development, maintenance, refactoring and
search of large libraries of proofs, send a mail to [Frédéric
Blanqui](https://blanqui.gitlabpages.inria.fr/) with a title and short
abstract. We welcome talks, tutorials, demos, on library descriptions
or on methodologies, algorithms and tools trying to tackle the
challenges raised by the development, maintenance, refactoring and
search of large libraries of proofs.

**Registration:** Registration to the 2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs is free but mandatory. To attend the workshop, please send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/).

**Funding application:** If you are attending the Isabelle workshop, the Coq workshop, the ITP conference or the 2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs, and want to be reimbursed of your transport to Tbilisi, and of your accommodation and meals between September 12 and September 15, following the COST [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/), with a daily allowance of 80 euros, you need to:
- check your [eligibility](https://europroofnet.github.io/eligibility)
- [register](https://e-services.cost.eu/action/CA20111/working-groups/apply) to at least one EuroProofNet working group
- send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with the following information: departure date from home, return date at home, and estimation in EUROS of the transport to Tbilisi with a screen capture

**Funded participants (13):** Abdelghani Alidra, Claudio Sacerdoti Coen, Clement Pit-Claudel, Ján Perháč, Luca Pasetto, Mauricio Ayala-Rincon, Max Zeuner, Muhammad Usama Sardar, Natalia Slusarz, Nicolas Magaud, Simon Guilloud, Thaynara Arielly de Lima, Théo Winterhalter

<!--Priority will be given to people giving a talk, people living in inclusive target countries (Albania, Armenia, Bosnia and Herzegovina, Bulgaria, Croatia, Cyprus, Czech Republic, Estonia, Georgia, Greece, Hungary, Latvia, Lithuania, Malta, Moldova, Montenegro, North Macedonia, Poland, Portugal, Romania, Serbia, Slovakia, Slovenia, Turkey and Ukraine), young researchers (<= 40) and women.-->

<!--
**Programme:**
-->

**Scientific organizers:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/), [Angeliki Koutsoukou Argyraki](https://www.cl.cam.ac.uk/~ak2110/) and [Claudio Sacerdoti](http://www.cs.unibo.it/~sacerdot/)

**Local organizer:** [Besik Dundua](https://cte.ibsu.edu.ge/en/besik-dundua/)

**Previous workshop:** [1st EuroProofNet Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-meeting1)
