# Topics in Absolute Anabelian Geometry I: Generalities

**★ REUSABLE** · Owners: [P14 cuspidalization](../../work-packages/14-cuspidalization.md), with [P15 reconstruction](../../work-packages/15-mono-anabelian-reconstruction.md) as consumer.

Shinichi Mochizuki, *Journal of Mathematical Sciences, the University of Tokyo* **19** (2012), 139–242. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20I.pdf); [January 2024 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Topics%20in%20Absolute%20Anabelian%20Geometry%20I%20%28comments%29.pdf). Pin the corrected journal statement, not an unversioned theorem-number string.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Lemma 4.5(v),(vi) | Functorial recognition of cusp conjugacy classes under covers; cusp decomposition groups as commensurators of inertia | Target/proof inspected at p.207; uses Combinatorial GC 1.2, 2.4, 1.6, 2.7 |
| Theorem 4.7(i),(ii) | Equivalence between geometric elementary-operation-chain categories and the corresponding group-theoretic categories | Target inspected at pp.209–210; assumes relative Isom-GC on the specified **chain-full** class |
| Theorem 4.7(iii),(iv), if used | Dominant-localization versions of the chain comparison | Same location; **additional relative Hom-GC hypothesis**, rather than a consequence of Isom-GC alone |
| Selected §2 geometric-kernel and §3 local-geometricity results | Recover the required arithmetic/geometric group extension and its admissible morphisms in each retained consumer | Source-family/caller targets; exact clauses remain to be locked |

**Evidence.** The §4 rows are source-target audited. The §2/§3 row is an owned expansion task, not a claim that every theorem in these sections is needed.

## Prerequisite interfaces

- [P05 étale fundamental groups](../../work-packages/05-etale-fundamental-groups.md): arithmetic extensions and cover/open-subgroup correspondence.
- [P06 curves](../../work-packages/06-curves-and-belyi.md), [P09 weights](../../work-packages/09-abelian-degeneration-and-weights.md), [P11 group theory](../../work-packages/11-trees-and-profinite-groups.md): curve/cusp combinatorics and the imported weight/group lemmas.
- [P12 relative anabelian geometry](../../work-packages/12-relative-anabelian-geometry.md): distinguish the Isom contract for 4.7(i),(ii) from the stronger Hom contract for (iii),(iv).
- [Combinatorial GC](combinatorial-gc.md): the four explicit imports in Lemma 4.5.

## Parallel outputs and acceptance

Define elementary operations and chain-fullness before their reconstruction proofs. A team can prove the conditional chain theorem using a relative-Isom typeclass/interface while P12 proves that interface; final integration discharges the hypothesis. Export cusp inertia recognition with cover/base-change naturality, and the equivalence of chain categories. This supports [AbsTop II](abstop-ii.md), then [AbsTop III](abstop-iii.md), and is useful independently for anabelian reconstruction of punctures and covers.

**Closure task — P14 owner.** Integrate the 2024 replacement of the cusp-recognition criterion in Lemma 4.5(iv), then trace its effect on (v),(vi). Audit the selected §2/§3 calls separately and assign their own statements. Every chain theorem must retain its field class, prime set, slimness/cyclotomic assumptions, and Isom-versus-Hom premise through the exported interface.

[Source graph](README.md) · [Project home](../../README.md)
