# F10 · Faltings, p-adic Hodge Theory

**★ REUSABLE · Retained on the selected printed local pro-p proof route.** Gerd Faltings, *p-adic Hodge Theory*, JAMS **1** (1988), 255–299, [DOI 10.1090/S0894-0347-1988-0924705-1](https://doi.org/10.1090/S0894-0347-1988-0924705-1); [primary journal record](https://www.jstor.org/stable/1990970).

## Exact caller anchors and statement-lock tasks

| Item requested by the caller | Required work |
|---|---|
| Part I Theorem 4.4(i),(iv), cited by Local Pro-p Lemma 2.1 | **Task F10-A:** extract the exact Hodge–Tate comparison/edge-map assertions for the curve or abelian-variety cohomology used there. Export the rational comparison, filtration/degree conventions and functoriality. |
| Part I Theorem 4.2; Part II Theorems 2.4 and 3.1, cited in Local Pro-p §§9,11 | **Task F10-R:** extract the relative/integral comparisons and bounded-torsion estimates with every base, smoothness/properness and good-reduction hypothesis, and every uniformity quantifier. |
| Proof of the retained assertions | **Task F10-P:** enumerate their almost-étale, integral-cohomology and descent lemmas, including references, and assign each to a proof subpackage before estimating effort. |

The named caller references are audited; the original theorem statements have not yet been independently checked in this plan. The intended arithmetic specialization includes finite extensions of `ℚ_p` and the smooth curves/abelian varieties in the selected anabelian argument. That description does **not** replace the precise relative/integral hypotheses to be locked by F10-R.

A rational absolute Hodge–Tate statement cannot silently substitute for a relative integral comparison with uniform bounds. A modern alternative proof is welcome only after proving it exports every required comparison map and estimate.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md), [P03](../../work-packages/03-continuous-cohomology.md), geometric étale/coherent cohomology and [P09](../../work-packages/09-abelian-degeneration-and-weights.md). This belongs to [P10](../../work-packages/10-p-adic-comparison.md), consumed by [P12](../../work-packages/12-relative-anabelian-geometry.md). Rational comparison and integral/relative estimates are distinct teams coordinated by a common coefficient/cohomology interface.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates definitions of ℓ-adic cohomology and continuous cohomology, not these comparison theorems. Definitions alone do not discharge their cohomological finiteness, base-change or integral estimates. Publish the curve `H¹` comparison first, with functoriality; subsequent relative/integral milestones serve `p`-adic representations and arithmetic families outside IUT.

[Foundation map](README.md) · [Tate](tate-p-divisible.md) · [Bloch–Kato](bloch-kato-local.md) · [Local Pro-p](../anabelian/local-pro-p.md)
