# P24 IUT II global Kummer gluing and horizontal links

**Status:** planned. **Value:** IUT SPECIFIC.

IUT global assembly; reusable Kummer and categorical APIs are separate dependencies.

## Prerequisite outputs

- [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md)
- [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md)
- [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md)
- [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md)
- [P23 IUT II local theta evaluation and synchronization](23-iut-ii-local-evaluation.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P24.1 | Global Gaussian objects | Prove the required section4 global Frobenioids, good/archimedean realizations and Props4.2(i)/4.4(i). |
| P24.2 | Kummer gluing | Prove Cors4.6(iii)-(v),4.7(iii),4.8(i)-(iii); state gluing maps, quotient data, evaluation and naturality explicitly. |
| P24.3 | Pilots and links | Construct Def4.9(viii) pilot data, Cor4.10(ii),(iv) and Cor4.11(ii),(iii), with source/target and degree normalizations fixed. |
| P24.4 | Export | Prove the exact local/global compatibility interfaces consumed by III.3.11 and the preliminary III.1/2 constructions; no compatibility is left as prose. |

## Source targets

- [iut ii](../sources/iut/iut-ii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P25 IUT III log-links and coricity](25-iut-iii-log-links.md), [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md), [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md), [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
