# P07 Geometric elliptic curves, torsion and reduction

**Status:** planned. **Value:** ★ REUSABLE.

Elliptic curves, arithmetic representations, isogenies, pairings and local reduction theory.

## Prerequisite outputs

- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P07.1 | Geometric bridge | Identify the existing Weierstrass elliptic-curve API with the required smooth proper genus-one pointed curves and group schemes. |
| P07.2 | Torsion | Construct multiplication-by-n, E[n], the required finite-etale structures, Weil pairing and Galois action; prove the cyclotomic determinant statement with its prime/characteristic hypotheses. |
| P07.3 | Reduction | Connect existing DVR minimal equations and reduction types to the geometric good/semistable/split-multiplicative models used downstream. |
| P07.4 | Signed quotients | Construct the once-punctured curve and its +/-1 orbicurve quotient, selected torsion covers and signed labeling operations. |

## Source targets

- [elliptic curves](../sources/foundations/elliptic-curves.md)
- [tate uniformization](../sources/foundations/tate-uniformization.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md), [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md), [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md), [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
