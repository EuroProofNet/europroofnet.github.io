---
speakerfirst: Anja
speakerlast: Petković Komel
date: 2022-05-20 16:30
endtime: 2022-05-20 17:30
speakeraffiliation: TU Wien
title: The essence of elaboration
---

When using type theories in proof assistants the full syntax can quickly become too verbose to handle. One common solution to this problem is to design two type theories: a fully annotated type theory which has good meta-theoretic properties, is suitable for algorithmic processing and resides in the kernel of the proof assistant, and an economic one for the users' input. The two theories are linked by elaboration, a reconstruction of missing information that happens during, or in parallel with, type-checking.

In this talk we will take a look at the type-theoretic account of an elaboration map: a section of a "forgetful" type-theoretic transformation $r : S \to T$  from the fully annotated type theory S, which we will call standard type theory, to the economic one T, called a finitary type theory. This definition of elaboration map enjoys two important meta-theoretic properties: every finitary type theory has an elaboration map to a standard type theory and it satisfies a universal property, making it unique up-to judgemental equality.
We will also consider algorithmic aspects of elaboration and relate it to type-checking.

This is joint work with Andrej Bauer.
