# P11 Trees and discrete/profinite subgroup theory

**Status:** planned. **Value:** ★ REUSABLE.

Geometric group theory, profinite groups, graphs of groups and categorical Galois theory.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P11.1 | Trees | Formalize the needed group actions on trees, covering graphs, fixed-point statements and graph-of-groups constructions (Serre Trees selected targets). |
| P11.2 | Free and profinite groups | Develop the needed free-group presentations, profinite completions and subgroup/normalizer comparison statements; reconcile Ribes-Zalesskii edition numbering. |
| P11.3 | Anabelioid dictionary | Build Galois categories/anabelioids, covering morphisms, slimness and the selected reconstruction statements of Geometry of Anabelioids. |
| P11.4 | Countability | Prove the exact countable-generation/Galois-countability hypotheses required by the source corrections before using the general tempered/semigraph construction. |

## Source targets

- [serre trees](../sources/foundations/serre-trees.md)
- [ribes zalesskii](../sources/foundations/ribes-zalesskii.md)
- [geometry anabelioids](../sources/anabelian/geometry-anabelioids.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md), [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
