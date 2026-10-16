# IUT I: Construction of Hodge Theaters

**Source:** Shinichi Mochizuki, *Inter-universal Teichmüller Theory I: Construction of Hodge Theaters*, Publ. RIMS 57 (2021), 3–207. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Inter-universal%20Teichmuller%20Theory%20I.pdf) · [Author catalogue and corrections](https://www.kurims.kyoto-u.ac.jp/~motizuki/papers-english.html).

**Role:** IUT SPECIFIC. Source statements and construction proofs are separate targets. This card uses published result numbers; reconcile the author PDF and journal versions in A01.

## Selected targets

| Item | Exact source target | Required formal output | Owner |
|---|---|---|---|
| I.1 | Def3.1(a)–(f), printed68–71 | Initial theta data: number field/algebraic closure, punctured elliptic/orbicurves, stable reduction, mod-l image, selected valuations and cusp data | P21.1 |
| I.2 | Def4.1; Def5.2, especially(vi),(viii); Def6.1 | D/F-prime strips, capsules, local/global/mono-analytic forms and labeled/signed data | P21.2 |
| I.3 | Defs4.6,5.5,6.4,6.11,6.13 and their construction statements | Bridges, gluing groupoids and final signed elliptic NF theater | P21.3, P22.2/4 |
| I.4 | Props4.9,4.11; Cor4.12; Prop6.9(iii); Cor6.10(iii) | Procession construction/forgetful functors, ordered labels and etale-picture permutation symmetries | P22.3 |
| I.5 | Examples3.2–3.5 and5.1; Cor5.3 and related selected gluing statements | Local theta/q models, good/archimedean and global Frobenioids, isomorphism torsors and reconstruction | P22.1/2 |
| I.6 | Sections1–2 results actually imported by I.1–I.5, including any retained tempered subgroup/conjugacy statements | A clause-level source inventory and completed proofs of each retained interface | P22.1; A03 audit |

Theorem3.11 directly cites I.1, I.2's Def5.2 clauses, and I.4's signed procession/symmetry statements. The remaining rows provide their construction and interpretation layer. A source reference containing “cf.” is retained as contextual until its mathematical role is assigned.

## Prerequisites and parallel work

The native data types use [geometric curves/covers](../../work-packages/05-etale-fundamental-groups.md), [elliptic geometry](../../work-packages/07-elliptic-curves.md), early [tempered types](../../work-packages/13-tempered-anabelian-geometry.md), and [Frobenioid constructions](../../work-packages/18-frobenioid-definitions.md). Their syntax and concrete examples can proceed while [reconstruction](../../work-packages/15-mono-anabelian-reconstruction.md), [EtTh rigidity](../anabelian/etale-theta.md) and [categorical reconstruction](../anabelian/frobenioids-i.md) are proved.

The supplied stable-reduction and large-image hypotheses need formal predicates and consequences. A theorem that guarantees suitable initial data for every elliptic curve is a separate application target, not a prerequisite merely for accepting the given data.

## Completion and handoff

P22 exports actual theater objects, reconstruction/naturality theorems, prime-strip/procession functors and the exact allowed symmetries to [IUT II](iut-ii.md) and [IUT III](iut-iii.md). General arithmetic, anabelian and category libraries must remain independently importable.

[All sources](../README.md) · [P21](../../work-packages/21-iut-inputs-and-theater-data.md) · [P22](../../work-packages/22-iut-i-theater-reconstruction.md)
