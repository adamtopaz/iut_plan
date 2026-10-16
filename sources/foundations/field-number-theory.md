# F01 · Field and algebraic number theory

**★ REUSABLE · Retained results; accessible alternative references.**

Use [Milne, *Fields and Galois Theory*](https://www.jmilne.org/math/CourseNotes/ft.html) for separable closures, Krull topology and Galois correspondence; use [Milne, *Algebraic Number Theory*, v3.08](https://www.jmilne.org/math/CourseNotes/ANT.pdf) for the arithmetic interfaces. Lang's *Algebraic Number Theory* is the older caller's reference, rather than an additional library to duplicate.

## Selected results and boundaries

| Item | Lean-facing statement / selection task | Why retained |
|---|---|---|
| Infinite Galois correspondence | Closed subgroups of `Gal(L/K)` correspond to intermediate fields for an algebraic Galois extension; open subgroups correspond to finite subextensions. Reuse mathlib. | Absolute Galois groups and finite-cover dictionaries. |
| ANT Theorem 7.15; Lemma 7.16 | Product formula for a number field, together with place-extension and norm compatibility in a finite extension. Fix the source's normalized absolute values and prove the conversion to local-degree weights. | Global degrees and tensor-packet normalization. |
| ANT Theorem 5.1 and its logarithmic proof | Dirichlet unit theorem, including the full lattice in the product-formula hyperplane. | Frobenioids I Theorem 6.4 uses the lattice, beyond a group-rank formula. |
| Kronecker lemma | A nonzero algebraic integer all of whose complex conjugates have modulus at most one is a root of unity. | IUT III Proposition 3.10's global intersection argument. Caller: Lang, p.144, proof of Theorem 5. **Selection task F01-K:** pin the Lang edition or write a self-contained bounded-coefficient proof. |

These are characteristic-zero number-field statements. No prime-number theorem or abc reduction is imported by this card.

## Interfaces and parallel work

Ready inputs: field extensions, valuations, Dedekind rings and finite-dimensional linear algebra from mathlib and [P01](../../work-packages/01-shared-interfaces.md). Deliver arithmetic bridges through [P02](../../work-packages/02-local-global-fields.md), consumed by [P19](../../work-packages/19-frobenioid-reconstruction.md), [P27](../../work-packages/27-measured-tensor-packets.md) and [P29](../../work-packages/29-iut-iii-global-kummer.md). The Kronecker proof can be developed independently of anabelian geometry.

## Mathlib boundary and reusable release

At the [pinned baseline](../../plan/mathlib-baseline.md), infinite Galois correspondence, number fields, places/completions, the product formula and Dirichlet units are positive reuse. The task is to audit exact hypotheses and connect their normalizations to the exported interfaces. A release should expose extension-of-places/norm diagrams and the normalized logarithmic unit lattice for arithmetic Picard groups, heights and adelic geometry.

[Foundation map](README.md) · [Local fields](local-fields.md) · [Frobenioids I](../anabelian/frobenioids-i.md)
