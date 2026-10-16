# P23 IUT II local theta evaluation and synchronization

**Status:** planned. **Value:** IUT SPECIFIC.

Source-specific assembly of reusable theta and anabelian results.

## Prerequisite outputs

- [P20 Etale theta and its rigidity theorems](20-etale-theta.md)
- [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P23.1 | Mono-theta transport | Prove the required IUT II section1 rigidity and multiradial mono-theta environment comparisons, including exact input enhancement. |
| P23.2 | Galois evaluation | Formalize section2 and Cor2.5: evaluate the theta class at the selected torsion points and obtain the source-normalized quadratic j-squared profile. |
| P23.3 | Synchronization | Prove section3 conjugate synchronization, splitting monoids and Cors3.5/3.6 with common versus independent conjugacy ambiguity explicit. |
| P23.4 | Local realization | Compare the group-reconstructed output and the concrete theta/Gaussian monoids; preserve labels, constants, integral structures and automorphism actions. |

## Source targets

- [iut ii](../sources/iut/iut-ii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
