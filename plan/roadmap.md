# A parallel roadmap to Theorem 3.11

The mathematical endpoint is the complete statement and proof of **IUT III, Theorem 3.11**, with actual IUT objects and all three classes of indeterminacy. The plan develops useful arithmetic/anabelian libraries first, then proves the IUT I–III assembly. Every known branch has an owning package and a source-selection/audit gate where its exact proof boundary is not yet locked.

The [papers and books graph](../graphs/sources.md) answers “which texts?” The [output graph](../graphs/work-packages.md) answers “what can teams do concurrently?” The [source cards](../sources/README.md) and [package cards](../work-packages/README.md) supply the precise items and handoffs. Graph arrows run **prerequisite → consumer**.

## Parallel workstreams

| Workstream | Packages | Independent mathematical output | Wider value |
|---|---|---|---|
| Shared interfaces and profinite categories | P01, P11 | Outer maps, inverse systems, trees, graph groups, anabelioids | ★ REUSABLE |
| Local/global arithmetic | P02, P03, P04 | Local-unit logarithms, continuous Kummer, reciprocity/duality | ★ REUSABLE |
| Schemes, curves and covers | P05, P06 | Geometric pi1, arithmetic exact sequence, Riemann–Roch/duality, Belyi | ★ REUSABLE |
| Elliptic and analytic geometry | P07, P08 | Torsion/pairings, Tate curves, analytic coverings/theta preliminaries | ★ REUSABLE |
| Abelian and p-adic comparison | P09, P10 | Degeneration, finite-field weights, selected comparison and local Kummer results | ★ REUSABLE |
| Relative and tempered anabelian geometry | P12, P13 | p-adic Hom/Isom, stable graphs and torsion/cusp recognition | ★ REUSABLE |
| Cuspidalization and reconstruction | P14, P15, P16 | Belyi/abelian cuspidalization, function fields, local/global Galois reconstruction | ★ REUSABLE |
| Archimedean reconstruction | P17 | Circle/measure and Aut-holomorphic/global comparison | ★ REUSABLE |
| Categorical arithmetic and theta | P18, P19, P20 | Frobenioid construction/reconstruction and EtTh rigidity | ◇ IUT SUPPORT / ★ REUSABLE |
| IUT construction and transport | P21–P26, P28–P30 | Native theaters, evaluation, gluing, links and all compatibility assertions | IUT SPECIFIC |
| Measured local algebra | P27 | Tensor lattices, Haar/radial/angular normalizations and comparison | ★ REUSABLE |
| Final integration | P31 | The complete Theorem3.11 Lean proof | IUT SPECIFIC; last |

These workstreams are mathematical ownership boundaries, not fixed team counts. Large streams should split by deliverable suffix. One integration maintainer keeps the shared signatures and dependency graph coherent; separate reviewers check source fidelity and kernel-checked proof closure.

## First parallel assignments

Once P01 agrees the basic conventions, the following work can start concurrently from existing mathlib and ordinary definition work:

1. **P02:** finite-local-extension interface and p-adic unit logarithms.
2. **P03:** continuous cochains, low degrees and finite-to-continuous Kummer comparison.
3. **P05:** connected-scheme finite-etale covers and fiber functors, reusing abstract Galois categories.
4. **P06:** curve/divisor/linear-system APIs on existing schemes; merge pi1 interfaces when P05 supplies them.
5. **P07:** geometric Weierstrass/elliptic bridge and torsion definitions; use the agreed curve API.
6. **P11:** trees, profinite/free subgroup theory and anabelioid definitions.
7. **P17.1:** elementary circle-cover, segment-monoid and measure constructions.
8. **P18:** abstract Frobenioid definitions and monoid/category models.
9. **Audit team:** source/correction locks and the exact comparison/global-reconstruction/analytic-source leaves in A01–A07.

Do not serialize these behind a complete anabelian theorem. Definition-only and generic algebra/category outputs have independent value and can merge before their high-level consumers are ready.

## Integration waves

| Wave | What becomes usable | Mathematical completion gates |
|---|---|---|
| 0 | Stable signatures, mathlib reuse map, source versions and corrected statements | P01; A01–A03 |
| 1 | Local fields/logarithms, continuous Kummer, geometric pi1, curve/elliptic APIs, trees and categorical models | P02, P03, P05–P07, P11, P18; early P17.1 |
| 2 | Local CFT/duality, Tate/analytic geometry, abelian degeneration/weights, selected p-adic comparisons | P04, P08–P10; precise retained proof routes locked |
| 3 | Relative/tempered anabelian theorems, cuspidalization, local/global invariants, function-field reconstruction | P12–P16, full P17; ★ reusable theorems available independently |
| 4 | Frobenioid reconstruction and EtTh rigidity, native IUT input types and concrete packet calculus | P19, P20, P21, P27.C; theorem proofs still separate from IUT assembly |
| 5 | IUT I theaters → IUT II local evaluation/global gluing → III log-links/theta monoids | P22–P26; reconstructed P27.R |
| 6 | LGP constructions → final packet volume compatibility → global Kummer → all native compatibility | P28.C, P27.V, P29, P30; A01–A09 closed |
| 7 | **Theorem3.11 proved from the completed earlier imports** | **P31; final sink and last acceptance** |

Waves are integration checkpoints, not permission to postpone independent earlier work. P19 uses elementary archimedean data before the full global P17 output. P27 and P28 have the explicitly staged interfaces in the [interface guide](interfaces.md).

## Early useful releases

Release general results as they become complete, without waiting for IUT:

- Number-field local interfaces, unit logarithms and normalized lattice measures.
- Continuous Kummer maps and local reciprocity/norm functoriality.
- The arithmetic fundamental-group exact sequence and geometric cover APIs.
- Riemann–Roch/duality/Belyi infrastructure; elliptic torsion and Tate uniformization.
- Tempered reduction-graph reconstruction, relative p-adic Isom, cuspidalization and field reconstruction.

The [reusable-results catalogue](reusable-results.md) gives concrete statements, wider applications and package/source links.

## What “complete plan” means here

The plan accounts for the target's whole statement, all directly cited IUT prerequisites, the identified pre-IUT branches, source corrections, mathematical interpretation bridges and a final proof-closure check. Further proof dependencies discovered inside a selected source belong to its owning package and must be added before that package is accepted. **Completeness of the high-level plan is not a claim that the full minimal theorem-level closure has already been certified.** The owned audit gates make that remaining work explicit and schedulable.

No timeline is inferred from paper lengths. Calibrate effort using completed pilot outputs, shared API reuse and the exact retained proof route. No broad result such as full p-adic Hodge theory or the whole Weil conjectures is added merely because a narrower comparison/weight theorem is used.

[Home](../README.md) · [Package directory](../work-packages/README.md) · [Coverage checklist](../tracking/coverage.md)
