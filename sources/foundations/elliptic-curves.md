# F08 · Silverman, The Arithmetic of Elliptic Curves

**★ REUSABLE · Retained selected statements.** [Silverman's author page and errata](https://www.math.brown.edu/johsilve/AECHome.html), second edition (2009); [author's contents](https://www.math.brown.edu/johsilve/AEC/AECPrefaceTOCIntro.pdf).

## Selected results and boundaries

| Portion | Precise deliverable |
|---|---|
| Chapter III: elliptic curves and their morphisms | Equivalence between smooth projective geometrically integral genus-one curves with a rational origin and the appropriate nonsingular Weierstrass models, with agreement of group structures and morphisms. |
| Chapter III §§6–8: dual isogenies, Tate module, Weil pairing | For positive `n` invertible in the base field, `[n]` is a finite étale isogeny of degree `n²`, geometric `E[n] ≅ (ℤ/n)²`, and the Weil pairing is perfect, alternating and Galois equivariant. Export the cyclotomic determinant for `T_ℓ(E)` with `ℓ` invertible. |
| Chapter VII: local elliptic curves | Geometric good/multiplicative reduction, local model comparison and the particular finite-extension behavior used by initial data and theta constructions. |

**Selection task F08-E:** lock proposition numbers after checking the selected edition and record the compatibility of the torsion-field definition `F(E[ℓ])` with geometric points. The contents/subject selection is verified; this card does not claim a completed theorem-by-theorem proof audit of Silverman.

The IUT input assumes its specified mod-`ℓ` Galois image; this does not add Serre's open-image theorem to the prerequisite list. Mordell–Weil, Siegel, modularity and BSD are not imported by this card. Tate uniformization is separately [F09](tate-uniformization.md).

## Interfaces and parallel work

Ready inputs: [P06](../../work-packages/06-curves-and-belyi.md) geometric curves and existing Weierstrass algebra. Deliver [P07](../../work-packages/07-elliptic-curves.md), consumed by [P08](../../work-packages/08-tate-and-analytic-curves.md), [P09](../../work-packages/09-abelian-degeneration-and-weights.md), [P20](../../work-packages/20-etale-theta.md) and [P21](../../work-packages/21-iut-inputs-and-theater-data.md). Work on algebraic torsion/pairings can proceed before anabelian proofs.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates Weierstrass equations, nonsingularity, discriminant, `j`, the point group law, integral/minimal equations and reduction predicates. It does not certify the complete geometric-category bridge, torsion/pairing package or Tate uniformization. Extend the existing theory through explicit bridge theorems.

Release the geometric/Weierstrass equivalence and then finite étale torsion with Weil pairing. They serve isogeny descent, Galois representations, modular curves and explicit arithmetic.

[Foundation map](README.md) · [Tate curves](tate-uniformization.md) · [Abelian varieties](abelian-varieties-weights.md)
