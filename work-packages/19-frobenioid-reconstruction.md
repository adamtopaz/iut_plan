# P19 Frobenioid reconstruction, reciprocity and degrees

**Status:** planned. **Value:** ◇ IUT SUPPORT.

Specialized reusable categorical reconstruction, with explicit arithmetic normalization.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md)
- [P11 Trees and discrete/profinite subgroup theory](11-trees-and-profinite-groups.md)
- [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md)
- [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md)
- [P18 Frobenioid and poly-Frobenioid constructions](18-frobenioid-definitions.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P19.1 | Categorical reconstruction | Prove FrobenioidsI Thm3.4 selected clauses and required4.2/4.9 consequences with standard-type, slimness and non-group-like hypotheses explicit. |
| P19.2 | Arithmetic degree | Prove Thm6.4(ii),(iv), including Dirichlet/Picard inputs, positive scale ambiguity for realifications and conditions forcing degree-one normalization. |
| P19.3 | Local Kummer | Prove FrobenioidsII Thm2.4 with saturation/temp-slimness and corrected countability requirements; recover both Kummer and reciprocity maps. |
| P19.4 | Poly reconstruction | Prove the required Thm5.5 clauses, including heterogeneous modifications and lattice conditions. Do not insert unsupported injectivity or degree-one claims. |

## Source targets

- [frobenioids i](../sources/anabelian/frobenioids-i.md)
- [frobenioids ii](../sources/anabelian/frobenioids-ii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P20 Etale theta and its rigidity theorems](20-etale-theta.md), [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md), [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
