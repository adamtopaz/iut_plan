# P09 Abelian varieties, degeneration and finite-field weights

**Status:** planned. **Value:** ★ REUSABLE.

Abelian varieties, Jacobians, semistable degeneration, l-adic representations and curve reduction.

## Prerequisite outputs

- [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P09.1 | Abelian/Jacobian geometry | Implement the required abelian varieties and curve Jacobians, torsion, Tate modules and functoriality; lock the specialization actually used in the anabelian proofs. |
| P09.2 | Finite-field weights | Prove the abelian-variety Weil/RH statement and the weight0/1/2 exclusions consumed by Absolute Anabelian Geometry Lem1.1.5 and Combinatorial GC. |
| P09.3 | Degeneration | Formalize the required Faltings-Chai III.Cor7.3 specialization: semiabelian degeneration, Tate-module filtration and nondegenerate period pairing. |
| P09.4 | Special-fiber interface | Export stable/nodal pointed-curve dual graphs, vertex Jacobians, cusps and inertia with the exact weight and filtration hypotheses. Audit any additional stable-reduction existence theorem used by this proof route. |

## Source targets

- [abelian varieties weights](../sources/foundations/abelian-varieties-weights.md)
- [faltings chai](../sources/foundations/faltings-chai.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md), [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
