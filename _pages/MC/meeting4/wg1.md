
## WG1: Tools on Proof Systems Interoperability

Report on 2023-2024

---

### Deliverables

**Deliverable 5 (September 2023):** Release of software for translating proofs coming from important proof systems based on type theory like Isabelle, Agda, PVS, Lean or Minlog, to Dedukti and back.

**Deliverable 10 (September 2024):** Release of software for translating proofs coming from important proof systems based on set theory like Mizar, Atelier B or TLAPS to Dedukti and back.

---
### WG1 meeting in January

- 23-25 January 2024 in Gruissan, France
- Work on `lean2dk`, `hol2dk`, `Personoj`, Dedukti, LambdaPi, BiTT, SMT solvers, ...

![[Pasted image 20241011150643.png]]

---

### WG1+2+4 meeting in September

- 26-27 September 2024 in Fontainebleau, France
- Talks on translations from Event-B, LEO-III, Lean, GDV, ...

---
### Publications

- [Translating HOL-Light proofs to Coq](https://doi.org/10.29007/6k4x), Frédéric Blanqui (at *LPAR*)
- [Sharing proofs with predicative theories through universe-polymorphic elaboration](https://doi.org/10.46298/lmcs-20(3:23)2024), Thiago Felicissimo and Frédéric Blanqui (in *LMCS*)
- [Maude2Lean: Theorem proving for Maude specifications using Lean](https://doi.org/10.1016/j.jlamp.2024.101005), Rubén Rubio and Adrián Riesco (in [_JLAMP_](https://www.sciencedirect.com/journal/journal-of-logical-and-algebraic-methods-in-programming))

---
### Translation tools updated this year

- [Hol2dk](https://github.com/Deducteam/hol2dk): HOL-Light to Dedukti and Lambdapi
- [Isabelle_dedukti](https://github.com/Deducteam/isabelle_dedukti): Isabelle to Dedukti or Lambdapi
- [Logic embedding tool](https://github.com/leoprover/logic-embedding): Translates non-classical proof obligations into higher-order logic
- [Personoj](https://github.com/Deducteam/personoj): PVS to Lambdapi
- [Lean2dk](https://github.com/Deducteam/lean2dk): Lean4 to Dedukti

Full list: https://europroofnet.github.io/tools/

---

### New tools in development

- Extension of GDV to output LP proofs  
- Extension of Carcara to output LP proofs (PhD Alessio Coltellacci)  
- Extension of LEO-III to output LP proofs (MSc Melanie Taprogge)  
- Verification of proofs (Event-B proof obligations from Rodin) (PhD Anne Grieu)

---