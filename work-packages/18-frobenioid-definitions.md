# P18 Frobenioid and poly-Frobenioid constructions

**Status:** planned. **Value:** ◇ IUT SUPPORT.

Categorical arithmetic and divisor-based reconstruction; broader reuse is more specialized than the classical results.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P18.1 | Abstract structures | Define base categories, divisor/rational-function monoids, Frobenius degrees and the exact Frobenioid classes used by reconstruction. |
| P18.2 | Concrete models | Construct the monoid-to-category examples and realification/perfection of FrobenioidsI Thm5.2, Prop5.3 and Cor5.4. |
| P18.3 | Poly structures | Define the required local/global poly-Frobenioids, modifications and equivalences with all indexing data. |
| P18.4 | Interpretation | Export ordinary mathematical models and prove they satisfy the abstract structures; do not encode a future reconstruction theorem as part of the definition. |

## Source targets

- [frobenioids i](../sources/anabelian/frobenioids-i.md)
- [frobenioids ii](../sources/anabelian/frobenioids-ii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P19 Frobenioid reconstruction, reciprocity and degrees](19-frobenioid-reconstruction.md), [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
