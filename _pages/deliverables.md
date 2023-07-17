---
title: "Deliverables"
layout: single
permalink: /deliverables/
author_profile: true
---

**September 2022:**

- Database gathering proofs from the proof systems Coq, HOL-Light and Matita, and their translations.

    * [Logipedia](http://logipedia.inria.fr/)
    * [Nubo](https://github.com/Deducteam/nubo/)

**March 2023:**

- Inventory of automated theorem provers producing proofs, description of proof formats, and inventory of checking tools for these proof formats.

    * [inventory](https://github.com/EuroProofNet/ATP/wiki)

- Comparison of the approaches used in the international Software Verification competition SV-COMP.

- Definition of a mathematical framework for modular reasoning about type theories and their extensions.

**September 2023:**

- Release of software for translating proofs coming from important proof systems based on type theory like Isabelle, Agda, PVS, Lean or Minlog, to Dedukti and back.

    * [hol2dk](https://github.com/Deducteam/hol2dk): HOL-Light to Dedukti, Lambdapi and Coq
    * [lambdapi](https://lambdapi.readthedocs.io/en/latest/options.html#export): Dedukti and Lambdapi to Coq
    * [isabelle_dedukti](https://github.com/Deducteam/isabelle_dedukti): Isabelle to Dedukti and Lambdapi
    * [Personoj](https://github.com/Deducteam/personoj): PVS to Lambdapi
    * [Agda2dedukti](https://github.com/Deducteam/Agda2Dedukti): Agda to Dedukti
    * [Coqine](https://github.com/Deducteam/CoqInE): Coq to Dedukti
    * [Holide](https://github.com/Deducteam/Holide): OpenTheory to Dedukti
    * [HOLLightToDk](https://github.com/Deducteam/HOLLightToDk): HOL-Light to Dedukti via OpenTheory
    * [STTfaXport](https://github.com/Deducteam/sttfaxport): Dedukti/STTfa to Coq, Lean, PVS, Matita, OpenTheory
    * [Krajono](https://github.com/Deducteam/Krajono): Matita to Dedukti
    
- Software prototype for the automated inference of program specifications as logical axioms.

- Tools for managing the dependencies between proofs, and querying and searching the database.

    * [FindFacts](https://search.isabelle.in.tum.de/)
    * [SErAPIS](https://behemoth.cl.cam.ac.uk/search/)
    * [DAMF](https://distributed-assertions.github.io/)
    
**March 2024:**

- Detailed technical report on the evaluation of techniques for learning proof search guidance and premise selection in automated theorem provers.

**January 2025:**

- Software for translating proof formats used by automated theorem provers to Dedukti.

    * [ZenonModulo](https://github.com/Deducteam/zenon_modulo)
    * [ArchSAT](https://github.com/Gbury/archsat)
    * [iProverModulo](https://github.com/gburel/iProverModulo)
    * [Ekstrakto](https://github.com/Deducteam/ekstrakto) TSTP to Lambdapi
    * [Skonverto](https://github.com/Deducteam/SKonverto) deskolemizer

**September 2025:**

- Release of software for translating proofs coming from important proof systems based on set theory like Mizar, Atelier B or TLAPS to Dedukti and back.

- Collection of verification challenges with summary of working recipes for verifying them.

- Technique for syntax-semantics interface for program verification with or without type systems.

- Extension of the database and associated tools to other systems like Agda, Minlog, PVS, Lean, Mizar, Atelier B, TLAPS.

- White paper on including restricted natural language proof formats to existing proof libraries.

- Prototype implementation of the mathematical framework, with basic user interface, user documentation and gallery of examples of type theories.
