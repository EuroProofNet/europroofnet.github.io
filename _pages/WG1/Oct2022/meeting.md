---
title: "Dedukti tools developers meeting 1"
layout: single
permalink: /dk-meeting1/
author_profile: true
breadcrumbs: true
---

<img src="/_pages/WG1/Oct2022/20221016_162105_resized.jpg"/>

**Date:** 16-18 October 2022

**Venue:** [La Résidence](https://la-residence.com/), 5 rue des Mousses, 88340 Le Val d’Ajol, France

**How to get there?** There are direct trains from Paris to Remiremont train station (East of France). A shuttle will be organized from Remiremont train station and the hotel on October 15 at 15:30, and from the hotel to Remiremont train station on October 19 at 15:00. If you want to take the shuttle, send a mail to [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/).

**Programme:** Working in small groups on the development of tools for generating, handling or transforming Dedukti files.

**Registration:** Deadline: 18 September 2022. The number of participants is limited. If you want to participate, please contact [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/). The cost of accommodation and meals is 134 euros/day/person. EuroProofNet can reimburse a limited number of people only. Check [eligibility rules](https://europroofnet.github.io/eligibility/) and [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) to get more details.

**Organizer:** [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/)

**Participants:**
[Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/),
Michael Färber,
[Jesper Cockx](https://jesper.sikanda.be/),
[Thiago Felicissimo](http://www.lsv.fr/~felicissimo/),
[Predrag Janičić](http://poincare.matf.bg.ac.rs/~janicic/),
[Julien Narboux](https://dpt-info.di.unistra.fr/~narboux/),
Théo Winterhalter,
Claude Stolze,
[Amélie Ledein](http://www.lsv.fr/~ledein/),
François Thiré,
[Bruno Barras](http://www.lix.polytechnique.fr/~barras/),
[Gilles Dowek](http://www.lsv.fr/~dowek/)

<!--
[lambdapi](https://github.com/Deducteam/lambdapi)
[ekstraskto](https://github.com/Deducteam/ekstrakto)
[skonverto](https://github.com/Deducteam/skonverto)
[larus](https://github.com/janicicpredrag/Larus)
[dkcheck](https://github.com/Deducteam/Dedukti)
[universo](https://github.com/Deducteam/universo)
-->

- [Thiago Felicissimo](http://www.lsv.fr/~felicissimo/) worked on improving [agda2dedukti](https://github.com/Deducteam/Agda2Dedukti), with the help of Jesper Cockx. He continued his work on the compilation of pattern-matching to eliminators, and more precisely implemented the generation of the Below construction for datatypes, which is needed to compile recursive calls (see [Jesper's PhD thesis](https://jesper.sikanda.be/files/thesis-final-digital.pdf) for more details). Moreover, thanks to a flag added to Agda by Jesper, the translator can for the first time run on the main branch of Agda, without any special changes needed. Finally, he also worked on solving errors in the translation of the Agda standard library. Thiago and Jesper found a bug in the Agda code which [has been corrected by Jesper](https://github.com/agda/agda/issues/6205). The changes to Agda2Dedukti can be found [here](https://github.com/thiagofelicissimo/Agda2Dedukti/tree/elimPattMatch).

- [Jesper Cockx](https://jesper.sikanda.be/) worked on a prototype [formalization of Canonical Dedukti]((https://gist.github.com/jespercockx/0849d23ace39f8c72059b9ec65fd53cd)) (name subject to change) in [Lambdapi](https://github.com/Deducteam/lambdapi). He added [benchmarking capabilities to Agda's conversion checker]((https://github.com/agda/agda/pull/6199)) in order to get an idea of how often eta-equality is actually used in the standard library. He fixed an internal [error]((https://github.com/agda/agda/issues/6205)) in the Agda API that was causing problems for Agda2Dedukti. He also helped Thiago with his work on Agda2Dedukti, and in particular on translating pattern matching to eliminators.

- [Frédéric Blanqui](https://blanqui.gitlabpages.inria.fr/) merged in the [Lambdapi standard library](https://github.com/fblanqui/lib) the [work](https://github.com/fblanqui/lib/pull/5) of Quentin Buzet on the formalization of the Coq SSReflect libraries [ssrnat](https://github.com/math-comp/math-comp/blob/master/mathcomp/ssreflect/ssrnat.v) on natural numbers and [seq](https://github.com/math-comp/math-comp/blob/master/mathcomp/ssreflect/seq.v) on polymorphic lists. He also merged the formalization of [binary integers](https://github.com/fblanqui/lib/pull/1) of Quentin Garchery, after having removed its dependency to the calculus of constructions: the formalization is now in first-order logic. Frédéric also worked with Julien Narboux and Predrag Janičić on the representation in Lambdapi of the proofs of coherent logic. Finally, he worked on [isabelle_dedukti](https://github.com/Deducteam/isabelle_dedukti) too.

- Théo Winterhalter worked with Jesper Cockx on describing an alternative description of Dedukti inside Lambdapi itself. This work on design was also about understanding both Dedukti and Lambdapi both as tools and theories.

- Michael Färber and François Thiré: definition of a Dedukti standard.

Dedukti is a language which is implemented by three various active tools: Lambdapi: a proof assistant on top of Dedukti implemented in OCaml, Dkcheck: the original checker for Dedukti implemented in OCaml, Kontroli: another type checker for Dedukti implemented in Rust.

Each of those three languages recognizes a common subset of the
language. The purpose of the first version of the standard is to have
a language which is compatible with the three versions.

Taking the interesection of the three languages recognized by those
tools is not enough. The rationale behind this first version of the
design is made so that it is easy to modify the existing tools to make
it compliant with the standard.

The standard specifies both syntactic rules and semantic rules for the
Dedukti language.

This should also help the translation of tools to Dedukti because
targetting the standard will be enough to get programs/proofs that can
be interpreted the the three tools.

**Lunches and dinners**

All meals will be taken at the restaurant of the hôtel except the dinner on Sunday 16 October which will be at the [Restaurant du Sô](https://restaurantduso.fr/), 400 m from the hotel La Résidence.

**Sunday 16 October:**

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

**Monday 17 October:**

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

**Tuesday 18 October:**

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

**Wednesday 19 October:**

|08:00-08:30|breakfast|
|08:30-10:30|work session 1|
|10:30-10:45|coffee break|
|10:45-12:45|work session 2|
|12:45-14:00|lunch|

<img src="/_pages/WG1/Oct2022/20221016_122649_resized.jpg"/>
<img src="/_pages/WG1/Oct2022/20221016_122726_resized.jpg"/>

<img src="/_pages/WG1/Oct2022/20221016_122621_resized.jpg"/>
<img src="/_pages/WG1/Oct2022/20221016_122627_resized.jpg"/>
