---
title: "Dedukti tools developers meeting 2"
layout: single
permalink: /dk-meeting2/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG1/Jan2023/20230129_135357_resized.jpg"/>

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Date:** 27-29 January 2023

Remark: the official dates of the meeting taken into account for reimbursements are from January 27 to January 29. However, since many people will arrive on January 26 and leave on January 30, the program includes two optional work sessions on January 26 afternoon and January 30 morning for the people who will be there.

**Venue:** [Villa Clythia](https://www.caes.cnrs.fr/sejours/la-villa-clythia/), 2754 avenue Henri-Giraud 83600 Fréjus, France

**How to get there?** Villa Clythia is at 3 km from the TGV train station of Saint Raphaël - Valescure, and 60 km from the Nice airport. <!--For instance, there is a direct train from Paris Gare de Lyon on January 26 at 08:18 (arrival at 13:01), and a direct train to Paris Gare de Lyon on January 30 at 15:57 (arrival at 20:42).-->

<!--A shuttle will be organized from/to the train station on October 15 at 15:30, and from the hotel to Remiremont train station on October 19 at 15:00. If you want to take the shuttle, send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)-->

**Programme:** Working alone or in small groups on the development of tools for generating, handling or transforming Dedukti files, taking advantage of the participation of experts on Dedukti or other languages and tools, to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables). See [previous meeting](../dk-meeting1).

**Application procedure:** The number of participants is limited. If you want to participate, check the [eligibility rules](https://europroofnet.github.io/eligibility/) and send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) with the following information and documents:

  * URL of your homepage
  * planned date and time of arrival
  * planned date and time of departure
  * cost of travel in euros with quote (screen capture)
  * work plan: describe what you would like to do to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables)

**Cost:** Participants will have to pay for their travel, bedroom and meals at Villa Clythia. To cover the bedroom and meals, the daily allowance is fixed at 110 euros. See the [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) for more details.

**Participants (15):**

- [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) fixed small bugs and made improvements in [Lambdapi](https://github.com/Deducteam/lambdapi) ([943](https://github.com/Deducteam/lambdapi/pull/943), [944](https://github.com/Deducteam/lambdapi/pull/944), [949](https://github.com/Deducteam/lambdapi/pull/949), [950](https://github.com/Deducteam/lambdapi/pull/950), [952](https://github.com/Deducteam/lambdapi/pull/952), [953](https://github.com/Deducteam/lambdapi/pull/953), [954](https://github.com/Deducteam/lambdapi/pull/954)) and developed a new translator from [HOL-Light](https://www.cl.cam.ac.uk/~jrh13/hol-light/) to Dedukti and Lambdapi based on a fork of HOL-Light: see [dk branch](https://github.com/Deducteam/hol-light/tree/dk).

- [Thiago Felicissimo](http://www.lsv.fr/~felicissimo/): [Agda2Dedukti](https://github.com/Deducteam/Agda2Dedukti), Canonical Dedukti

- Yoan Géran: coherent logic to Dedukti

- [Predrag Janičić](http://poincare.matf.bg.ac.rs/~janicic/): coherent logic and [Larus](https://github.com/janicicpredrag/Larus) to Dedukti

- [Julien Narboux](https://dpt-info.di.unistra.fr/~narboux/) and Predrag Janicic developed with the help of Artur Korniłowicz support for exporting proofs from their coherent logic prover called [Larus](https://github.com/janicicpredrag/Larus) to the proof assistant Mizar. Julien Narboux and Yohan Geran discussed the transformation of proofs into coherent logic form, the generation of tactic based proofs from predicate logic and the integration of the GeoCoq library into Logipedia.

- [Emilie Grienenberger](http://www.lsv.fr/~grienenberger/): [HOLLightToDk](https://github.com/Deducteam/HOLLightToDk)

- [Claudio Sacerdoti Coen](http://www.cs.unibo.it/~sacerdot/): [type classes in Lambdapi](https://github.com/Deducteam/lambdapi/pull/418) using [Elpi](https://github.com/LPCIC/elpi)

- [Enrico Tassi](http://www-sop.inria.fr/members/Enrico.Tassi/): [type classes in Lambdapi](https://github.com/Deducteam/lambdapi/pull/418) using [Elpi](https://github.com/LPCIC/elpi)

- [Amélie Ledein](http://www.lsv.fr/~ledein/)
[K](https://kframework.org/) and [Metamath](https://us.metamath.org/) to Dedukti

- Thomas Traversié worked on the elimination of the user-defined rewriting rules in a Dedukti theory. Such a transformation is done by replacing these rewriting rules with axioms. The main difficulty is to handle the different possible translations of a term, depending on where the rewriting rules are applied. He started to implement this technique.

- [Simon Guilloud](https://people.epfl.ch/simon.guilloud) and Amélie Ledein have implemented Sequent Calculus inside Lambdapi. Simon have explored variants of FOL where conjunctions and disjunctions are represented as lists and the possibility of using Lambdapi's rewrite system to compute partial normal forms of formulas. He also has started a reduction of the Sequent Calculus system to Natural Deduction and lambda calculus (using Curry-Howard).

- Claude Stolze finished implementing a translator from [Atelier B](https://www.atelierb.eu/) proof obligations (in POG format) to Lambdapi. 5387 POG files (5.7 GiB) have been processed and the resulting Lambdapi files have been typechecked successfully. This will be the basis for proving these proof obligations using external tools.

- [Artur Korniłowicz](http://math.uwb.edu.pl/~arturk/): [Mizar](http://mizar.org/) to Dedukti

- Gabriel Hondet: [personoj](https://github.com/Deducteam/personoj) (PVS to Dedukti) and [STTfaxport](https://github.com/Deducteam/sttfaxport) (Dedukti to other provers)

- François Thiré worked on dkcheck, dkmeta, and universo, to make them
robust and easier to interact with (in particular to get a modular
proof exporter of the Isabelle proofs encoded into the STTfa
logic). The main task was to provide users with an API that is safe
and convenient. This work led to a new API which is better (especially
regarding safety) and with less side-effects. This should help the
future developments of interoperability projects using the Dk tools
API. In particular, this should ease the integration with
[STTfaxport](https://github.com/Deducteam/sttfaxport), a tool to
export proofs from the logic STTfa to various proof systems.

**Thursday 26 January (optional, for people who arrives the day before the meeting):**

|14:00-16:00|work session 3|
|16:00-16:15|coffee break|
|16:15-18:15|work session 4|
|18:15-19:30|free time|
|19:30-21:00|dinner|
|21:00-23:00|work session 5 (optional)|

**Friday 27 January:**

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

**Saturday 28 January:**

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

**Sunday 29 January:**

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

**Monday 30 January (optional, for people who leaves after the meeting):**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|

<img src="/_pages/WG1/Jan2023/20230127_164233_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_121027_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_121204_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_121220_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_121227_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_124100_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_124117_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230127_133547_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230128_090818_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230128_090836_resized.jpg"/>
<img src="/_pages/WG1/Jan2023/20230129_135024_resized.jpg"/>
<!--img src="/_pages/WG1/Jan2023/20230126_161449_resized.jpg"/-->
<!--img src="/_pages/WG1/Jan2023/20230126_161524_resized.jpg"/-->
