# F14 · Abelian varieties, Jacobians and finite-field Weil weights

**★ REUSABLE · Retained specialized Weil theorem.** Canonical original caller: Mumford, *Abelian Varieties*, p.206, cited by [Absolute Anabelian Geometry](../anabelian/absolute-anabelian-curves.md), Lemma 1.1.5. Accessible alternative: [Milne, *Abelian Varieties*, v2.00](https://www.jmilne.org/math/CourseNotes/AV.pdf), **Chapter II, Theorem 1.1(b), printed p.75**, and **Lemmas 1.2–1.3**.

## Selected results and proof boundary

For an abelian variety `A/𝔽_q` and `ℓ` different from the characteristic, the Frobenius characteristic polynomial on its rational Tate module has algebraic roots whose every complex realization has absolute value `√q`. State whether Frobenius acts covariantly or contravariantly and derive the corresponding `H¹` formulation; twists/inverses alter the convention.

The accessible proof uses polarizations, the Rosati involution and its positivity, together with the degree/characteristic-polynomial theory of endomorphisms. These supporting statements must be formalized. For curve consumers, also construct the Jacobian and its Tate-module identification with geometric abelianization.

**Selection task F14-W:** pin those supporting results and the Jacobian comparison, then derive the precise weight-separation/no-trivial-quotient lemmas used by Absolute Anabelian Lemma 1.1.5 and Combinatorial GC Proposition 2.4. Weight-0/1/2 filtrations need their own construction; the pure abelian-variety theorem alone does not define them.

This specialized route avoids importing the full Weil conjectures for arbitrary varieties. Honda–Tate classification, global Faltings isogeny/Mordell theorems and all moduli theory are not automatic dependencies.

## Interfaces and parallel work

Ready inputs: [P06](../../work-packages/06-curves-and-belyi.md) curves/Picard groups, finite étale torsion and geometric cohomology. Deliver [P09](../../work-packages/09-abelian-degeneration-and-weights.md), alongside [F13](faltings-chai.md). Consumers: [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P14](../../work-packages/14-cuspidalization.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md). The finite-field Rosati/weights branch can proceed independently of `p`-adic comparison.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) does not certify this abelian-variety package or its Weil theorem. Reuse linear algebra, schemes, finite fields and existing elliptic algebra; audit exact declarations before implementation. Release Jacobian/Tate-module and polarization interfaces, then finite-field Weil weights. These benefit arithmetic monodromy, point counts and Galois representations.

[Foundation map](README.md) · [Combinatorial GC](../anabelian/combinatorial-gc.md) · [Reusable results](../../plan/reusable-results.md)
