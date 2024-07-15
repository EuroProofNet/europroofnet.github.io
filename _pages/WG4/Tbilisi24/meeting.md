---
title: "EuroProofNet meeting on proof libraries"
layout: single
permalink: /wg4-tbilisi24/
author_profile: true
breadcrumbs: true
---

**Date:** 13-14 September 2024

**Venue:** [Tbilisi State University, Chavchavadze ave. 1, 0179 Tbilisi, Georgia](https://www.viam.science.tsu.ge/itp2024/venue)

This meeting includes several sessions shared with other co-located events:
- **September 13:**
  - session with the [15th Conference on Interactive Theorem Proving](https://www.viam.science.tsu.ge/itp2024/) (ITP'24)
  - 2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs
- **September 14:**
  - session with the [Coq workshop](https://coq-workshop.gitlab.io/2024/)
  - session with the [Isabelle workshop](https://sketis.net/isabelle/isabelle-workshop-2024)

**2nd Workshop on the development, maintenance, refactoring and search of large libraries of proofs**

- Post-processing Coq Proof Scripts to Make Them More Robust, Titouan Lozac’h and Nicolas Magaud

Proof assistants like Coq are increasingly popular to help mathematicians carry out proofs of the results they conjecture. However, formal proofs remain highly technical and are especially difficult to reuse. In this paper, we present a framework to carry out a posteriori script transformations. These transformations are meant to be applied as an automated post-processing step, once the proof has been completed. We implemented two transformations so far:  the first one takes an arbitrary large proof script and produces an equivalent single-line proof script, which can be executed by Coq in one single step. 
The second example implements the converse operation, fully expanding a proof script into atomic proof steps. Other applications can be envisioned : removing all named hypotheses, increasing automation, removing some pre-defined proof patterns, etc. We apply our tool to various Coq proof scripts, including rather large ones from the GeoCoq library.

- Verifying Nominal Equational Reasoning Modulo Algorithms, Mauricio Ayala-Rincón

The PVS library on nominal equational reasoning includes
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
anti-unification modulo algorithms.

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

<!--Priority will be given to people giving a talk, people living in inclusive target countries (Albania, Armenia, Bosnia and Herzegovina, Bulgaria, Croatia, Cyprus, Czech Republic, Estonia, Georgia, Greece, Hungary, Latvia, Lithuania, Malta, Moldova, Montenegro, North Macedonia, Poland, Portugal, Romania, Serbia, Slovakia, Slovenia, Turkey and Ukraine), young researchers (<= 40) and women.-->

<!--
**Programme:**
-->

**Scientific organizers:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/), [Angeliki Koutsoukou Argyraki](https://www.cl.cam.ac.uk/~ak2110/) and [Claudio Sacerdoti](http://www.cs.unibo.it/~sacerdot/)

**Local organizer:** [Besik Dundua](https://cte.ibsu.edu.ge/en/besik-dundua/)

**Previous workshop:** [1st EuroProofNet Workshop on the development, maintenance, refactoring and search of large libraries of proofs](../wg4-meeting1)
