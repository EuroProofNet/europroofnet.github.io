---
title: "Inter-WG developers meeting, Le Val d'Ajol, 23-25 April 2024"
layout: single
permalink: /inter-wg-24/
author_profile: true
breadcrumbs: true
---

<!--img src="/_pages/WG1/Val_d_Ajol24/IMG_20240124_144635.jpg"/-->

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Date:** 23-25 April 2024

Remark: the official dates of the meeting taken into account for reimbursements are from April 23 to April 25 (3 days). However, since most people will arrive on April 22 and leave on April 26, the program includes two optional work sessions on April 22 afternoon and April 26 morning for the people who will be there.

**Venue:** [La Résidence](https://la-residence.com/), 5 rue des Mousses, 88340 Le Val d’Ajol, France

**How to get there?** There is a direct train from Paris to Remiremont train station (East of France) on April 22 at 12:22, arrival at 15:09, and a direct train from Remiremont to Paris on April 26 at 15:56, arrival at 18:46. A shuttle will be organized from Remiremont to the hotel on April 22 at 15:10, and from the hotel to Remiremont on April 26 at 15:00.

**Program:** The goal is to discuss encodings, translations and searching tools, as well as library development and management tools, and work alone or in small groups on the development of tools for writing, maintaining, generating, checking, transforming or searching proofs, taking advantage of the participation of experts on various languages and tools, to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables).

**Cost:** The cost of accommodation and meals is about 150 euros/day/person. Participants have to make a bank transfer of half of the cost to La Résidence ([IBAN](https://europroofnet.github.io/_pages/WG1/Jul2023/IBAN-R%C3%A9sidence.png): FR7617206002135619393901050) in order to confirm their participation, and send a mail to contact@la-residence.com and [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/), with subject "EuroProofNet seminar 22-26 April 2024", to inform us of the bank transfer. The second half will have to be paid at the hotel. It is possible to be reimbursed of the first half if the hotel is informed of the cancellation before April 7.

**Funding:** EuroProofNet can reimburse the transport and a daily allowance for the accommodation and meals to a limited number of participants with the following priorities: contribution to EuroProofNet objectives and deliverables, people from COST inclusiveness target countries, young researchers, under-represented genders. Check [eligibility rules](https://europroofnet.github.io/eligibility/) and [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) to get more details.

**Registration and funding application:** If you want to participate, apply to [EuroProofNet](https://e-services.cost.eu/action/CA20111/working-groups/apply) if not already done, and send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with the following information and documents:

  * URL of your homepage
  * planned date and time of arrival
  * planned date and time of departure
  * cost of travel in euros with quote (screen capture)
  * work plan: describe what you would like to do
  * special diet if any

**Participants (10):**

- [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) will work on the translation of HOL-Light proofs to Coq using [hol2dk](https://github.com/Deducteam/hol2dk), and possibly the alignment of the type of real numbers between these two systems.

- [Pascal Fontaine](https://people.montefiore.uliege.be/pfontain/) will work on the modular implementation of SMT, and hope to finalize a working SAT-solver - Theory reasoner interaction.  If times allow, he will adapt the testing infrastructure and design the proof production module of the solver.

- [Stephan Schulz](http://wwwlehre.dhbw-stuttgart.de/~sschulz/DHBW_Stephan_Schulz/Stephan_Schulz.html) plans to improve the TPTP compliance of E, primarily by
adding support for features not yet implemented. If time permits, he will
also  write a full TPTP proof parser for E, or work towards making E proof
objects more detailed and unambiguous.

- Alessio Coltellacci will work translating Alethe proofs from SMT solvers to Lambdapi using [Carcara](https://github.com/ufmg-smite/carcara).

- Abdelghani Alidra plans to work on aligning the code of the Lambdapi Language Server Protocol with the one of [CoqLsp](https://github.com/ejgallego/coq-lsp) and ultimately merge the two tools in a single one that can be used for both languages. This would result in the reduction of the development and maintenance costs and benefit from the latest features of CoqLsp.

- [Rishikesh Vaishnav](https://lmf.cnrs.fr/Perso/RishVaishnav) will work on the representation of Lean proofs in Dedukti using [lean2dk](https://github.com/Deducteam/lean2dk), and especially on turning definitional equalities for proof irrelevance into propositional equalities.

- Nicolas Margulies will work on the encoding of cubical type theory in Dedukti.

- Yoan Géran will work on the generation of Coq proof scripts for coherent logic with [dkpltact](https://gitlab.crans.org/geran/dkpltact).

- Gabriel Hondet will work on fixing problems in the Dedukti type checker [dkcheck](https://github.com/Deducteam/dedukti).

- Michael Färber will work on fixing problems in the Dedukti type checker [kontroli](https://github.com/01mf02/kontroli-rs).

**Monday 22 April (optional, for people arriving the day before the meeting):**

|16:00-16:30|welcome coffee|
|16:30-18:30|work session 4|
|18:30-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Tuesday 23 April:**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|
|14:00-16:00|work session 3|
|16:00-16:15|coffee break|
|16:15-18:15|work session 4|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Wednesday 24 April:**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|
|14:00-16:00|work session 3|
|16:00-16:15|coffee break|
|16:15-18:15|work session 4|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Thursday 25 April:**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|
|14:00-16:00|work session 3|
|16:00-16:15|coffee break|
|16:15-18:15|work session 4|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Friday 26 April (optional, for people leaving after the meeting):**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|

<!--img src="/_pages/WG1/Val_d_Ajol24/IMG_20240123_172836.jpg"/-->
<!--img src="/_pages/WG1/Val_d_Ajol24/IMG_20240123_135333.jpg"/-->
