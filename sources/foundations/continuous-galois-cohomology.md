# F04 · Neukirch–Schmidt–Wingberg, Cohomology of Number Fields

**★ REUSABLE · Selected retained results; route-dependent additional leaves.** [Author distribution](https://www.mathi.uni-heidelberg.de/~schmidt/NSW2e/): second edition, corrected printing; version 2.3, May 2020. Pin that version before copying theorem numbers.

## Selected results and boundaries

| Portion / exact caller anchor | Required theorem interface and audit task |
|---|---|
| Chapters I–III: continuous cohomology | Continuous cochains of profinite groups with discrete torsion coefficients, low-degree exactness, restriction/corestriction, cup products and Hilbert 90. State the topology on every coefficient module. |
| Kummer/inverse-limit boundary | For characteristic-zero `K`, identify `Kˣ/(Kˣ)^n` with continuous `H¹(G_K, μ_n)` for positive `n`; prove transition-map, norm and field-extension naturality. Define the completed target with the actual inverse system and prove the comparison. |
| NSW Theorem 7.2.6, cited by Frobenioids II Theorem 2.4(ii) | **Task F04-726:** check the printed statement against the categorical reciprocity caller and export only that specialization, including its saturation/normal-open-subgroup hypotheses on the caller side. |
| Local-field chapter VII | **Task F04-D:** enumerate local Tate-duality, cohomological-dimension and local pro-`p` structure lemmas used by the chosen reconstruction/Hom proof. Formalize those exact coefficient cases; do not add every local or global duality theorem by default. |
| XII Theorem 12.2.1 | Standard Neukirch–Uchida reference for number-field reconstruction. **Task F04-NU:** verify the edition's precise formulation and match it to [P16](../../work-packages/16-local-global-galois-reconstruction.md); keep the separate solvably-closed variant. |

**Recursive task F04-G:** after choosing the exact Neukirch–Uchida/solvably-closed proof, enumerate its global class-field/formation, decomposition-group recognition, approximation and density inputs. Retain global reciprocity/existence or Chebotarev only where that proof consumes them, with separate theorem statements and source locks. Local reciprocity alone cannot discharge global field reconstruction. This task is a required closure gate for [P16](../../work-packages/16-local-global-galois-reconstruction.md), not a claim that the whole global portion of NSW must be formalized.

EtTh Corollary 2.19(ii) also uses vanishing of a derived inverse limit for specified finite systems. Prove their Mittag–Leffler property and the relevant vanishing theorem; arbitrary inverse limits are not exact. This homological-algebra work can run separately from arithmetic.

## Interfaces and parallel work

Ready inputs: profinite groups, continuous actions, representations and homological algebra from [P01](../../work-packages/01-shared-interfaces.md). Deliver through [P03](../../work-packages/03-continuous-cohomology.md), supporting [P04](../../work-packages/04-class-field-theory.md), [P10](../../work-packages/10-p-adic-comparison.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md), [P19](../../work-packages/19-frobenioid-reconstruction.md) and [P20](../../work-packages/20-etale-theta.md).

## Mathlib boundary and reusable release

The [baseline](../../plan/mathlib-baseline.md) locates continuous-cohomology definitions and `H⁰`, ordinary-cohomology tools, finite Hilbert 90, cyclotomic characters and profinite completions. It does not establish a ready continuous `H¹` Kummer/duality API. Release continuous low-degree exactness and natural Kummer comparison first; these benefit descent, Selmer theory and Galois representations long before IUT assembly.

[Foundation map](README.md) · [Kummer sheaves](stacks-kummer.md) · [Global solvably-closed reconstruction](../anabelian/global-solvably-closed.md)
