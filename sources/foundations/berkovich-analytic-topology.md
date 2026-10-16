# F18 · Berkovich, nonarchimedean analytic topology

**★ REUSABLE · Retained topology interface; source specialization to lock.** Vladimir Berkovich, [*Spectral Theory and Analytic Geometry over Non-Archimedean Fields*](https://doi.org/10.1090/surv/033), Mathematical Surveys and Monographs 33 (1990); [author bibliography](https://www.wisdom.weizmann.ac.il/~vova/).

## Selected interface and audit task

[André's tempered-cover construction](../anabelian/andre-tempered.md), §§4–5, combines finite étale covers with topological covers of nonarchimedean analytic curves. This requires the actual analytic topology, not the totally disconnected topology of `K`-rational points and not a scheme's étale/pro-étale site.

**Selection task F18-T:** inspect André's analytic-space and topological-cover references and choose the minimal Berkovich results needed to construct those covers, their fiber functors and inverse systems. Pin individually:

1. The analytic realization of a smooth curve over a complete nonarchimedean field and its relation to the rigid realization chosen in [F17](rigid-analytic-foundations.md).
2. Local path/covering properties for the analytic curves in question, with all smoothness, separatedness, base-completion and countability hypotheses that the selected theorem requires.
3. Compatibility of algebraic finite étale covers with the selected analytic cover category; reduction/skeleton comparisons only where the stable-graph proof uses them.

This is a concrete source-selection obligation. The plan has not certified that all three items follow from one proposition in the 1990 monograph, nor that the whole book is necessary. If André requires a later étale-comparison paper, register it as a separate source and assign its exact results before closing this audit. No general local-contractibility theorem for arbitrary singular analytic spaces is assumed.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md), ordinary topology/covering spaces from [P01](../../work-packages/01-shared-interfaces.md), and [F17](rigid-analytic-foundations.md). Deliver analytic foundations through [P08](../../work-packages/08-tate-and-analytic-curves.md); main consumer [P13](../../work-packages/13-tempered-anabelian-geometry.md). This topology/comparison team can work separately from arithmetic local reciprocity and IUT categorical constructions.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates ordinary topological fundamental groupoids and general topology. It does not locate the required Berkovich analytic realization or its tempered-cover comparison. Reuse covering-space machinery only after proving the analytic hypotheses. A reusable release is the analytification/topological-cover interface for smooth curves and the finite-étale comparison, supporting nonarchimedean topology and tropical/skeleton applications.

[Foundation map](README.md) · [Serre Trees](serre-trees.md) · [Semi-graphs](../anabelian/semi-graphs.md)
