# Arithmetic and geometric foundation sources

These cards select **results** from books and papers. They do not ask contributors to translate entire textbooks into Lean. **★ REUSABLE** marks an interface with applications beyond IUT. A retained theorem may have alternative proof references; those alternatives are not cumulative prerequisites.

The baseline is the [pinned mathlib survey](../../plan/mathlib-baseline.md). “Not located” records a scoped search result, not a proof of total absence. When a theorem number is not independently locked, its card assigns an explicit selection task, with a consumer and a required mathematical interface. Completing those tasks is part of the plan.

| Card | Source(s), selected result | Main package | Parallel/reuse milestone |
|---|---|---|---|
| [F01](field-number-theory.md) | Milne field/number theory; product formula 7.15, norm 7.16, Dirichlet 5.1; Kronecker lemma | [P02](../../work-packages/02-local-global-fields.md) | ★ Normalize existing arithmetic APIs and release the global logarithmic lattice. |
| [F02](local-fields.md) | Serre, *Local Fields*: local extensions, units, norm/trace, log/exp | [P02](../../work-packages/02-local-global-fields.md) | ★ Complete local-unit log with exact kernel/image lattice. |
| [F03](class-field-theory.md) | Milne CFT I.1.1/I.1.4, III.3.1/III.3.2; Serre alternative | [P04](../../work-packages/04-class-field-theory.md) | ★ Local reciprocity/existence with all tower diagrams. |
| [F04](continuous-galois-cohomology.md) | NSW continuous cohomology, 7.2.6 and selected XII reconstruction | [P03](../../work-packages/03-continuous-cohomology.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md) | ★ Continuous Kummer, local duality and global reconstruction leaves. |
| [F05](sga1-and-pi1.md) | SGA 1 / Stacks 58.6.2, 58.6.3 and 58.14.3 | [P05](../../work-packages/05-etale-fundamental-groups.md) | ★ Scheme finite-étale Galois category and arithmetic exact sequence. |
| [F06](stacks-kummer.md) | Stacks 59.28.1, Picard/Kummer exact sequence | [P03](../../work-packages/03-continuous-cohomology.md) | ★ Étale torsors and point-evaluation naturality. |
| [F07](algebraic-curves.md) | Hartshorne or Liu: curve duality, Riemann–Roch, linear systems | [P06](../../work-packages/06-curves-and-belyi.md) | ★ Divisor/line-bundle and section-separation APIs. |
| [F08](elliptic-curves.md) | Silverman AEC III, VII: geometric models, torsion and pairings | [P07](../../work-packages/07-elliptic-curves.md) | ★ Geometric/Weierstrass bridge, finite étale torsion and Weil pairing. |
| [F09](tate-uniformization.md) | Silverman *Advanced Topics* V: Tate uniformization | [P08](../../work-packages/08-tate-and-analytic-curves.md) | ★ Tate curve plus torsion/Kummer compatibility. |
| [F10](faltings-p-adic-hodge.md) | Faltings 1988 I.4.4, I.4.2, II.2.4/II.3.1 | [P10](../../work-packages/10-p-adic-comparison.md) | ★ Selected rational and relative/integral comparison; keep uniform bounds. |
| [F11](tate-p-divisible.md) | Tate 1967 §3.3 Theorems 1–2 | [P10](../../work-packages/10-p-adic-comparison.md) | ★ Exact local `C_p`/twist cohomology computations. |
| [F12](bloch-kato-local.md) | Bloch–Kato local §3, Example 3.11, Lemma 3.8.1 | [P10](../../work-packages/10-p-adic-comparison.md) | ★ Abelian-variety exponential/Kummer square and local conditions. |
| [F13](faltings-chai.md) | Faltings–Chai III.7.3, selected period pairing | [P09](../../work-packages/09-abelian-degeneration-and-weights.md) | ★ Semistable Tate-module filtration. |
| [F14](abelian-varieties-weights.md) | Mumford / Milne AV II.1.1(b): finite-field Weil weights | [P09](../../work-packages/09-abelian-degeneration-and-weights.md) | ★ Jacobian/Tate module, Rosati positivity and weight separation. |
| [F15](serre-trees.md) | Serre, *Trees*, selected Chapter I results | [P11](../../work-packages/11-trees-and-profinite-groups.md) | ★ Bass–Serre and tree-action/stabilizer interface. |
| [F16](ribes-zalesskii.md) | Ribes–Zalesskii, first-edition 3.3.15 and selected subgroup theory | [P11](../../work-packages/11-trees-and-profinite-groups.md) | ★ Completion/subgroup and normalizer bridges. |
| [F17](rigid-analytic-foundations.md) | Bosch: Tate algebras, affinoid gluing, analytic comparison | [P08](../../work-packages/08-tate-and-analytic-curves.md) | ★ Discs/annuli and finite-cover analytification. |
| [F18](berkovich-analytic-topology.md) | Berkovich: analytic realization and topological covers | [P08](../../work-packages/08-tate-and-analytic-curves.md), [P13](../../work-packages/13-tempered-anabelian-geometry.md) | ★ Analytic topology bridge for tempered coverings. |
| [F19](geometric-cohomology.md) | Milne LEC / original SGA / Stacks: curve H1, selected base change and duality | P05.6, P06.5 | ★ Geometric coefficient/transition/duality interfaces feeding comparison and reconstruction. |
| [F20](fontaine-period-rings.md) | Fontaine1982: selected period-ring/de Rham/crystalline/formal-group interfaces requested by local Bloch-Kato | P10.5 | ★ Period representations and exponential compatibility beyond Hodge-Tate. |

| [F21](ega-formal-normalization.md) | EGA IV second part7.8.3: selected normalization/excellence assertions | P08.5, P20.5 | ★ Formal/analytic-model normality and comparison. |
| [F22](faltings-crystalline-1990.md) | Faltings crystalline paper: PartII Thm2.6-following remark | P08.5, P20.5 | ★ Selected formal normalization; original edition lock. |

[André](../anabelian/andre-tempered.md) is listed with the [anabelian sources](../anabelian/README.md), because its tempered fundamental-group comparison is the consumer of the analytic foundations. Abstract Haar measure, tensor products, groupoids and topology already in mathlib are coordinated by [P01](../../work-packages/01-shared-interfaces.md) and [P27](../../work-packages/27-measured-tensor-packets.md), rather than duplicated as entire textbook projects.

The deepest source locks are F04-G (global Galois reconstruction), F10-P (relative/integral comparison), F13-P (degeneration), and F18-T (analytic covering topology). Their closure must be completed before any claim that the recursive proof bibliography is exhaustive.

[All sources](../README.md) · [Papers/books graph](../../graphs/sources.md) · [Reusable result milestones](../../plan/reusable-results.md) · [Home](../../README.md)
