# P08 Nonarchimedean analytic curves and Tate uniformization

**Status:** planned. **Value:** ★ REUSABLE.

Nonarchimedean uniformization, degenerating elliptic curves, analytic fundamental groups and theta functions.

## Prerequisite outputs

- [P02 Local and global fields, unit logarithms and lattices](02-local-global-fields.md)
- [P05 Finite etale covers and arithmetic fundamental groups](05-etale-fundamental-groups.md)
- [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P08.1 | Analytic category | Choose and implement a precise rigid/Berkovich analytic framework sufficient for the retained coverings, analytification and convergence arguments (A05). |
| P08.2 | Tate curve | Prove Tate uniformization over finite extensions of Q_p, the analytic uniformization over an appropriate complete field and the induced equivariant algebraic-point multiplicative quotient, torsion description and q-valuation normalization (Silverman Advanced V). |
| P08.3 | Covering comparisons | Prove the finite-etale/analytic comparison and the topological covering facts required to define tempered coverings. General analytic spaces beyond this scope are not automatic targets. |
| P08.4 | Theta preliminaries | Construct the actual Tate theta products/series, convergence, divisor and functional equations needed by EtTh; preserve its parameter/root conventions. |
| P08.5 | Corrected formal models | Define the formal ringed-space models used by corrected EtTh, prove the selected normality/normalization and Hensel/excellence lemmas, and prove any required bridge to rigid/Berkovich analytic realizations. Source anchors: EGA IV second part7.8.3 and Faltings crystalline PartII Thm2.6-following remark. |

## Source targets

- [rigid analytic foundations](../sources/foundations/rigid-analytic-foundations.md)
- [tate uniformization](../sources/foundations/tate-uniformization.md)
- [andre tempered](../sources/anabelian/andre-tempered.md)

- [Berkovich analytic topology](../sources/foundations/berkovich-analytic-topology.md)

- [EGA formal normalization](../sources/foundations/ega-formal-normalization.md)
- [Faltings crystalline/formal normalization](../sources/foundations/faltings-crystalline-1990.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md), [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md), [P20 Etale theta and its rigidity theorems](20-etale-theta.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
