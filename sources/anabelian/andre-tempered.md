# André: tempered coverings and fundamental groups

**★ REUSABLE** · Owner: [P13 tempered anabelian geometry](../../work-packages/13-tempered-anabelian-geometry.md), supported by [P08 analytic curves](../../work-packages/08-tate-and-analytic-curves.md) and [P11 group theory](../../work-packages/11-trees-and-profinite-groups.md).

Yves André, *On a Geometric Description of* `Gal(Q̄_p/Q_p)` *and a p-adic Avatar of* `GT̂`, *Duke Mathematical Journal* **119** (2003), 1–39. Version to lock: [arXiv:math/0203181v2](https://arxiv.org/abs/math/0203181v2), dated October 24, 2002, with journal comparisons where numbering differs.

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| §4 | Tempered coverings and their fundamental group: coverings becoming topological after finite étale base change; comparison with finite étale covers and profinite completion | Foundation route selected; exact construction lemmas need proof audits |
| Proposition 5.1.1 | The arithmetic/geometric tempered fundamental-group exact sequence and its Galois action at the stated p-adic analytic scope | Recognizable selected result; original theorem hypotheses and basepoint conventions still to lock |
| Lemma 3.2.1 | Free-group/profinite normalizer input used by EtTh Lemma 2.17 | Exact import verified at the caller; original group-theoretic statement/proof to audit |
| Selected §6 statements, if invoked | Topology and outer-automorphism interfaces for curve tempered groups | Source-family target; include only where a retained caller needs it |

**Evidence.** The arXiv version and section structure were primary-checked; the theorem edges are retained at caller/foundation level. The much stronger Galois-group/GT identifications in §§7–9 have not been established as necessary for Theorem 3.11.

## Prerequisite interfaces

[P08](../../work-packages/08-tate-and-analytic-curves.md) supplies the selected rigid/Berkovich analytic category, finite étale/topological covers and analytification; [P05](../../work-packages/05-etale-fundamental-groups.md) supplies the finite-étale comparison; [P11](../../work-packages/11-trees-and-profinite-groups.md) supplies covering graphs and subgroup/normalizer results. Coordinate with [Geometry of Anabelioids](geometry-anabelioids.md) and [Semi-graphs](semi-graphs.md) on topological-group and covering-category interfaces.

## Parallel outputs and acceptance

Separate analytic covering theory from graph/group lemmas. Export the actual tempered group, its topology, its profinite-completion comparison and arithmetic exact sequence. Prove compatibility with the geometric version adopted in Semi-graphs. Main consumers: [Semi-graphs](semi-graphs.md) and [EtTh 2.17](etale-theta.md). These are foundational tools for nonarchimedean analytic geometry independently of IUT.

**Closure task — P08/P13 owners.** Audit §4's references for analytic and covering existence results; André's earlier *Period Mappings and Differential Equations: From C to C_p* is a referenced foundation family whose required portions must be selected if this proof route is retained. Match the arithmetic base field/completed-algebraic-closure conventions of 5.1.1 and integrate the countability requirements from the Semi-graphs corrections. The analytic foundations source card [records alternative foundation choices](../foundations/rigid-analytic-foundations.md); choose a proved bridge rather than require both entire analytic theories.

[Source graph](README.md) · [Project home](../../README.md)
