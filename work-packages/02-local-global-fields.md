# P02 Local and global fields, unit logarithms and lattices

**Status:** planned. **Value:** ★ REUSABLE.

Local harmonic analysis, p-adic representations, height theory and computational arithmetic.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P02.1 | Finite extensions | Connect arbitrary finite extensions of Q_p and number-field completions to existing valued/local-field structures, ring of integers, residue field and ramification APIs. |
| P02.2 | Units and logarithms | Prove convergence, multiplicativity, functoriality, torsion kernel, exp/log inverses on sufficiently small units, and the image lattice of log on all units. Include residue characteristic two. |
| P02.3 | Integral arithmetic | Provide norm/trace, fractional ideals, integral closure and finite-etale product decompositions. Export explicit local-degree normalizations. |
| P02.4 | Global normalizations | Reconcile the existing product formula and Dirichlet unit theorem with the local conventions; prove the all-place integrality/root-of-unity lemma with archimedean hypotheses. |

## Source targets

- [field number theory](../sources/foundations/field-number-theory.md)
- [local fields](../sources/foundations/local-fields.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md), [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md), [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md), [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md), [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md), [P25 IUT III log-links and coricity](25-iut-iii-log-links.md), [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
