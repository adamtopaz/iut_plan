# F19 · Geometric etale and coherent cohomology

**★ REUSABLE · Foundational interface selected by the geometric and comparison consumers.** References: [Milne, Lectures on Etale Cohomology, v2.21](https://www.jmilne.org/math/CourseNotes/LEC.pdf), selected sections3,9,11,14,17,19,20,24; the original SGA results or [Stacks etale cohomology](https://stacks.math.columbia.edu/tag/03N1) for proof-level completion; [curve cohomology/duality](algebraic-curves.md) for the coherent side.

## Selected outputs

| Output | Precise target or selection boundary | Owner |
|---|---|---|
| Curve etale H1 | Compare finite etale torsors/continuous pi1 modules with curve cohomology, and construct the finite-coefficient to Tate/l-adic systems with their functoriality | P05.6 with P03 |
| Proper base change | Milne LEC Thm17.10, with torsion etale coefficients and its standing geometric hypotheses; retain the specializations actually used by curve/Jacobian/comparison proofs | P05.6 |
| Smooth/proper-smooth base change | LEC Thms20.1–20.2 in their stated variety/finite-coefficient setting, with the required invertibility/prime-to-characteristic conditions; extend to a more general scheme version only where a consumer needs it | P05.6 |
| Curve duality and Tate twists | The dimension-one specialization of LEC Thm24.1 with its coefficient-ring and local-constant/finiteness hypotheses; match geometric versus arithmetic Frobenius conventions | P05.6 with P09 |
| Coherent curve H1 | Divisors, line bundles, coherent cohomology, Serre duality and comparison with the de Rham side required by a retained p-adic comparison | P06.5 with P10 |

**Task F19-C:** lock the exact input category and proof lemmas for each retained specialization, including finiteness, smoothness/properness, coefficient hypotheses and transition maps. Milne's lecture notes give an accessible statement map but explicitly prioritize exposition; select a complete original/Stacks proof where a proof is only sketched. The plan does not require every theorem in SGA4/5 or the full Weil-conjecture proof.

## Mathlib boundary and handoff

The [baseline](../../plan/mathlib-baseline.md) already contains etale/pro-etale sites and ell-adic cohomology definitions. These definitions do not supply the geometric comparison/base-change/duality results requested here. Reuse the existing sheaf/homological foundations, then prove the selected geometric theorems as independent outputs.

P05.6/P06.5 feed [P09](../../work-packages/09-abelian-degeneration-and-weights.md), [P10](../../work-packages/10-p-adic-comparison.md), [P12](../../work-packages/12-relative-anabelian-geometry.md) and [P15](../../work-packages/15-mono-anabelian-reconstruction.md). The small pi1 core of P05 can be released before these larger cohomological outputs; the latter should not delay every finite-cover theorem.

[Foundation map](README.md) · [SGA1/pi1](sga1-and-pi1.md) · [Kummer](stacks-kummer.md) · [Reusable milestones](../../plan/reusable-results.md)
