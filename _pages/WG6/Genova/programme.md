---
title: "WG6 meeting in Genoa in April 2025"
layout: single
permalink: /wg6-genoa/programme/
author_profile: true
breadcrumbs: true
---

### Programme {#schedule}

| | Thu 17 | Fri 18 |
|:---:|:---:|:---:|
| 08:50-09:05 | registration | - |
| 09:05-09:30 | [Altenkirch](#taltenkirch) | - |
| 09:30-09:55 | [De Pascalis](#mdepascalis) | [Winterhalter](#twinterhalter) |
| 09:55-10:20 | [Damato](#sdamato) | [Bouverot-Dupuis](#mbouverot) |
| 10:20-11:00 | _break_ | _break_ |
| 11:00-11:50 | [Lamiaux](#tlamiaux) | [North](#prnorth) |
| 11:50-12:00 | _break_ | _break_ |
| 12:00-12:25 | [Cioffo](#ccioffo) | [Giusto](#agiusto) |
| 12:25-12:50 | [Spadetto](#mspadetto) | [Najmaei](#nnajmaei) |
| 12:50-14:20 | _lunch_ | _lunch_ |
| 14:20-15:10 | [Gavazzo](#fgavazzo) | [Kovács](#akovacs) |
| 15:10-15:20 | _break_ | _break_ |
| 15:20-15:45 | [Doré](#mdore) | [Neumann](#jneumann) |
| 15:45-16:10 | [Perticone](#lperticone) | [Petrakis](#ipetrakis) |
| 16:10-16:40 | _break_ | _break_ |
| 16:40-17:05 | [Laretto](#alaretto) | [Sabelli](#psabelli) |
| 17:05-17:30 | [Ranalter](#dranalter) | [Novotny](#snovotny) |
| 19:00- | [Dinner](/wg6-genoa/local-info#dinner) |  |



### Invited talks


###### Francesco Gavazzo: A Mathematical Theory of Term Relations {#fgavazzo}

Syntactic methods play a central role in many fields of Logic and Theoretical Computer Science, including type theory, programming language semantics, proof theory and its computational interpretations, algebra, and rewriting systems. These methods characterise various behaviours resting solely on syntax, thereby avoiding the (notoriously difficult) introduction of `extra-linguistic' semantic objects such as term meanings. Unfortunately, their inherent syntax-dependence prevents syntactic methods to scale from a collection of application-specific methodologies to a an abstract mathematical theory readily  applicable across diverse logical and computational formalisms: how frequently must critical properties—such as confluence, termination, type safety, cut-elimination, congruence, and compositionality—be proven anew?

A recurring concept within syntactic methodologies is that of a *term relation*, a relation, broadly intended, between syntactic terms (programs, proofs, types, agents, formulas, etc.): examples of term relations include rewriting and conversion, program equivalences and metrics, bisimulation, logical relations, and type elaboration. However, despite their pervasiveness, term relations have rarely been studied systematically, and never as an abstract and (language-)independent mathematical object.

In this talk, we present the foundations for a general mathematical theory of term relations. We begin by illustrating how term relations emerge naturally as a relational counterpart to the categorical theory of syntax interpretation, as exemplified by the initial algebra semantics paradigm. We then explore the algebraic structure inherent in the space of term relations, revealing how this structure underpins a synthetic theory that abstracts away from specific  syntax structures. Accordingly, we axiomatically define term relations through suitable extensions of relation algebras, dubbed *Term Relation Algebras* (TRAs).

Remarkably, TRAs allow numerous operational and syntactic properties to be proven abstractly, independent of specific languages or syntactic notions, transforming typically cumbersome and error-prone syntactic proofs into concise algebraic calculations. Among those results, we will mention confluence theorems (e.g. Tait and Martin-Löf confluence techniques), theories of program dynamics, and congruence results for various notions of program equivalence (e.g. applicative bisimilarity).

###### András Kovács: A generalized logical framework {#akovacs}

Logical frameworks and the closely related two-level type theories let us work in a mixed syntax of a metatheory and a chosen object theory. Here, we have a second-order view on the object theory, where contexts, variables and substitutions are implicit, and binders are represented as meta-level functions. We generalize this to a setup where we can work with multiple models of multiple object theories at the same time, and we can also switch between "external" first-order views and "internal" second-order views of the same model. An important feature of the framework is that it's fully structural as a type theory; in particular it does not have any modalities. The main semantic idea is to have a universe hierarchy of "iterated internal presheaves". In the empty context, we have PSh 1 as the universe of presheaves over 1, i.e. sets. Internally to PSh 1, we can define a category C, from which we can obtain a universe of presheaves over C. In this universe, we can define another category D and get a universe of internal presheaves over D, and so on.

###### Thomas Lamiaux: A unified Framework for Initial Semantics, and it is 2 functorial {#tlamiaux}

We focus on the initial semantics aiming to model the syntax and substitution structure of programming languages with variable binding as initial objects. Three distinct yet similar approaches to initial semantics have been proposed. An initial semantics result was first proved by Fiore, Plotkin, and Turi using {\Sigma}-monoids in their seminal paper published at LICS'99. Alternative frameworks were later introduced by Hirschowitz and Maggesi using modules over monads, and by Matthes and Uustalu using heterogeneous substitution systems. Since then, all approaches have been significantly developed by numerous researchers. While similar, the links between this different approaches remain unclear. This is especially the case as the literature is difficult to access, since it was mostly published in (short) conference papers without proofs, and contains many technical variations and evolutions.
In [A Unified Framework for Initial Semantics](https://urlsand.esvalabs.com/?u=https%3A%2F%2Farxiv.org%2Fabs%2F2502.10811&e=ed7a584b&h=456504aa&f=y&p=y), we introduce a framework based on monoidal categories that unifies these three distinct approaches to initial semantics, by suitably generalizing and combining them. Doing so we show that modules over monoids provide an abstract and easy to manipulate framework, that {\Sigma}-monoids and strengths naturally arise when stating and proving an initiality theorem, and that heterogeneous substitution systems enable us to prove the initiality theorem modularly. Moreover, to clarify the literature, we provide an extensive related work.
In this talk, we will give an account of this work, introducing the different concepts with examples and explaining how they assemble. Doing so, we hope to make it more accessible to newcommers to the field. If times permits, we will also discussed more recent work where we show that models can be computed by a 2-functor, and how it can be used to further relate different instantiations and design generalized recursion principles for typed languages.

###### Paige Randall North: Comparing semantic frameworks for dependently-sorted algebraic theories {#prnorth}

Algebraic theories with dependency between sorts form the structural core of Martin-Löf type theory and similar systems. Their denotational semantics are typically studied using categorical structures such as contextual categories, categories with families, display map categories, comprehension categories, and many others. While comparisons between specific models appear in the literature, a unified analysis of this zoo of categorical structures has been lacking.

In this talk, I will describe our work in which we aim to give a clear 2-categorical analysis of this zoo. We use comprehension categories as a unifying language. We show that almost all established notions embed as sub-2-categories (usually full) of the 2-category of comprehension categories. The frameworks naturally divide into two groups: those representing types as certain (display) maps, and those treating types as primitive. We give 2-functors between all notions and describe when they are adjunctions and when they are equivalences. The analyses that we give are often well-known or folklore, or only discussed in the literature at a 1-categorical level (which we see as inadequate for certain purposes). This work aims to give a clear reference point for the organization of this zoo of categorical structures.

This is joint work with Benedikt Ahrens and Peter LeFanu Lumsdaine ([arXiv:2412.19946](https://arxiv.org/abs/2412.19946)).



### Contributed talks

###### Thorsten Altenkirch: Containers in Higher Kinds {#taltenkirch}

Joint work with Zhili Tian (University of Nottingham).

Strictly positive types can be represented as containers, and every container has an initial algebra - W-type, and a terminal coalgebra - M-type. In particular, containers give rise to functors of such algebras. However, there are types which don't fit into this scheme. An example is the coinductive type Bush, where it has a head of type X and tail being Bush of Bush of X. Hence we want to define a notion of containers in higher kinds which model strictly positive functors like the functor giving rise to Bush, which has type (Set → Set) → (Set → Set)

We define a notion of higher-kinded container HCont over a given kind Ty, where Ty are just the types of simply typed λ-calculus with one base type. Technique and definition of hereditary substitution such as de Bruijn indexing and normal form are borrowed in order to implement the intended model. We also give the semantics by interpreting HCont to a higher-kinded functors.

We would like to show: that higher containers give rise to higher hereditary functors; that higher containers for a model of simply typed λ-calculus; provide a notion of higher container morphisms which are complete; construct initial algebras and terminal coalgebras of endo-containers,

This development is based on discussions with Håkon Gylterud.


###### Mathis Bouverot-Dupuis: Code Generation via Meta-programming in Dependently Typed Proof Assistants {#mbouverot}

Dependently typed proof assistants offer powerful meta-programming features, which users can take advantage of to implement proof automation or compile-time code generation. This talk surveys meta-programming frameworks in Rocq, Agda, and Lean, with seven implementations of a running example: deriving instances for the Functor type class. This example is fairly simple, but sufficiently realistic to highlight recurring difficulties with meta-programming: conceptual limitations of frameworks such as term representation – and in particular binder representation –, meta-language expressiveness, and verifiability as well as current limitations such as API completeness, learning curve, and prover state management, which could in principle be remedied. We will conclude with insights regarding features an ideal meta-programming framework should provide.

This is joint work with Yannick Forster.


###### Cipriano Junior Cioffo: A categorical account of the setoid model {#ccioffo}

Setoids play a fundamental role in the interplay between intensional and extensional type theories and in the computer-formalization of mathematical proofs.

In particular, they are key to bridging the two levels of the Minimalist Foundation (MF), a common-core foundation for mathematics introduced by Maietti and Sambin in 2005 and completed by Maietti in 2009. The Minimalist Foundation consists of two type theories, an extensional one and an intensional one, and an interpretation of the former within a setoid model built over the latter.

A basic categorical analysis of the setoids construction is achieved through what are called quotient completions, constructions that freely add quotients to an appropriate category. Notably, the elementary quotient completion introduced by Maietti and Rosolini (2013) is defined for Lawvere's elementary doctrines, which correspond to suitable faithful fibrations. This construction generalizes the exact completion on a category with weak finite limits of Carboni-Celia Magno (1982) and Carboni-Vitale (1998).

In this talk, we present a fibred categorical description of setoids in dependent type theory through an appropriate category of truncated Kan objects, i.e., simplicial objects with a groupoidal structure. Indeed, a setoid may be seen as a proof-relevant groupoid, meaning that unital and associativity laws are considered valid up to higher coherence conditions. This description is particularly useful because it, in turn, allows for the characterization of dependent setoids—used in the setoid model to interpret dependent types—through the well-known notion of an action on a Grothendieck fibration.

Our main goal is to provide a a fibred version of the elementary quotient completion as a step towards a complete algebrization of  the setoid model of MF in Maietti (2009).

More in detail, starting from a comprehension category playing the role of an intensional type theory, it is possible to construct another comprehension category of dependent setoids corresponding to an extensional type theory freely generated from the starting one.

Examples of the above construction include the fibered structure of the predicative Effective Topos introduced by Maietti and Maschio (2021) presented in preprint "Fibred sets within a predicative and constructive effective topos" (arXiv:2411.19239).

This is a joint work with Maria Emilia Maietti, Samuele Maschio, and Pietro Sabelli.


###### Stefania Damato: Distributive Laws for Monadic Containers {#sdamato}

Monads have received a lot of attention in functional programming and denotational semantics for their ability to model a wide range of programmatic side-effects. Combining several side-effects together can be modelled by monad composition, but in general, given two monads, the composite of their underlying functors does not admit a monad structure. Distributive laws were introduced by Beck as a sufficient condition for such a composition to form a monad, thereby ensuring that the corresponding side-effects are combined in a coherent way. However, constructing distributive laws is known to be quite difficult due to the complexities involved in checking their axioms. As a result, various work has been done on different approaches for constructing distributive laws, and for identifying cases where there are none (so-called 'no-go theorems').

Our specific focus will be on monadic containers, which are containers whose interpretation as a Set functor carries a monad structure. We develop a characterisation of distributive laws for monadic containers, providing an algebraic way of reasoning about distributive laws between strictly positive data types. This parallels Ahman and Uustalu's characterisation of distributive laws for containers whose Set functor interpretation carries a _comonad_ structure, which they call directed containers. Furthermore, by combining our work with theirs, we construct characterisations of mixed distributive laws (i.e. of directed containers over monadic containers and vice versa), thereby completing the 'zoo' of distributive laws from a container perspective.

All of the distributive law characterisations have been formalised in Cubical Agda, due to its treatment of dependent equalities and some of its extensionality properties. We have also formalised various monadic container examples, as well as some distributive law uniqueness proofs.

This talk is based on joint work with Chris Purdy.


###### Michele De Pascalis: Monoid Structures on Indexed Containers {#mdepascalis}

Containers represent a wide class of type constructions, which are relevant to functional programming and (co)inductive reasoning. Indexed containers generalize this notion to better fit the scope of dependently typed programming. When interpreting types to be sets, a container describes an endofunctor on the category of sets while an I-indexed container describes an endofunctor on the category Set^I of I-indexed families of sets.

We consider a monoidal structure on the category of I-indexed containers such that the tensor product of containers describes the composition of the respective induced endofunctors. We then give a combinatorial characterization of monoids in this monoidal category, and we show how these monoids correspond precisely to monads on the induced endofunctors on Set^I. Lastly, we conclude by presenting some examples of monads on Set^I that fall under our characterization, including the product of two monads, a variants of the state and writer monads and an example of a free monad. The technical results of this work are accompanied by a formalization in the proof assistant Cubical Agda.


###### Maximilian Doré: Linear Types with Dynamic Multiplicities in Dependent Type Theory {#mdore}

We construct a linear type system inside dependent type theory. For this, we equip the output type of a program with a bag containing copies of each of the input variables. We call the number of copies of an input variable its multiplicity. We then characterise a dependent type which ensures that a program uses exactly the given multiplicity of each input variable. We can program in the resulting system in a practical way, and construct standard programs on lists such as folds, unfolds and sorting algorithms. Since our linear type system
is constructed internally to a functional language, we can moreover dynamically compute multiplicities, which allows us to capture that a program uses a varying number of copies of some input depending on the other inputs. We can thereby give precise types to many functional programs that cannot be typed in systems with static multiplicities.


###### Andrea Giusto: Fibrations with comprehension and their completion {#agiusto}

One of the distinctive features of dependent type theories is the possibility of extending a context with a type in that context. This operation has been studied using categorical tools, mainly describing it as additional structure over (Grothendieck) fibrations. In particular, Jacobs' comprehension categories represent a general framework where one can model dependent type theories: the extension of contexts is given by the comprehension functor. A particular case is obtained by considering fibrations with Lawvere comprehension (a.k.a. Ehrhard's D-categories), which have some additional structure.

In this talk we will describe a universal construction that freely adds the comprehension structure to an arbitrary fibration. In the last part we will also briefly study the relation between the two notions of comprehension named above.

This is joint work with Francesco Dagnino (DIBRIS, UniGe) and Jacopo Emmenegger (DIMA, UniGe).


###### Andrea Laretto: Directed First-Order Logic {#alaretto}

We present syntax and semantics for a proof-irrelevant first-order directed type theory equipped with a "asymmetric" directed notion of propositional equality (which can be thought of as transitions/rewrites between terms), where the main semantics interprets types as preorders. We then provide a universal property to such "directed equalities" by describing introduction and elimination rules that allows them to be contracted only with certain syntactic restrictions, based on polarity, which do not allow for symmetry to be derived. We give a characterization of such directed equality as a relative left adjoint, generalizing the idea by Lawvere of equality as left adjoint. The logic is equipped with a precise syntactic system of polarities, inspired by dinaturality, that keeps track of the occurrence of variables (positive/negative/both). The semantics of this logic and its system of variances is then captured categorically using the notion of directed doctrine, which we prove sound and complete with respect to the syntax.


###### Niyousha Najmaei: Syntax for non-full comprehension categories {#nnajmaei}

Comprehension categories provide a powerful framework for the semantic interpretation of dependent type theory and calculus of constructions.
To simplify the specification of interpretations, a comprehension category is commonly assumed to be full. Intuitively, the fullness condition states that all context morphisms are obtained from term morphisms.

However, there are multiple reasons for which it might be desirable to avoid a fullness condition.
Firstly, some important comprehension categories are not full; we would still like to interpret (a version of) type theory in such structures.
Secondly, Coraglia and Emmenegger recently sketched fragments of a syntax for dependent type theory with coercive subtyping, and an interpretation of such syntax in (a structure equivalent to) non-full comprehension categories.
In this interpretation, the added flexibility provided by the lack of fullness is crucial.

In the present work, we develop a dependently-typed syntax with an interpretation in non-full comprehension categories.
In detail, we develop two different possible semantic structures, on top of non-full comprehension categories, for the interpretation of the type and term formers of dependent type theories in non-full comprehension categories.
For both approaches, we specify a suitable syntax with a sound interpretation in the respective semantic structure.
One of the approaches yields a more comprehensive account of Coraglia and Emmenegger's syntax and semantics for dependent type theory with coercive subtyping.

Joint work with Benedikt Ahrens, Paige Randall North, Niels van der Weide


###### Jacob Neumann: GATs, Cats, and CwFs: A Celestial Dance {#jneumann}

A peculiar feature of category theory is that the collection of all categories is itself a category, and thus the constructions and definitions one makes within a category can be considered in the case where categories themselves are the objects. This capacity for self-reference gets magnified and intensified when combined with two other areas of study which manage to 'apply to themselves': the discipline of generalised algebraic theories (GATs) and the semantics of type theory--especially when presented in the form of categories with families (CwFs).

In this talk, I'll attempt to document the elaborate (and, at times, dizzying) interplay between these three topics. Some points of consideration include the following.
- Every GAT gives rise to a category of algebras and algebra homomorphisms, which, moreover, always comes equipped with an initial object.
- CwFs can be presented as a GAT, whose initial algebra is the syntax model. So we can modularly study type theories by extending the GAT of CwFs, and always obtain an initial syntax model.
- There is a universal GAT, an extension of the GAT of CwFs, whose syntax model is a signature language characterising all GATs. We can use this to make (quotient inductive-)inductive definitions across all GATs.
- In particular, we can define the notions of displayed algebra and section of an arbitrary GAT, which turns the category of algebras into a CwF of algebras.
- Categories can also be presented as a GAT, so we may consider the CwF whose contexts are categories, types are displayed categories, etc. We can restrict this CwF to a fibrant sub-CwF, the category model, which interprets a directed type theory.
- By extending the GAT of CwFs to match features of the category model, we obtain a notion of directed CwF. In the syntax model of directed CwFs, it's possible to perform synthetic category theory and, perhaps, define the notion of CwF.


###### Samuel Novotný: Towards Resolving Type Inconsistencies in Transparent Intensional Logic {#snovotny}

Transparent Intensional Logic, developed by Pavel Tichý, is one of the two main methodologies for the logical analysis of natural language. Formally, it is a hyperintensional partial variant of the typed λ-calculus, whose hyperintensionality arises from its ability to distinguish between its term, called a construction or procedure, and the value it constructs. This procedural nature of Transparent Intensional Logic is also reflected in the ramification of its type system, known as Tichý’s Type Theory, which represents a unique interconnection of Church’s Simple Type Theory and Russell’s Ramified Type Theory. However, this connection turned out to be imprecise, revealing type inconsistencies that limit the applicability of this logical system not only in theoretical research but also in practical applications such as automated semantic analysis.

In this talk, we address the challenge of detecting type inconsistencies in Transparent Intensional Logic and propose a novel solution through a modified type system based on the concept of reference types. Our proposed adjustment introduces a more precise framework for analyzing type relations in Transparent Intensional Logic constructions and restructures its type system to align more closely with those used in standard functional programming languages. Additionally, it enables type inference, making it possible to derive the types of constructions automatically without explicit annotations – a capability previously absent in TIL. This, in turn, enhances the implementation potential of Transparent Intensional Logic, which has so far been used primarily as a syntactic standard.

The proposed formal approach to type checking in Transparent Intensional Logic has been implemented in the statically typed functional programming language Haskell, showcasing its practical feasibility and contribution to the automation of logical construction analysis. This work is a joint effort by Samuel Novotný and Ján Perháč.


###### Lorenzo Perticone: Parametric Distributive Laws: uniform monad composition {#lperticone}

Monads play an important role in both the syntax and semantics of modern functional programming languages (Moggi, 1991: Notions of computation and monads). The problem of combining them has been of profound interest at least since the 90s, and different approaches have been employed to tackle it: currently, the most prevalent notion is that of monad transformers (Cenciarelli and Moggi, 1993: A syntactic approach to modularity in denotational semantics; Liang, Hudak, Jones, 1995: Monad transformers and modular interpreters).
We provide a novel abstract framework to describe such ''compositions'' which we call parametric distributive laws. Our description of this framework relies on the language of 2-categories: since distributive laws are monads in monads, we can obtain a semi-strict ''walking distributive law'' by Grey-tensoring the walking monad with itself. We can then construct a ''parametric walking distributive law'' by Grey-tensoring again, this time with our chosen 2-category of parameters.
We demonstrate the applicability of this approach by providing two concrete examples, involving the Writer and Either monads; this is made easier through abstract definitions for the monads. Moreover, we apply our framework, characterizing which monad morphisms respect a given parametric distributive law. Finally, we show how the Yang-Baxter equation emerges from an iterated version of our construction, a semi-strict ``walking iterated distributive law'' in the sense of Cheng (2007: Iterated distributive laws).


###### Iosif Petrakis: Categories with dependent and codependent arrows {#ipetrakis}

We study categories with family and dependent arrows, introduced in [1] and developed further in [2], that grasp type-dependency in categorical terms. As arrows are categorical generalisations of functions, family arrows and dependent arrows are categorical generalisations of type families and dependent functions in Martin-Löf Type Theory, respectively. We explain how the Sigma-objects in the type-categories of Pitts [3] are affected by the presence of the second projections as dependent arrows. Categories with cofamily arrows and codependent arrows are defined in a dual way. We present the canonical cofamily and codependent structure of the category of small types.

[1] I. Petrakis: Categories with dependent arrows, arXiv:2303.14754v1, 2023.  
[2]  I. Petrakis, Y. Ehrhardt: Categories with dependent and codependent arrows, submitted to TYPES 2024, Post-Proceedings.  
[3] A. M. Pitts: Categorical logic, in S. Abramsky, D. M. Gabbay, T. S. E. Maibaum (Eds.) Handbook of Logic in Computer Science, Vol. 5, Clarendon Press, Oxford, 2000, 39-128.


###### Daniel Ranalter: Erasure-Respecting Semantics for DHOL {#dranalter}

Dependently-typed Higher Order Logic (DHOL) equips the classical, extensional, and
well-researched HOL with dependent types. Reasoning directly on the level of DHOL is efficient
but due to the recency of its inception, only a few systems implement it. Furthermore, even
these systems are lacking optimizations that typically come with maturity and more widespread
adaption. To help with the latter, DHOL is equipped with a translation into the readily
supported HOL.
As DHOL currently lacks a clearly defined semantics, it is not obvious if mixing reasoning on
the DHOL level with reasoning on the translated statements would preserve soundness of the
calculus. We present ongoing work into an translation-respecting semantics for DHOL, i.e. a
model conforming to this interpretation should simultaneously hold for a set of  DHOL formulas
as well as the set of HOL formulas coming from the erasure thereof. This would justify the
simultaneous reasoning in both logics in Automated Theorem Provers like Lash, thereby giving
those systems access to the best of both worlds. We expect a noticeable speed-up in the time it
takes to prove statements when allowing for this mixing.
For this, we build on the familiar foundation of Henkin semantics for HOL. Models following
from Henkin's interpretation tie types to sets, terms of a type to elements in the
corresponding set, and lambda abstractions to subsets of functions between the corresponding
sets to maintain completeness.
Our interpretation of DHOL introduces additional structure to the set-theoretic HOL models. The
resulting interpretation is a generalization thereof, yielding the familiar Henkin models in
the non-dependent case. 
Finally, with the justification of a uniform semantics across both logics, we want to evaluate
the performance increase of mixing statements in automated reasoning on a set of DHOL problems.


###### Pietro Sabelli: On the conservativity of type theories with classical logic over arithmetic {#psabelli}

A starting point in investigating the arithmetic strength of type theories is Beeson’s well-known theorem on the conservativity of Martin-Löf type theory without universes over Heyting Arithmetic [1]. Recently, this theorem has been extended to a version of the Calculus of Inductive Constructions, which has been shown to be conservative over Higher-order Heyting Arithmetic [3].

In this talk, we present an adaptation of the above results to the case of classical logic, developed in joint work with Michele Contente. The type theories under consideration are the Calculus of Inductive Constructions and the Minimalist Foundation, a common-core foundation that can be considered a predicative version of the former. In particular, we show that the Minimalist Foundation with classical logic and without universes is conservative over Peano Arithmetic and that the Calculus of Inductive Constructions with classical logic is conservative over Higher-order Peano Arithmetic. The main tool used to obtain such results is an extension of Gödel’s double-negation translation for arithmetic to the Minimalist Foundation developed in joint work with Maria Emilia Maietti [2].

[1] Beeson, M. J. (1985). Foundations of constructive mathematics. Springer Berlin  
[2] Maietti, M. E. and Sabelli, P. (2025). Equiconsistency of the Minimalist Foundation with its classical version. Annals of Pure and Applied Logic  
[3] Otten, D. and van den Berg, B. (2024). Conservativity of Type Theory over Higher-Order Arithmetic. 32nd EACSL Annual Conference on Computer Science Logic.


###### Matteo Spadetto: A 2-categorical approach to the sematics of axiomatic dependent type theory {#mspadetto}

To formulate the semantics of dependent type theory, we encounter two distinct, but related, approaches: syntactic and categorical. The syntactic approach directly mirrors the syntax of the theory, via choice functions that translate the inference rules into the language of a model [1]. On the other hand, the categorical approach adds structure to the model, structure that allows to automatically recover such choice functions. For instance, in presence of extensionality, the property that the display maps of a model are closed under composition up to isomorphism reformulates categorically the inference rules for the dependent sum types.
However, in case we drop extensionality, such a simple 1-dimensional characterisation of the type constructors is harder to find. Given this challenge, in this talk we adopt Garner’s perspective [3] to study the semantics of axiomatic type theory, i.e. very intensional type theory, from a 2-categorical point of view.
Axiomatic type theory [2,4,5] is a dependent type theory whose computation rules are replaced by propositional equalities. Its type constructors can be encoded into natural 2-categorical data that we use to provide a presentation of the semantics of axiomatic type theory via 2-dimensional models called display map 2-categories. In other words, we show that these structures induce appropriate display map categories in the syntactic formulation, i.e ordinary models. We compare the class of the models according to this notion of semantics to the class of those derived from the usual notion of semantics.

[1] M. Hofmann. Syntax and semantics of dependent types, pages 13–54. Springer, London, 1997.  
[2] S. Boulier and T. Winterhalter. Weak type theory is rather strong. 30th International Conference on Types for Proofs and Programs, 2019.  
[3] R. Garner. Two-dimensional models of type theory. Mathematical Structures in Computer Science, 19(4):687–736, 2009.  
[4] D. Otten and M. Spadetto. Models for axiomatic type theory. Workshop on Homotopy Type Theory & Univalent Foundations, 2024.  
[5] B. van den Berg. Path categories and propositional identity types. ACM Trans. Comput. Log., 19(2):Art. 15, 32, 2018.


###### Théo Winterhalter: Local abstraction over computation in type theory {#twinterhalter}

I will present ongoing work on the design of a type theory with support for abstraction over user-defined computation rules. Currently, proof assistants like Agda and Rocq, as well as the Dedukti logical framework, support extensions of definitional equality through user-defined computation rules that are global: once they are added, they are here to stay. Importing a development that makes use of those rules, means relying on them, whether we want it or not, which can lead to annoying incompatibilities.
In contrast, I propose to consider the ability to introduce such computation rules only locally to a certain definition.
This takes the form of a prenex quantification at the definition level. This quantification is supplemented with the possibility to provide one or several instantiations that verify the equations definitionally.
Additionally, I plan to show that a procedure inlining definitions abstracting over definitional equality is possible, in the style of monomorphisation or of C++ templates. In the process we would get a conservativity result over more conventional type theories.

There are several benefits to such a system.
First, it provides encapsulation for user-defined computation rules, which is important to avoid unwanted bad interactions and limits the scope in which invariants of type theory (such as termination, confluence, type preservation and consistency) are broken.
Second, abstraction lets users factorise code that crucially relies on definitional equality, as well as hide implementation details that are irrelevant in some settings.
Finally, it gives a way to encode certain features without paying the price of the encoding. As an example, one could decide to work with the nice interface of certain inductive types while relying on the fact that they can all be implemented (including their computational behaviour) using suitable W types.
