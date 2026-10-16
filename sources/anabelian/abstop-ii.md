# Topics in Absolute Anabelian Geometry II: Decomposition Groups and Endomorphisms

**★ REUSABLE** · Owner: [P14 cuspidalization](../../work-packages/14-cuspidalization.md).

Shinichi Mochizuki, *Journal of Mathematical Sciences, the University of Tokyo* **20** (2013), 171–269. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20II.pdf); [January 2024 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20II%20%28comments%29.pdf).

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Example 3.6(i),(ii) | A smaller open in a number-field-defined curve admitting a finite étale map to the projective line minus three points; the associated elementary-operation chain | Construction inspected at pp.263–264; imports Belyi and Noncritical Belyi Maps |
| Corollary 3.7(a)–(c) | Reconstruct the omitted-point/cuspidal extension `Π_U → Π_X` and its decomposition groups from the specified group-theoretic data | Target/proof inspected at pp.264–266; assumes the paper's GSAFG data, all-primes geometric quotient, slim base, open cyclotomic image, strictly Belyi input, and relative Isom-GC on a chain-full class |
| Corollary 2.11, if selected | Expanded argument referenced by the Semi-graphs 2020 comments for Corollary 3.11's proof | Located correction-reference; theorem's exact independent proof requirements remain to audit |
| §§1–2 configuration/point-theoretic results, if invoked | Only the subclauses consumed by a retained reconstruction proof | Caller-selection task; these chapters are not a single mandatory package |

**Evidence.** Example 3.6 and Corollary 3.7 are source-target audited. The remaining rows are conditional source-selection work.

## Prerequisite interfaces

- [P06 curves and Belyi](../../work-packages/06-curves-and-belyi.md), specifically [Noncritical Belyi](noncritical-belyi.md), supplies the geometric construction.
- [P12 relative anabelian geometry](../../work-packages/12-relative-anabelian-geometry.md) supplies the correct relative Isom theorem.
- [AbsTop I](abstop-i.md) supplies Theorem 4.7(i) and cusp recognition; [P05 étale π₁](../../work-packages/05-etale-fundamental-groups.md) supplies the arithmetic extension and cover correspondence.

## Parallel outputs and acceptance

Separate the geometric Belyi-chain construction from its group-theoretic reconstruction. Export the actual cuspidal group extension, distinguished decomposition subgroups, and functoriality under the allowed maps. Main consumer: [P15 mono-anabelian reconstruction](../../work-packages/15-mono-anabelian-reconstruction.md), particularly AbsTop III 1.9(a). These outputs are independently useful for reconstructing deleted points and function fields from curve groups.

**Closure task — P14 owner.** The 2024 comments specify additional recognition data at the terminal three-point-line step of Corollary 3.7(a): its geometric group is free profinite of rank two and has three cusp classes. Encode the complete corrected clause. If using the later Corollary 2.11 explanation of an earlier Semi-graphs proof, audit that lemma's own dependency slice; a paper-level reference cycle must not become a circular theorem proof.

[Source graph](README.md) · [Project home](../../README.md)
