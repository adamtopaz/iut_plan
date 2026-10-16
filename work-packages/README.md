# Work packages

Arrows and dependency entries run from prerequisites to consumers. **★ REUSABLE** marks useful mathematics beyond IUT; **◇ IUT SUPPORT** marks specialized reusable substrate; **IUT SPECIFIC** marks source-specific assembly. All packages are planned, not completed.

The [graph](../graphs/work-packages.md) and [roadmap](../plan/roadmap.md) describe parallel work and early type-level exports. P31 is the unique final sink. Package IDs name integration units; deliverable suffixes such as P13.1 permit finer scheduling.

| Package | Value | Main prerequisite packages |
|---|---|---|
| [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md) | ★ REUSABLE | Existing mathlib |
| [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md) | ★ REUSABLE | P01 |
| [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md) | ★ REUSABLE | P01 |
| [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md) | ★ REUSABLE | P02, P03 |
| [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md) | ★ REUSABLE | P01 |
| [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md) | ★ REUSABLE | P05 |
| [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md) | ★ REUSABLE | P05, P06 |
| [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md) | ★ REUSABLE | P02, P05, P07 |
| [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md) | ★ REUSABLE | P03, P05, P06, P07 |
| [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md) | ★ REUSABLE | P02, P03, P04, P05, P08, P09 |
| [P11 Trees and discrete/profinite subgroup theory](11-trees-and-profinite-groups.md) | ★ REUSABLE | P01 |
| [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md) | ★ REUSABLE | P04, P05, P06, P09, P10 |
| [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md) | ★ REUSABLE | P05, P08, P11, P12 |
| [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md) | ★ REUSABLE | P04, P05, P06, P09, P11, P12 |
| [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md) | ★ REUSABLE | P06, P12, P14, P16 |
| [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md) | ★ REUSABLE | P02, P03, P04, P05 |
| [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md) | ★ REUSABLE | P01, P05, P06, P07, P15 |
| [P18 Frobenioid and poly-Frobenioid constructions](18-frobenioid-definitions.md) | ◇ IUT SUPPORT | P01 |
| [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md) | ◇ IUT SUPPORT | P02, P04, P11, P13, P17, P18 |
| [P20 Etale theta and its rigidity theorems](20-etale-theta.md) | ★ REUSABLE | P03, P08, P13, P19 |
| [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md) | IUT SPECIFIC | P05, P06, P07, P13, P18 |
| [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md) | IUT SPECIFIC | P15, P16, P17, P19, P20, P21 |
| [P23 IUT II local theta evaluation and synchronization](23-iut-ii-local-evaluation.md) | IUT SPECIFIC | P20, P22 |
| [P24 IUT II global Kummer gluing and horizontal links](24-iut-ii-global-gluing.md) | IUT SPECIFIC | P15, P17, P19, P22, P23 |
| [P25 IUT III log-links and coricity](25-iut-iii-log-links.md) | IUT SPECIFIC | P02, P16, P17, P22, P24 |
| [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md) | IUT SPECIFIC | P20, P24, P25 |
| [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md) | ★ REUSABLE | P02, P03, P17, P21 |
| [P28 IUT III LGP and lgp constructions](28-iut-iii-lgp-constructions.md) | IUT SPECIFIC | P19, P24, P25, P26, P27 |
| [P29 IUT III global Kummer and non-interference](29-iut-iii-global-kummer.md) | IUT SPECIFIC | P15, P24, P25, P27, P28 |
| [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md) | IUT SPECIFIC | P22, P24, P25, P26, P27, P28, P29 |
| [P31 IUT III Theorem 3.11](31-theorem-3-11.md) | IUT SPECIFIC | P30 |

**Interface refinements:** P13.1 (tempered types) precedes geometric reconstruction; P17.1 (circle/measure) precedes global reconstruction; P27.1–2 (concrete measured algebra) precede reconstructed packets, and final Prop3.9(iv) is completed with P28.4. The [interface guide](../plan/interfaces.md) records these staged exports.

[Home](../README.md)
