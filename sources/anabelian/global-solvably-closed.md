# Global Solvably Closed Anabelian Geometry and Neukirch–Uchida

**★ REUSABLE — major independent milestone** · Owner: [P16 local/global Galois reconstruction](../../work-packages/16-local-global-galois-reconstruction.md).

Shinichi Mochizuki, *Mathematical Journal of Okayama University* **48** (2006), 1–21. [14-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Global%20Solvably%20Closed%20Anabelian%20Geometry.pdf). The principal underlying theorem is in Kôji Uchida, [*Isomorphisms of Galois Groups of Solvably Closed Galois Extensions*](https://doi.org/10.2748/tmj/1178229803), *Tohoku Mathematical Journal* **31** (1979), 359–362. A standard organizing source is [Neukirch–Schmidt–Wingberg, corrected second edition](https://www.mathi.uni-heidelberg.de/~schmidt/NSW2e/), §XII, notably Theorem 12.2.1; pin numbering before use.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Neukirch–Uchida for **number fields** | Scheme/field isomorphisms correspond to continuous outer isomorphisms of absolute Galois groups | Recognizable global theorem used by Absolute Anabelian Geometry 1.3.5 and the global reconstruction route; select one canonical proof |
| Global Solvably Closed, Theorem 2.1 | For the source's solvably closed Galois extensions of number fields, group isomorphisms correspond to isomorphisms of the extension fields carrying their base fields onto each other | Primary author theorem text matched at p.7; traces to Uchida 1979 |
| Outer automorphism corollary | Quotient the extension-field statement by the appropriate inner action to obtain the precise `Aut(F) ↔ Out(G_F)` interface used globally | Required derivation/interpretation bridge; exact caller source number is unresolved |

**Evidence.** The call at AbsTop III p.1090 is image-audited. The current author Theorem 2.1 has a primary-text match; journal/version reconciliation and original Uchida proof closure remain open. The local-field analogue without enhanced data has a different scope; see [alternatives/boundaries](alternatives-and-boundaries.md).

## Prerequisite interfaces

[P02 number fields/places](../../work-packages/02-local-global-fields.md), [P03 continuous cohomology](../../work-packages/03-continuous-cohomology.md), [P04 class field theory](../../work-packages/04-class-field-theory.md), and [P11 profinite subgroup theory](../../work-packages/11-trees-and-profinite-groups.md). The selected global proof may require further global class-field/cohomological and decomposition-group lemmas; the P16 source audit must enumerate them rather than infer a local-to-global theorem from P04 alone.

## Parallel outputs and acceptance

Formalize the ordinary number-field theorem first if sufficient for all retained consumers. Treat the solvably closed variant as required only for a caller that genuinely needs that extra generality. Export the outer-isomorphism statement and functorial recovery of the required global/local data. Consumers: [AbsTop III](abstop-iii.md) and [Absolute anabelian curves](absolute-anabelian-curves.md). This library would support independent global anabelian work well beyond IUT.

## Owned numbering-resolution task

**P16 owner:** AbsTop III p.1090 cites “Theorem 3.1” of Global Solvably Closed. The current author PDF's relevant result is **Theorem 2.1**; its §3 instead contains **Proposition 3.1** on single-prime examples. Preserve both locators, compare journal/author/LaTeX versions, and record the exact match before closing the [audit gate](../../tracking/audit-gates.md). Use Uchida or NSW as the canonical proof source only after matching the needed statement and proof hypotheses. The single-prime examples and full curve theorem 2.5 are not automatically additional prerequisites of this Galois-group call.

[Source graph](README.md) · [Project home](../../README.md)
