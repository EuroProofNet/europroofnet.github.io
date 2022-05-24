---
speakerfirst: Maximilian
speakerlast: Doré
date: 2022-05-20 14:40
speakeraffiliation: University of Oxford
title: Automating Kan composition
slides: dore-europroofnet-stockholm-slides.pdf
---

Cubical type theory offers a new of conducting topological arguments with its built-in Kan composition. Constructing a cube with Kan composition amounts to constructing a higher cube with appropriate boundaries, which is a very combinatorial task amenable to automation. In this talk I want to discuss recent work on doing this with the well-known algorithmic technique of constraint satisfaction. If we want to construct an n-dimensional cube as the top lid of a (n+1)-dimensional cube, we can solve a constraint satisfaction problem (CSP) with 2n+1 variables, the domains of which are all n-cubes which have a boundary matching with the lid. The constraints represent that the boundaries of all faces of the cube must align with each other. The CSP can be solved efficiently in Haskell by employing monadic constraint solving, which also gives an elegant interface to employ different search strategies. In the future I hope to adapt this approach to all flavours of cubical type theory, to derive more involved arguments solving several mutually dependent goals at once, and to derive counterexamples to errant goals.

A highly experimental implementation of the solver can be found at [https://github.com/maxdore/csolver](https://github.com/maxdore/csolver). Eventual goal is to provide a tactic or internal implementation in Cubical Agda akin to Agsy.
