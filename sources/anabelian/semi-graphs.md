# Semi-graphs of Anabelioids

**★ REUSABLE** · Owner: [P13 tempered anabelian geometry](../../work-packages/13-tempered-anabelian-geometry.md), sharing graph/subgroup work with [P11](../../work-packages/11-trees-and-profinite-groups.md).

Shinichi Mochizuki. Reference version: [92-page author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Semi-graphs%20of%20Anabelioids.pdf), together with the [May 2020 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Semi-graphs%20of%20Anabelioids%20%28comments%29.pdf). The theorem locators below refer to this author version; publication metadata and file hashes belong in the source lock.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| §1, especially Corollary 1.6(iii) | Tree/profinite normalizer ingredients imported by EtTh Lemma 2.17 | Caller-audited; select and inspect exact clauses |
| Theorem 3.7; Corollaries 3.9, 3.11 | Recover vertex/edge groups and the combinatorial universal cover/quotient graph from the specified tempered/group data | Known route into the theta package; individual statement/proof audit pending, including 2020 corrections |
| Theorem 6.4 | Dominant scheme morphisms correspond to continuous outer homomorphisms of the paper's **DOF type**; the base-Galois map is an open immersion arising from an actual field embedding | Target/proof inspected at author pp.70–71; proof passes through profinite completion and Galois Sections 1.2 |
| Theorem 6.5(iii), Corollary 6.11, Theorem 6.12 | Cusp/decomposition and integral-structure interfaces explicitly imported in EtTh 1.6 | Caller inspected; exact callee subclauses still to lock |
| Theorem 6.8(iii) | For finite extensions `K,L` of `ℚ_p`, arithmetic tempered-group isomorphisms of once-punctured elliptic curves preserve torsion-point decomposition groups, compatibly with geometric abelianizations/Tate modules | Target inspected at author pp.74–75; retain all geometric and arithmetic hypotheses |
| Remark 6.8.1 | The Isom specialization of 6.4 suffices for 6.8(iii),(iv) | Source-inspected optimization; other consumers must be audited before omitting full Hom |

**Evidence.** Theorem 6.4 and 6.8(iii) are source-target audited; several deeper graph/cusp imports have only caller-level or route-level audits. The DOF predicate, temperoids, and relevant graph hypotheses must be definitions in Lean rather than English assumptions.

## Prerequisite interfaces

- [P05 arithmetic étale π₁](../../work-packages/05-etale-fundamental-groups.md), [P08 analytic curves](../../work-packages/08-tate-and-analytic-curves.md), [P11 trees/profinite groups](../../work-packages/11-trees-and-profinite-groups.md): stable coverings, graphs of groups and topology.
- [P09 degeneration and weights](../../work-packages/09-abelian-degeneration-and-weights.md): stable-curve/Jacobian information used in reconstruction.
- [P12 relative Hom/Isom](../../work-packages/12-relative-anabelian-geometry.md), via [Galois Sections](galois-sections.md) and [Local Pro-p](local-pro-p.md).
- [Geometry of Anabelioids](geometry-anabelioids.md) and [André](andre-tempered.md): categorical/group dictionary and the tempered covering theory.

## Parallel outputs and acceptance

Split category/tempered definitions, graph recognition, relative-morphism comparison, and torsion/cusp recognition. Export the graph with its distinguished vertex/edge/cusp subgroups and actual invariance statements. The main downstream consumer is [P20 Étale theta](../../work-packages/20-etale-theta.md); the outputs also form an independent library for nonarchimedean anabelian geometry.

**Closure task — P13 owner.** Integrate the 2020 comments: Galois-countability is needed in the general §3 constructions, and the same restriction propagates to Frobenioids II. They also correct Corollary 3.11's prime-set hypotheses and clarify the proof of Theorem 3.7(iii). Prove countability/coherence for the actual geometric examples. The comments' later AbsTop II explanation can be used only after auditing its independent lemma dependencies; choose a theorem-level DAG even where paper references run in both directions.

[Source graph](README.md) · [Project home](../../README.md)
