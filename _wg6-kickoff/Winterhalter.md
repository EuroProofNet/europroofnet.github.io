---
speakerfirst: Théo
speakerlast: Winterhalter
date: 2022-05-21 11:20
speakeraffiliation: Max Planck Institute for Security and Privacy (MPI-SP)
title: "MetaCoq: Sound and complete type checking for Coq, in Coq"
slides: winterhalter-europroofnet-stockholm-slides.pdf
---

Coq is built around a well-delimited kernel that performs type checking for
definitions in a variant of the Calculus of Inductive Constructions
(CIC). Although the meta-theory of CIC is very stable and reliable, the
correctness of its implementation in Coq is less clear. Indeed, implementing
an efficient type checker for CIC is a rather complex task, and many parts of
the code rely on implicit invariants which can easily be broken by further
evolution of the code. Therefore, on average, one critical bug has been found
every year in Coq.

With MetaCoq we offer both a formal specification of the meta-theory of Coq 
(currently excluding η-laws, modules, strict propositions and template 
polymorphism) and  an implementation of a type checker that we prove correct and 
complete with  respect to this specification. In order to do this, we have to 
prove several meta-theoretic properties such as confluence of the reduction or 
subject  reduction, and rely on the axiom of strong normalisation.

I will mostly focus on the type checker and the meta-theory of Coq developed as
part of the MetaCoq project lead by Matthieu Sozeau and including 
Jakob Botsch Nielsen, Simon Boulier, Yannick Forster, Meven Lennon-Bertrand
and Nicolas Tabareau.
