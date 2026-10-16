# F06 · The Stacks Project: étale Kummer theory

**★ REUSABLE · Retained exact target.** [Stacks §59.28, tag 03PK](https://stacks.math.columbia.edu/tag/03PK).

## Precise targets

1. **Lemma 59.28.1:** for a scheme `S` and a positive integer `n` invertible on `S`, prove exactness of `1 → μ_n → G_m → G_m → 1` on its small and big étale sites, where the last map is the `n`th power.
2. **The cohomology sequence following Lemma 59.28.1**, using **Theorem 59.24.1** (`H¹(S,G_m)` and the Picard group): define the connecting Kummer class and its relation to units and `Pic(S)[n]`.
3. The field specialization and its compatibility with Galois cohomology, as a bridge to [F04](continuous-galois-cohomology.md), including pullback/evaluation at points and inverse-system naturality.

All IUT field applications here have characteristic zero. Over a characteristic-`p` special fiber, `μ_p` is not an étale coefficient object with the same exact sequence. **Lemma 59.28.3** supplies an fppf/syntomic version if a selected integral proof needs it; it is optional until that consumer is identified.

## Interfaces and parallel work

Ready inputs: étale sites, sheaves of abelian groups, roots-of-unity group schemes, torsors, Picard groups and sheaf-cohomology exactness. Main owner [P03](../../work-packages/03-continuous-cohomology.md), with the scheme/Galois bridge from [P05](../../work-packages/05-etale-fundamental-groups.md) and divisor/Picard API from [P06](../../work-packages/06-curves-and-belyi.md).

Consumers: [P14](../../work-packages/14-cuspidalization.md), [P15](../../work-packages/15-mono-anabelian-reconstruction.md), [P20](../../work-packages/20-etale-theta.md), [P23](../../work-packages/23-iut-ii-local-evaluation.md), [P24](../../work-packages/24-iut-ii-global-gluing.md). Site exactness, Picard comparison and continuous field Kummer can be separate tasks once the connecting-map conventions agree.

## Mathlib boundary and reusable release

The [pinned audit](../../plan/mathlib-baseline.md) locates finite field-theoretic Kummer extensions, finite Hilbert 90, cyclotomic characters and étale sites. Their existence does not certify this sheaf sequence or the continuous inverse-limit map. Audit and prove the bridges explicitly.

First release: `μ_n` torsors, Kummer connecting classes, units/Picard exactness and evaluation naturality. These serve descent on curves, torsion line bundles, isogeny descent and Selmer constructions.

[Foundation map](README.md) · [SGA 1](sga1-and-pi1.md) · [Reusable results](../../plan/reusable-results.md)
