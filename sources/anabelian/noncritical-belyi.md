# Noncritical Belyi Maps

**★ REUSABLE — compact independent milestone** · Owner: [P06 curves and Belyi](../../work-packages/06-curves-and-belyi.md).

Shinichi Mochizuki, *Mathematical Journal of Okayama University* **46** (2004), 105–113. [Nine-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Noncritical%20Belyi%20Maps.pdf); [July 2016 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Noncritical%20Belyi%20Maps%20%28comments%29.pdf). This is a useful selected source for the strengthened Belyi construction, alongside [Belyi's original paper](https://www.mathnet.ru/eng/im1682), *On Galois Extensions of a Maximal Cyclotomic Field*, English edition (1980), 247–256.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Lemmas 2.1–2.4 | Rational-function separation and reduction lemmas used in the finite-set refinement | Original primary text located; proof-by-proof image audit remains |
| Theorem 2.5 | For a smooth proper connected curve over `Q̄` and disjoint finite point sets `S,T`, obtain a map to `ℙ¹` with branch locus in `{0,1,∞}`, sending `S` into that set and `T` outside it; retain the number-field descent clause | Author pp.5–6, primary statement matched |
| Corollary 1.2 | Belyi opens form a Zariski basis | Author p.1, primary statement matched |

**Evidence.** The source edge is inspected in AbsTop II Example 3.6. The exact targets above were matched in primary author-PDF text; corrected page-image verification remains a source-lock task. The statement is about finite sets and a prescribed open, not just existence of some Belyi map.

## Prerequisite interfaces

[P06](../../work-packages/06-curves-and-belyi.md) supplies smooth proper curves, divisors/line bundles, genus, degree, linear systems and morphisms to the projective line. The proof uses curve Serre duality and basepoint-free linear-system arguments, plus elementary rational-function and number-field descent constructions. Agree with [P05](../../work-packages/05-etale-fundamental-groups.md) on the theorem turning the unramified restricted map into the finite-étale-cover interface needed by the anabelian teams.

## Parallel outputs and acceptance

Prove the refined theorem once and derive ordinary Belyi existence and the Zariski-basis result. A separate team can develop the rational-function lemmas before the curve cohomology work finishes. Export the finite-étale three-point-line map for a suitably chosen smaller open, including avoidance of a prescribed finite set. Consumer: [AbsTop II Example 3.6 and Corollary 3.7](abstop-ii.md), then mono-anabelian reconstruction. This is useful for arithmetic curves, dessins and reconstruction projects independently of IUT.

**Closure task — P06 owner.** Lock whether this proof directly replaces, or uses any portion of, the original Belyi proof, so that the two sources are not double-counted. Audit the finite-set descent clause and all curve-cohomology prerequisites. The 2016 comments contain typographical corrections; include them in the source record.

[Source graph](README.md) · [Project home](../../README.md)
