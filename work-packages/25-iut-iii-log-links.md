# P25 IUT III log-links and coricity

**Status:** planned. **Value:** IUT SPECIFIC.

IUT links and coherence; analytic logarithm and measure results remain reusable below this layer.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md)
- [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md)
- [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md)
- [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P25.1 | Log-shell objects | Implement Def1.1 and Prop1.2 local/global log-shells, group actions, independent Ism/sign ambiguity and volume interfaces. |
| P25.2 | Log-links | Prove the log-link construction, its iterates, the specified nonarchimedean inclusions/archimedean surjections and exact normalized-volume statements. |
| P25.3 | Lattice | Construct Def1.4 log-theta lattice and prove Prop1.3 and Thm1.5 vertical, horizontal and bi-coricity. |
| P25.4 | LGP extension | Prove the extension required by Rem3.8.2 at exact data-level scope; an assertion that a definition generalizes formally needs an explicit comparison proof. |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md), [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md), [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
