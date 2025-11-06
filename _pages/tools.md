---
title: "Tools"
layout: single
permalink: /tools/
author_profile: true
---

To contribute to the web site, please open an [issue](https://github.com/EuroProofNet/europroofnet.github.io/issues), create a [pull request](https://github.com/EuroProofNet/europroofnet.github.io) or send a mail to the [science communication coordinators](../contact).

**Interactive theorem provers**

- [Agda](https://wiki.portal.chalmers.se/agda/pmwiki.php)
- [Coq](http://coq.inria.fr/)
- [Isabelle](https://isabelle.in.tum.de/)
- [Lean](http://leanprover.github.io/)
- [Lambdapi](https://github.com/Deducteam/lambdapi)
- [LISA](https://github.com/epfl-lara/lisa)
- [Matita](http://matita.cs.unibo.it/)
- [Mizar](http://mizar.org/)
- [TLAPS](https://github.com/tlaplus/tlapm)

**Automated theorem provers**

- [ArchSAT](https://github.com/Gbury/archsat): SMT solver generating Dedukti/FOL.
- [cvc5](https://cvc5.github.io/): efficient versatile SMT solver generating proof traces.
- [E](https://www.eprover.org): High-performance equational theorem prover for first-order logic (and
  increasingly higher-order logic), creating proof objects in TPTP format.
- [Eldarica](https://github.com/uuverifiers/eldarica): SMT solver for problems in the constrained Horn fragment. Can output models of Horn clauses in SMT-LIB, and proofs of unsatisfiability in several formats.
- [Goéland](https://github.com/GoelandProver/Goeland): A first-order concurrent tableau-based automated theorem prover with equality and management of theories with DMT that produce proofs in Rocq, LambdaPi, TPTP and Lisa. 
- [Larus](https://github.com/janicicpredrag/Larus): Larus is a theorem prover for coherent logic that uses SAT/SMT provers to construct proofs. Larus can generate natural language proofs (in LaTeX) and machine checkable proofs (Coq/Isabelle/Mizar).
- [Leo-III](https://github.com/leoprover/Leo-III): ATP for (polymorphic) higher-order logic, providing proofs in TPTP format.
- [Princess](https://github.com/uuverifiers/princess): ATP and SMT solver for first-order logic modulo various theories, with support for outputting proofs in different formats.
- [Vampire](https://vprover.github.io/): ATP handing first-order and higher-order logic with equality and theories producing fine-grained TPTP compliant proofs.
- [veriT](https://verit-solver.org/): SMT solver generating detailed proof traces in the Alethe format.
- [ZenonModulo](https://github.com/Deducteam/zenon_modulo): ATP generating Dedukti/FOL or Lambdapi/FOL.
- [Zipperposition](http://sneeuwballen.github.io/zipperposition/): Superposition prover initially designed for prototyping ideas but increasingly powerful especially on higher-order benchmarks.
- [z3](https://github.com/Z3Prover/z3/wiki): efficient SMT solver that generates [proofs](https://stackoverflow.com/questions/29577754/getting-proof-from-z3py) (for a subset of checks, at least).

**Type-checkers for the λΠ-calculus modulo theory**

- [Dkcheck](https://deducteam.github.io/): type-checker 
- [Kontroli](https://github.com/01mf02/kontroli-rs): parallel version of dkcheck
- [Lambdapi](https://github.com/Deducteam/lambdapi): interactive extension of dkcheck with metavariables and tactics

**Problem data bases**

- [TPTP](https://www.tptp.org): Thousands of Problems for Theorem Provers
- [TGTP](http://hilbert.mat.uc.pt/TGTP/index.php): Thousand of Geometric Problems for Geometric Theorem Provers
- [ADGLib](https://github.com/ADG-Foundation/ADG-Lib): Axiom systems, standard signature and library of problems for Geometric Theorem Provers

**Proof data bases**

- [Lean MathLib](https://github.com/leanprover-community/mathlib4)
- [Coq Opam Packages](https://coq.inria.fr/opam/www/)
- [Isabelle Archive of Formal Proofs](https://www.isa-afp.org/)
- [Mizar Mathematical Library](http://mizar.org/library/)
- [Logipedia](https://github.com/Deducteam/Logipedia): Matita arithmetic library translated to Dedukti/STTfa, Coq, Lean, OpenTheory, HOL-Light, PVS
- [Nubo](https://github.com/Deducteam/nubo): metadata on Dedukti libraries

**Proof data bases tools**

- [agda2train](https://github.com/omelkonian/agda2train): extracts JSON proof objects from Agda programs, to be used for machine learning purposes (as in [Quill](https://github.com/konstantinosKokos/quill/))
- [DAMF](https://distributed-assertions.github.io/): Distributed Assertion Management Framework
- [Lambdapi](https://github.com/Deducteam/lambdapi) >= 2.4.0 includes commands for [indexing](https://lambdapi.readthedocs.io/en/latest/options.html) Dedukti and Lambdapi files, making complex [search queries](https://lambdapi.readthedocs.io/en/latest/query_language.html) and running a [web server](https://lambdapi.readthedocs.io/en/latest/options.html) for making queries on the web

**Search engines**

- [FindFacts](https://search.isabelle.in.tum.de/): search tool for Isabelle
- [SErAPIS](https://behemoth.cl.cam.ac.uk/search/): search tool for Isabelle
- [LeanExplore](https://www.leanexplore.com/): search tool for Lean
- [Loogle](https://loogle.lean-lang.org/): search tool for Lean
- [Moogle](https://www.moogle.ai/): search tool for Lean
- [LeanSearch](https://leansearch.net/): search tool for Lean
- [LeanCopilot](https://github.com/lean-dojo/LeanCopilot): copilot for Lean
- [LeanStateSearch](https://premise-search.com/): search tool for Lean
- [LeanFinder](https://huggingface.co/spaces/delta-lab-ai/Lean-Finder): search tool for Lean
- [Online Lambdapi search tool](https://lambdapi.saclay.inria.fr/)

**Proof translation tools**

- [Agda2Dedukti](https://github.com/Deducteam/Agda2Dedukti): Agda to Dedukti/Agda or Lambdapi/Agda
- [CoqInE](https://github.com/Deducteam/CoqInE): Coq to Dedukti/Coq
- [Dk2agda](https://github.com/Deducteam/dk2agda): Dedukti to Agda
- [Ekstrakto](https://github.com/Deducteam/ekstrakto): TSTP to TPTP and Lambdapi/FOL (subsumed by GDV-LP)
- [eo2lp](https://github.com/ciaran-matthew-dunne/eo2lp): Eunoia (EO) to LambdaPi (LP)
- [GDV-LP](https://github.com/orgs/TPTPWorld/repositories): TPTP to Lambdapi/FOL ([doc](https://www.tptp.org/Seminars/GDV/GDV-LP.html))
- [Hol2dk](https://github.com/Deducteam/hol2dk): HOL-Light to Dedukti and Lambdapi
- [Holide](https://github.com/Deducteam/Holide): OpenTheory to Dedukti/STTfa
- [HOLLightToDk](https://github.com/Deducteam/HOLLightToDk): HOL-Light to Dedukti/STTfa
- [Krajono](https://github.com/Deducteam/Krajono): Matita to Dedukti/Matita
- [Isabelle\_dedukti](https://github.com/Deducteam/isabelle_dedukti): Isabelle to Dedukti or Lambdapi
- [Logipedia](https://github.com/Deducteam/Logipedia): Dedukti/STTfa to Coq, Lean, Matita, OpenTheory, HOL-Light, PVS
- [Logic embedding tool](https://github.com/leoprover/logic-embedding): Translates non-classical proof obligations into higher-order logic
- [Personoj](https://github.com/Deducteam/personoj): PVS to Lambdapi
- [pp2lp](https://github.com/ciaran-matthew-dunne/pp2lp): Atelier B's Predicate Prover (PP) to LambdaPi (LP). 
- [Skonverto](https://github.com/Deducteam/SKonverto): construct a proof of a formula from a proof of its skolemized version
- [tptp-utils](https://github.com/leoprover/tptp-utils): Translates various TPTP/TSTP formats into each other
- [Universo](https://github.com/Deducteam/universo): type universes rewriting tool
- [SMTCoq](https://smtcoq.github.io/): reconstruct proofs from SMT solvers in Coq
- [CoqHammer](https://coqhammer.github.io/): reconstruct proofs from ATPs in Coq
- [Maude2Lean](https://fadoss.github.io/maude2lean/)
- [Lean2Coq](https://coq.discourse.group/t/alpha-announcement-coq-is-a-lean-typechecker/581): Lean to Coq
- [B-pog-translator](https://github.com/Deducteam/B-pog-translator): translator from Atelier B proof obligation files to Lambdapi
- [Predicativize](https://github.com/Deducteam/predicativize): translate Dedukti proofs to Dedukti proofs with universe polymorphism, and translate them to Agda
- [Lean2dk](https://github.com/Deducteam/lean2dk): Lean4 to Dedukti
- [Carcara-LP](https://github.com/NotBad4U/carcara/tree/lambdapi-translate): Alethe to Lambdapi translator
- [mml2lambdapi](https://github.com/arturkornilowicz/mml2lambdapi.git): translator from Mizar to Lambdapi
- [BEer](https://github.com/VTrelat/BEer): higher-order encoder for Atelier B proof obligations to SMT-LIB
- [Kamelo](https://gitlab.com/semantiko/kamelo): translator from K(ore) to Dedukti
- [MM2DK](https://gitlab.com/semantiko/): translator from Metamath to Dedukti
- [EventB2LP](https://gitlab.irit.fr/evb2lp/evbrodin2lp/evb2lp): translator from EventB to Lambdapi

**AI models for theorem proving**

- [Quill](https://github.com/konstantinosKokos/quill/): neural representation of dependently-typed Agda terms, with an application in premise selection (uses the JSON dataset generated from [agda2train](https://github.com/omelkonian/agda2train))
