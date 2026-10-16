# F12 · Bloch–Kato, local §3

**★ REUSABLE · Retained local theorem, not a conjectural global input.** Spencer Bloch and Kazuya Kato, *L-functions and Tamagawa Numbers of Motives*, in *The Grothendieck Festschrift I* (1990), 333–400; [publisher](https://link.springer.com/chapter/10.1007/978-0-8176-4574-8_9), [original chapter scan](https://math.stanford.edu/~conrad/BSDseminar/refs/BKTamagawa.pdf).

## Precise targets

- **§3, Example 3.11, printed p.361:** for an abelian variety over a finite extension of `ℚ_p`, its classical exponential and the cohomological exponential agree through the tangent-space/de Rham comparison and the Kummer map. Extract the local-condition identifications needed by Local Pro-p Lemma 4.1.
- **Lemma 3.8.1, printed p.355:** the stated injectivity between continuous `H¹` groups with de Rham period coefficients, for a de Rham representation. Lock the period-ring/lattice notation from the scan before writing the Lean statement.
- **Definition 3.10 and Example 3.10.1:** the exponential and the formal-group compatibility used in Example 3.11's proof.

**Selection task F12-K:** match the exact `p`-primary specialization of Example 3.11 to the caller; distinguish integral Tate-module local conditions from their rationalizations and record the local-duality/semistable-reduction and period-ring lemmas used in the printed proof. The chapter's more general total Tate-module notation does not license dropping topology or prime cases.

This imports neither the full Tamagawa-number conjecture nor the norm-residue theorem. The source's precise local statement is useful even if the global conjectural parts are not formalized.

## Interfaces and parallel work

Ready inputs: [P03](../../work-packages/03-continuous-cohomology.md), [P04](../../work-packages/04-class-field-theory.md), [P09](../../work-packages/09-abelian-degeneration-and-weights.md), and [P10](../../work-packages/10-p-adic-comparison.md)'s period/representation definitions. Main consumer: [P12](../../work-packages/12-relative-anabelian-geometry.md). Formal-group and Kummer naturality can start while the comparison theorem is developed.

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) finds foundational cohomology, without certifying period rings, the Bloch–Kato exponential or these local-condition identities. Deliver finite-dimensional de Rham local conditions with explicit maps, then the abelian-variety exponential/Kummer square. These are independent milestones for Selmer theory, local heights and `p`-adic representations.

[Foundation map](README.md) · [Tate](tate-p-divisible.md) · [Faltings](faltings-p-adic-hodge.md)

**Supporting proof slice:** [F20 Fontaine](fontaine-period-rings.md) owns the period-ring/de Rham/crystalline/formal-group inputs of Prop1.17 and the local section3 argument. Local duality from P04 and semistable/special-fiber weight inputs from P09 remain explicit prerequisites; Hodge-Tate comparison alone does not supply them.
