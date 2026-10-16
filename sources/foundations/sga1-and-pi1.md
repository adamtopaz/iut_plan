# F05 · SGA 1 and the Stacks fundamental-group route

**★ REUSABLE · Retained geometric interfaces; alternative proofs overlap.** [Grothendieck et al., *SGA 1*, revised annotated edition](https://arxiv.org/abs/math/0206203). For selected results, the Stacks Project offers explicit hypotheses and recursively linked proofs. They are alternative implementations of the same interfaces.

## Precise targets

| Source item | Interface |
|---|---|
| [Stacks Theorem 58.6.2](https://stacks.math.columbia.edu/tag/0BQ8); SGA 1 Exposé V | For a connected scheme with a geometric point, finite étale covers form the relevant Galois category, equivalent to finite continuous sets for `π₁`. Basepoint change is canonical up to inner conjugacy; morphisms induce continuous outer maps. |
| Stacks Lemma 58.6.3, same section | `π₁(Spec K)` agrees with the absolute Galois group as a profinite topological group. |
| [Stacks Lemma 58.14.3, tag 0BTX](https://stacks.math.columbia.edu/tag/0BTX); SGA 1 arithmetic sequence | If `X/k` is quasi-compact and quasi-separated with connected geometric base change, prove `1 → π₁(X_k̄) → π₁(X) → G_k → 1`. Track geometric basepoints throughout. |
| SGA 1 Exposés XII–XIII | **Selection task F05-C:** select complex Riemann-existence and tame curve-group presentation statements used by the retained anabelian proof; enumerate their comparison and cusp-inertia consequences. A chapter heading is not a completed dependency audit. |

The scheme proof requires effective descent of finite étale covers, fiber functors and limit arguments. Let the linked Stacks proofs supply their precise supporting lemma list. General effective descent for arbitrary schemes is not required merely to construct this interface. Orbicurves require an explicit stack or equivariant-cover bridge, separately in [P06](../../work-packages/06-curves-and-belyi.md).

## Interfaces and parallel work

Ready inputs: scheme/étale APIs, finite étale algebras and the proved abstract Galois-category equivalence in mathlib, coordinated in [P01](../../work-packages/01-shared-interfaces.md). Delivery: [P05](../../work-packages/05-etale-fundamental-groups.md). Consumers: [P12](../../work-packages/12-relative-anabelian-geometry.md), [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P14](../../work-packages/14-cuspidalization.md), [P15](../../work-packages/15-mono-anabelian-reconstruction.md). Descent, fibers and basepoint functoriality admit separate subteams with a shared finite-cover representation.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) positively locates abstract Galois categories, their equivalence theorem, finite étale algebra fibers, schemes and étale sites. The scheme Galois-category instantiation and arithmetic exact sequence were not located at the needed scope. Reuse the abstract theorem; prove the geometric bridge. Both milestones are broadly useful for étale cohomology, descent and all anabelian programs.

[Foundation map](README.md) · [Kummer theory](stacks-kummer.md) · [André](../anabelian/andre-tempered.md)
