# The Geometry of Frobenioids II: Poly-Frobenioids

**◇ IUT SUPPORT** · Owners: [P18](../../work-packages/18-frobenioid-definitions.md), [P19](../../work-packages/19-frobenioid-reconstruction.md), with archimedean interfaces from [P17](../../work-packages/17-archimedean-reconstruction.md).

Shinichi Mochizuki, *Kyushu Journal of Mathematics* **62** (2008), 401–460. [72-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Frobenioids%20II.pdf); [February 2019 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Frobenioids%20II%20%28comments%29.pdf). Also integrate the Galois-countability restriction explicitly extended to this paper in the [Semi-graphs 2020 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Semi-graphs%20of%20Anabelioids%20%28comments%29.pdf).

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| §1/§2 local p-adic constructions | Actual local Frobenioid objects attached to the arithmetic/tempered data | Definition-family target; lock selected examples and their interpretation theorems |
| Theorem 2.4(i),(ii) | Category-theoreticity of Kummer/reciprocity for the specified `ℤ`-type p-adic Frobenioids, with temp-slim base and clause-specific saturation/distinguished-open-subgroup assumptions | Target inspected at author pp.19–20; canonical cyclic reciprocity target in (ii) uses fieldwise saturation and cites NSW 7.2.6 |
| §3 archimedean constructions | The selected radial/angular order and local category interfaces used in later assemblies | Definition/caller route; audit corrected sign conventions |
| Theorem 5.5, selected clauses | Poly-standard poly-Frobenioid equivalences preserve the relevant local/global components, bases, modifications and divisor structures | Target inspected at pp.58–62; the explanation on p.65 retains possible noninjectivity of heterogeneous divisor maps and the scale-fixing lattice condition |

**Evidence.** 2.4 and selected 5.5 statements are source-target audited. The exact instantiation and all categorical-to-arithmetic interpretation bridges remain proof obligations. A generic category equivalence does not carry unstated saturation, lattice or measure normalization data.

## Prerequisite interfaces

[Frobenioids I](frobenioids-i.md) supplies the abstract theory. Use [P03 Kummer/cohomology](../../work-packages/03-continuous-cohomology.md), [P04 reciprocity/duality](../../work-packages/04-class-field-theory.md), [P13 tempered groups](../../work-packages/13-tempered-anabelian-geometry.md), and [P17 archimedean reconstruction](../../work-packages/17-archimedean-reconstruction.md). Local p-adic and archimedean instances can be developed by separate teams after agreeing the P18 base/divisor interfaces.

## Parallel outputs and acceptance

Deliver local p-adic realization and reconstructed Kummer/reciprocity separately from archimedean realization, then integrate poly-Frobenioids with local-global compatibility. Export component-recovery and degree-normalization theorems, retaining heterogeneous divisor-map behavior. Consumers: [P20](../../work-packages/20-etale-theta.md), [P24](../../work-packages/24-iut-ii-global-gluing.md), [P28](../../work-packages/28-iut-iii-lgp-constructions.md).

**Closure task — P19 owner.** Audit NSW 7.2.6 against the exact version and required reciprocity statement. Integrate the 2019 correction replacing a profinite category by a tempered one in the proof of 2.4(ii), the corrected archimedean minus-log convention, and the 2020 countability conditions. Enumerate the precise clauses of 5.5 each IUT consumer uses; do not convert the entire paper to one opaque theorem.

[Source graph](README.md) · [Project home](../../README.md)
