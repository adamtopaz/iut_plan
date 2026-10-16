# F09 · Silverman, Advanced Topics: Tate uniformization

**★ REUSABLE · Retained nonarchimedean theorem.** [Silverman, *Advanced Topics in the Arithmetic of Elliptic Curves*](https://www.math.brown.edu/johsilve/ATAECHome.html), GTM 151 (1994), Chapter V, *Elliptic Curves over Complete Fields*, printed pp.408–453 in the [publisher record](https://link.springer.com/book/10.1007/978-1-4612-0851-8). Chapter IV supplies selected reduction theory when needed.

## Selected results and boundaries

- For a finite extension `K/ℚ_p` and `q ∈ K` with `0 < |q| < 1`, construct `E_q` and prove its analytic uniformization over the appropriate complete analytic field. Separately derive the Galois-equivariant algebraic-point isomorphism `K̄ˣ/q^ℤ ≅ E_q(K̄)`, and prove compatibility between these exports.
- Identify `[n]`-torsion by roots of unity and `n`th roots of `q`; export the exact sequence `0 → μ_n → E_q[n] → ℤ/n → 0` in characteristic zero and its Kummer extension class.
- Prove the `j`-expansion and valuation normalization, and the converse uniformization at split multiplicative reduction. Handle nonsplit reduction only with the explicit extension/twist data required by the caller.
- Develop the convergent products/series and divisor/translation identities needed to connect the Tate cover to the precise theta object in [EtTh](../anabelian/etale-theta.md). That theta normalization is fixed by EtTh, rather than an arbitrary classical complex theta function.

**Selection task F09-T:** pin exact Chapter V theorem/proposition numbers and match `q`, roots, sign and divisor conventions to EtTh §1. This is the missing source lock, not an invitation to formalize the whole textbook.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md), [P07](../../work-packages/07-elliptic-curves.md), and the analytic foundations in [F17](rigid-analytic-foundations.md). Deliver [P08](../../work-packages/08-tate-and-analytic-curves.md), feeding [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P20](../../work-packages/20-etale-theta.md) and [P23](../../work-packages/23-iut-ii-local-evaluation.md). Series/divisor calculations and finite torsion/Kummer diagrams can proceed as parallel subprojects.

## Mathlib boundary and reusable release

Existing Weierstrass and reduction theory is reusable; the [pinned searches](../../plan/mathlib-baseline.md) did not locate a Tate-curve/uniformization theorem. Complex Jacobi theta and Weierstrass `℘` are useful on a separate complex branch and do not supply this statement.

Release uniformization plus the torsion extension/Kummer diagram. Applications include local elliptic Galois representations, multiplicative degeneration, local heights and Mumford-curve examples.

[Foundation map](README.md) · [André](../anabelian/andre-tempered.md) · [Local Kummer theory](stacks-kummer.md)
