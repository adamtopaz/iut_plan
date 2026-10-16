# P06 Algebraic curves, linear systems and Belyi maps

**Status:** planned. **Value:** ★ REUSABLE.

Curve arithmetic, dessins, finite covers, rational maps and geometric reconstruction.

## Prerequisite outputs

- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P06.1 | Curves and covers | Define smooth proper connected curves, punctured curves, function fields, genus, hyperbolicity, finite maps and needed Riemann-Hurwitz/tame-cover formulas. |
| P06.2 | Linear systems | Prove the curve forms of Riemann-Roch, Serre duality, divisor/line-bundle correspondence and basepoint-free linear-system statements consumed by reconstruction. |
| P06.3 | Belyi | Formalize Belyi existence and the open-curve formulation; formalize Noncritical Belyi Cor1.2 and Thm2.5 with prescribed finite sets. |
| P06.4 | Orbicurves | Provide tame orbicurves/quotient stacks or a proved equivalent equivariant-cover encoding, with inertia/cusp and field-of-moduli data. |
| P06.5 | Coherent/de Rham curve interfaces | Export coherent curve H1, Serre duality, de Rham comparison inputs and the selected function/Jacobian bridges required by P09/P10/P15; agree coefficient/filtration conventions with P03/P05. |

## Source targets

- [algebraic curves](../sources/foundations/algebraic-curves.md)
- [noncritical belyi](../sources/anabelian/noncritical-belyi.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md), [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md), [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md), [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md), [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md), [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
