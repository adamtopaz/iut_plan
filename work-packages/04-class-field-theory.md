# P04 Local reciprocity, duality and local Galois structure

**Status:** planned. **Value:** ★ REUSABLE.

Local number theory, Galois cohomology, arithmetic duality and non-IUT anabelian geometry.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P04.1 | Reciprocity | Formalize Milne CFT I.Theorems1.1 and1.4, or an equivalent source-locked proof route: local reciprocity and existence with explicit topology and Frobenius convention. |
| P04.2 | Naturality | Prove norm/restriction and inclusion/transfer compatibility, including Milne CFT III.Lemma3.2. Export the completed multiplicative-group/Galois-abelianization comparison. |
| P04.3 | Local duality | Select and prove the local Tate-duality, cohomological-dimension and local pro-p structure statements actually consumed by the reconstruction proofs (A04). |
| P04.4 | Compatible layers | Prove compatibility with unit filtrations, cyclotomic characters and finite extensions. Do not infer additive field reconstruction from reciprocity alone. |

## Source targets

- [class field theory](../sources/foundations/class-field-theory.md)
- [continuous galois cohomology](../sources/foundations/continuous-galois-cohomology.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md), [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md), [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
