# F07 · Curves, Riemann–Roch and Serre duality

**★ REUSABLE · Retained results; choose one organized proof route.** [Hartshorne, *Algebraic Geometry*](https://link.springer.com/book/10.1007/978-1-4757-3849-0), Chapters III–IV, or [Liu, *Algebraic Geometry and Arithmetic Curves*](https://www.math.u-bordeaux.fr/~qliu/Book/index.html), Chapters 6–7. These are genuine alternatives for the curve-cohomology foundations; do not count both whole texts.

## Selected results and boundaries

| Exact mathematical target | Consumer / source selection |
|---|---|
| Divisor/invertible-sheaf dictionary; degree and principal divisors | Smooth projective geometrically integral curves over a field; function-field and Picard interfaces for reconstruction. |
| Serre duality on a smooth projective curve `C/k` | Perfect pairing between `H¹(C,L)` and `H⁰(C,ω_C ⊗ L⁻¹)` for a line bundle `L`; retain the trace and base-field hypotheses. |
| Riemann–Roch | `h⁰(L) − h⁰(ω_C ⊗ L⁻¹) = deg(L) + 1 − g`; deduce vanishing for large degree, prescribed values/jets, and basepoint-free linear systems. |
| Finite morphisms and punctured curves | Function-field correspondence, ramification/inertia, and the selected Riemann–Hurwitz consequences used by the cover constructions. |

**Selection task F07-RR:** pin exact theorem labels in the chosen edition; specialize each statement to the fields and curves actually used by AbsTopIII Propositions 1.1–1.3 and [Noncritical Belyi Theorem 2.5](../anabelian/noncritical-belyi.md). The two retained consumers are the reason this is more than optional background. Their proofs need section-separation constructions as well as the numerical Riemann–Roch equality.

Stable pointed curves and their dual graphs need a separate API, including nodes and branches. Existence of stable reduction is retained only for proof consumers that invoke it; an IUT input already assumed semistable does not itself require an existence theorem. Hyperbolic orbicurves require stack/equivariant-cover semantics, including quotient by the elliptic involution.

## Interfaces and parallel work

Ready inputs: scheme/line-bundle/cohomology infrastructure from [P01](../../work-packages/01-shared-interfaces.md). Deliver [P06](../../work-packages/06-curves-and-belyi.md); consumers [P07](../../work-packages/07-elliptic-curves.md), [P09](../../work-packages/09-abelian-degeneration-and-weights.md), [P14](../../work-packages/14-cuspidalization.md) and [P15](../../work-packages/15-mono-anabelian-reconstruction.md). Divisors, duality and cover theory can be separate teams sharing one geometric curve definition.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) provides extensive schemes, smoothness/properness and sheaf infrastructure, without certifying this complete curve package. Run a fresh declaration audit before starting each theorem. Release curve Riemann–Roch/duality and explicit section-separation corollaries as useful milestones for Jacobians, moduli, linear series and algebraic-geometric codes.

[Foundation map](README.md) · [SGA 1](sga1-and-pi1.md) · [Elliptic curves](elliptic-curves.md)
