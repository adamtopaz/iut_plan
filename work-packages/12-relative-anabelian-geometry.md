# P12 Relative p-adic anabelian Hom and Isom

**Status:** planned. **Value:** ★ REUSABLE.

A major reusable p-adic anabelian theorem, independent of IUT assembly.

## Prerequisite outputs

- [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md)
- [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P12.1 | Native statement | State the required relative Isom/Hom maps over a fixed sub-p-adic field or an actual base-field embedding, with continuous outer maps and all openness/geometric conditions. |
| P12.2 | Isom specialization | A finite-p-adic Isom specialization can be an early release for local EtTh consumers. Also prove the number-field/sub-p-adic Isom class or actual localization/descent bridge required by the retained AbsTopII/III consumers; document whether it genuinely avoids any full Hom proof machinery. |
| P12.3 | Published proof route | Formalize Local Pro-p ThmA/16.5 and the Galois Sections Thm1.2 route at the required scope, including all selected comparison inputs. |
| P12.4 | Functoriality | Prove naturality for open subgroups/covers, marked points and base change, with the exact ambiguity carried throughout. |

## Source targets

- [local pro p](../sources/anabelian/local-pro-p.md)
- [galois sections](../sources/anabelian/galois-sections.md)
- [absolute anabelian curves](../sources/anabelian/absolute-anabelian-curves.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md), [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
