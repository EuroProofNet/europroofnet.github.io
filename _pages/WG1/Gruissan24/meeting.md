---
title: "Meeting on Dedukti and proof systems interoperability in Gruissan in January 2024"
layout: single
permalink: /wg1-gruissan24/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG1/Gruissan24/IMG_20240124_144635.jpg"/>

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Date:** 23-25 January 2024

Remark: the official dates of the meeting taken into account for reimbursements are from January 23 to January 25 (3 days). However, since most people will arrive on January 22 and leave on January 26, the program includes two optional work sessions on January 22 afternoon and January 26 morning for the people who will be there.

**Venue:** [Hotel Phoebus](https://hotels-gruissan.com/), Boulevard de Planasse 11430 Gruissan, France

**How to get there?** Hotel Phoebus is 26 minutes away by bus from
Narbonne train station, and 2h10 by public transport from Montpellier
airport MPL. There are many direct trains from Paris Gare de Lyon to
Narbonne: 08:26-12:46, 09:42-14:24, 11:46-16:13, 14:56-19:20,
16:56-21:20, 17:42-22:20. If many people arrive at the same time, we
may organize a private shuttle.

<!--A shuttle will be organized from/to the train station on October 15 at 15:30, and from the hotel to Remiremont train station on October 19 at 15:00. If you want to take the shuttle, send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)-->

**Program:** Discussing the encoding in Dedukti of logical features (universe polymorphism with impredicativity, type classes, etc.), working alone or in small groups on the development of tools for generating, handling or transforming Dedukti files, taking advantage of the participation of experts on Dedukti or other languages and tools, working on the translation of proofs from one system to another system, to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables).

**Application procedure:** The number of participants is limited. If you want to be funded, check the [eligibility rules](https://europroofnet.github.io/eligibility/) and send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with the following information and documents:

  * URL of your homepage
  * planned date and time of arrival
  * planned date and time of departure
  * cost of travel in euros with quote (screen capture)
  * work plan: describe what you would like to do

**Cost:** Participants have to organize their travel by themselves. For accommodation and meals, they will have to pay to the hotel 30% in advance (that can be reimbursed in case of cancellation before January 14) and the remaining on site. See the [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) for more details. The daily allowance is fixed at 120 euros.

**Participants (13):**

- [Rishikesh Vaishnav](https://lmf.cnrs.fr/Perso/RishVaishnav) Rish made progress with his translation project from Lean to Dedukti ([lean2dk](https://github.com/Deducteam/lean2dk)). He began by translating the prelude file of Lean standard library, and discovered the need for a reduction rule for subsingleton inductives that is not well-typed and requires further investigation. He then proceeded to debug and eliminate sources of non-left-linearity in his translation.

- Bruno Barras, [Thiago Felicissimo](http://www.lsv.fr/~felicissimo/) and [Théo Winterhalter](https://theowinterhalter.github.io/) worked on a new formalism to extend Dedukti and Lambdapi with user-defined equational theories. The idea would be to cover theories such as those of universes (with max, 0 and successor) or interval variables in Cubical Type Theory. One of the biggest challenges seems to be the interaction between these new symbols that are identified up to theory and higher-order terms which may feature rewrite rules. We have thought of several criteria so that the resulting type theory remains well behaved, but more investigation needs to be done before we are ready to experiment with an implementation.

- [Thomas Traversié](https://thomastraversie.github.io/) worked on the transformation of higher-order classical proofs into intuitionistic proofs, and improved the [implementation](https://github.com/thomastraversie/Construkti) of this transformation on Dedukti and Lambdapi proofs. To test it, he worked on Frédéric Blanqui's translator of HOL-Light proofs, so that it outputs proofs with explicit natural deduction rules.

- [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) worked on adding sharing in the Lambdapi output of [hol2dk](https://github.com/Deducteam/hol2dk/) ([PR88](https://github.com/Deducteam/hol2dk/pull/88)), fixed some bugs in hol2dk ([PR89](https://github.com/Deducteam/hol2dk/pull/89)), provided explanations about Lambdapi and hol2dk, and discussed the certification of SMT proofs with Alessio and of LEO-III proofs with Melanie.

- [Thiago Felicissimo](http://www.lsv.fr/~felicissimo/) <!--will work on CompLF.-->

- Abdelghani Alidra: Documenting the installation process of Dedukti and Lambdapi. Hands-on learning of the Lambdapi syntax and supportive theory. Discussing bugs and future evolutions of the Lambdapi Vscode plugin.

- Gabriel Hondet will work on Lambdapi and [STTfaxport](https://github.com/Deducteam/sttfaxport).

- Alessio Coltellacci with work on the encoding of Alethe proofs from SMT solvers to Lambdapi.

- [Nicolas Magaud](https://dpt-info.u-strasbg.fr/~magaud/) will investigate how to use the Dedukti/Lambdapi toolchain to transform the Isabelle/HOL formal description of Faradžev-Read algorithm into an equivalent formal description in Coq.

- [Claudio Sacerdoti Coen](http://www.cs.unibo.it/~sacerdot/) plans to work on importing/exporting from Matita to Dedukti and developing a type checker for
Dedukti written in Rust using term graphs.

- Melanie Taprogge discussed the encoding of higher-order logic, simplification and inference rules in Lambdapi with Frédéric and Alessio, gained a deeper understanding of Lambdapi, experimented with the translation of proofs generated by the higher-order logic ATP Leo-III in preparation for a planned automated translation.

- [Bruno Barras](http://www.lsv.fr/~barras/) plans to work on Lambdapi (reduction engine, use of de Bruijn indices).

- [Filip Maric](http://www.matf.bg.ac.rs/~filip) will work on using Dedukti/Lambdapi (esp. isabelle_dedukti) to translate a whole Isabelle/HOL development into a similar one in Coq.

**Monday 22 January (optional, for people arriving the day before the meeting):**

|14:00-16:00|work session 3|
|16:00-16:15|coffee break|
|16:15-18:15|work session 4|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Tuesday 23 January:**

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

**Wednesday 24 January:**

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

**Thursday 25 January:**

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

**Friday 26 January (optional, for people leaving after the meeting):**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|

<img src="/_pages/WG1/Gruissan24/IMG_20240123_172836.jpg"/>
<img src="/_pages/WG1/Gruissan24/IMG_20240123_135333.jpg"/>
