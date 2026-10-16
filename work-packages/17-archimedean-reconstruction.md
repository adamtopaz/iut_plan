# P17 Archimedean topology and Aut-holomorphic reconstruction

**Status:** planned. **Value:** ★ REUSABLE.

Complex and topological reconstruction methods, fundamental groups and canonical measure conventions.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md)
- [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P17.1 | Elementary topology | Develop circle universal covers, real/complex topological modules, segment monoids, radial/angular measures and choice-independent normalizations. |
| P17.2 | Aut-holomorphic spaces | Formalize the selected AbsTopIII Props2.2,2.5-2.6 and Cors2.3,2.7-2.9 reconstruction of complex/Aut-holomorphic orbicurve structures and its geometric admissibility hypotheses. |
| P17.3 | Global compatibility | Prove the needed section4 Prop4.2, Lemmas4.3-4.4 and Cor4.5 log-Frobenius compatibility and section5 Prop5.8(iv)-(vi)/Cor5.10(iv) realization. |
| P17.4 | Complex input audit | Close A07: select the precise complex uniformization/covering/analytic lemmas used by these reconstructions; include additional sources only when a retained proof consumes them. |

## Source targets

- [abstop iii](../sources/anabelian/abstop-iii.md)
- [algebraic curves](../sources/foundations/algebraic-curves.md)

**Two-stage export:** circle/segment/measure constructions can be proved from P01 and real/complex topology immediately. The global Aut-holomorphic interpretation waits for P15. P19 needs the corresponding local archimedean output, not all global reconstruction theorems.

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md), [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md), [P25 IUT III log-links and coricity](25-iut-iii-log-links.md), [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
