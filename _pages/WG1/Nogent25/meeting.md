---
title: "WG1 meeting"
layout: single
permalink: /Nogent25/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG1/Nogent25/IMG_20250211_094409.jpg"/>

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Date:** 11-13 February 2025

**Venue:** <a href="https://www.hotel-beaurivage-nogentsurseine.com/">Hôtel Beau Rivage</a>, 20 rue de Villiers aux Choux 10400 Nogent-sur-Seine, France

**How to get there?** There are direct trains from Paris Gare de l'Est to Nogent-sur-Seine (for instance 09:42-10:38 and 11:42-12:40), and from Nogent-sur-Seine to Paris Gare de l'Est (for instance 14:20-15:16 and 15:20-16:19). The hotel is a 20-minutes walk from the train station.

**Program:** The goal is to discuss logic encodings and proof translation tools, taking advantage of the participation of experts on various languages and tools, to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables).

**Cost:** The cost of accommodation and meals is about 160 euros/day/person. Participants have to make a bank transfer of half of the cost to <a href="https://www.hotel-beaurivage-nogentsurseine.com/">Hôtel Beau Rivage</a> in order to confirm their participation, and send a mail to aubeaurivage@wanadoo.fr and Frédéric Blanqui, with subject "EuroProofNet seminar 10-14 February 2025", to inform us of the bank transfer. The second half will have to be paid at the hotel. It is possible to be reimbursed of the first half if the hotel is informed of the cancellation before January 27.

**Participants (18):** Frédéric Blanqui, Rishikesh Vaishnav, Melanie Taprogge, Théo Winterhalter, Anne Grieu, Alessio Coltellacci, Thomas Traversié, Ciarán Dunne, Claudio Sacerdoti Coen, Gabriel Hondet, Abdelghani Alidra, Jérémy Dubut, Bruno Barras, Michael Färber, Olivier Hermant, Nicolas Margulies, Catherine Dubois, Guillaume Burel

- [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) added new proof tactics in Lambdapi ([1194](https://github.com/Deducteam/lambdapi/pull/1194), [1195](https://github.com/Deducteam/lambdapi/pull/1195)) and, together with Rishikesh Vaishnav, started to translate HOL-Light to Lean, by extending Lambdapi ([1197](https://github.com/Deducteam/lambdapi/pull/1197)) and Hol2dk ([173](https://github.com/Deducteam/hol2dk/pull/173)).
- [Rishikesh Vaishnav](https://lmf.cnrs.fr/Perso/RishVaishnav) finished writing his paper on [Lean4Less](https://github.com/rish987/Lean4Less) and collaborated with Frédéric Blanqui on the translation from HOL-Light to Lean. He also started work on addressing the scaling issues faced by Lean4Less by attempting an alternate translation implementation that uses proof by reflection, rather than explicitly constructed proof terms.
- [Michael Färber](https://gedenkt.at/) gave a talk about [jaq](https://github.com/01mf02/jaq) and [Typst](https://typst.app/). He also worked with Gabriel Hondet on a redesign of the [Pratter](https://forge.tedomum.net/koizel/pratter) API (resulting in version v5.0) and helped with the integration of this new version into Lambdapi ([1196](https://github.com/Deducteam/lambdapi/pull/1196)). Furthermore, he worked on a prototype of XML support for jaq. Finally, he worked together with Nicolas Margulies on a new approach using lambda calculus for [denotational semantics for the jq language](https://github.com/01mf02/jq-lang-spec).
- [Thomas Traversié](https://thomastraversie.github.io/) worked on translation mechanisms to exchange proofs between Dedukti theories, by extending theory morphisms and logical relations from LF to Dedukti. This work will be continued during his STSM hosted by Florian Rabe.
- Melanie Taprogge continued her ongoing work on implementing the Lambdapi output of the HOL ATP Leo-III by evaluating the coverage of the current proof encoding using the TPTP problem library. She then improved and extended the implementation accordingly.
- [Jérémy Dubut](https://jeremydubut.com) worked on the alignement of functions on natural numbers (even, odd, factorial, ...) between HOL light and Coq, as well as on a profiler to check the time required to build each proof in an Isabelle theory.
- [Guillaume Burel](http://web4.ensiie.fr/~guillaume.burel/) discussed with Ciarán Dunne about his embedding of Eunoia in Lambdapi, and more generally about generalization of  set theories. He also updated [lrat2dk](https://github.com/gburel/lrat2dk) to make it compile with recent versions of OCaml, and he began to clean its output to prepare new formats such as Lambdapi or Rocq.
- [Claudio Sacerdoti Coen](https://www.unibo.it/sitoweb/claudio.sacerdoticoen/en) and Abdelghani Alidra worked on indexing and retrieval in heterogenous libraries, focusing on providing a web interface to search for results in the HOL library exported to Lambdapi, up to the alignments in use when exporting the library to Coq.
- [Théo Winterhalter](https://theowinterhalter.github.io/) worked on alignment of concepts between Hol Light and Coq with Alessio Coltellacci ([PR#6](https://github.com/Deducteam/coq-hol-light/pull/6)), and, had discussions with Rishikesh Vaishnav about Lean4Less.
- [Olivier Hermant](https://www.cri.minesparis.psl.eu/~hermant/) worked on different encodings of set theory in Dedukti, by updating a translator from B proof obligations to Why3 and Dedukti.
- Anne Grieu continued her work on the Lambdapi translation of the proofs generated by Rodin/Event-B. In the first step, the B typed set theory defined by J.-R Abrial has been mechanized in Lambdapi on top of the  standard library. Now, the work considers alternatives to big Lambdapi proofs considering for instance reflection principles or deep rewriting mechanisms in Lambdapi.
- [Ciarán Dunne](https://ciaran-matthew-dunne.github.io/) made further progress on his tool for translating the rules of cvc5's proof calculus from Eunoia to Lambdapi. 
- [Catherine Dubois](http://web4.ensiie.fr/~catherine.dubois/) discussed with Anne Grieu the Coq export of EventB proofs and machines translated into Lambdapi or Dedukti. Different ways of aligning set theories were explored. She also studied the translation from EventB to TLA+ recently proposed by Bodeveix and Filali (IRIT, Toulouse).

**Tuesday 11 February:**

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

**Wednesday 12 February:**

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

**Thursday 13 February:**

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


<img src="/_pages/WG1/Nogent25/IMG_20250211_192948.jpg"/>
<img src="/_pages/WG1/Nogent25/IMG_20250211_094446.jpg"/>
<img src="/_pages/WG1/Nogent25/IMG_20250211_094349.jpg"/>
