# The Absolute Anabelian Geometry of Hyperbolic Curves

**★ REUSABLE** · Owners: [P16 Galois reconstruction](../../work-packages/16-local-global-galois-reconstruction.md), [P13 tempered/graph reconstruction](../../work-packages/13-tempered-anabelian-geometry.md).

Shinichi Mochizuki, in *Galois Theory and Modular Forms* (2003), 77–122. [45-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Absolute%20Anabelian%20Geometry.pdf); [June 2016 correction](https://www.kurims.kyoto-u.ac.jp/~motizuki/Absolute%20Anabelian%20Geometry%20%28comments%29.pdf). Keep this distinct from the later three-paper *Topics* series.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Proposition 1.2.1, selected clauses (i)–(vii) | For finite extensions of `ℚ_p`, group-theoretic recovery of the local multiplicative/valuation/cyclotomic invariants needed by each caller | Exact imports inspected in AbsTop III 5.8(i) and 1.10(a),(b); original clause audit remains to complete |
| Lemma 1.1.5 | Recognition of the geometric kernel using semistable Tate modules and weight constraints | Caller proof route audited; Faltings–Chai III.7.3 and the abelian-variety Weil result require original-source matching |
| Lemma 1.3.8 | Arithmetic quotient preservation under the relevant local arithmetic curve-group isomorphisms | Explicit import inspected in EtTh 1.6; preserve geometric-kernel recognition prerequisites |
| Lemmas 1.3.7, 1.3.9 | Cusp inertia commensurators and group-theoretic cusp recognition | Target identified; 1.3.9's corrected proof is part of the required source lock |
| Theorem 1.3.4; Corollary 1.3.5 | Relative Isom for hyperbolic curves over sub-p-adic fields; then absolute scheme-Isom/outer-π₁-Isom equivalence **over number fields** | Primary theorem text matched; 1.3.4 refers to Local Pro-p, and 1.3.5 also uses Neukirch–Uchida |
| Selected §2 stable/logarithmic-special-fiber reconstruction | Only the specialization/graph subclauses required by retained tempered/theta callers | Caller/source-family target; precise clause list still to audit |

**Evidence.** Later callers for 1.2.1 and 1.3.8 were image-inspected. The original theorem texts for 1.3.4/1.3.5 were matched in primary web text; the original corrected page-image check remains part of source locking. The §2 selection is still a planned expansion.

## Prerequisite interfaces

Use [P02 fields](../../work-packages/02-local-global-fields.md), [P03 cohomology](../../work-packages/03-continuous-cohomology.md), [P04 reciprocity/duality](../../work-packages/04-class-field-theory.md), [P05 π₁](../../work-packages/05-etale-fundamental-groups.md), [P09 degeneration/weights](../../work-packages/09-abelian-degeneration-and-weights.md), [P11 subgroup theory](../../work-packages/11-trees-and-profinite-groups.md), and [P12 relative Isom](../../work-packages/12-relative-anabelian-geometry.md). The global absolute-Isom corollary also uses [Neukirch–Uchida](global-solvably-closed.md).

## Parallel outputs and acceptance

Separate local multiplicative-invariant recovery, geometric-kernel/cusp recognition, and global absolute curve Isom. Export them with exact hypotheses and naturality; consumers are [AbsTop III](abstop-iii.md), [EtTh](etale-theta.md), and [Semi-graphs](semi-graphs.md). These are independently useful theorems in local/global anabelian geometry. Arithmetic-quotient recognition and local multiplicative recovery do not by themselves provide arbitrary local additive field reconstruction; the additional filtered theorem is on the [alternatives card](alternatives-and-boundaries.md).

**Closure task — P13/P16 owners.** Integrate the 2016 replacement of the cusp-recognition argument in Lemma 1.3.9 and its related clarification to 1.1.4. Match every imported clause of 1.2.1 to its actual local-class-field-theory theorem and prove the weight/kernel lemmas from P09. Decide whether §2's exact consumers need further stable/log-curve sources, then expand those edges.

[Source graph](README.md) · [Project home](../../README.md)
