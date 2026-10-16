# F17 · Bosch, Lectures on Formal and Rigid Geometry

**★ REUSABLE · Retained analytic foundation; precise scope selection remains.** Siegfried Bosch, [*Lectures on Formal and Rigid Geometry*, LNM 2105](https://link.springer.com/book/10.1007/978-3-319-04417-0) (2014). An accessible [author preprint, April 2008](https://www.uni-muenster.de/IVV5WS/WebHop/user/weckerm/heft378.pdf) exposes the section organization below; it must not be cited with the 2014 theorem numbering.

## Selected portions and finite selection task

| Author-preprint section | Needed interface |
|---|---|
| §§1.1–1.6 | Nonarchimedean Banach/Tate algebras, affinoid algebras and subdomains; functions on discs and annuli over a complete nontrivially valued nonarchimedean field. |
| §§1.9–1.13 | Selected acyclicity/sheaf/gluing and analytification results needed to construct the analytic Tate curve and compare finite étale algebraic/analytic covers. |
| §§2.1–2.8 | Formal models and generic-fiber constructions **only if selected** by the semistable/period-pairing proof. |

**Selection task F17-A:** read the Tate/tempered and degeneration consumers, choose the required individual propositions from these sections, and prove the exact analytification and covering comparison interfaces. General proper-mapping theorems, all formal blowing-up theory and every cohomology theorem in the book are not automatically retained.

For the main IUT local branch specialize to finite extensions of `ℚ_p` and the completed algebraic closure when required. Convergent theta products on the Tate cover must be tied to the precise EtTh normalization. Rigid spaces alone do not define the ordinary topology of topological covers used by André; the [analytic topology companion](berkovich-analytic-topology.md) supplies a separately audited bridge.

## Interfaces and parallel work

Ready inputs: [P02](../../work-packages/02-local-global-fields.md), normed algebra/series and [P06](../../work-packages/06-curves-and-belyi.md). Deliver [P08](../../work-packages/08-tate-and-analytic-curves.md); consumers [P09](../../work-packages/09-abelian-degeneration-and-weights.md), [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P20](../../work-packages/20-etale-theta.md). Affinoid analysis, Tate uniformization and analytic covering comparison are distinct parallel milestones.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) finds rich normed-algebra and scheme foundations, while the scoped rigid/Berkovich searches did not locate the required analytic-curve library. Release discs/annuli, affinoid gluing and the chosen algebraic/analytic finite-cover comparison. These serve nonarchimedean geometry, Mumford curves and analytic families.

[Foundation map](README.md) · [Tate curves](tate-uniformization.md) · [André](../anabelian/andre-tempered.md)
