# F13 · Faltings–Chai, Degeneration of Abelian Varieties

**★ REUSABLE · Retained specialized degeneration result.** Gerd Faltings and Ching-Li Chai, [*Degeneration of Abelian Varieties*](https://link.springer.com/book/10.1007/978-3-662-02632-8), Ergebnisse 22 (1990).

## Exact caller anchor and selected scope

[Absolute Anabelian Geometry](../anabelian/absolute-anabelian-curves.md), **Lemma 1.1.5**, explicitly cites **Chapter III, Corollary 7.3** for the semistable/semiabelian degeneration input. The related combinatorial reconstruction uses nondegeneracy of the period pairing. These are the retained requests, rather than the whole theory of toroidal compactifications.

**Selection task F13-D:** extract Corollary III.7.3 with its exact base, polarization, degeneration and residue-field hypotheses; list the Tate-module filtration and period-pairing assertions actually consumed. Write the specialized statement for the semistable Jacobian of the relevant curve over a complete discretely valued field with finite residue field, with a prime `ℓ` different from residue characteristic. Check separately whether a claim for `ℓ = p` is used; it cannot be obtained from the prime-to-`p` statement by renaming the prime.

**Recursive task F13-P:** choose a proof of that specialization and enumerate its semiabelian extension, lattice/uniformization and pairing lemmas. Identify every use of stable reduction existence, as distinct from working under a semistable-reduction hypothesis. If the chosen proof uses formal models, connect to [F17](rigid-analytic-foundations.md). The original corollary's full statement/proof is not independently audited here.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md) valuation theory, [P06](../../work-packages/06-curves-and-belyi.md) stable curves/Jacobians, [P07](../../work-packages/07-elliptic-curves.md) torsion conventions. Deliver [P09](../../work-packages/09-abelian-degeneration-and-weights.md). Consumers: [P12](../../work-packages/12-relative-anabelian-geometry.md), [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P14](../../work-packages/14-cuspidalization.md) and [P16](../../work-packages/16-local-global-galois-reconstruction.md) through their curve-kernel/graph reconstruction proofs. Finite-field weights are a separate parallel team, [F14](abelian-varieties-weights.md).

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) does not certify the required semiabelian/Jacobian degeneration theorem; existing elliptic reduction predicates alone do not supply it. A reusable milestone is a functorial semistable Tate-module filtration with its nondegenerate period pairing, specialized and tested on Tate curves. This serves monodromy, degenerating Jacobians and stable-curve geometry.

[Foundation map](README.md) · [Tate uniformization](tate-uniformization.md) · [Combinatorial GC](../anabelian/combinatorial-gc.md)
