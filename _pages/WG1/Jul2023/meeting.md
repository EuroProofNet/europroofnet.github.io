---
title: "Inter-WG developers meeting"
layout: single
permalink: /dk-meeting-july2023/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG1/Jul2023/20230726_150641_resized.jpg"/>

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Date:** 25-28 July 2023

**Venue:** [La Résidence](https://la-residence.com/), 5 rue des Mousses, 88340 Le Val d’Ajol, France

**How to get there?** There are direct trains from Paris to Remiremont train station (East of France). A shuttle will be organized from Remiremont train station and the hotel on July 24 at 15:15, and from the hotel to Remiremont train station on July 28 at 15:15. Le Val d'Ajol is also 1h30 away by car from Bâle airport, and 3h by car from Luxembourg, Karlsruhe or Zurich. There are also a few [buses](https://www.fluo.eu/ftp/document/ligne6.pdf) between Remiremont and Val d'Ajol.

**Programme:** Working individually or in small groups on the development of tools to make progress on the [deliverables](../deliverables) consisting of databases or software developments.

**Cost:** The cost of accommodation and meals is 150 euros/day/person. EuroProofNet can reimburse to a limited number of people the transport + a daily allowance for the accommodation and meals for a number of participants with the following priorities: contribution to EuroProofNet objectives and deliverables, people from COST inclusiveness target countries, young researchers, under-represented genders. Check [eligibility rules](https://europroofnet.github.io/eligibility/) and [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) to get more details.

**Registration and funding application:** Deadline: 14 May 2023. The number of participants is limited. If you want to participate, apply to [EuroProofNet](https://e-services.cost.eu/action/CA20111/working-groups/apply) if not already done, and fill in the following [application form](https://forms.gle/xXNP9jneVwhTTFNW6). Applicants will be notified by May 18. Accepted participants will then have to make a bank transfer of half of the cost to La Résidence ([IBAN](./IBAN-Résidence.png): FR7617206002135619393901050) in order to confirm their participation. In case of cancellation before July 21, they will be reimbursed. The second half will have to paid at the hotel.

**Participants:**

* [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) fixed [ZenonModulo](https://github.com/Deducteam/zenon_modulo) to generate proofs where the negated conjecture is taken as hypothesis instead of as axiom, and improved the translation [hol2dk](https://github.com/Deducteam/hol2dk) from HOL-Light to Coq.

* [Jesper Cockx](https://jesper.sikanda.be/) worked on refactoring a library for well-scoped syntax representations in Agda (https://github.com/jespercockx/agda-core/blob/main/Scope.agda). This is intended to be used in the Agda Core project to specify the typing rules of a core language for Agda in Agda, which will improve interoperability between Agda and other languages.

* [Amélie Ledein](https://lmf.cnrs.fr/Perso/AmelieLedein)

* [Gilles Dowek](http://www.lsv.fr/~dowek/) presented his work on deskolemization ([slides](http://www.lsv.fr/~dowek/Slides/skolem.pdf), [paper](https://arxiv.org/abs/2305.10016)) and has discussed with several members of the meeting about the implementation of a deskolemization algorithm.

* [Rishikesh Vaishnav](https://github.com/rish987/) worked on his [Lean2Dk implementation](https://github.com/rish987/lean2dk) for translating Lean into Dedukti, and made progress on the Pure Type System -> lambda-Pi-calculus modulo embedding.

* [Claudio Sacerdoti](https://www.unibo.it/sitoweb/claudio.sacerdoticoen) worked on implementing a search engine for LambdaPI. He completed the implementation started during the last WP meeting and he added a web interface.

* Alessio Coltellacci

* Pascal Fontaine

* [Stephan Schulz](https://wwwlehre.dhbw-stuttgart.de/~sschulz/)
  improved the TPTP proof output of the ATP PyRes to match inout
  expected by several TPTP processing tools. He also modified the
  prover E to provide additional explicit type information in TFF/THF
  proofs, that, while not required by the TPTP standard, is expected
  by some tools, and performed further work on E.

* Geoff Sutcliffe

* Simon Guilloud

* [David Delahaye](https://www.lirmm.fr/~delahaye/) has tested the latest version of [Zenon Modulo](https://github.com/Deducteam/zenon_modulo) (development version) on the [BWare project](http://bware.lri.fr/) benchmark. The results showed (with a low timeout of 3s) that we obtained similar results (10,459 proofs obtained over 12,828 problems) to the version of Zenon Modulo used in the BWare project (in 2016). David Delahaye also worked on the Lambdapi output for the [Goéland](https://github.com/GoelandProver/Goeland/) automated deduction tool (based on tableaux and the use of concurrency).

* Isaac Lluís worked with David Delahaye and Olivier Hermant to test [ZenonModulo](https://github.com/Deducteam/zenon_modulo) on a few thousand problems to see if it needed updating. He also worked on the LambdaPi output for the concurrent theorem prover [Goéland](https://github.com/GoelandProver/Goeland), taking advantage of the presence of the Deducteam.

* [Olivier Hermant](https://www.cri.minesparis.psl.eu/people/hermant/) worked on the lambdapi output of the automated theorem provers Zenon Modulo and Goéland, and on the implementation of an algorithm to change numeric base, on which he gave a short presentation.
  
* Wojciech Loboda worked on the definition and the implementation of an algorithm to change numeric base, after an article of Jean-Paul Delahaye published in [Pour la Science No 519](https://www.pourlascience.fr/sr/logique-calcul/changer-de-numeration-avec-le-systeme-esperluette-20629.php)

**Monday 24 July:** (for those arriving on July 24)

|15:15-15:45|shuttle|
|15:45-16:00|check-in|
|16:00-16:15|coffee break|
|16:15-18:15|work session 1|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 2 (optional)|

**Tuesday 25 July:**

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

**Wednesday 26 July:**

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

**Thursday 27 July:**

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

**Friday 28 July:**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|check out & coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|
|14:00-15:00|free time|
|15:00-15:45|shuttle|

<img src="/_pages/WG1/Jul2023/20230727_113125_resized.jpg"/>
<img src="/_pages/WG1/Jul2023/20230727_093108_resized.jpg"/>
<img src="/_pages/WG1/Jul2023/20230727_093043_resized.jpg"/>
<img src="/_pages/WG1/Jul2023/20230727_093153_resized.jpg"/>
<img src="/_pages/WG1/Jul2023/20230727_093100_resized.jpg"/>
