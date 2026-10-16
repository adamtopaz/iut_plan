# Owned audit gates

The plan assigns unresolved source/statement choices to explicit work items. These gates refine the theorem-level dependency graph before the affected proofs are accepted. They are research/translation tasks with outputs, not added mathematical axioms.

**Initial status:** all implementation gates are open. The source survey and documentation review do not mark a Lean proof complete.

| Gate | Owner | Required output and exit condition | Work that can proceed meanwhile |
|---|---|---|---|
| A01 Source and correction lock | P01; each source owner | Fix author/journal/edition URLs, exact result numbers/page crosswalks and correction attachments. Compare corrected hypotheses/definitions with each consumer. Produce a per-result reference manifest. | Standard APIs and theorem-signature design |
| A02 Numbering discrepancies | P14, P16, P15 | Reconcile the two AbsTopIII caller/callee mismatches below by matching statements and proofs. Record the corrected source target and any changed hypotheses. | Unambiguous local invariants and geometric definitions |
| A03 IUT clause-level closure | P21–P30, coordinated by P30 | Expand every retained direct citation in the final theorem's matrix, every “formal generalization,” and every invoked IUT I/II subconstruction to definitions and exact proof dependencies. Assign any newly found leaf an owner before acceptance. | Each branch's known proof obligations and reusable libraries |
| A04 Classical theorem closure | P04, P06, P09, P10, P11, P16 | Translate caller citations to exact standard theorems/proofs; choose one proof route; inventory all additional classical inputs until they reach proved imports or owned tasks. Include global-CFT/density/approximation leaves under the global Galois reconstruction route. | Already selected statements and supporting APIs |
| A05 Analytic realization | P08, P13 | Lock the rigid/Berkovich framework, analytic/topological-covering comparison and the exact Andre/EtTh input. Prove a bridge if two frameworks are used. | Tate series/local algebra and abstract covering definitions |
| A06 p-adic comparison specialization | P10, P12 | Match Faltings/Tate/Bloch–Kato original statements and all uniform integral bounds to the Local Pro-p consumers. Decide whether the required Isom specialization changes the proof cone; remove a dependency only after all consumers are checked. | Continuous cohomology, good-reduction and Tate-module APIs |
| A07 Archimedean closure | P17, P19, P25 | Lock the needed complex/Aut-holomorphic reconstruction, circle/measure, admissibility and comparison theorems. Audit any further analytic or quasiconformal inputs actually consumed. | Elementary circle/segment/measure models |
| A08 Interpretation and compatibility | P30; independent source reviewer | For every abstract interface, supply its interpretation in the genuine source objects; prove all functoriality/ambiguity/normalization laws and the final theorem's entire clause matrix. | Conditional consumers against explicit signatures |
| A09 Final proof closure | P31; independent Lean/source reviewers | Reproducible full build, no `sorry`/unproved mathematical axioms, reference/import manifest and independent native-statement fidelity review. | Documentation and reusable releases |

## Concrete source-number mismatches

1. **AbsTopIII printed1090 → Global Solvably Closed Anabelian Geometry.** The caller names “Thm3.1” for an Aut(field)/Out(Galois group) identity. The current author PDF's relevant Uchida statement is Thm2.1; its section3 has Prop3.1 on examples. P16 must identify the exact field class and statement before using the edge.
2. **AbsTopIII printed995 → Absolute Anabelian Cuspidalizations.** The caller names “Thm2.1(i); Thm1.1(iii).” The current author PDF instead has Prop2.1 and the maximal cuspidally abelian statement at Thm1.16(iii). P14/P15 must reconcile versions and check all input enhancements rather than mechanically substitute numbers.

## Corrections that affect interfaces

Use the [author catalogue](https://www.kurims.kyoto-u.ac.jp/~motizuki/papers-english.html) and each source card's correction links. The 2026-10-15 source pass located later comments for numerous pre-IUT sources. In particular:

- General tempered/semigraph constructions have Galois-countability restrictions that also affect Frobenioid applications. Geometric specializations need their own hypothesis verification.
- Geometry of Anabelioids has countable-generation qualifications in selected reconstruction statements.
- EtTh's log-meromorphic definition has a corrected root-on-a-tempered-cover condition.
- AbsTopI's cusp criterion and AbsTopII's Belyi-cuspidalization hypotheses have corrections; Combinatorial GC has revised proof ingredients.

The [source cards](../sources/README.md) identify the exact attachments and affected statements. Reading an attachment is not a proof that every consumer satisfies the corrected hypotheses; that is the owning package's task.

## Record a resolved gate

For each item, add the chosen source version/result, exact Lean statement and proved import, consumers, reviewer and date. If a source is replaced by a standard alternative proof, retain the mathematical equivalence/interpretation check and remove duplicate mandatory work from the schedule.

[Home](../README.md) · [Coverage](coverage.md) · [Completion standard](../CONTRIBUTING.md)
