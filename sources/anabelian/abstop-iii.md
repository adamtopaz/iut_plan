# Topics in Absolute Anabelian Geometry III: Global Reconstruction Algorithms

**★ REUSABLE** for the function-field/local-invariant theorems; **◇ IUT SUPPORT** for the later log-shell/theater organization. Owners: [P15](../../work-packages/15-mono-anabelian-reconstruction.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md), [P17](../../work-packages/17-archimedean-reconstruction.md).

Shinichi Mochizuki, *Journal of Mathematical Sciences, the University of Tokyo* **22** (2015), 939–1156. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20III.pdf); [June 2019 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20III%20%28comments%29.pdf).

## Selected targets and teams

| Target / owner | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Propositions 1.1–1.3, 1.4, 1.6, 1.8 / P15 | Divisor/linear-system and intermediate reconstruction lemmas used by 1.9 | Named internal dependencies; perform individual proof audits |
| Theorem 1.9(a),(b) / P15 | Mono-anabelian function-field reconstruction from `1 → Δ_X → Π_X → G_K → 1` for a **strictly Belyi** hyperbolic orbicurve over a sub-p-adic field | Target inspected at pp.986–988; step (a) invokes AbsTop II 3.7(a)–(c) |
| Corollary 1.10(a),(b),(c),(iii) / P15+P16 | Local cyclotome normalization and, with the stated local-field hypotheses, additive function-field reconstruction using abelian cuspidalization, Kummer theory, p-adic approximation and continuity | Target/proof inspected at pp.993–996; keep clause-specific inputs distinct |
| Proposition 5.8(i) and the selected related clauses / P16 | Recover images of `O_Kˣ` and `Kˣ` in `G_Kᵃᵇ`, residue characteristic/degree, absolute degree, ramification index, roots-of-unity order and transfer functoriality | Target inspected at p.1124; imports Absolute Anabelian Geometry 1.2.1 |
| Selected §§3–5 local/global and archimedean constructions / P15–P17 | Log-shell, local-global and topological structures actually consumed by IUT I–III | Construction/caller inventory; exact result-level matching remains to audit |

**Evidence.** Rows for 1.9, 1.10 and 5.8 have source-target audits. The imported proper-cuspidalization theorem numbers are unresolved below. The selected §§3–5 row is a remaining interface-expansion obligation.

## Prerequisite interfaces

Use [P02 local/global fields](../../work-packages/02-local-global-fields.md), [P03 cohomology](../../work-packages/03-continuous-cohomology.md), [P04 local reciprocity/duality](../../work-packages/04-class-field-theory.md), [P05 π₁](../../work-packages/05-etale-fundamental-groups.md), [P06 curves/duality/Belyi](../../work-packages/06-curves-and-belyi.md), and [P14 cuspidalization](../../work-packages/14-cuspidalization.md). Source-specific imports are [AbsTop II](abstop-ii.md), [Absolute anabelian curves](absolute-anabelian-curves.md), [Galois Sections](galois-sections.md), [Proper cuspidalizations](proper-cuspidalizations.md), and [Global solvably closed](global-solvably-closed.md).

## Parallel outputs and acceptance

Run function-field reconstruction, local multiplicative-invariant recovery, and archimedean reconstruction as separate strands. Their common contracts are the admissible group extensions, twists and morphism groupoids from [P01](../../work-packages/01-shared-interfaces.md). Export reconstruction **with naturality**, not merely existence of an abstract isomorphic field/module. Consumers include [P22](../../work-packages/22-iut-i-theater-reconstruction.md), [P24](../../work-packages/24-iut-ii-global-gluing.md) and [P25](../../work-packages/25-iut-iii-log-links.md). Proposition 5.8's multiplicative module alone is a different output from 1.9/1.10's function-field addition.

## Owned source-resolution tasks

1. **P15 owner:** Corollary 1.10(iii), p.995, cites Proper Cuspidalizations “Theorem 2.1(i); Theorem 1.1(iii).” The current author PDF has Proposition 2.1 and Theorem 1.16(iii). Match the mathematical statements and journal/author versions before locking these edges; see the [source card](proper-cuspidalizations.md).
2. **P16 owner:** The global reconstruction passage at p.1090 cites Global Solvably Closed “Theorem 3.1”; the current author's relevant theorem is 2.1. Preserve the literal citation and resolve the version mismatch against the [source card](global-solvably-closed.md).
3. **P15/P16/P17 owners:** Integrate the 2019 corrections, particularly the added hyperbolic-orbicurve-type hypotheses in Propositions 3.2(iv), 3.3(ii), and nonempty compact-open condition in 5.7(i). Complete a per-IUT-caller clause table for §§3–5.

[Source graph](README.md) · [Project home](../../README.md)

**Archimedean target lock (P17):** selected exact anchors are Propositions2.2,2.5–2.6; Corollaries2.3,2.7–2.9; Proposition4.2; Lemmas4.3–4.4; Corollary4.5; and the consumed Proposition5.8(iv)–(vi)/Corollary5.10(iv) clauses. Preserve their elliptically-admissible/orbicurve hypotheses and expand the retained proofs under A07.
