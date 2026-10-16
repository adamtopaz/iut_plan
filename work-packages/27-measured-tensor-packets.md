# P27 Measured tensor packets and integral structures

**Status:** planned. **Value:** ★ REUSABLE.

Measured local algebra, tensor-product lattices, determinant/degree formulas and arithmetic volume normalization.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md)
- [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md)
- [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P27.1 | Concrete finite packets | Prove finite tensor products of finite separable local extensions split as finite products of fields; construct integral orders, normalized lattices and permutation actions. |
| P27.2 | Measure | Prove Haar scaling/determinant and exact local-degree/progression weights, plus the separate archimedean radial/angular definitions. Do not call every weighted log-volume an ordinary Haar measure. |
| P27.3 | Reconstructed packets | After P25, prove Props3.1-3.3 and the needed Prop3.9 clauses identify the group-reconstructed packets and their integral structures with the concrete models. |
| P27.4 | Log-link compatibility | After P28, finish Prop3.9(iv) and every dependence on the LGP setup. These later outputs are exported separately so concrete local algebra can merge early. |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)
- [local fields](../sources/foundations/local-fields.md)

**Two-stage export:** P27.1–2 form the standalone concrete mathematics; the reconstructed comparison uses P25. The final Prop3.9(iv) proof is accepted with P28.4. P28 consumes only the earlier P27 exports. This refinement is essential: the full packets/volume chapter must not be treated as a circular black box.

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md), [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md), [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
