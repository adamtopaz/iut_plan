# F03 · Local class field theory: Milne and Serre

**★ REUSABLE · Retained theorem; choose one proof route.** Accessible route: [Milne, *Class Field Theory*, v4.03](https://www.jmilne.org/math/CourseNotes/CFT.pdf), 2020. Alternative: [Serre, *Local Fields*](local-fields.md), Chapters XII–XIV. Their local reciprocity proofs are alternatives; formalizing both is unnecessary.

## Selected results and boundaries

| Exact source item | Required theorem interface |
|---|---|
| Milne I Theorem 1.1 | For a nonarchimedean local field `K`, local reciprocity `Kˣ → Gal(Kᵃᵇ/K)` with the specified Frobenius convention; finite abelian quotients identified with norm quotients. |
| Milne I Theorem 1.4 | Existence theorem identifying open finite-index subgroups with norm subgroups of finite abelian extensions. |
| Milne III Theorem 3.1 | Cohomological Artin-map construction from the local fundamental class; needed if choosing this proof instead of Lubin–Tate. |
| Milne III Lemma 3.2 and §3.3 | Compatibility with norm, inclusion/transfer, restriction and towers. |

**Proof-completion task F03-N:** Milne's displayed Lemma III.3.2 labels its proof “To be added”. Supply the norm/transfer proof from cup-product functoriality or lock an equivalent proved Serre/NSW lemma. A displayed diagram alone is not a completed source proof.

Retain the inertia/unit and unramified/valuation identifications, and specify arithmetic versus geometric Frobenius once. Local duality and any pro-`p` group classification are separate [F04](continuous-galois-cohomology.md) selections. Full global CFT is not inferred from the presence of local CFT.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md) local fields and [P03](../../work-packages/03-continuous-cohomology.md) continuous cohomology. Prove/export [P04](../../work-packages/04-class-field-theory.md). Principal consumers: [P16](../../work-packages/16-local-global-galois-reconstruction.md) local multiplicative invariants and [P19](../../work-packages/19-frobenioid-reconstruction.md) Frobenioid reciprocity. The Lubin–Tate proof additionally needs its formal-group construction; that is a route decision, not a free prerequisite.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) finds finite Kummer theory, finite Hilbert 90 and ordinary cohomology. Local reciprocity/existence and their continuous diagrams were not located at the required scope. Audit the separately maintained [ClassFieldTheory project](https://github.com/kbuzzard/ClassFieldTheory) before duplicating effort; count only pinned declarations whose proof dependencies have been inspected.

A reusable milestone is the finite abelian norm-quotient theorem plus all tower diagrams, followed by the completed reciprocity statement. Applications include explicit abelian extensions, local Galois representations and arithmetic duality.

[Foundation map](README.md) · [Local fields](local-fields.md) · [Frobenioids II](../anabelian/frobenioids-ii.md)
