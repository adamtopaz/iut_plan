# P31 IUT III Theorem 3.11

**Status:** planned. **Value:** IUT SPECIFIC.

Final integration target. No later Corollary3.12 inequality or IUT IV/abc reduction is included.

## Prerequisite outputs

- [P30 Native statement and compatibility closure](30-iut-iii-compatibility.md)

The prerequisites above describe the main proof boundary, not a ban on earlier parallel definition work. Agree on exported types first; a conditional consumer may develop against theorem hypotheses, but its final acceptance requires the corresponding proofs and interpretation bridges.

## Deliverables

| Item | Target | Completion requirement |
|---|---|---|
| P31.1 | Final proof | Assemble the multiradial representation (i), log-Kummer correspondence (ii), and horizontal Theta-link compatibility (iii) from previously proved interfaces. |
| P31.2 | Kernel check | Compile the complete import closure at the pinned Lean/mathlib versions, audit axioms/sorry-free status, and independently review theorem-statement fidelity. |
| P31.3 | Release | Publish the full dependency manifest and reusable library contributions, with exact correspondence to the source and all correction/version locks. |

## Source targets

- [iut iii](../sources/iut/iut-iii.md)

## Acceptance and handoff

Every required theorem is a compiled proof from the selected foundations and earlier proved exports, with its actual topological/geometric hypotheses. Interpret abstract structures in the genuine mathematical objects; record residual choice, conjugacy and normalization explicitly. Statements, source selection and proof completion are tracked separately under the [completion standard](../CONTRIBUTING.md).

**Final sink:** this package is accepted last. It is the goal of the entire roadmap.

[All packages](README.md) · [Parallel roadmap](../plan/roadmap.md) · [Source graph](../graphs/sources.md) · [Audit gates](../tracking/audit-gates.md)
