# Absolute Anabelian Cuspidalizations of Proper Hyperbolic Curves

**★ REUSABLE** · Owner: [P14 cuspidalization](../../work-packages/14-cuspidalization.md); consumer [P15 function-field reconstruction](../../work-packages/15-mono-anabelian-reconstruction.md).

Shinichi Mochizuki, *Journal of Mathematics of Kyoto University* **47** (2007), 451–539. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Absolute%20Anabelian%20Cuspidalizations.pdf); [February 2014 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Absolute%20Anabelian%20Cuspidalizations%20%28comments%29.pdf). The author catalogue also supplies a separately numbered LaTeX version; record which one is used.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Maximal cuspidally abelian reconstruction; candidate Theorem 1.16(iii) in current author PDF | Recover the relevant cuspidally abelian group extensions for a proper hyperbolic curve under the source's field, prime-set and admissibility assumptions | Caller in AbsTop III 1.10(iii), p.995, inspected; theorem-number match is unresolved |
| Kummer/function reconstruction; candidate Proposition 2.1 in current author PDF | Relate the cuspidal reconstruction to rational-function/Kummer data used by the later additive reconstruction | Same caller; exact original clause/hypothesis matching remains |
| Green trivializations and auxiliary cuspidal extension lemmas | Only those used in the retained maximal-abelian/Kummer proof slice | Planned proof-dependency expansion |

**Evidence.** These are **caller-audited, version-unresolved** targets. An ordinally similar result in another PDF is a candidate match, not proof that the requested theorem has been found.

## Prerequisite interfaces

Use [P03 continuous cohomology/Kummer](../../work-packages/03-continuous-cohomology.md), [P04 local duality](../../work-packages/04-class-field-theory.md), [P05 étale π₁](../../work-packages/05-etale-fundamental-groups.md), and [P06 curves/divisors](../../work-packages/06-curves-and-belyi.md). The original proof audit must decide which relative-Isom, point-recognition, or finite-field arguments are retained. The [Tamagawa source on the alternatives card](alternatives-and-boundaries.md) may supply actual lemmas here even when its full theorem is not a mandatory replacement route.

## Parallel outputs and acceptance

Define cuspidally central/abelian extensions and their universal properties independently of the reconstruction proof. Export the chosen extension and its functorial comparison to Kummer classes and rational functions. This is useful for anabelian reconstruction beyond IUT. The direct consumer is [AbsTop III Corollary 1.10(iii)](abstop-iii.md), where additional approximation/continuity arguments recover addition.

## Owned numbering-resolution task

**P14/P15 owners:** Preserve AbsTop III's literal citation “Theorem 2.1(i); Theorem 1.1(iii)” and compare it with the current author PDF's **Proposition 2.1** and **Theorem 1.16(iii)**. Check journal, original author and LaTeX versions, locate the exact statements and proof uses, then record a side-by-side version map in the source lock. Until that match succeeds, these edges remain version-unresolved in the [audit gates](../../tracking/audit-gates.md).

Integrate the 2014 comments as part of this audit, especially the revised point-theoreticity discussion in Remark 1.18.2/Remark 10 of the LaTeX version. Audit any newly selected Tamagawa lemma at its own exact scope; do not infer a whole-paper dependency from the correction's bibliography.

[Source graph](README.md) · [Project home](../../README.md)
