---
title: "EuroProofNet Workshop on Proof Libraries"
layout: single
permalink: /WG4_Orsay25/
author_profile: true
breadcrumbs: true
---

This workshop/WG4 meeting is part of the [EuroProofNet Symposium](../Symposium). See the symposium page to get information on the other co-located events.

The objective is to have talks and demos like in the [1st Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-meeting1) and, if time permits, some common development sessions.

**Date:** 15-16 September 2025

**Venue:** [Institut Pascal](https://www.institut-pascal.universite-paris-saclay.fr/), 530 Rue André Rivière, 91400 Orsay [[access]](../Access) [[hotels]](../Hotels) [[food]](../Food)

**Organizers:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/), [Claudio Sacerdoti](http://www.cs.unibo.it/~sacerdot/), [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/)

**Registration:** fill in this [form](https://forms.gle/QLFzh3Ugv5WgkhZr7) (registration is free but mandatory)

<!--
**Important dates:**
- May 25 CEST: deadline for [funding requests](https://forms.gle/QLFzh3Ugv5WgkhZr7) and talk proposals
- June 4: notification

**Talk/demo proposals:** If you want to give a talk or make a tool demo, send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with a title and abstract before May 25.
-->

<!--
we have 2 days

each day: 8 45-minutes talks or 12 30-minutes talks
total: 16 45-minutes talks or 24 30-minutes talks

for the moment, we have 15 talks

09:00-10:30 talks
10:30-11:00 break
11:00-12:30 talks
12:30-14:00 lunch
14:00-15:30 talks
15:30-16:00 break
16:00-17:30 talks
-->

**Schedule:**

Please note that you have to organize yourself for lunches (and dinners), but there are many [options](../Food) around.

| time | Monday 15 September |
|-|-|
| 08:30-09:00 | welcome |
| 09:00-09:45 | [Manuel Eberl](http://cl-informatik.uibk.ac.at/users/meberl/) (U. Innsbruck, Austria), the Isabelle Archive of Formal Proofs |
| 09:45-10:30 | [Michael Rothgang](https://www.math.uni-bonn.de/people/rothgang/) (U. Bonn, Germany), growing Lean mathlib: review and triage tooling for a large formalised mathematics library |
| 10:30-11:00 | break   |
| 11:00-11:45 | Justin Asher,  LeanExplore: A search engine for Lean 4 declarations |
| 11:45-12:30 | [Nicolas Magaud](https://dpt-info.u-strasbg.fr/~magaud/) (U. Strasbourg, France), Optimization of Rocq proof scripts |
| 12:30-14:00 | [lunch](../Food) |
| 14:00-14:45 | [Mohammad Abdulaziz](https://mabdula.github.io/) (King's College London, UK), an Isabelle Library of Combinatorial Optimisation Results |
| 14:45-15:30 | [Yannick Forster](https://yforster.de/) (Inria Paris, France), the Coq Library of undecidability proofs |
| 15:30-16:00 | break   |
| 16:00-16:45 | Christian Merten (U. Utrech, Netherlands), algebraic geometry in Lean's mathematical library mathlib |
| 16:45-17:30 | [Niels van der Weide](https://nmvdw.github.io/) (U. Radboud, Netherlands), the Unimath Coq library |
| 17:30-18:30 | happy hour |

| time | Tuesday 16 September |
|-|-|
| 09:00-09:45 | [Sylvie Boldo](https://pages.saclay.inria.fr/sylvie.boldo/) (Inria Saclay, France), Numerical Analysis in Rocq -- Simplicial Lagrange Finite Elements |
| 09:45-10:30 | [Joseph Tooby-Smith](https://josephtoobysmith.com/) (U. Reykjavik, Iceland), PhysLean: Digitalizing Physics in Lean |
| 10:30-11:00 | break   |
| 11:00-11:45 | [Kathrin Stark](https://www.k-stark.de/) (U. Heriot-Watt, UK), On Autosubst: Mechanising binders in Coq |
| 11:45-12:30 | [Matthieu Sozeau](https://sozeau.gitlabpages.inria.fr/www/) (Inria Nantes, France), MetaRocq: Metaprogramming and Mechanization of Rocq in Rocq |
| 12:30-14:00 | [lunch](../Food) |
| 14:00-14:45 | [Julien Narboux](https://www.irif.fr/~narboux/) (U. Paris Cité, France) and [Pierre Boutry](https://pierre-boutry.fr/) (U. Strasbourg, France), GeoCoq: a library for foundations of geometry |
| 14:45-15:30 | [Cyril Cohen](https://perso.crans.org/cohen/) (Inria Lyon, France), Hierarchy Builder |
| 15:30-16:00 | break   |
| 16:00-16:45 | [Markus Himmel](https://github.com/TwoFX) (Lean FRO, Germany), the Lean standard library: development methodology and tooling |
| 16:45-17:30 | [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/) (U. Paris-Saclay, France), coordinating large formalization projects |

**Abstracts:**

- [Manuel Eberl](http://cl-informatik.uibk.ac.at/users/meberl/) (U. Innsbruck, Austria), the Isabelle Archive of Formal Proofs [[link]](https://www.isa-afp.org/)

- [Michael Rothgang](https://www.math.uni-bonn.de/people/rothgang/) (U. Bonn, Germany), growing Lean mathlib: review and triage tooling for a large formalised mathematics library [[link]](https://leanprover-community.github.io/mathlib-overview.html)

Lean's mathematical library mathlib is one of the fastest-growing libraries of formalised mathematics. It is developed in the open by a large and diverse community of various backgrounds.
Review and triage of all incoming contributions presents an ongoing challenge as mathlib's growth continues. I'll present mathlib's processes and tools to enable review to scale. A core component is a custom editorial dashboard (built jointly with Johan Commelin) which keeps track of each contribution's status over time. This allows for efficient triage, enables intelligent automatic reviewer assignment and ensuring no contribution is left behind.

- [Justin Asher](https://justinasher.me/) (USA),  LeanExplore: A search engine for Lean 4 declarations [[web]](https://www.leanexplore.com/)

The rapid growth of Lean 4 libraries like Mathlib makes finding relevant theorems a significant challenge. This talk introduces LeanExplore, a search engine that enables semantic search of Lean declarations using natural language. We present a hybrid ranking strategy that combines multi-source semantic embeddings, keyword relevance (BM25+), and a PageRank-based score for declaration importance. A key feature is our use of an LLM to generate informal English translations for formal statements, significantly improving search accuracy. Accessible via a website and Python API, LeanExplore also integrates with AI assistants through the model context protocol (MCP), creating new opportunities for AI-driven theorem proving.

- [Nicolas Magaud](https://dpt-info.u-strasbg.fr/~magaud/) (U. Strasbourg, France) and Alexandre Jean, Optimization of Rocq proof scripts

Proof assistants like Rocq are becoming mainstream tools to help mathematicians carry out proofs of the results they conjecture. However, formal proofs remain highly technical and are increasingly larger both in terms of script size and script execution/compilation time. We present a generic framework, called coq-ditto which aims at post-processing correct proof scripts and at transforming them into some  equivalent proof scripts, optimized according to some given criteria. The first available transformations include factorizing proof steps into a single-line proof scripts, replacing calls to automatic tactics such as auto with the actual proof steps they suggested.  We choose to develop a generic framework which allows to combine and revert proof scripts transformations depending on the user needs.
We apply our tool to various proof developments including the standard library of Rocq and the library GeoCoq which formalizes geometry. 

- [Mohammad Abdulaziz](https://mabdula.github.io/) (King's College London, UK), an Isabelle Library of Combinatorial Optimisation Results [[github]](https://github.com/mabdula/Isabelle-Graph-Library)

Combinatorial optimisation is a fundamental area of computer science, and applied mathematics. It involves solving computational problems optimally w.r.t. a given metric. Important problems in the area include shortest path, minimum spanning trees, maximum flows, minimum-cost flows, maximum cardinality/weight matching, and linear programming. Practically, these problems are some of the most impactful in computer science, where they used in applications ranging from logistics to kidney-donor-patient matching. Theoretically, work in this area has led to many important breakthroughs in the theory of computing, including the realisation that polynomial time computation is a notion of efficient computation, the primal-dual paradigm to designing algorithms, and the characterisation of computational problems as polytopes.

In this talk I will describe an ongoing development of a formal mathematical library of results from the theory of combinatorial optimisation. The library currently has most results covered in a standard textbook on the subject, including algorithms for solving all the standard problems. Notable results include Edmonds' blossom shrinking algorithm, Orlin's scaling algorithm for minimum-cost flows, and the AdWords algorithm for matching online advertisements on search engines.

- [Yannick Forster](https://yforster.de/) (Inria Paris, France), the Coq Library of undecidability proofs [[github]](https://github.com/uds-psl/coq-library-undecidability)

The Rocq library of undecidable problems is a collaborative formalisation of undecidability proofs, mostly carried out in the form of student projects. I will explain how this library can be helpful for novel research results, how it was developed by undergraduate students, how Rocq facilitated such a development, and how it could be ported to other proof assistants.

The library has contributions by Dominique Larchey-Wendling, Dominik Kirst, Andrej Dudenhefner, Johannes Hostert, Fabian Kunze, Marc Hermes, Mark Koch, Benjamin Peters, Dominik Wehr, Lennard Gäher, Niklas Mück, Hizbullah Jabbar, Simon Spies, Maximilian Wuttke, Edith Heiter, and Gert Smolka.

- Christian Merten (U. Utrech, Netherlands), algebraic geometry in Lean's mathematical library mathlib

Since the first definition of schemes in Lean by Kevin Buzzard et al. in 2018, the algebraic geometry library in mathlib has undergone significant development. In an effort led by Andrew Yang, many fundamental tools and results in scheme theory were established. I will give an overview of where we are at, what we are missing and speculate why it remains difficult to attract new contributors to this part of the library.

- [Niels van der Weide](https://nmvdw.github.io/) (U. Radboud, Netherlands), the Unimath Rocq library [[link]](https://unimath.github.io/UniMath/)

In this talk, we discuss the UniMath, which is a library in Rocq based on univalent foundations. UniMath covers various areas in mathematics ranging from (higher) category theory and homological algebra to algebraic theories and substitution systems. Specifically, we discuss the basics of univalent foundations, and how it affects the development of (higher) category theory.

Univalent foundations is a version of dependent type theory extended with the univalence axiom. Roughly speaking, this axiom states that two types are identified if they are equivalent, and as a consequence we get a more refined treatment of identity. In addition, this axiom gives us new and interesting perspectives on mathematics, and, in particular, category theory. 

Categories come with multiple notions of equivalence, namely isomorphism and adjoint equivalence. This bifurcation is reflected in univalent foundations, where one can distinguish between two kinds of categories. On the one hand, one has setcategories, which are identified up to isomorphism, and on the other hand, one has univalent categories, which are identified up to adjoint equivalence. These notions come with suitable equivalence principles that allows us to transport structure and properties. While such principles usually have to be proven by hand, they are automatic in univalent foundations.

- [Sylvie Boldo](https://pages.saclay.inria.fr/sylvie.boldo/) (Inria Saclay, France), Numerical Analysis in Rocq -- Simplicial Lagrange Finite Elements [[link]](https://lipn.univ-paris13.fr/coq-num-analysis/)

The finite elements method is a popular method to numerically solve partial differential equations. In the long-term goal of proving its correctness, we focus here on the formal definition of what is a finite element: a record in the Rocq proof assistant with both values and proofs of validity, including the main one called unisolvence. We then instantiate this record with the most popular and useful, the simplicial Lagrange finite elements for any dimension and any polynomial degree.
These proofs require many results (definitions, lemmas, canonical structures) about finite families, affine spaces, multidimensional polynomials, in the context of finite or infinite-dimensional spaces.

This is common work with F. Clément, V. Martin, M. Mayero, and H. Mouhcine.

- [Joseph Tooby-Smith](https://josephtoobysmith.com/) (U. Reykjavik, Iceland), PhysLean: Digitalizing Physics in Lean [[link]](https://physlean.com/)

PhysLean is a project to create a monolithic library of results from physics in Lean 4, akin to Mathlib for mathematics. 
It contains results from a range of different areas of physics including classical mechanics, relativity, condensed matter physics, quantum field theory, string theory etc.
In this talk I will give a high-level overview of the current content of PhysLean.
I will also explain how formalizing results from physics, for physicists, differs to formalizing results from mathematics, for mathematicians, and what features we have 
put in place to make this as an efficient and open process as possible.

- [Kathrin Stark](https://www.k-stark.de/) (U. Heriot-Watt, UK), On Autosubst: Mechanising binders in Coq [[link]](https://www.ps.uni-saarland.de/extras/autosubst2/)

Mechanising metatheory in the Coq proof assistant is often considered tedious as reasoning with binders without native support requires a lot of uninteresting technicalities. To relieve users from so-produced boilerplate, the Autosubst compiler automates working with de Bruijn terms. Autosubst translates second-order HOAS specifications into the corresponding pure or scoped de Bruijn algebra: It hence generates a corresponding instantiation operation for parallel substitutions, several equational substitution lemmas, and tactics that among others implement automation for assumption-free substitution lemmas. In this talk, we outline the design and usage of Autosubst; including recent plans for extensibility.

- [Matthieu Sozeau](https://sozeau.gitlabpages.inria.fr/www/) (Inria Nantes, France), MetaRocq: Metaprogramming and Mechanization of Rocq in Rocq [[link]](https://metarocq.github.io/)

The MetaRocq library is a library and set of plugins for Rocq that 
provides metaprogramming facilities on top of Rocq and develops the 
metatheory of the core type theory of Rocq with accompanying verified
implementations of type-checking and extraction. In this talk, I will present
the different components of the library and the challenges and solutions we 
developed to make the proof development scale to the large language and 
specifications we study. I will also discus possible improvements to the proof 
assistant that would help in our development and future research directions.

The MetaRocq library was developed collaboratively by Abhishek Anand, 
Danil Annenkov, Simon Boulier, Cyril Cohen, Yannick Forster, Jason Gross, 
Meven Lennon-Bertrand, Kenji Maillard, Gregory Malecha, Jakob Botsch Nielsen,
Matthieu Sozeau, Nicolas Tabareau and Théo Winterhalter.

- [Julien Narboux](https://www.irif.fr/~narboux/) (U. Paris Cité, France) and [Pierre Boutry](https://pierre-boutry.fr/) (U. Strasbourg, France), GeoCoq: a library for foundations of geometry [[link]](https://geocoq.github.io/GeoCoq/)

GeoCoq is a library about the foundations of geometry. It contains a formalization of the axioms systems of Euclid, Hilbert, and Tarski, along with a model of these axioms, proofs of mutual interpretations between different variants of these axiom systems, and a systematic development of geometry culminating in the so-called arithmetization of geometry that connects the synthetic approach to the analytic geometry. In this talk, we will provide a brief overview of the library's content and report on its porting to other proof assistants. GeoCoq has been partially ported semi-automatically to Mizar and Isabelle by Roland Coghetto, and using more foundational techniques by translating to Dedukti by Yoan Géran and Pierre Boutry. We will discuss the advantages and drawbacks of both approaches.GeoCoq’s team has also taken part recently in the ADGLib initiative, trying to define a standard language and tools for the manipulation of geometric knowledge.If time permits, we will mention the current effort to obtain a constructive version of the library.

- [Cyril Cohen](https://perso.crans.org/cohen/) (Inria Lyon, France), Hierarchy Builder [[github]](https://github.com/math-comp/hierarchy-builder/)

Libraries of machine checked code are, nowadays, organized around hierarchies of algebraic structures. Unfortunately the language of Type Theory and the features provided by the Coq system make the construction of a hierarchy hard even for expert users. The difficulty begins with the non-orthogonal choices, between storing information as record fields or parameters, and between using type classes and canonical structures for inference. To this, one may add the concerns about performance and about the usability, by a non expert, of the final hierarchy.

HB gives the library designer a language to describe the building blocks of algebraic structures and to assemble them into a hierarchy. Similarly it provides the final user linguistic constructs to build instances (examples) of structures and to teach the elaborator of Coq how to take advantage of this knowledge during type inference. Finally HB lets the library designer improve the usability of his library by providing alternative interfaces to the primitive ones, a feature that can also be used to accommodate changes to the hierarchy without breaking user code.

This is a joint work with Kazuhiko Sakaguchi, Pierre Roux and Enrico Tassi.

- [Markus Himmel](https://github.com/TwoFX) (Lean FRO, Germany), the Lean standard library: development methodology and tooling

The Lean standard library is part of the Lean distribution and provides users with tools for functional programming, software verification and verified software development. Its main goals are comprehensiveness, consistency and a smooth out-of-the-box experience. Achieving these high standards requires a systematic approach to standard library development and maintenance. In this presentation, I will show a tool that the Lean FRO is using to detect and track defects in the Lean standard library such as missing material or inconsistencies within the library. The tool is integrated into the GitHub PR workflow to enable merging of contributions without having to fear that new inconsistencies are introduced into the library.

- [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/) (U. Paris-Saclay, France), coordinating large formalization projects

Formalized mathematics has a rich history of large formalization projects involving many participants. In this talk I will first review past experiences coordinating such projects. Then I will focus on the main tools currently used by the Lean users community, including the Zulip web chat software, GitHub infrastructure and the LeanBlueprint plasTeX plugin.

**Previous workshops:**
- [1st Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-meeting1), Tbilisi, Georgia, 23-24 September 2022
- [Workshop on Libraries of Formal Proofs and Natural Mathematical Language](../cambridge-2023), Cambridge, UK, 7-8 September 2023
- [2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-tbilisi24), Tbilisi, Georgia, 13-14 September 2024
