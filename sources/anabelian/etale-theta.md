# The Étale Theta Function and its Frobenioid-theoretic Manifestations

**★ REUSABLE** for standalone theta rigidity; **◇ IUT SUPPORT** for categorical realization · Owner: [P20 Étale theta](../../work-packages/20-etale-theta.md).

Shinichi Mochizuki, *Kyushu Journal of Mathematics* **63** (2009), 227–349. Use the [author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Etale%20Theta%20Function%20and%20its%20Frobenioid-theoretic%20Manifestations.pdf) with the [March 2022 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Etale%20Theta%20Function%20and%20its%20Frobenioid-theoretic%20Manifestations%20%28comments%29.pdf). The author PDF and journal pagination differ; lock both before assigning Lean declaration names.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| §1 theta construction; Theorem 1.6 | The specific theta function/class on the Tate covering, its Kummer interpretation, and control of its constant ambiguity via cusp/integral data | Theorem 1.6 and its proof inspected at journal pp.250–251; expand the earlier analytic lemmas during P20 |
| Theorem 1.10(ii), with the relevant part of (iii) | Torsion-point evaluation and preservation of standard-type theta classes up to sign; the integral-structure conclusion has an additional odd-residue-characteristic assumption | Target inspected at p.256; retains Semi-graphs 6.8(iii) |
| Lemma 2.17 | A virtually finite-rank free group gains no additional normalizers in its profinite completion for subgroups whose intersection with the free subgroup is nonabelian; corresponding tempered-open-subgroup statement | Target inspected at p.284; imports André 3.2.1 and Semi-graphs 1.6(iii) |
| Corollary 2.19 | Cyclotomic, discrete, and constant-multiple rigidity for the specified mono-theta environments and their compatible systems | Target/proof inspected at pp.289–294; preserve all sign/root-of-unity/conjugacy indeterminacies |
| §§3–5 | Frobenioid realization and the comparison with the group-theoretic theta data | Required source-family interface; precise per-caller clause list still to lock |

**Evidence.** The first four rows have source-target audits. The §§3–5 selection has a caller/construction audit and needs its internal proof dependency list. A published theorem used as a mathematical interface still needs a Lean proof in this campaign.

## Prerequisite interfaces

- [P03 continuous cohomology](../../work-packages/03-continuous-cohomology.md): Kummer classes, twists, inverse systems, and the particular finite-system `R¹ lim = 0` arguments used in 2.19(ii).
- [P08 Tate and analytic curves](../../work-packages/08-tate-and-analytic-curves.md): convergent products, theta divisor/functional equations, and Tate-parameter conventions.
- [P11 trees and profinite groups](../../work-packages/11-trees-and-profinite-groups.md), [P13 tempered geometry](../../work-packages/13-tempered-anabelian-geometry.md), [P14 cuspidalization](../../work-packages/14-cuspidalization.md): normalizers, stable graphs, cusp and torsion-point decomposition groups.
- [P18 definitions](../../work-packages/18-frobenioid-definitions.md) and [P19 reconstruction](../../work-packages/19-frobenioid-reconstruction.md): the categorical realization of these data.

Selected source links: [Semi-graphs](semi-graphs.md), [André](andre-tempered.md), [Absolute anabelian curves](absolute-anabelian-curves.md), [Frobenioids I](frobenioids-i.md), [Frobenioids II](frobenioids-ii.md).

## Parallel outputs and acceptance

Split analytic theta construction, group-theoretic rigidity, inverse-limit coherence, and categorical realization into separate modules with agreed inputs. Export actual isomorphisms/equivalences and their naturality, including the residual ambiguity groups. Consumers are [P22 theater reconstruction](../../work-packages/22-iut-i-theater-reconstruction.md), [P23 local evaluation](../../work-packages/23-iut-ii-local-evaluation.md), [P24 global gluing](../../work-packages/24-iut-ii-global-gluing.md), and [P26 theta monoids](../../work-packages/26-iut-iii-theta-monoids.md).

**Closure task — P20 owner.** Integrate the 2022 correction to Definition 3.1(ii): the corrected meromorphic class requires every positive-order root to exist on some tempered covering. Audit the correction's subsequent arguments and all selected §§3–5 consumers. A cusp argument for Theorem 1.6 is a possible local optimization; the whole route still uses torsion evaluation through 1.10 and 2.19 until separately replaced.

[Source graph](README.md) · [Project home](../../README.md)

**Corrected formal models:** March2022 comments item(xlvi), pp7-8, has additional (NorFor)/(NorForZar) tasks: [EGA IV normalization](../foundations/ega-formal-normalization.md), [Faltings crystalline PartII remark](../foundations/faltings-crystalline-1990.md) and AbsTopII Lem2.1. P08.5/P20.5 own the formal-ringed-space/analytic interpretation. Also check correction(v)'s odd-ell/excluded-case qualifications for Prop2.12 and the retained section2 models' odd residue characteristic. These are source hypotheses to prove at every consumer, not mere bibliography notes.
