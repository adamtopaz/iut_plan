# P29 IUT III global Kummer and non-interference

**Status:** planned. **Value:** IUT SPECIFIC.

Global IUT Kummer assembly with its ordinary number-theoretic leaf available independently.

## Prerequisite outputs

- [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md)
- [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md)
- [P25 IUT III log-links and coricity](25-iut-iii-log-links.md)
- [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md)
- [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P29.1 | Global Kummer | Prove Prop3.10(i) comparisons between reconstructed global fields, monoids and realified/non-realified Frobenioids. |
| P29.2 | Non-interference | Prove Prop3.10(ii) using the all-place integrality/root-of-unity result with every archimedean condition; finite-place units alone do not imply torsion. |
| P29.3 | Vertical compatibility | Formalize the totality of permitted log-link precomposites and Prop3.10(iii); prove MOD compatibility and the exact limitation for mod data. |
| P29.4 | Horizontal preparation | Export natural isomorphisms, embeddings and degree/evaluation compatibility at the exact labeled interfaces needed for Theorem3.11(ii),(iii). |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
