# P30 Native statement and compatibility closure

**Status:** planned. **Value:** IUT SPECIFIC.

Theorem-specific integration and mathematical interpretation review.

## Prerequisite outputs

- [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md)
- [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md)
- [P25 IUT III log-links and coricity](25-iut-iii-log-links.md)
- [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md)
- [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md)
- [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md)
- [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P30.1 | Statement fidelity | Write the literal full Lean statement using actual defined objects, input hypotheses and output groupoids; compare clause by clause with III573-580. |
| P30.2 | Indeterminacies | Implement Ind1 procession automorphisms, independent Ind2 local summand actions and Ind3 one-sided compatibility with exact domains and quotients. |
| P30.3 | Naturality and coherence | Prove all automorphism-equivariance, Kummer comparison, horizontal/vertical and evaluation compatibility squares listed in the clause matrix, including the content of Remarks3.11.1-4 needed to interpret them. |
| P30.4 | Closure review | Close A01-A09 and verify every retained source item has a proof/import. Prove that an abstract implementation interprets the native objects; no conclusion is assumed as a structure field. |

## Source targets

- [iut i](../sources/iut/iut-i.md)
- [iut ii](../sources/iut/iut-ii.md)
- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P31 IUT III Theorem 3.11](31-theorem-3-11.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
