# P28 IUT III LGP and lgp constructions

**Status:** planned. **Value:** IUT SPECIFIC.

IUT LGP assembly; underlying tensor and degree calculus remains a separate reusable output.

## Prerequisite outputs

- [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md)
- [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md)
- [P25 IUT III log-links and coricity](25-iut-iii-log-links.md)
- [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md)
- [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P28.1 | Local LGP | Prove Props3.4 and3.5, including monoid actions, splitting monoids and precise upper semi-compatibility for local Kummer maps. |
| P28.2 | Global objects | Implement Ex3.6 and Prop3.7(i)-(v) global/realified Frobenioids, embeddings and compatible degree maps. |
| P28.3 | Pilots and lattice | Construct Def3.8 LGP/lgp links, pilots and lattice; prove the comparisons needed to extend earlier constructions. |
| P28.4 | Volume finish | Complete the joint P27/P28 proof of Prop3.9(iv) with shared normalizations. Keep this output downstream of local packet construction to avoid a package-level proof cycle. |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
