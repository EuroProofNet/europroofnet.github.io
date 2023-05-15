---
title: "Dedukti tools developers meeting 3"
layout: single
permalink: /dk-meeting3/
author_profile: true
breadcrumbs: true
---

<!--img src="/_pages/WG1/Jan2023/20230129_135357_resized.jpg"/-->
[<img src="/_pages/WG2/May2023/20230512_125001_small.jpg" />](/_pages/WG2/May2023/20230512_125001.jpg)

[<img src="/_pages/WG2/May2023/20230512_125012_small.jpg" />](/_pages/WG2/May2023/20230512_125012.jpg)

## Organization

**Date:** 11-13 May 2023

**Venue:** Liège, Belgium

Thursday 11 May: A4/R30 morning, A4/S100 afternoon 

Entrance through the [Bâtiment central de l'université de Liège](https://goo.gl/maps/S72NG3nxf1YrQmcm8) downtown Liège (See the [pictures](../dk-meeting3-access) of the way, from the entrance).

Friday 12 May: Salle MIPS, Institut Montefiore, Sart Tilman (outside Liège, take bus 48)

Saturday 13 May: A4/S100 (downtown)

**Organizers:** [Alexander Steen](https://www.alexandersteen.de/)
  and [Pascal Fontaine](https://people.montefiore.uliege.be/pfontain/)
  
This is the second EuroProofNet WG2 meeting, which will take the form of a hackathon, from Thursday May 11 morning to Saturday May 13 mid-afternoon.

<!--**How to get there?**-->

<!-- **Application procedure:** The number of participants that can be reimbursed is limited. If you would like to be reimbursed of your travel, check the [eligibility rules](https://europroofnet.github.io/eligibility/) and 
[fill in this form](https://forms.gle/ZoHXRSKdbk8TxXc79). -->

**Cost:** Participants will have to pay for their travel, accommodation and meals. If you are reimbursed by EuroProofNet, note that the daily allowance has been fixed to 160 euros. See the [reimbursement rules](https://europroofnet.github.io/reimbursement-rules/) for more details.

<!--**Participants (15):**-->

## Programme

Working alone or in small groups on the development of tools for automated theorem proving and proofs (in particular Dedukti proofs), taking advantage of the participation of experts on Dedukti, formula and proof exchange standards, and theorem provers and solvers, and to make progress on EuroProofNet [objectives](../objectives) and [deliverables](../deliverables).  See [previous meeting](../dk-meeting3).

| --------------- | ------------------------------------------------------------------------------------ |
| Day 1           | Thursday 11 May |
| --------------- | ------------------------------------------------------------------------------------ |
| 09:00-10:00     | Get together, planning work, scheduling work sessions |
| --------------- | ------------------------------------------------------------------------------------ |
| 10:00-12:00     | Dedukti |
| --------------- | ------------------------------------------------------------------------------------ |
| 12:00-14:00     | Lunch |
| --------------- | ------------------------------------------------------------------------------------ |
| 14:00-17:00     | TPTP and proofs |
| --------------- | ------------------------------------------------------------------------------------ |
| 17:00-18:00     | Working session |
| --------------- | ------------------------------------------------------------------------------------ |
| 19:00-21:00     | Dinner |
| --------------- | ------------------------------------------------------------------------------------ |

| --------------- | ------------------------------------------------------------------------------------ |
| Day 2           | Friday 12 May |
| --------------- | ------------------------------------------------------------------------------------ |
| 09:00-12:00     | SMT and proofs |
| --------------- | ------------------------------------------------------------------------------------ |
| 12:00-14:30     | Lunch |
| --------------- | ------------------------------------------------------------------------------------ |
| 14:30-19:00     | Working session |
| --------------- | ------------------------------------------------------------------------------------ |
| 19:00-21:00     | Dinner |
| --------------- | ------------------------------------------------------------------------------------ |

| --------------- | ------------------------------------------------------------------------------------ |
| Day 3           | Saturday 13 May |
| --------------- | ------------------------------------------------------------------------------------ |
| 09:00-12:00     | Working session |
| --------------- | ------------------------------------------------------------------------------------ |
| 12:00-14:00     | Lunch |
| --------------- | ------------------------------------------------------------------------------------ |
| 14:00-17:00     | Working session |
| --------------- | ------------------------------------------------------------------------------------ |

## Participants

Bruno Andreotti
Frédéric Blanqui
Bernard Boigelot
Guillaume Burel
Roland Coghetto
Alessio Coltellacci
Robin Coutelier
Bruno Dutertre
Mathias Fleury
Pascal Fontaine
Chantal Keller
Anja Petković Komel
Lucas Michel
Tanja Schindler
Stephan Schulz
Hans-Jörg Schurr
Claude Stolze
Martin Suda
Alex Steen
Baptiste Vergain

## Activities

On Thursday May 11 morning, Frederic Blanqui and Guillaume Burel presented Dedukti.  [Frédéric's slide set 1](https://europroofnet.github.io/_pages/WG1/Jun2022/frederic.pdf),
[Frédéric's slide set 2](https://resources.mpi-inf.mpg.de/departments/rg1/conferences/vtsa22/slides/lecture1.pdf),
[Frédéric's slide set 3](https://resources.mpi-inf.mpg.de/departments/rg1/conferences/vtsa22/slides/lecture2.pdf), 
[Guillaume's slides](/_pages/WG2/May2023/slides/Burel.pdf).  Thursday morning has been dedicated to understanding Dedukti, discussing previous works on transforming proofs from automated theorem provers to Dedukti, and details about encoding particular proof steps inside Dedukti.

On Thursday May 11 afternoon, Geoff Sutcliffe presented TPTP, TSTP proofs, and tools to handle outputs from automated theorem provers supporting these languages.  [Geoff's pages](https://tptp.org/Seminars/TPTPWorld/Contents.html).  Thursday afternoon has been dedicated to discussions on how to translate TSTP proofs into Dedukti, the difficulties associated to particular rules used for some solvers, and a road map for efficient and complete understanding of TSTP proofs has been discussed.  The discussion will be continued notably at the [WG2 meeting/TPTP tea party, in July](https://europroofnet.github.io/tptp23-meeting/).

On Friday May 12 morning, Hans-Jörg Schurr presented SMT and the Alethe proof format.  [Hans-Jörg's material](https://homepage.cs.uiowa.edu/~hschrr/alethe.tar.gz)  The discussion took the whole half day, and several points were discussed, notably planned evolution with SMT-LIB 3, aspects of Skolemization, difficulties in extending the format, and issues in proof checking.

Friday May 12 afternoon was dedicated to discussions and works in smaller groups (report below).

On Saturday May 13 morning, Bruno Andreotti presented the Carcara tool for handling SMT Alethe proofs. [Bruno's slides](/_pages/WG2/May2023/slides/Andreotti.pdf).  The remaining of Saturday morning was dedicated to discussions on proof tools and proof elaboration, essentially around SMT.

### Activities in small groups

Saturday May 13 afternoon was dedicated to discussions and works in smaller groups (report below).

Stephan Schulz improved the proof output for a pedagogical tool for propositional logic, and worked on debugging the interaction of higher-order logic and ite in E.

Alexander Steen, Martin Suda and Anja Petković Komel worked with Frederic Blanqui and Guillame Burel to better understand Dedukti and LambdaPi, and get up-to-date with previous attempts at formalizing ATP proofs in Dedukti.  They started working on a concept for a tool that takes TPTP proofs from Vampire and Leo-III, and translates them into a lampdaPi verification file.

Bruno Andreotti, Frédéric Blanqui, Alessio Coltellacci, Pascal Fontaine, and Hans-Jörg Schurr discussed how to implement a translation of Alethe proofs to Dedukti.  Bruno Andreotti did preliminary works on Carcara to support a possible proof translation module.

Pascal Fontaine and Alexander Steen worked on the [inventory of provers, formats, and tools](https://github.com/EuroProofNet/ATP/wiki).  Several people contributed to improve the wiki. 

Claude Stolze worked on the implementation of integers and polynoms on integers in Dedukti.

## Pictures

<img src="/_pages/WG2/May2023/20230512_112102_resized.jpg"/>

<img src="/_pages/WG2/May2023/20230512_112114_resized.jpg"/>

<img src="/_pages/WG2/May2023/20230512_112123_resized.jpg"/>

<img src="/_pages/WG2/May2023/20230512_112217_resized.jpg"/>

<img src="/_pages/WG2/May2023/20230512_112236_resized.jpg"/>
