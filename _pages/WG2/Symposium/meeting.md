---
title: "WG2: Workshop on Automated Reasoning and Proof Logging"
layout: single
permalink: /wg2-symposium/
author_profile: true
breadcrumbs: true
---

This will be the final meeting of the WG2 and the [International Workshop on Highlights in Organizing and Optimizing Proof-logging Systems](https://jakobnordstrom.se/WHOOPS25/) (WHOOPS'25). It is part of the [Final EuroProofNet Symposium](https://europroofnet.github.io/Symposium/).

**Date:** Thursday 11th to Saturday 13th (WG2), Saturday 13th and Sunday 14th (WHOOPS'25)

**Venue:**  [Institut Pascal](https://www.institut-pascal.universite-paris-saclay.fr/), 530 Rue André Rivière, 91400 Orsay [[access]](../Access) [[hotels]](../Hotels) [[food]](../Food)

**Organizers** [Mathias Fleury](https://cca.informatik.uni-freiburg.de/fleury/) and [Sophie Tourret](https://members.loria.fr/sophie.tourret/)

**Registration:** fill in this [form](https://forms.gle/QLFzh3Ugv5WgkhZr7) (registration is free but mandatory)

**Talks** If you want to give a talk, please send an email to [Mathias Fleury](https://cca.informatik.uni-freiburg.de/fleury/)

**Objective:** The aim of this meeting series is to bring together researchers working on the topics of [working group 2 of EuroProofNet](https://europroofnet.github.io/wg2/). Our work focuses on two topics: Our first aim is to work and improve automated theorem provers. Our second aim is to make them correct by improving proof logging -- both in an attempt to produce short proofs but also to work on proof formats that support many features instead of having one format for each required feature. Proof logging is an important topic, as it makes it possible to check the work of a solver without trusting it. Our third aim is to translate proofs via the Dedukti proof system.

The program will be composed of talks and sessions to work alone or in small groups on the development of tools for automated theorem proving and proofs (in particular Dedukti proofs), taking advantage of the participation of experts on Dedukti, formula and proof exchange standards, and theorem provers and solvers, and to make progress on EuroProofNet objectives and deliverables.

**Program** Preliminary version:

Please note that you have to organize yourself for lunches (and dinners), but there are many [options](../Food) around.

| Time           | Thursday                     | Friday                                | Saturday                                               |
|----------------|------------------------------|---------------------------------------|--------------------------------------------------------|
| 09:00 -- 9:30  | Opening & Presentation       | AR                                    | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
| 09:30 -- 10:30 | Dedukti session (I)          | AR                                    | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
| 10:30 -- 11:00 | Break                        | Break                                 | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
| 11:00 -- 12:30 | Dedukti session (II)         | AR                                    | [VeriPB tutorial](https://jakobnordstrom.se/WHOOPS25/) |
|                | Anja Petković Komel (remote) |                                       |                                                        |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
| 12:30 -- 14:00 | [lunch](../Food)             | [lunch](../Food)                      | [lunch](../Food)                                       |
| 14:00 -- 15:30 | Alethe (I)                   | Other proof techniques & Applications |                                                        |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
| 15:30 -- 16:00 | Break                        | Break                                 | Break                                                  |
| 16:00 -- 17:00 | Alethe (II)                  | Other proof techniques                |                                                        |
|                |                              | Geoff Sutcliffe (remote)               |                                                        |
|                |                              |                                       |                                                        |
|                |                              |                                       |                                                        |
| 17:00 -- 17:30 | Discussion                   | Discussion                            |                                                        |
| 17:30 -- 18:30 |                              | Happy hour                            |                                                        |


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

+ Geoff Sutcliffe (University of Miami), TBA  <!-- Friday -->

+ Bruno Andreotti (Universidade Federal de Minas Gerais), TBA  <!-- Thursday afternoon -->

+ Hans-Jörg Schurr (University of Iowa), TBA  <!-- Thursday afternoon -->

+ Ciarán Dunne (Inria Saclay), TBA

+ Vincent Trélat (Inria Saclay), TBA  <!-- methode B smtlib -->

+ Alessio Coltellacci (University of Lorraine, CNRS, Inria, Nancy), TBA <!-- long-->


<!--
**Objectives/Deliverables:**
  - D10. Release of software for translating proofs coming from important proof systems based on set theory like Mizar, Atelier B or TLAPS to Dedukti and back.
-->
