# The final theorem and its prerequisite clauses

**Final target:** Mochizuki, IUT III, Theorem3.11, “Multiradial algorithms via LGP-monoids/Frobenioids,” printed573–580. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Inter-universal%20Teichmuller%20Theory%20III.pdf) · [Source card](../sources/iut/iut-iii.md).

The target is the full theorem, with its native initial theta data and LGP-Gaussian log-theta lattice. The final proof is [P31](../work-packages/31-theorem-3-11.md). Fix the statement requirements early so independent libraries export the right interfaces; accept the final native Lean theorem only after all its prerequisites are proved.

## Mathematical specification

The implementation must express all three assertion groups:

1. **Multiradial representation:** construct the procession-indexed topological tensor modules and integral structures with their prescribed volumes, splitting monoid/action, reconstructed global fields/Frobenioids and degrees; quotient by exactly Ind1/Ind2; prove functoriality for procession isomorphisms and compatibility with etale-picture and bi-coricity symmetries.
2. **Log-Kummer correspondence:** construct the stated Kummer isomorphisms and compare them with each theater in a vertical column; prove the roots-of-unity/non-interference assertion, the MOD versus mod distinction, Ind3's specified one-sided behavior and exact volume compatibility.
3. **Horizontal theta-link compatibility:** prove every stated comparison of prime strips, projective mono-theta systems, global Kummer data and evaluation maps; establish the stated stabilization/equivariance under arbitrary domain/codomain automorphisms with the correct indeterminacies.

The Lean formulation may use equivalent categorical encodings, but it needs a proved interpretation back into these native objects and a clause-by-clause correspondence. A weaker scalar/log-volume assertion, the later Corollary3.12 inequality, or an abstract record that assumes these compatibility laws is a different result.

## Direct citation and ownership matrix

The following references were recorded from the complete printed573–580 statement/proof. “Cf.”/interpretive references are included for audit, without assuming each is independently indispensable. Combined ranges abbreviate repeated references; the source card and package acceptance expand retained proof inputs.

| Clause / printed page | Direct source references | Formalization owner and output |
|---|---|---|
| Setup /573 | I Def3.1; III Def3.8(iii); Thm1.5(i); Rem3.8.2 | P21 initial data; P25 coricity; P28 native LGP lattice |
| Procession /573 | I Prop6.9(iii) | P22 signed procession functor |
| (i)(a) /574 | III Props3.2(ii),3.4(vi),3.9(ii) | P27.R/V, P28 packet/integral structures and normalized volumes |
| (i)(b) /574 | III Props3.5(i),(ii)(c),3.2(i),(iii) | P28 splitting monoid, packet embedding/poly-isomorphism and action |
| (i)(c) /574 | III Props3.9(iii),3.10(i) | P27/P29 reconstructed fields/Frobenioids and global degree |
| Ind2 /575 | III Prop1.2(vi),(vii); Prop3.2(iii) | P25/P27/P30 independent local/summand actions and archimedean sign ambiguity |
| (i) symmetry /575 | I Cor6.10(iii); II Cors4.10(iv),4.11(ii),(iii); III Cor2.3(ii), Rems2.3.2,3.8.2, Thm1.5(iii) | P22/P24/P25/P26/P30 permutation and bi-coricity naturality |
| (ii) first Kummer display /575 | II Cors4.6(iii),4.8(i),(ii); III Props3.5(i),3.10(i) | P24/P28/P29 labeled constant/function/number-field comparisons |
| (ii)(a) /576 | III Props3.2(i),(ii),3.4(ii),3.5(i),3.9(ii) | P27/P28 local integral/rational tensor-packet Kummer comparison and volumes |
| (ii)(b) /576 | III Prop3.5(i),(ii)(c) | P28 splitting-monoid Kummer isomorphism |
| (ii)(c) /576 | III Props3.10(i),(ii),3.7(iii),(iv),(v) | P28/P29 global Frobenioid and LGP/lgp comparisons |
| Vertical compatibility /577 | III Prop3.5(ii)(c); Prop3.10(ii),(iii); Rem3.10.1 | P29/P30 roots-of-unity intersection, total log-link precompositions, MOD/mod distinction |
| Ind3 /577 | III Prop3.5(ii)(a),(b) | P28/P30 exact nonarchimedean inclusion and archimedean surjection systems |
| Volume compatibility /577 | III Prop3.9(iv) | P27.V/P28.4/P30 exact normalization and log-link comparison |
| (iii)(a) /577 | III Thm1.5(ii),(iii) | P25/P30 horizontal Kummer/prime-strip comparison |
| (iii)(b) /577–578 | III Props2.1(vi),3.4(ii),3.7(iii),(iv); II Cors4.6(iv),(v),4.10(ii); III Thm1.5(ii),Cor2.3(iii) | P24/P25/P26/P28/P30 unit portions/environment strips and horizontal comparison |
| (iii)(c) /578–579 | III Cor2.3(ii)–(iv), Rem3.8.2, Props2.1(ii),(iii),(vi),3.4(ii),3.7(iii),(iv), Thms2.2(iii),1.5(ii); II Cors4.6(iv),(v),4.10(ii); III Rem3.11.4 | P20/P24/P26/P28/P30 projective mono-theta systems, Kummer evaluation and arbitrary-automorphism equivariance |
| (iii)(d) /579–580 | II Cors4.6(iv),4.8(iii),4.7(iii); I Def5.2(vi),(viii); II Props4.2(i),4.4(i); III Cor2.3(ii),Rems2.3.2,3.8.2,Thm1.5(ii),Rem3.11.4 | P21/P24/P25/P26/P29/P30 global gluing and all related evaluation/naturality squares |
| Proof /580 | Definitions and references in the assertions; Remarks3.11.1–3.11.4 | P30 interpretive/compatibility closure, followed by P31 final assembly |

## Indeterminacy acceptance tests

| Indeterminacy | Exact implementation obligation | Inadequate replacement |
|---|---|---|
| Ind1 | Automorphisms of the specified ordered procession and its admissible data, with induced actions/naturality | Arbitrary permutations that do not preserve the actual procession |
| Ind2 | Independent copies of the specified Ism/local action on each direct summand of each of the j+1 tensor factors; archimedean order-two counterparts | One global simultaneous automorphism or an unspecified “up to isomorphism” |
| Ind3 | The source's inclusion/surjection comparisons under vertical log-links, including the allowed iterates/precomposites | Exact commutation everywhere, arbitrary enlargement, or extra indeterminacy not supplied by the source |

## Final release gate

P31 may be accepted when every matrix row has an actual imported Lean theorem with the required interpretation, no source-version ambiguity remains on a retained edge, all [audit gates](../tracking/audit-gates.md) are closed for the proof route, and an independent review checks the full assertion rather than only a convenient consequence. The full import closure must compile without unproved mathematical assumptions.

[Home](../README.md) · [Roadmap](roadmap.md) · [Source graph](../graphs/sources.md) · [Completion standard](../CONTRIBUTING.md)
