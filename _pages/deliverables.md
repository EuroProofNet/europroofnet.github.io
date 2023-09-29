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

    * [EuroProofNet Automated Theorem Proving Wiki](https://github.com/EuroProofNet/ATP/wiki)

- Comparison of the approaches used in the international Software Verification competition SV-COMP and other relevant ones.
    * [EuroProofNet Program Verification Wiki](https://github.com/EuroProofNet/ProgramVerification/wiki)
    * Presentation: Beyer, D. [Verification Tools, Exchange Formats, and Combination Approaches](https://europroofnet.github.io/_pages/WG3/Feb2023/Slides/DirkVerification.pdf). Contributed talk in the EuroProofNet - WG3 meeting.
    * Paper: Bhayat, A., Georgiou, P., Eisenhofer, C., Kovács, L., Reger, G. (2022). [Lemmaless Induction in Trace Logic](https://doi.org/10.1007/978-3-031-16681-5_14). In: Buzzard, K., Kutsia, T. (eds) Intelligent Computer Mathematics. CICM 2022. Lecture Notes in Computer Science, vol 13467. Springer, Cham.
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

    * [FindFacts](https://search.isabelle.in.tum.de/): search application to find formal theory content of Isabelle and the AFP
    * [SErAPIS](https://behemoth.cl.cam.ac.uk/search/): search engine for the Isabelle 2021 and Archive of Formal Proofs 2021 libraries
    * [DAMF](https://distributed-assertions.github.io/): Distributed Assertion Management Framework
    * [Lambdapi](https://github.com/Deducteam/lambdapi) >= 2.4.0 includes commands for [indexing](https://lambdapi.readthedocs.io/en/latest/options.html) Dedukti and Lambdapi files, making complex [search queries](https://lambdapi.readthedocs.io/en/latest/query_language.html) and running a [web server](https://lambdapi.readthedocs.io/en/latest/options.html) for making queries on the web
    
**March 2024:**

- Detailed technical report on the evaluation of techniques for learning proof search guidance and premise selection in automated theorem provers.

**January 2025:**

- Software for translating proof formats used by automated theorem provers to Dedukti.

    * [ZenonModulo](https://github.com/Deducteam/zenon_modulo)
    * [ArchSAT](https://github.com/Gbury/archsat)
    * [iProverModulo](https://github.com/gburel/iProverModulo)
    * [Ekstrakto](https://github.com/Deducteam/ekstrakto): TSTP to Lambdapi
    * [Skonverto](https://github.com/Deducteam/SKonverto) deskolemizer
    * [GDV-LP](https://github.com/orgs/TPTPWorld/repositories): TPTP to Lambdapi/FOL ([doc](https://www.tptp.org/Seminars/GDV/GDV-LP.html))

**September 2025:**

- Release of software for translating proofs coming from important proof systems based on set theory like Mizar, Atelier B or TLAPS to Dedukti and back.

    * [B-pog-translator](https://github.com/Deducteam/B-pog-translator): translator from Atelier B proof obligation files to Lambdapi
    
- Collection of verification challenges with summary of working recipes for verifying them.

- Technique for syntax-semantics interface for program verification with or without type systems.

- Extension of the database and associated tools to other systems like Agda, Minlog, PVS, Lean, Mizar, Atelier B, TLAPS.

- White paper on including restricted natural language proof formats to existing proof libraries.

- Prototype implementation of the mathematical framework, with basic user interface, user documentation and gallery of examples of type theories.
