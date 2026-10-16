# P05 Finite etale covers and arithmetic fundamental groups

**Status:** planned. **Value:** ★ REUSABLE.

Foundational infrastructure for algebraic geometry, etale cohomology and all arithmetic anabelian results.

## Prerequisite outputs

- [P01 Shared interfaces and the mathlib baseline](01-shared-interfaces.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P05.1 | Finite covers | Construct the category of finite-etale covers of a scheme, fiber functors and the necessary effective descent/connectedness lemmas. |
| P05.2 | Galois category | Instantiate the existing abstract Galois-category theorem for connected schemes: Stacks58.6.2; identify pi1(Spec K) with the absolute Galois group:58.6.3. |
| P05.3 | Outer functoriality | Prove change of basepoint up to inner conjugacy, morphism-induced continuous maps, open subgroups/connected covers and Galois-cover actions. |
| P05.4 | Arithmetic sequence | Prove Stacks58.14.3: the arithmetic geometric exact sequence for a qcqs geometrically connected scheme over a field. Export sections/decomposition maps when a point supplies them. |
| P05.5 | Coefficients | Implement the needed torsor/Kummer exact sequence (Stacks59.28.1 with n invertible) and its comparison with P03; retain the fppf distinction at noninvertible n. |
| P05.6 | Geometric cohomology | Build the curve etale H1/torsor/pi1 comparison, finite-to-l-adic transition maps and the selected finiteness/base-change/duality statements consumed by P09/P10. Lock scope under A04 using the geometric cohomology source card. This later output does not block release of the P05 finite-cover core. |

## Source targets

- [sga1 and pi1](../sources/foundations/sga1-and-pi1.md)
- [stacks kummer](../sources/foundations/stacks-kummer.md)

- [geometric cohomology](../sources/foundations/geometric-cohomology.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

Downstream consumers: [P06 Algebraic curves, linear systems and Belyi maps](06-curves-and-belyi.md), [P07 Geometric elliptic curves, torsion and reduction](07-elliptic-curves.md), [P08 Nonarchimedean analytic curves and Tate uniformization](08-tate-and-analytic-curves.md), [P09 Abelian varieties, degeneration and finite-field weights](09-abelian-degeneration-and-weights.md), [P10 Selected p-adic comparison and local Kummer results](10-p-adic-comparison.md), [P12 Relative p-adic anabelian Hom and Isom](12-relative-anabelian-geometry.md), [P13 Tempered groups and geometric reconstruction](13-tempered-anabelian-geometry.md), [P14 Combinatorial, abelian and Belyi cuspidalization](14-cuspidalization.md), [P16 Local invariants and global Galois reconstruction](16-local-global-galois-reconstruction.md), [P17 Archimedean topology and Aut-holomorphic reconstruction](17-archimedean-reconstruction.md), [P21 IUT I input and theater data types](21-iut-inputs-and-theater-data.md).

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
