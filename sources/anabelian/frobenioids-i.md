# The Geometry of Frobenioids I: The General Theory

**◇ IUT SUPPORT** · Owners: [P18 definitions](../../work-packages/18-frobenioid-definitions.md), [P19 reconstruction](../../work-packages/19-frobenioid-reconstruction.md).

Shinichi Mochizuki, *Kyushu Journal of Mathematics* **62** (2008), 293–400. [126-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Frobenioids%20I.pdf); [January 2024 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Frobenioids%20I%20%28comments%29.pdf). Page locators below are **author-PDF** locators and differ from journal pages.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Definitions of divisor/rational-function monoids, Frobenius degrees, Frobenioids, base projection and standard-type conditions | Types and predicates for the literal categorical statements | Construction source selected; each downstream theorem must list its actual predicates |
| Theorem 3.4(iii)–(v) | Equivalence-invariance of morphism classes, units, Frobenius degrees and base projection under the clause-specific standard-type, group-like/base-isomorphism and slimness conditions | Target inspected at author pp.62–63; part (iii) retains a degree-monoid automorphism unless the stated non-group-like-object condition applies |
| Theorem 5.2; Proposition 5.3; Corollary 5.4 | Construct categories from divisor/function monoids and compare their realifications/equivalences | 5.2 target inspected at p.100; audit the exact adjacent clauses used |
| Theorem 6.4(ii),(iv) | Arithmetic degree is recovered up to positive rescaling under realified equivalence; the specified lift to an un-realified equivalence fixes the scale | Target/proof inspected at pp.114–115; Dirichlet units explicitly enters the proof |
| Selected 4.2/4.9 clauses, if required | Intermediate reconstruction results used by the retained later Frobenioid/theta statements | Existing source-family selection; exact caller map remains to audit |

**Evidence.** 3.4, 5.2 and 6.4 have source-target audits at the listed scope. The full construction/proof slice and adjacent subclauses remain to expand. A divisor-monoid definition alone does not establish categorical reconstructibility.

## Prerequisite interfaces

Use [P01 category/outer-morphism interfaces](../../work-packages/01-shared-interfaces.md), [P02 fields/lattices](../../work-packages/02-local-global-fields.md), and the [Geometry of Anabelioids](geometry-anabelioids.md) dictionary. The arithmetic specialization additionally uses product formula, ideals, units and arithmetic Picard/degree data; coordinate those with the [field/number-theory source card](../foundations/field-number-theory.md).

## Parallel outputs and acceptance

Separate abstract monoid/category definitions (P18), general reconstruction (P19), and arithmetic-degree specialization (P19). The third team can state its arithmetic instance while the abstract category is developed. Export explicit interpretation and equivalence-invariance theorems with normalization factors. Consumers are [Frobenioids II](frobenioids-ii.md), [P20 Étale theta](../../work-packages/20-etale-theta.md), and later IUT Frobenioid packages [P24](../../work-packages/24-iut-ii-global-gluing.md)/[P28](../../work-packages/28-iut-iii-lgp-constructions.md). Standard arithmetic pieces are independently reusable; the particular categorical theory is marked as support rather than as a standard arithmetic theorem.

**Closure task — P18/P19 owners.** Integrate all relevant 2024 comments, including corrections in 3.4 and any selected later reconstruction lemmas. Build a per-clause hypothesis table from the exact IUT/EtTh/Frd II consumers. Keep the positive-rescaling ambiguity until a proved scale-fixing hypothesis discharges it.

[Source graph](README.md) · [Project home](../../README.md)
