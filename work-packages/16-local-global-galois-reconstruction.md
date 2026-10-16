# P16 Local invariants and global Galois reconstruction

**Status:** planned. **Value:** ★ REUSABLE.

Local and global anabelian number theory, Galois invariants and field reconstruction.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P03 Continuous cohomology, Kummer theory and inverse limits](03-continuous-cohomology.md)
- [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P16.1 | Local invariants | Prove Absolute Anabelian Geometry Prop1.2.1 and the exact cyclotomic/valuation/degree/unit statements used by AbsTopIII Cor1.10 and Prop5.8(i)-(iii). |
| P16.2 | Global proof foundations | Audit and formalize the selected global-CFT, decomposition recognition, density/approximation and other prerequisites of the retained NSW XII/Uchida proof. This subproject owns deeper global leaves, rather than treating Neukirch-Uchida as an unexplained axiom. |
| P16.3 | Global isomorphism | Prove the needed Neukirch-Uchida theorem and Uchida solvably closed specialization, with continuous outer Galois isomorphisms; resolve source-number mismatch A02. |
| P16.4 | Boundary and consumers | Export only the local multiplicative invariant data actually reconstructed; keep additive local-field reconstruction separate. Prove the specified global Aut/Out identity and its functorial use. |

## Source targets

- [continuous galois cohomology](../sources/foundations/continuous-galois-cohomology.md)
- [absolute anabelian curves](../sources/anabelian/absolute-anabelian-curves.md)
- [global solvably closed](../sources/anabelian/global-solvably-closed.md)
- [abstop iii](../sources/anabelian/abstop-iii.md)

**Staged release:** P16.local is the local multiplicative/invariant package. P16.global is the field-class-matched global reconstruction proof, including its owned deeper global arithmetic leaves. Local consumers, including standalone theta rigidity, need not wait for the global theorem.

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P15 Mono-anabelian function-field and global reconstruction](15-mono-anabelian-reconstruction.md), [P22 IUT I theater reconstruction and symmetries](22-iut-i-theater-reconstruction.md), [P25 IUT III log-links and coricity](25-iut-iii-log-links.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
