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

**Venue:** [Institut Pascal](https://www.institut-pascal.universite-paris-saclay.fr/), 530 Rue André Rivière, 91400 Orsay [[access]](../Access) [[hotels]](../Hotels) [[food options]](../Food)

**Organizers:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/), [Claudio Sacerdoti](http://www.cs.unibo.it/~sacerdot/), [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/)

**Registration/funding requests:** fill in this [form](https://forms.gle/QLFzh3Ugv5WgkhZr7) (registration is free but mandatory)

**Important dates:**
- May 25 CEST: deadline for [funding requests](https://forms.gle/QLFzh3Ugv5WgkhZr7) and talk proposals
- June 1st: notification

**Talk/demo proposals:** If you want to give a talk or make a tool demo, send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with a title and abstract before May 25.

**Speakers:**

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

- [Markus Himmel](https://github.com/TwoFX) (Lean FRO, Germany), the Lean standard library: development methodology and tooling

<!-- The Lean standard library is part of the Lean distribution and provides users with tools for functional programming, software verification and verified software development. Its main goals are comprehensiveness, consistency and a smooth out-of-the-box experience. Achieving these high standards requires a systematic approach to standard library development and maintenance. In this presentation, I will show a tool that the Lean FRO is using to detect and track defects in the Lean standard library such as missing material or inconsistencies within the library. The tool is integrated into the GitHub PR workflow to enable merging of contributions without having to fear that new inconsistencies are introduced into the library.-->

- [Michael Rothgang](https://www.math.uni-bonn.de/people/rothgang/) (U. Bonn, Germany), growing Lean mathlib: review and triage tooling for a large formalised mathematics library [[link]](https://leanprover-community.github.io/mathlib-overview.html)

<!-- Lean's mathematical library mathlib is one of the fastest-growing libraries of formalised mathematics. It is developed in the open by a large and diverse community of various backgrounds.
Review and triage of all incoming contributions presents an ongoing challenge as mathlib's growth continues. I'll present mathlib's processes and tools to enable review to scale. A core component is a custom editorial dashboard (built jointly with Johan Commelin) which keeps track of each contribution's status over time. This allows for efficient triage, enables intelligent automatic reviewer assignment and ensuring no contribution is left behind.-->

- [Manuel Eberl](http://cl-informatik.uibk.ac.at/users/meberl/) (U. Innsbruck, Austria), the Isabelle Archive of Formal Proofs [[link]](https://www.isa-afp.org/)

- [Nicolas Magaud](https://dpt-info.u-strasbg.fr/~magaud/) (U. Strasbourg, France), optimisation of Coq proof scripts

- [Cyril Cohen](https://perso.crans.org/cohen/) (Inria Lyon, France), Hierarchy Builder [[github]](https://github.com/math-comp/hierarchy-builder/)

<!-- Libraries of machine checked code are, nowadays, organized around hierarchies of algebraic structures. Unfortunately the language of Type Theory and the features provided by the Coq system make the construction of a hierarchy hard even for expert users. The difficulty begins with the non-orthogonal choices, between storing information as record fields or parameters, and between using type classes and canonical structures for inference. To this, one may add the concerns about performance and about the usability, by a non expert, of the final hierarchy.

HB gives the library designer a language to describe the building blocks of algebraic structures and to assemble them into a hierarchy. Similarly it provides the final user linguistic constructs to build instances (examples) of structures and to teach the elaborator of Coq how to take advantage of this knowledge during type inference. Finally HB lets the library designer improve the usability of his library by providing alternative interfaces to the primitive ones, a feature that can also be used to accommodate changes to the hierarchy without breaking user code.

This is a joint work with Kazuhiko Sakaguchi, Pierre Roux and Enrico Tassi.-->

- [Mohammad Abdulaziz](https://mabdula.github.io/) (King's College London, UK), an Isabelle Library of Combinatorial Optimisation Results [[github]](https://github.com/mabdula/Isabelle-Graph-Library)

<!-- Combinatorial optimisation is a fundamental area of computer science, and applied mathematics. It involves solving computational problems optimally w.r.t. a given metric. Important problems in the area include shortest path, minimum spanning trees, maximum flows, minimum-cost flows, maximum cardinality/weight matching, and linear programming. Practically, these problems are some of the most impactful in computer science, where they used in applications ranging from logistics to kidney-donor-patient matching. Theoretically, work in this area has led to many important breakthroughs in the theory of computing, including the realisation that polynomial time computation is a notion of efficient computation, the primal-dual paradigm to designing algorithms, and the characterisation of computational problems as polytopes.

In this talk I will describe an ongoing development of a formal mathematical library of results from the theory of combinatorial optimisation. The library currently has most results covered in a standard textbook on the subject, including algorithms for solving all the standard problems. Notable results include Edmonds' blossom shrinking algorithm, Orlin's scaling algorithm for minimum-cost flows, and the AdWords algorithm for matching online advertisements on search engines.-->

- [Julien Narboux](https://www.irif.fr/~narboux/) (U. Paris Cité, France) and [Pierre Boutry](https://pierre-boutry.fr/) (U. Strasbourg, France), the Coq library on geometry [[link]](https://geocoq.github.io/GeoCoq/)

- Christian Merten (U. Utrech, Netherlands), algebraic geometry in Lean's mathematical library mathlib

<!-- Since the first definition of schemes in Lean by Kevin Buzzard et al. in 2018, the algebraic geometry library in mathlib has undergone significant development. In an effort led by Andrew Yang, many fundamental tools and results in scheme theory were established. I will give an overview of where we are at, what we are missing and speculate why it remains difficult to attract new contributors to this part of the library.-->

- [Sylvie Boldo](https://pages.saclay.inria.fr/sylvie.boldo/) (Inria Saclay, France), Numerical Analysis in Rocq -- Simplicial Lagrange Finite Elements [[link]](https://lipn.univ-paris13.fr/coq-num-analysis/)

<!-- The finite elements method is a popular method to numerically solve partial differential equations. In the long-term goal of proving its correctness, we focus here on the formal definition of what is a finite element: a record in the Rocq proof assistant with both values and proofs of validity, including the main one called unisolvence. We then instantiate this record with the most popular and useful, the simplicial Lagrange finite elements for any dimension and any polynomial degree.
These proofs require many results (definitions, lemmas, canonical structures) about finite families, affine spaces, multidimensional polynomials, in the context of finite or infinite-dimensional spaces.

This is common work with F. Clément, V. Martin, M. Mayero, and H. Mouhcine.-->

- [Joseph Tooby-Smith](https://josephtoobysmith.com/) (U. Reykjavik, Iceland), PhysLean: Digitalizing Physics in Lean [[link]](https://physlean.com/)

<!-- PhysLean is a project to create a monolithic library of results from physics in Lean 4, akin to Mathlib for mathematics. 
It contains results from a range of different areas of physics including classical mechanics, relativity, condensed matter physics, quantum field theory, string theory etc.
In this talk I will give a high-level overview of the current content of PhysLean.
I will also explain how formalizing results from physics, for physicists, differs to formalizing results from mathematics, for mathematicians, and what features we have 
put in place to make this as an efficient and open process as possible.-->

- [Yannick Forster](https://yforster.de/) (Inria Paris, France), the Coq Library of undecidability proofs [[github]](https://github.com/uds-psl/coq-library-undecidability)

- [Niels van der Weide](https://nmvdw.github.io/) (U. Radboud, Netherlands), the Unimath Coq library [[link]](https://unimath.github.io/UniMath/)

- [Kathrin Stark](https://www.k-stark.de/) (U. Heriot-Watt, UK), Autosubst [[link]](https://www.ps.uni-saarland.de/extras/autosubst2/)

- [Matthieu Sozeau](https://sozeau.gitlabpages.inria.fr/www/) (Inria Nantes, France), MetaCoq [[link]](https://metarocq.github.io/)

- [Patrick Massot](https://www.imo.universite-paris-saclay.fr/~patrick.massot/) (U. Paris-Saclay, France), coordinating large formalization projects

<!-- Formalized mathematics has a rich history of large formalization projects involving many participants. In this talk I will first review past experiences coordinating such projects. Then I will focus on the main tools currently used by the Lean users community, including the Zulip web chat software, GitHub infrastructure and the LeanBlueprint plasTeX plugin.-->

**Previous workshops:**
- [1st Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-meeting1), Tbilisi, Georgia, 23-24 September 2022
- [Workshop on Libraries of Formal Proofs and Natural Mathematical Language](../cambridge-2023), Cambridge, UK, 7-8 September 2023
- [2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-tbilisi24), Tbilisi, Georgia, 13-14 September 2024
