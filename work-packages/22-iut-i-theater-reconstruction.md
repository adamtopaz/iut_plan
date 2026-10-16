# P22 IUT I theater reconstruction and symmetries

**Status:** planned. **Value:** IUT SPECIFIC.

IUT assembly; prior reusable results must remain separately importable.

## Prerequisite outputs

- [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md)
- [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md)
- [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md)
- [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md)
- [P20 Etale theta and its rigidity theorems](20-etale-theta.md)
- [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P22.1 | Local interfaces | Formalize the required IUT I sections1-2 tempered/categorical reconstruction and compatibility inputs selected by the theater constructions. |
| P22.2 | Theaters | Prove sections3-6 construction/gluing and reconstruction statements needed for Theta and signed/NF theaters, with isomorphism torsors explicit. |
| P22.3 | Processions | Prove Prop6.9(iii), Cor6.10(iii), and supporting4.11/4.12: procession functors, labels, forgetful symmetries and etale-picture permutations. |
| P22.4 | Final bridge | Construct Def6.13 final theater and prove its claimed uniqueness/functoriality relative to the chosen initial data; export the exact IUT II/III input structures. |

## Source targets

- [iut i](../sources/iut/iut-i.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P23 IUT II local theta evaluation and synchronization](23-iut-ii-local-evaluation.md), [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md), [P25 IUT III log-links and coricity](25-iut-iii-log-links.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
