# P26 IUT III theta monoids and etale-picture reconstruction

**Status:** planned. **Value:** IUT SPECIFIC.

The IUT multiradial theta layer, after standalone EtTh rigidity is complete.

## Prerequisite outputs

- [P20 Etale theta and its rigidity theorems](20-etale-theta.md)
- [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md)
- [P25 IUT III log-links and coricity](25-iut-iii-log-links.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P26.1 | Vertical theta | Prove Prop2.1 vertically coric monoids, Kummer isomorphisms and the projective mono-theta comparisons of clauses(ii),(iii),(vi). |
| P26.2 | Multiradial theta | Prove Thm2.2 and Cor2.3 with their exact input groupoids, automorphism equivariance, evaluation maps and constant/splitting data. |
| P26.3 | Prime-strip variants | Implement Def2.4 and the split-subquotient/realified prime-strip constructions actually used by LGP objects. |
| P26.4 | No silent identification | Prove the required natural comparison maps; keep distinct realizations and their prescribed poly-isomorphisms explicit. |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
