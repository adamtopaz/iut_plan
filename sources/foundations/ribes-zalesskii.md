# F16 · Ribes–Zalesskii, Profinite Groups

**★ REUSABLE · Selected retained group-theoretic leaves.** Luis Ribes and Pavel Zalesskii, [*Profinite Groups*, second edition](https://link.springer.com/book/10.1007/978-3-642-01642-4), Ergebnisse 40 (2010). The older Semi-graphs bibliography uses the **first edition (2000)**, so theorem numbers must be translated explicitly.

## Selected results and boundaries

- **First-edition Proposition 3.3.15**, cited by Semi-graphs: **task F16-R** is to extract the exact subgroup/freeness assertion, check all closedness and finite-generation assumptions, and pin the second-edition counterpart or retain the first edition as the proof source.
- Free discrete groups, their profinite completions and the selected subgroup/normalizer properties underlying **EtTh Lemma 2.17**. That lemma's actual arithmetic/tempered application is specified in [EtTh](../anabelian/etale-theta.md); André Lemma 3.2.1 and Semi-graphs Corollary 1.6(iii) supply its named immediate sources.
- **Task F16-N:** match the exact nonabelian-intersection hypotheses of that normalizer comparison to standard profinite lemmas. It is not a blanket equality of normalizers for all subgroups of all dense embeddings.

Prove every continuity/closure assertion in the completion comparison. A discrete free subgroup, a free profinite group and a free pro-`p` group are different objects. The subgroup theorem selected for one cannot be substituted into another without the comparison proof.

## Interfaces and parallel work

Ready inputs: free groups, compact/profinite groups, inverse limits and completion from [P01](../../work-packages/01-shared-interfaces.md). Deliver [P11](../../work-packages/11-trees-and-profinite-groups.md), alongside [F15](serre-trees.md). Consumers: [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P20](../../work-packages/20-etale-theta.md). The abstract subgroup proofs are independent of local fields once their exact hypotheses are settled.

## Mathlib boundary and reusable release

The [pinned baseline](../../plan/mathlib-baseline.md) positively locates profinite categories, completion and its adjunction, and profinite realizations of Galois groups. It does not certify the selected subgroup/normalizer theorems. Reuse the completion machinery; extend it with the needed embedding, closure and subgroup results. Such APIs benefit profinite group theory, Galois groups and fundamental groups far beyond IUT.

[Foundation map](README.md) · [André](../anabelian/andre-tempered.md) · [Semi-graphs](../anabelian/semi-graphs.md)
