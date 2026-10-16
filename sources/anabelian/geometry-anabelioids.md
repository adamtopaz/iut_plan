# The Geometry of Anabelioids

**★ REUSABLE** · Shared owners: [P01 interfaces](../../work-packages/01-shared-interfaces.md), [P05 fundamental groups](../../work-packages/05-etale-fundamental-groups.md), [P13 tempered geometry](../../work-packages/13-tempered-anabelian-geometry.md).

Shinichi Mochizuki, *Publications of RIMS* **40** (2004), 819–881. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Anabelioids.pdf); [May 2022 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/The%20Geometry%20of%20Anabelioids%20%28comments%29.pdf).

## Selected targets

| Target family | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| §1 anabelioid constructions and morphisms | Categories of finite continuous group-sets, connected components, fundamental groups up to conjugacy, and the categorical realization of continuous outer group maps | Required foundational route; exact theorem clauses remain to select from the retained callers |
| §2 localization, slimness and reconstruction | Recognize the specified group/category data and prove equivalence-invariance of the corresponding constructions | Caller/source-family selection; neither all of §2 nor every reconstruction theorem is yet certified as needed |
| Propositions 2.3.5, 2.3.6, if selected | The relevant countability-sensitive localization/isogeny-category constructions | Exact numbering is identified by the 2022 comments; original theorem matching remains an owned task |

**Evidence.** This card records a required categorical source family whose consumer-level need is clear. Its minimal theorem list is **planned/caller-audited**, unlike the target-audited EtTh and relative-Hom rows elsewhere. No guessed theorem number is used to fill that gap.

## Prerequisite interfaces

Use mathlib's abstract Galois-category work through [P01](../../work-packages/01-shared-interfaces.md) and prove its geometric interpretation in [P05](../../work-packages/05-etale-fundamental-groups.md). Needed contracts include connected/disconnected Galois categories, fiber functors, change of basepoint up to inner automorphism, profinite groups, continuous group-sets, universes, equivalences, and morphism groupoids. Any extension from finite Galois categories to the paper's larger localization or tempered categories is a separate theorem.

## Parallel outputs and acceptance

The abstract category/group dictionary can proceed independently of algebraic geometry after interface agreement. Export equivalences with inverse constructions and naturality under the chosen morphism classes. Consumers: [Semi-graphs](semi-graphs.md), [AbsTop I](abstop-i.md), and [P18 Frobenioid definitions](../../work-packages/18-frobenioid-definitions.md). This is general categorical anabelian infrastructure rather than an IUT-only data model.

**Closure task — P01/P13 owners.** Produce a caller-to-clause table from those three consumers. Integrate the 2022 comments, which add countable topological-generation hypotheses to selected clauses of 2.3.5/2.3.6 and connectedness to 2.3.5(vi). Determine which needed finite-category results are already supplied by mathlib and prove the interpretation bridge instead of duplicating them. Exact source locking is a prerequisite for claiming a complete proof closure.

[Source graph](README.md) · [Project home](../../README.md)
