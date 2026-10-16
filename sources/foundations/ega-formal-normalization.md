# F21 · EGA IV and formal-model normalization

**★ REUSABLE · Selected normalization hypotheses in corrected EtTh constructions.** Grothendieck–Dieudonné, *EGA IV, Étude locale des schémas et des morphismes de schémas*, second part, Publ. Math. IHES24 (1965),5–231. [Original NUMDAM text](https://www.numdam.org/item/PMIHES_1965__24__5_0/).

## Retained caller and exact selection task

The [March2022 EtTh comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Etale%20Theta%20Function%20and%20its%20Frobenioid-theoretic%20Manifestations%20%28comments%29.pdf), item(xlvi), printed7–8, uses EGA IV second part **Scholie7.8.3(ii),(iii),(v),(vi)** in the corrected `(NorFor)`/`(NorForZar)` formal-normalization discussion. It also cites [Faltings's crystalline paper](faltings-crystalline-1990.md) and AbsTopII Lem2.1 for the Hensel/normalization comparison.

**Task F21-N:** translate the exact retained excellence/normalization/finite-extension statements and their hypotheses into Lean, prove the required instances for the formal models, and reproduce the corrected argument. Caller references and corrected model discussion are located; original EGA theorem hypotheses/proof lemmas still require a source lock under A01/A04. Audit existing mathlib normalization/excellence infrastructure before developing new definitions.

The correction constructs its spaces as **ringed spaces obtained by tensoring formal structure sheaves with the base field**. They are not identified by definition with a rigid or Berkovich generic fiber. A consumer needing that identification must prove a comparison map and its required properties.

## Ownership and usefulness

[P08.5](../../work-packages/08-tate-and-analytic-curves.md) owns formal schemes, generic-fiber/ringed-space interpretation and selected normalization; [P20.5](../../work-packages/20-etale-theta.md) applies them to corrected theta realization. Abstract normality, completion/Hensel and finite-normalization lemmas are reusable in formal/analytic algebraic geometry.

[Foundation map](README.md) · [EtTh source](../anabelian/etale-theta.md) · [Analytic foundations](rigid-analytic-foundations.md) · [Audit gates](../../tracking/audit-gates.md)
