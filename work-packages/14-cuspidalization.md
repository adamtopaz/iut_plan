# P14 Combinatorial, abelian and Belyi cuspidalization

**Status:** planned. **Value:** ★ REUSABLE.

Reconstruction of punctures, additional covers, cuspidal groups and curve function theory.

## Prerequisite outputs

- [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md)
- [P11 Trees and discrete/profinite subgroup theory](11-trees-and-profinite-groups.md)
- [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P14.1 | Combinatorial recognition | Prove Combinatorial GC Prop1.2, Prop2.4, Thm1.6, Cor2.7 with the corrected proof and stable-weight inputs. |
| P14.2 | Cusp criterion | Formalize corrected AbsTopI Lem4.5 and Thm4.7 chain-category reconstruction. Separate the relative Isom assumptions from the additional Hom assumptions in stronger clauses. |
| P14.3 | Abelian cuspidalization | Resolve the caller/callee numbering mismatch A02, then prove the selected maximal cuspidally abelian and rational-function/Green-trivialization results. |
| P14.4 | Belyi cuspidalization | Prove AbsTopII Cor3.7 for the stated strictly-Belyi, chain-full, slim/cyclotomic and corrected terminal-rank/three-cusp hypotheses. |

## Source targets

- [combinatorial gc](../sources/anabelian/combinatorial-gc.md)
- [proper cuspidalizations](../sources/anabelian/proper-cuspidalizations.md)
- [abstop i](../sources/anabelian/abstop-i.md)
- [abstop ii](../sources/anabelian/abstop-ii.md)
- [noncritical belyi](../sources/anabelian/noncritical-belyi.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
