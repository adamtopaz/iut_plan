# IUT II: Hodge-Arakelov-theoretic Evaluation

**Source:** Shinichi Mochizuki, *Inter-universal Teichmüller Theory II: Hodge-Arakelov-theoretic Evaluation*, Publ. RIMS 57 (2021), 209–401. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Inter-universal%20Teichmuller%20Theory%20II.pdf) · [Author catalogue and corrections](https://www.kurims.kyoto-u.ac.jp/~motizuki/papers-english.html).

**Role:** IUT SPECIFIC. Divide local evaluation from global gluing so each has a precise interface and can be developed by separate teams.

## Selected targets

| Item | Exact source target | Output and mathematical scope | Owner |
|---|---|---|---|
| II.1 | Required section1 multiradial mono-theta constructions; selected Cors1.10–1.12 when invoked | Cyclotomic and mono-theta reconstruction functors with the stated enhanced input/ambiguity | P23.1; A03 |
| II.2 | Section2, especially Cor2.5 | Galois-theoretic theta evaluation at labeled torsion points, with the correct parameter/root conventions | P23.2 |
| II.3 | Section3, especially Cors3.5–3.6 | Gaussian/splitting monoids and conjugate synchronization, with a common conjugacy ambiguity distinguished from independent choices | P23.3/4 |
| II.4 | Props4.2(i),4.4(i) and supporting global constructions | Good/archimedean/global Gaussian Frobenioids and comparison maps | P24.1 |
| II.5 | Cor4.6(iii)–(v); Cor4.7(iii); Cor4.8(i)–(iii) | Local/global Kummer maps, gluing, labeled number-field data and evaluation/naturality | P24.2 |
| II.6 | Def4.9(viii); Cor4.10(ii),(iv); Cor4.11(ii),(iii) | Pilots, horizontal modified theta-links, full poly-isomorphisms and etale pictures | P24.3/4 |

II.4–II.6 are directly cited throughout III.3.11. II.1–II.3 supply their local construction and reconstruction layer. A03 must expand each retained section-level row to exact proof inputs; the list does not imply every unrelated remark in the paper is mandatory.

## Parallelism and prerequisites

Start local theta/evaluation implementation after [EtTh](../anabelian/etale-theta.md) and the actual [IUT I theater interfaces](iut-i.md) are available. A global team can design the II.4–II.6 gluing and pilot types against those local signatures while the proofs of II.2–II.3 are in progress. The global acceptance gate still requires the completed local proof, [function-field reconstruction](../anabelian/abstop-iii.md), [archimedean comparison](../../work-packages/17-archimedean-reconstruction.md), and [Frobenioid reconstruction](../anabelian/frobenioids-ii.md).

The j-squared profile must arise from actual normalized theta evaluation. Exporting an arbitrary tuple of abstract monoid elements does not satisfy the source's interpretation requirement.

## Handoff

[P23](../../work-packages/23-iut-ii-local-evaluation.md) and [P24](../../work-packages/24-iut-ii-global-gluing.md) supply the exact Kummer, pilot, symmetry and horizontal-link interfaces used by IUT III. All compatibility assertions are mathematical proof obligations, not annotations on the diagram.

[All sources](../README.md) · [IUT I](iut-i.md) · [IUT III](iut-iii.md)
