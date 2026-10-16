# Interfaces that allow parallel work

The [package graph](../graphs/work-packages.md) schedules mathematical outputs. A team should be able to implement a consumer against a stable signature while another team supplies its proof. This requires agreement on actual objects and comparison maps, not only theorem names.

## Shared contracts

| Contract | Producers | Required data and laws | Consumers |
|---|---|---|---|
| Local arithmetic | P02, P04 | Finite local extensions, integers, norms/trace, units/valuations, cyclotomic modules, local reciprocity conventions and continuous naturality | P08, P10, P12, P16, P19, P25, P27 |
| Arithmetic curve group | P05, P06 | Geometrically connected pointed/hyperbolic curves or orbicurves; cover category; geometric/arithmetic pi1 exact sequence; continuous outer morphisms over a base Galois map | P12–P16, P21 |
| Kummer class | P03, P05 | Discrete finite roots-of-unity coefficients; completed/Tate systems; local/global constant and function classes; restriction, norm and evaluation comparison | P10, P15, P19, P20, P23–P29 |
| Analytic/tempered curve | P08, P13 | Analytification, finite/topological/tempered covers, topological group and its profinite completion; geometric and field data kept separate | P19–P23 |
| Reconstruction | P12–P17, P19, P20 | Input groupoid, functorial output, comparison to the original object, uniqueness/ambiguity, open-subgroup and base-change compatibility | P22 onward |
| Measured packet | P02, P17, P27 | Finite tensor/product decomposition, integral lattice, independent factor actions, normalized local/radial/angular volumes and scale laws | P28–P31 |
| IUT transport | P22–P30 | Source and target realization, explicit Kummer/poly-isomorphism or inclusion/surjection, exact indeterminacy action and all required naturality squares | P31 |

## Staged exports

Whole-package completion is too coarse for some important dependencies. These stages are part of the plan, not optional optimizations.

| Export | Available after | What it permits immediately | What still waits |
|---|---|---|---|
| P05.core finite-etale covers/pi1 | P01 and existing schemes | P06/P07 geometric definitions and finite-cover results | The separate P05.6 geometric cohomology comparison joins P03/P06 before P09/P10 need it |
| P08.5 formal ringed-space/normalization models | P02/P05.core and selected EGA/Hensel/normalization proofs | Corrected EtTh realization via P20.5 | Any identification with a rigid/Berkovich generic fiber needs a proved bridge |
| P16.local multiplicative invariants | P02/P03/P04 and the exact local recovery proof | Local theta/helper and shell consumers | Global field reconstruction is a separate P16.global output |
| P20.rigidity standalone EtTh sections1-2 | P03, P08, P13 reconstruction and exact local-invariant helpers | Independent theta rigidity release | Frobenioid/formal-model realization needs P19/P08.5 |
| P13.1 tempered-cover/group definitions | P05, P08, P11 definitions and basic covering results | IUT data types, analytic examples, Frobenioid model construction | P13 stable/torsion reconstruction needs P12 |
| P17.1 circle/segment/measure model | P01 and existing real/complex topology | Local archimedean Frobenioid models, concrete archimedean packets | Global Aut-holomorphic reconstruction needs P15 and the rest of P17 |
| P18.1–3 abstract Frobenioid constructions | P01 | Model/API design in parallel with arithmetic/anabelian theorem proofs | Arithmetic/category reconstruction needs P19 |
| P27.C concrete packets | P02 and the elementary P17.1 export | Standalone local tensor/measure theorems and examples | Identification with reconstructed prime-strip packets |
| P27.R reconstructed packet comparison | P21, P25 and P27.C | Inputs to P28 local/global LGP constructions | The final LGP log-link volume compatibility |
| P28.C LGP constructions | P19, P24, P25, P26, P27.R | The data needed to finish the normalized volume theorem | Final joint comparison P27.V/P28.4 |
| P27.V final Prop3.9(iv) compatibility | P28.C plus earlier packet/measure results | P29, P30 and final theorem's volume clauses | No later Corollary3.12 inequality is included |

In particular, **P27.R → P28.C → P27.V** is the intended order. Treating all of Proposition 3.9 as a prerequisite of every LGP definition creates an artificial cycle. The same care is required when a source paper packages elementary constructions together with later reconstruction theorems.

## Prevent common interface failures

- An arbitrary abstract local Galois isomorphism is not an actual local field embedding. Relative Hom, absolute Isom and filtered-local statements have different domains.
- A scheme's etale fundamental group, an analytic tempered group and the topological fundamental group of its underlying space are different objects.
- Finite Kummer extensions, continuous H1, inverse-limit Kummer maps and etale sheaf Kummer sequences need proved bridges.
- The module/unit/degree recovery in AbsTopIII Prop5.8(i)–(iii) does not by itself recover addition on a local field.
- A realified Frobenioid equivalence may rescale degree. Proving the normalization required by a consumer is a separate assertion.
- Weighted/radial log-volume and ordinary Haar measure must not be silently identified.
- “Functorial” means a specified input category/groupoid and naturality statement, including every independent automorphism permitted by the source.

[Home](../README.md) · [Work packages](../work-packages/README.md) · [Completion standard](../CONTRIBUTING.md)
