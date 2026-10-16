# Coverage and completion checklist

This ledger checks the plan's coverage. It is not a list of already formalized mathematics. The checkboxes below are left open for the future implementation and source-lock work; the package/source inventory itself is provided in this repository.

## Scope of the mathematical plan

| Obligation family | Assigned owner | Location |
|---|---|---|
| Existing mathlib reuse and precise additional imports | P01 | [Baseline](../plan/mathlib-baseline.md) |
| Local/global fields, units, roots of unity and logarithms | P02 | [Package](../work-packages/02-local-global-fields.md) |
| Continuous cohomology, Kummer, CFT/duality and inverse systems | P03–P04 | [Foundation sources](../sources/foundations/README.md) |
| Curves/orbicurves, etale pi1, covers, Belyi, torsion and reduction | P05–P09 | [Package directory](../work-packages/README.md) |
| Deep selected comparison and its recursive inputs | P10; A04/A06 | [Comparison package](../work-packages/10-p-adic-comparison.md) |
| Trees/profinite groups and all retained relative/tempered/anabelian reconstruction | P11–P16 | [Anabelian sources](../sources/anabelian/README.md) |
| Complex/archimedean reconstruction, local/global compatibility and measure | P17; A07 | [Archimedean package](../work-packages/17-archimedean-reconstruction.md) |
| Frobenioid definitions/reconstruction and EtTh rigidity/realization | P18–P20 | [Source graph](../graphs/sources.md) |
| IUT I inputs, theaters, processions and symmetries | P21–P22 | [IUT I](../sources/iut/iut-i.md) |
| IUT II local evaluation, synchronization and global Kummer/pilot gluing | P23–P24 | [IUT II](../sources/iut/iut-ii.md) |
| III links/coricity/theta/LGP/global Kummer/volumes and all compatibility | P25–P30 | [IUT III](../sources/iut/iut-iii.md) |
| Full native Theorem3.11, last | P31 | [Clause matrix](../plan/theorem-3-11.md) |
| Additional proof leaves discovered in any retained source | Its source/package owner; A03/A04 | [Audit gates](audit-gates.md) |

## Implementation exit criteria

- [ ] A01 editions and corrections locked for every retained source item.
- [ ] A02 citation-number mismatches reconciled.
- [ ] A03 every direct theorem clause and recursive IUT assembly input mapped to proved exports.
- [ ] A04–A07 all retained classical, analytic, comparison and archimedean proof leaves closed.
- [ ] Every ★ reusable output can be imported independently of IUT-specific definitions.
- [ ] Staged packet/Frobenioid/tempered interfaces have no circular proof assumptions.
- [ ] A08 native interpretation, independent automorphism actions and every compatibility square proved.
- [ ] A09 full reproducible build and independent statement/proof-closure review passed.
- [ ] P31 accepted after every prerequisite; no later result is used to justify Theorem3.11.

## Avoid unnecessary work

The target does not automatically require Corollary3.12, IUT IV, abc/Szpiro, full modularity, the section conjecture, Faltings's Mordell theorem, or all theorems in any cited textbook. Initial-data existence is distinct from using supplied initial data. Narrow abelian-variety Weil and selected p-adic comparison theorems do occur and are explicitly owned.

Filtered-local reconstruction, alternative affine Isom proofs and alternative expositions are marked as optional/alternative on their source cards. They become mandatory only when a consumer selects their exact interface and the dependency graph is updated. Boundary counterexamples explain scope; they are not positive prerequisites unless the project chooses to formalize the boundary theorem itself.

[Home](../README.md) · [Roadmap](../plan/roadmap.md) · [All packages](../work-packages/README.md)
