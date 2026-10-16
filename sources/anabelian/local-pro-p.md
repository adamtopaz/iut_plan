# The Local Pro-p Anabelian Geometry of Curves

**★ REUSABLE — major independent milestone** · Owner: [P12 relative anabelian geometry](../../work-packages/12-relative-anabelian-geometry.md).

Shinichi Mochizuki, *Inventiones Mathematicae* **138** (1999), 319–423. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Local%20Pro-p%20Anabelian%20Geometry%20of%20Curves.pdf); [June 2019 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Local%20Pro-p%20Anabelian%20Geometry%20of%20Curves%20%28comments%29.pdf). The theorem and appendix numbering must be pinned to this edition before implementation.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Theorem A = Theorem 16.5 and following remark | Over a **fixed sub-p-adic field `K`**, dominant morphisms from the specified smooth pro-varieties to hyperbolic pro-curves correspond to open continuous outer homomorphisms **over `G_K`**, for profinite and geometrically pro-p versions | Source target matched in the existing audit; retain the pro-object and admissibility hypotheses |
| Required finite-p-adic hyperbolic-curve **Isom specialization** | A field-relative geometric isomorphism/outer-group-isomorphism equivalence at the scope demanded by each consumer | Planned narrower implementation target; derive it from, or independently prove it in place of, the relevant part of A |
| Lemmas 2.1, 2.2 | Local comparison/cohomology ingredients used in the anabelian proof | Caller inspected: Faltings I.4.4(i),(iv), and Tate §3.3 Theorems 1,2 |
| Lemma 4.1 | Local abelian-variety Kummer image/exponential compatibility | Caller inspected: Bloch–Kato §3 Example 3.11 and Lemma 3.8.1 |
| Selected §9/§11 comparison arguments | Relative/integral Hodge–Tate comparison and uniform estimates in the good-reduction setting | Caller inspected: Faltings II.2.4, II.3.1, I.4.2; original statements still to audit |

**Evidence.** The theorem-A route and its consumers are source-audited. The classical comparison imports are **caller-audited**; matching their original exact hypotheses is part of P10. The theorem concerns relative curve geometry, not field reconstruction from an unenhanced absolute Galois group.

## Prerequisite interfaces

- [P02 local fields](../../work-packages/02-local-global-fields.md), [P03 continuous cohomology](../../work-packages/03-continuous-cohomology.md), [P04 duality](../../work-packages/04-class-field-theory.md): local Galois and Kummer theory.
- [P05 arithmetic π₁](../../work-packages/05-etale-fundamental-groups.md), [P06 curves](../../work-packages/06-curves-and-belyi.md), [P07 elliptic geometry](../../work-packages/07-elliptic-curves.md), [P09 Jacobians/degeneration](../../work-packages/09-abelian-degeneration-and-weights.md): geometric objects and their representations.
- [P10 selected p-adic comparison](../../work-packages/10-p-adic-comparison.md): the rational, relative and integral comparisons actually used, with their uniformity data.

## Parallel outputs and acceptance

Agree the required finite-p-adic Isom interface first. The geometric and p-adic-comparison teams can then work behind that interface, while [Galois Sections](galois-sections.md), [Semi-graphs](semi-graphs.md), and [AbsTop I](abstop-i.md) develop conditional consumers. Before final integration, replace every relative-anabelian assumption by an unconditional Lean theorem. A full Hom theorem is an additional broadly useful milestone, but its necessity must be established per caller rather than inferred from the strongest available citation.

**Closure task — P12 owner.** Trace the minimal proof slice for the chosen Isom target and check whether the relative/integral estimates can actually be specialized away. Keep the printed proof route as the baseline until a replacement proof is supplied. Integrate the 2019 appendix corrections. Do not include Faltings's Mordell theorem or the full Bloch–Kato conjecture merely because these authors appear in the proof.

[Source graph](README.md) · [Project home](../../README.md)
