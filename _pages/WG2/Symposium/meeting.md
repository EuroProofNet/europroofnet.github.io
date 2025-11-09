---
title: "WG2: Workshop on Automated Reasoning and Proof Logging"
layout: single
permalink: /wg2-symposium/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG2/Symposium/5.jpeg"/>

The videos of the WG2 talks are available [here](https://www.youtube.com/playlist?list=PLaT9F1eDUuN35otNw390wa-Lx_MCO6izM) and the videos of the WHOOPS talks are available [there](https://www.youtube.com/playlist?list=PLaT9F1eDUuN1hrdsSidWTFhuAxY4Yf_hy).

This will be the final meeting of the WG2 and the [International Workshop on Highlights in Organizing and Optimizing Proof-logging Systems](https://jakobnordstrom.se/WHOOPS25/) (WHOOPS'25). It is part of the [Final EuroProofNet Symposium](https://europroofnet.github.io/Symposium/).

**Date:** Thursday 11th to Saturday 13th (WG2), Saturday 13th and Sunday 14th (WHOOPS'25)

**Venue:**  [Institut Pascal](https://www.institut-pascal.universite-paris-saclay.fr/), 530 Rue André Rivière, 91400 Orsay [[access]](../Access) [[hotels]](../Hotels) [[food]](../Food). Remark that there might be a strike on the day before.

**Organizers** [Mathias Fleury](https://cca.informatik.uni-freiburg.de/fleury/) and [Sophie Tourret](https://members.loria.fr/sophie.tourret/)

**Registrations are closed** <!--fill in this [form](https://forms.gle/QLFzh3Ugv5WgkhZr7) (registration is free but mandatory)-->

**Talks** If you want to give a talk, please send an email to [Mathias Fleury](https://cca.informatik.uni-freiburg.de/fleury/)

**Objective:** The aim of this meeting series is to bring together researchers working on the topics of [working group 2 of EuroProofNet](https://europroofnet.github.io/wg2/). Our work focuses on two topics: Our first aim is to work and improve automated theorem provers. Our second aim is to make them correct by improving proof logging -- both in an attempt to produce short proofs but also to work on proof formats that support many features instead of having one format for each required feature. Proof logging is an important topic, as it makes it possible to check the work of a solver without trusting it. Our third aim is to translate proofs via the Dedukti proof system.

The program will be composed of talks and sessions to work alone or in small groups on the development of tools for automated theorem proving and proofs (in particular Dedukti proofs), taking advantage of the participation of experts on Dedukti, formula and proof exchange standards, and theorem provers and solvers, and to make progress on EuroProofNet objectives and deliverables.

**Program** Preliminary version:

Please note that you have to organize yourself for lunches (and dinners), but there are many [options](../Food) around.

| Time           | Thursday                                                      | Friday                                                                               | Saturday                                               |
|----------------|---------------------------------------------------------------|--------------------------------------------------------------------------------------|--------------------------------------------------------|
| 09:00 -- 9:30  | Opening & Presentation                                        | AR                                                                                   | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                |                                                               | [Julie Cailler](./slides/JulieCailler.pdf)                                           |                                                        |
| 09:30 -- 10:30 | Dedukti session (I)                                           |                                                                                      | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                | [Alessio Coltellacci](./slides/AlessioC.pdf) (long)           | [Vincent Trélat](./slides/VTrelat.pdf) (long)                                        |                                                        |
|                |                                                               |                                                                                      |                                                        |
|                |                                                               |                                                                                      |                                                        |
| 10:30 -- 11:00 | Break                                                         | Break                                                                                | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
| 11:00 -- 12:30 | Dedukti session (II)                                          | AR                                                                                   | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                | [Anja Petković Komel](./slides/vampireToDedukti.pdf) (remote) | [Florian Pollitt](./slides/FlorianPollitt.pdf)                                       |                                                        |
|                | [Melanie Tapproge](./slides/Taprogge.pdf)                     | [Hai Xia](./slides/HaiXia.pdf)                                                       |                                                        |
|                |                                                               |                                                                                      |                                                        |
| 12:30 -- 14:00 | [lunch](../Food)                                              | [lunch](../Food)                                                                     | [lunch](../Food)                                       |
| 14:00 -- 15:30 | Alethe (I)                                                    | AR & Other proof techniques                                                          |                                                        |
|                | [Ciarán Dunne](./slides/ciaran-talk.pdf)                      | [Maria Paola Bonacina](./slides/EuroProofNet-9-2025-MPBonacina-talk.pdf)             |                                                        |
|                | Discussion                                                    | [Roussanka Loukanova](./slides/Roussanka-li-mtta.pdf)                                |                                                        |
|                |                                                               |                                                                                      |                                                        |
| 15:30 -- 16:00 | Break                                                         | Break                                                                                | Break                                                  |
| 16:00 -- 17:00 | Alethe (II)                                                   | [Geoff Sutcliffe](https://tptp.org/Seminars/GDVLambdaPiTrust/Contents.html) (remote) |                                                        |
|                | [Bruno Andreotti](./slides/Andreotti-slides.pdf)              | Discussion                                                                           |                                                        |
|                | [Hanna Lachnitt](./slides/lachnitt-slides.pdf)                | EPN Goals and what did we achieve?                                                   |                                                        |
|                |                                                               |                                                                                      |                                                        |
| 17:00 -- 17:30 | Hans-Jörg Schurr (WIP)                                        |                                                                                      |                                                        |
| 17:30 -- 18:30 | Happy hour                                                    |                                                                                      |                                                        |


**Talks**

+ Anja Petković Komel (Argot Collective), Michael Rawson (University of Southampton), and Martin Suda (Czech Technical University in Prague): Verified Vampire Proofs in the λΠ-calculus Modulo

Abstract: The Vampire automated theorem prover is extended to output machine-checkable proofs in the Dedukti concrete syntax for the λΠ-calculus modulo. This significantly reduces the trusted computing base, and in principle eases proof reconstruction in other proof-checking systems. Existing theory is adapted to deal with Vampire’s internal logic and inference system. To our knowledge this is the first time this has been attempted in a system as complex as Vampire. We will report on the implementation experience, give an overview of the extent of the proof translation and how Vampire’s Avatar architecture is handled, and present some of the first experimental results looking into the overhead proof reconstruction entails. 


+ Hai Xia (TU Wien), Uncovering and Verifying Optimal Graph Modularity: A MaxSAT Approach

Abstract: Network modularity is central to understanding phenomena in
diverse domains, from biology and social science to engineering and
computational physics. However, computing the optimal modularity—an
NP-hard measure quantifying community strength—has remained
computationally intractable at large scales. Most approaches resort to
heuristics without formal optimality guarantees. This paper
contributes to the computational science of complex systems by
introducing a novel MaxSAT-based framework that can compute optimal
network modularity values for larger networks than previously
possible. Leveraging this new capability, we extensively evaluate
heuristic solutions and, for the first time, include the
state-of-the-art memetic graph clustering heuristic
VieClus. Remarkably, VieClus identifies optimal modularity values for
all tested networks, ranging from 103 previously studied instances to
52 new, larger ones, and does so in seconds. This result contrasts
with earlier conclusions that heuristics frequently fail to find the
optimal modularity. By combining a powerful MaxSAT encoding, which
supports proof logging for verification, with a fast and effective
heuristic, we demonstrate that even intricate network structures can
be tackled efficiently. This synergy brings us closer to making
complex network analysis and community detection tractable, robust,
and verifiable—a goal firmly aligned with the core mission of
computational science.


+ Roussanka Loukanova (Bulgarian Academy of Sciences), Logging Information by Moschovakis Type-Theory of Algorithms

Abstract: Presenting Moschovakis Type-Theory of Recursion and Algorithms for logging information during algorithmic calculations, by its recursion or iteration assignments in memory locations.

+ Geoff Sutcliffe (University of Miami), [Proof Verification with GDV and LambdaPi It's a Matter of Trust](https://tptp.org/Seminars/GDVLambdaPiTrust/Abstract.html)

Abstract: Automated Theorem Proving (ATP) is concerned with the development and
use of software that automates sound reasoning. An ATP system can be required to
output a proof that serves as a certificate for the system's claim. To ensure
that a proof is correct, verification can be required. If the verifier outputs
evidence in a form that can be independently checked, that evidence serves as a
certificate for the verifier's claim. The sequence of finding a proof, verifying
the proof, and certifying the verification, builds an increasing level of trust
in the system. This talk traces one such path for TPTP format proofs generated
by ATP systems, via the GDV derivation verifier, and ending at the LambdaPi
checker.





+ Bruno Andreotti (Universidade Federal de Minas Gerais), Carcara: A proof checker, elaborator and translator for Alethe  <!-- Thursday afternoon -->

+ Hans-Jörg Schurr (University of Iowa), System ϒ --- Solid Foundations for SMT Proofs  <!-- Thursday afternoon -->

+ Ciarán Dunne (Inria Saclay), e2lp -- from Eunoia to LamdaPi

+ Vincent Trélat (Inria Saclay), Safely Encoding B Proof Obligations in SMT-LIB

+ Alessio Coltellacci (University of Lorraine, CNRS, Inria, Nancy), Reconstructung SMT Proofs in Lambdapi

+ Melanie Tapproge (University Greifswald), Encoding and Verifying Leo-III Proofs in the Dedukti Framework

Abstract: The diversity of output encodings of different reasoning
systems hinders proof verification and interoperability. The Dedukti
framework addresses this issue by implementing the λΠ-calculus modulo,
enabling proofs from different frameworks to be expressed, combined,
and checked automatically. We identify common challenges and
requirements for verifying proofs of automated theorem provers for
higher-order logic, and develop general strategies for systematically
deriving encodings of calculus rules and proof steps. Building on
these strategies, we propose a modular encoding approach, which we
demonstrate and evaluate using the higher-order logic prover
Leo-III. This effort has already led to the discovery and resolution
of minor bugs in the original prover.


+ Florian Pollitt (University Freiburg), Deterministic Scheduling

Abstract: SAT solvers are complex systems with many algorithms and
heuristics competing in a portfolio approach.  Furthermore they are
used in critical systems where performance regressions and brittleness
of results can be detrimental. As such, guaranteeing deterministic and
reproducible results is a big feature of SAT solvers.  This talk
focuses on the practical application of one solution to this
scheduling problem in the cadical SAT solver.

+ Julie Cailler (Loria), Deskolemization: From Tableaux to Machine-Checkable Proofs

+ Maria Paola Bonacina (Università degli Studi di Verona), Nondisjoint CDSAT: arrays, maps, and vectors with abstract domain

Abstract: Arrays in programming languages are finite, whereas sequences in
mathematics and computer science can be infinite. The basic operations in the
theory of arrays are read and write, so that the theory of arrays has been
considered for years the best candidate to reason about the computer memory. The
basic operation in the theory of sequences is associative concatenation, so that
sequences form a monoid with the empty sequence as unit. Surprisingly, a current
approach in satisfiability modulo theories proposes to reason about finite
arrays (and computer memory) by using theories of finite sequences, even if the
practical problems and benchmarks to be solved are about arrays.  In this talk I
explain the issues that led to this unexpected turn, I present a theory of
arrays with abstract domains that solves all these issues, and two variants
thereof that model maps and vectors (i.e., dynamic arrays).  The extension of
the CDSAT method for theory combination to unions of theories that share
predicate symbols other than equality makes it possible to reason about these
theories.

(Joint work in progress with Stéphane Graham-Lengrand and Natarajan Shankar)

+ Hanna Lachnitt (Stanford University), Reconstruction of cvc5 Proofs in Isabelle/HOL

**Discussion**

+ EPN Goals and what did we achieve?

We have to write a short summary on what we achieved for each
goal. The idea is to discus together such that we do not forget
important information.

<!--
**Objectives/Deliverables:**
  - D10. Release of software for translating proofs coming from important proof systems based on set theory like Mizar, Atelier B or TLAPS to Dedukti and back.
-->

<img src="/_pages/WG2/Symposium/1.jpeg"/>
<img src="/_pages/WG2/Symposium/2.jpeg"/>
<img src="/_pages/WG2/Symposium/3.jpeg"/>
<img src="/_pages/WG2/Symposium/4.jpeg"/>
<img src="/_pages/WG2/Symposium/6.jpeg"/>
<img src="/_pages/WG2/Symposium/7.jpeg"/>
<img src="/_pages/WG2/Symposium/whoops.jpeg"/>
