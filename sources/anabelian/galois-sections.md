# Galois Sections in Absolute Anabelian Geometry

**★ REUSABLE** · Owners: [P12](../../work-packages/12-relative-anabelian-geometry.md), [P13](../../work-packages/13-tempered-anabelian-geometry.md), [P15](../../work-packages/15-mono-anabelian-reconstruction.md).

Shinichi Mochizuki, *Nagoya Mathematical Journal* **179** (2005), 17–45. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Galois%20Sections.pdf); [August 2014 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Galois%20Sections%20%28comments%29.pdf).

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Theorem 1.2 | The relative anabelian input used after profinite completion in Semi-graphs 6.4, reducing to Local Pro-p Theorem A | Caller/route audited; match its exact scheme/pro-object signature before source lock |
| Theorem 2.3; Corollaries 2.5, 2.6, 2.8 | Dominant-localization and torsion/decomposition-group reconstruction in the retained tempered route | Explicit imports on that route; precise clause/hypothesis transcription remains to expand |
| Remark 2.8.1 | Isom-only version of the localization argument underlying the relevant torsion reconstruction | Source-inspected optimization, paired with Semi-graphs Remark 6.8.1 |
| Lemma 3.1 | The p-adic approximation statement used in the additive reconstruction step of AbsTop III 1.10(iii) | Caller inspected at AbsTop III pp.995–996; original corrected source statement still to lock |
| Theorem 4.3 | Synchronize the arithmetic and geometric cyclotomes in the specified curve/Galois setting | Caller inspected in AbsTop III 1.10(c), p.994; source theorem's complete hypotheses remain to audit |

**Evidence.** The retained dependency edges are audited at caller/route level. Do not present every theorem in this card as already transcribed from its original statement. In particular, “Galois sections” here does not mean the section conjecture is a prerequisite.

## Prerequisite interfaces

Use [Local Pro-p](local-pro-p.md) for the required relative Hom/Isom result; [P05](../../work-packages/05-etale-fundamental-groups.md) for arithmetic exact sequences and sections; [P03](../../work-packages/03-continuous-cohomology.md)/[P04](../../work-packages/04-class-field-theory.md) for cyclotomes and local cohomology; [P02](../../work-packages/02-local-global-fields.md) for approximation; and [P06](../../work-packages/06-curves-and-belyi.md) for curves and localization.

## Parallel outputs and acceptance

Separate the relative-localization comparison, approximation lemma, and cyclotome-rigidity theorem. Their consumers are, respectively, [Semi-graphs](semi-graphs.md), [AbsTop III](abstop-iii.md)'s function-field reconstruction, and its local normalization. Each module exports the correct naturality and its exact admissible map class. The Isom specialization can be delivered first if it covers every selected caller.

**Closure task — P12/P13/P15 owners.** Open each callee statement and match its actual field, point, and morphism assumptions. Integrate the 2014 correction to Lemma 3.1's field subscript; if Corollary 4.12 is later retained, it additionally requires a primitive twelfth root of unity. Audit source-number consistency before assigning permanent Lean theorem names.

[Source graph](README.md) · [Project home](../../README.md)

**Additional retained Isom-route inputs:** Remark2.8.1 explicitly retains Proposition1.1(ii) and Theorem1.3(iii). P12/P13 must state and prove those interfaces alongside the Isom specialization; the shortcut does not reduce the proof to the relative Isom theorem alone.
