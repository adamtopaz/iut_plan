# P15 Mono-anabelian function-field and global reconstruction

**Status:** planned. **Value:** ★ REUSABLE.

Constructive/reconstruction-oriented anabelian geometry and functorial recovery of arithmetic structures.

## Prerequisite outputs

- [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md)
- [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md)
- [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md)
- [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P15.1 | Function fields | Formalize AbsTopIII Props1.1-1.8 as needed and Thm1.9: reconstruct the function field for the specified strictly Belyi hyperbolic orbicurve from the group extension. |
| P15.2 | Local field additions | Prove the Cor1.10 refinements using local duality, cyclotome synchronization, abelian cuspidalization, p-adic approximation and continuity. |
| P15.3 | Functorial algorithms | Make the input groupoid, output structures, natural transformations and uniqueness up to stated isomorphism explicit. An existential field identification alone is insufficient. |
| P15.4 | Global output | Develop the selected global-theater algorithms of section5, carrying localizations, multiplicative monoids, constants and degree data needed by IUT I/II. |

## Source targets

- [abstop iii](../sources/anabelian/abstop-iii.md)
- [abstop ii](../sources/anabelian/abstop-ii.md)
- [galois sections](../sources/anabelian/galois-sections.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md), [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md), [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
