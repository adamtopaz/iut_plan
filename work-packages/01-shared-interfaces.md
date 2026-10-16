# P01 Shared interfaces and the mathlib baseline

**Status:** planned. **Value:** ★ REUSABLE.

Reusable profinite and categorical APIs for Galois theory, descent, representation theory and geometric fundamental groups.

## Prerequisite outputs

This is the starting integration package. It reuses the pinned mathlib baseline.

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P01.1 | Baseline | Pin the mathlib revision and identify exact imports; reuse the abstract Galois-category equivalence, schemes, finite Kummer theory and Haar measure. |
| P01.2 | Outer maps | Agree on continuous outer homomorphisms over a base Galois group, conjugacy orbits, equivalences and functoriality. Do not identify an orbit with a chosen map. |
| P01.3 | Systems | Agree on universes, fiber functors, inverse/filtered systems, topological modules and comparison maps; prove independence of choices. |
| P01.4 | Source locks | Run A01 and A02 in the audit ledger. Fix editions, author/journal page crosswalks, correction attachments and the export signature of each package. |

## Source targets

- [field number theory](../sources/foundations/field-number-theory.md)
- [sga1 and pi1](../sources/foundations/sga1-and-pi1.md)
- [continuous galois cohomology](../sources/foundations/continuous-galois-cohomology.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md), [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md), [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md), [P11 Trees and discrete/profinite subgroup theory](11-trees-and-profinite-groups.md), [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md), [P18 Frobenioid and poly-Frobenioid constructions](18-frobenioid-definitions.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
