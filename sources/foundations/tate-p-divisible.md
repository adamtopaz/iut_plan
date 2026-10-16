# F11 · Tate, p-divisible Groups

**★ REUSABLE · Retained selected local-cohomology leaves.** John Tate, *p-divisible Groups*, in *Proceedings of a Conference on Local Fields* (1967), pp.158–183, [publisher chapter](https://link.springer.com/chapter/10.1007/978-3-642-87942-5_12).

## Precise source request and remaining lock

[Local Pro-p](../anabelian/local-pro-p.md), Lemma 2.2, explicitly cites **§3.3, Theorems 1 and 2** for the local Galois-cohomology assertions used in the Hodge–Tate argument. This exact caller edge is retained. It is a different theorem family from Tate uniformization and from Tate's isogeny theorem for abelian varieties over finite fields.

**Selection task F11-T:** read those two original statements and enumerate the precise `H⁰`/`H¹` results for the completed algebraic closure and cyclotomic twists that the caller uses. Record degree, exceptional untwisted case, topology, coefficient field, and all functorial maps. The original statements are not freshly audited in this plan, so do not infer blanket vanishing of every positive-degree continuous cohomology group.

Requested specialization: a finite extension `K/ℚ_p`, its absolute Galois group, the completion `C_p` of an algebraic closure and the relevant Tate twists. Preserve the source's hypotheses if its statement is formulated over a broader complete discretely valued field. The needed proof may use ramification estimates and normalized traces; F11-T must register those supporting lemmas rather than treating the named cohomology theorems as primitive axioms.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md) local fields and [P03](../../work-packages/03-continuous-cohomology.md) topological coefficient cohomology. Delivery belongs to [P10](../../work-packages/10-p-adic-comparison.md), feeding [P12](../../work-packages/12-relative-anabelian-geometry.md) and the [Faltings](faltings-p-adic-hodge.md)/[Bloch–Kato](bloch-kato-local.md) comparison branch. The Tate local-cohomology team can proceed independently of Frobenioids and IUT theaters.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates `ℚ_p`, completions, continuous cohomology definitions and cyclotomic characters; it does not certify the required `C_p`-cohomology theorems. A meaningful reusable release includes completed algebraic closures and twist representations, then the exact low-degree cohomology computations. These support Hodge–Tate theory and local `p`-adic Galois representations beyond IUT.

[Foundation map](README.md) · [Continuous cohomology](continuous-galois-cohomology.md) · [Reusable results](../../plan/reusable-results.md)
