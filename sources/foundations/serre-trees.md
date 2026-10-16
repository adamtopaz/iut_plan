# F15 · Serre, Trees

**★ REUSABLE · Retained discrete graph/group foundation.** Jean-Pierre Serre, [*Trees*](https://link.springer.com/book/10.1007/978-3-642-61856-7), Springer Monographs in Mathematics; pin the chosen English edition and its errata.

## Selected exact caller anchors

[Semi-graphs of Anabelioids](../anabelian/semi-graphs.md) cites **Chapter I §2.2 Proposition 8**, **I §3.4 Theorem 5**, and **I §6.5, Corollary 3 to Proposition 26 / Proposition 27**. These labels identify a finite source-selection task, not a claim that every theorem in *Trees* is needed.

**Selection task F15-S:** match those results to their exact Semi-graphs consumers, extract the hypotheses on group actions, graph coverings and finite generation, and record which universal-cover, stabilizer/fixed-point and fundamental-group-of-a-graph-of-groups statements are used. Prove the chosen results for discrete groups before stating a profinite/tempered analogue. The existing caller audit locates these citations; original clause-by-clause statements are not locked here.

The shared interface should include an action without edge inversions when required, quotient graph, vertex/edge stabilizers, a maximal subtree, and the corresponding fundamental-group construction. Any removal of an edge-inversion hypothesis requires subdivision or its explicit replacement argument. Do not infer a fixed vertex from an arbitrary infinite group action.

## Interfaces and parallel work

Ready inputs: group actions, finite/discrete graphs, free groups, colimits and basic topology from [P01](../../work-packages/01-shared-interfaces.md). Deliver [P11](../../work-packages/11-trees-and-profinite-groups.md). Consumer: [P13](../../work-packages/13-tempered-anabelian-geometry.md), hence [P20](../../work-packages/20-etale-theta.md). Discrete Bass–Serre theory and [profinite subgroup theory](ribes-zalesskii.md) can be separate teams, with a later comparison interface.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) gives general group/category/profinite infrastructure; it does not certify the cited Bass–Serre package. Audit existing graph/free-group declarations before assigning missing lemmas. Release the tree-action/graph-of-groups correspondence and the exact fixed-point/stabilizer corollaries needed by the analytic skeleton. These also serve geometric group theory, amalgamated products, arithmetic groups and graph coverings.

[Foundation map](README.md) · [Ribes–Zalesskii](ribes-zalesskii.md) · [André](../anabelian/andre-tempered.md)
