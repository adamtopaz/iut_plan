# P13 Tempered groups and geometric reconstruction

**Status:** planned. **Value:** ★ REUSABLE.

Tempered anabelian geometry, reduction-graph reconstruction and nonarchimedean coverings.

## Prerequisite outputs

- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md)
- [P11 Trees and discrete/profinite subgroup theory](11-trees-and-profinite-groups.md)
- [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P13.1 | Tempered objects | Define tempered coverings and their topological automorphism groups; prove the fundamental exact sequence and profinite-completion comparison from Andre sections4-6. |
| P13.2 | Stable graph | Implement Semi-graphs Thm3.7 and Cors3.9/3.11 at their actual corrected hypotheses: recover stable graphs, vertices/edges and inertia data. |
| P13.3 | Relative comparison | Prove Semi-graphs Thm6.4/6.5 under its actual base-field/geometricity assumptions, using P12 rather than assuming an arbitrary local Galois isomorphism is geometric. |
| P13.4 | Torsion and cusps | Prove Thm6.8(iii) for once-punctured elliptic curves, compatibility with Tate modules, and the Cor6.11/Thm6.12 cusp/integral-structure outputs. |
| P13.5 | Corrections | Discharge the general Galois-countability requirements or prove that a specialized geometric construction suffices. Apply the correction attachments, not only the original preprint. |

## Source targets

- [andre tempered](../sources/anabelian/andre-tempered.md)
- [semi graphs](../sources/anabelian/semi-graphs.md)
- [galois sections](../sources/anabelian/galois-sections.md)

**Two-stage export:** covering/group definitions and the basic comparison belong to P13.1 and can proceed from P05/P08/P11. Geometric/torsion reconstruction waits for P12. IUT data-type work may consume the early definitions before reconstruction is complete.

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md), [P20 Etale theta and its rigidity theorems](20-etale-theta.md), [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
