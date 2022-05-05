---
speakerfirst: Andrej
speakerlast: Bauer
date: 2022-05-20 13:40
speakeraffiliation: University of Ljubljana
title: One syntax to rule them all
---

The raw syntax of a type theory, or more generally of a formal system with binding constructs, involves not only free and bound variables, but also meta-variables, which feature in inference rules. Each notion of variable has an associated notion of substitution. A syntactic translation from one type theory to another brings in one more level of substitutions, this time mapping type-theoretic constructors to terms. Working with three levels of substitution, each depending on the previous one, is cumbersome and repetitive. One gets the feeling that there should be a better way to deal with syntax.

In this talk I will present a relative monad capturing higher-rank syntax which takes care of all notions of substitution and binding-preserving syntactic transformations in one fell swoop. The categorical structure of the monad corresponds precisely to the desirable syntactic properties of binding and substitution. Special cases of syntax, such as ordinary first-order variables, or second-order syntax with variables and meta-variables, are obtained easily by precomposition of the relative monad with a suitable inclusion of restricted variable contexts into the general ones. The meta-theoretic properties of syntax transfer along the inclusion.

The relative monad is sufficiently expressive to give a notion of intrinsic syntax for simply typed theories. It remains to be seen how one could refine the monad to account for intrinsic syntax of dependent type theories.

This is joint work with Danel Ahman from the University of Ljubljana.
