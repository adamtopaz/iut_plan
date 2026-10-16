# P21 IUT I input and theater data types

**Status:** planned. **Value:** IUT SPECIFIC.

An explicit IUT vocabulary layer over general-purpose geometry; broadly useful ingredients remain in their independent libraries.

## Prerequisite outputs

- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md)
- [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md)
- [P18 Frobenioid and poly-Frobenioid constructions](18-frobenioid-definitions.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P21.1 | Initial data | Translate IUT I Def3.1(a)-(f) literally: fields, punctured elliptic/orbicurves, l-torsion image, selected places and cusp conditions. |
| P21.2 | Strips and labels | Define D/F-prime strips, capsules, signed/multiplicative labels and forgetful functors from Defs4.1,5.2,6.1 and surrounding constructions. |
| P21.3 | Bridges/processions | Define the bridge and procession structures, ordered index data, automorphism groupoids and the final theater type (Def6.13). |
| P21.4 | Hypotheses | Keep stable reduction and mod-l image conditions as supplied hypotheses; proving universal existence of initial data is a separate application, not a hidden theorem premise. |

## Source targets

- [iut i](../sources/iut/iut-i.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
