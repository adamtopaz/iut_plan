# P20 Etale theta and its rigidity theorems

**Status:** planned. **Value:** ★ REUSABLE.

Etale/tempered theta rigidity, Kummer reconstruction and degenerating elliptic-curve geometry.

## Prerequisite outputs

- [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md)
- [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md)
- [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md)
- [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P20.1 | Theta class | Construct the exact etale-theta/Kummer object, its torsion/cusp evaluations and normalized constant/cyclotomic data. |
| P20.2 | Rigidity | Prove EtTh Thms1.6/1.10, relevant2.8/2.17 inputs and Cor2.19: cyclotomic, discrete and constant-multiple rigidity, with its residual roots-of-unity/sign/conjugacy ambiguity. |
| P20.3 | Projective systems | Prove coherence through the specific finite Hom/root-of-unity systems and required R1-lim vanishing; include functoriality under every allowed automorphism. |
| P20.4 | Realization | Implement selected sections3-5 Frobenioid realizations, using the corrected log-meromorphic root-on-tempered-cover definition. Prove agreement with the analytic theta model. |
| P20.5 | Corrected formal-model realization | Prove the corrected root-on-tempered-cover definition and (NorFor)/(NorForZar) assertions, with P08.5 normalization/model bridges, odd-prime/residue hypotheses and all excluded cases checked for each consumer. |

## Source targets

- [etale theta](../sources/anabelian/etale-theta.md)

**Staged release:** P20.rigidity (sections1-2) consumes analytic/tempered, local-invariant and cohomological inputs; it can be released before P19 finishes. P20.realization (sections3-5) additionally needs P19 and the corrected formal-model output P08.5. Only this combined realization is required before the full IUT I construction closes.

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P23 IUT II local theta evaluation and synchronization](23-iut-ii-local-evaluation.md), [P26 IUT III theta monoids and etale-picture reconstruction](26-iut-iii-theta-monoids.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
