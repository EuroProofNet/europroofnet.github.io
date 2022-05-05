---
speakerfirst: Kenji
speakerlast: Maillard
date: 2022-05-20 15:00
title: The multiverse — Logical modularity for proof assistants
---

(J.w.w. Nicolas Margulies, Matthieu Sozeau, Nicolas Tabareau and Éric Tanter.)

Proof assistants play a dual role as programming languages and logical systems.
As programming languages, proof assistants offer standard modularity mechanisms
such as first-class functions, type polymorphism and modules. As logical
systems, however, modularity is lacking, and understandably so: incompatible
reasoning principles — such as univalence and uniqueness of identity
proofs — can indirectly lead to logical inconsistency when used in a given
development, even when they appear to be confined to different modules. The lack
of logical modularity in proof assistants also hinders the adoption of richer
programming constructs, such as effects. In this talk, I will describe a general
type-theoretic approach called the multiverse to endow proof assistants with
logical modularity. The multiverse consists of multiple universe hierarchies
that statically describe the reasoning principles and effects available to
define a term at a given type. We identify sufficient conditions for this
structuring to modularly ensure that incompatible principles do not interfere,
and to locally restrict the power of dependent elimination when necessary. This
extensible approach generalizes the ad-hoc treatment of the sort of propositions
in the Coq proof assistant.