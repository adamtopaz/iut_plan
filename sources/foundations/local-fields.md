# F02 · Serre, Local Fields

**★ REUSABLE · Retained foundation.** Jean-Pierre Serre, [*Local Fields*, GTM 67](https://link.springer.com/book/10.1007/978-1-4757-5673-9), English translation, 1979. Use the printed chapter/section, not unverified proposition numbering from another edition.

## Selected results and boundaries

| Portion | Required theorem interface |
|---|---|
| Chapters I–II: discrete valuations and completion | Finite extensions of complete discretely valued fields; unique extended valuation, completeness, integral closure and residue/ramification degrees. Specialize the main public API to finite extensions of `ℚ_p`. |
| Chapters III–V: different, ramification and norm | Norm/valuation and unit-filtration formulas actually needed by local reciprocity and reconstruction; match upper/lower ramification conventions when imported. |
| Higher units and characteristic-zero exponential/logarithm | On sufficiently deep principal units, `log` and `exp` are inverse isomorphisms with an additive ideal. Extend `log` to units; prove kernel = roots of unity, finite-index/image-lattice properties, field-embedding compatibility and `log(Norm u) = Trace(log u)`. |

**Selection task F02-L:** read the higher-unit/exp-log proofs and pin their exact section/proposition labels in the selected edition. Export an explicit convergence threshold in terms of the absolute ramification index; include `p = 2`. The full unit group need not map isomorphically onto the valuation ring, and the image lattice must be proved rather than replaced by that ring.

The hypotheses for the main log-shell interface are a finite extension `K/ℚ_p`, its fixed extended `p`-adic topology, and its ring of integers. More general complete discretely valued fields may be handled separately. CFT is owned by [F03](class-field-theory.md).

## Interfaces and parallel work

Ready inputs: [F01](field-number-theory.md), valued fields, finite extensions and Banach algebra series. Main package: [P02](../../work-packages/02-local-global-fields.md). Consumers: [P04](../../work-packages/04-class-field-theory.md), [P08](../../work-packages/08-tate-and-analytic-curves.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md), [P25](../../work-packages/25-iut-iii-log-links.md), [P27](../../work-packages/27-measured-tensor-packets.md).

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates local-field classes, `ℚ_p`, finite-extension and ramification infrastructure. `Analysis/Normed/Algebra/Logarithm.lean` supplies a general series definition, while the surveyed file leaves ultrametric convergence, multiplicativity and inverse properties as work. This is an integration-and-proof package, not a fresh construction of all valued fields.

Release the complete local-unit log API, exact lattice/index formulas and trace/norm naturality. These serve local Galois representations, regulators and nonarchimedean Lie theory independently of IUT.

[Foundation map](README.md) · [Cohomology](continuous-galois-cohomology.md) · [Reusable results](../../plan/reusable-results.md)
