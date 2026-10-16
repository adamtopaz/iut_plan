# P03 Continuous cohomology, Kummer theory and inverse limits

**Status:** planned. **Value:** ★ REUSABLE.

Galois representations, descent, Selmer/Kummer constructions and arithmetic duality.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P03.1 | Cochains | Complete the low-degree continuous cohomology API, exact sequences, restriction/corestriction and comparisons with finite/discrete models under stated hypotheses. |
| P03.2 | Finite Kummer | For n>=1 invertible in a field, connect finite Kummer extensions and Hilbert90 to continuous H1(G_K,mu_n(Ksep)); prove naturality. |
| P03.3 | Tate coefficients | Build Tate modules/twists and completed multiplicative Kummer maps with all transition maps; prove precisely the inverse-limit and R1-lim vanishing statements consumed later. |
| P03.4 | Scheme bridge | After P05 and the relevant exactness tools are available, identify the etale Kummer torsor construction with its Galois-cohomological form. This is a required later bridge for retained scheme/evaluation consumers; it is not needed to start the cochain core. |

## Source targets

- [continuous galois cohomology](../sources/foundations/continuous-galois-cohomology.md)
- [stacks kummer](../sources/foundations/stacks-kummer.md)
- [tate p divisible](../sources/foundations/tate-p-divisible.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P04 Local reciprocity, duality and local Galois structure](04-class-field-theory.md), [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md), [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md), [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md), [P20 Etale theta and its rigidity theorems](20-etale-theta.md), [P27 Measured tensor packets and integral structures](27-measured-tensor-packets.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
