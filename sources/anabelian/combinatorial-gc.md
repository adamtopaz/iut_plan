# A Combinatorial Version of the Grothendieck Conjecture

**★ REUSABLE** · Owner: [P14 cuspidalization](../../work-packages/14-cuspidalization.md), sharing foundations with [P11](../../work-packages/11-trees-and-profinite-groups.md).

Shinichi Mochizuki, *Tohoku Mathematical Journal* **59** (2007), 455–479. [Author PDF](https://www.kurims.kyoto-u.ac.jp/~motizuki/Combinatorial%20Grothendieck%20Conjecture.pdf); [May 2020 comments](https://www.kurims.kyoto-u.ac.jp/~motizuki/Combinatorial%20Grothendieck%20Conjecture%20%28comments%29.pdf).

## Selected targets

| Target | Mathematical hypotheses / exported interface | Citation precision |
|---|---|---|
| Proposition 1.2 | Vertex/edge subgroup and graph recognition at the paper's specified pro-prime-set stable-curve scope | Explicit import in AbsTop I Lemma 4.5; original exact target audit remains |
| Theorem 1.6 | Combinatorial anabelian reconstruction for the paper's PSC-type semi-graphs | Explicit import in the same cusp-recognition proof; integrate the revised 2020 argument |
| Proposition 2.4 | Recovery using the arithmetic action, period/weight separation, and the applicable stable-curve data | Imported by AbsTop I 4.5; its proof route includes period-pairing nondegeneracy and weights |
| Corollary 2.7 | The cusp/graph-recognition conclusion consumed in that route | Caller-audited; original exact subclauses still to lock |

**Evidence.** The four imports are verified in the caller's proof. This is **caller-audited**, not a completed audit of all four original proofs. The exact PSC-type predicate, prime-set hypotheses, admissible actions, and outer-isomorphism classes must be encoded before advertising a general curve-group theorem.

## Prerequisite interfaces

[P11 trees/profinite groups](../../work-packages/11-trees-and-profinite-groups.md) supplies graph-of-groups and subgroup theory; [P05](../../work-packages/05-etale-fundamental-groups.md)/[P06](../../work-packages/06-curves-and-belyi.md) supply the geometric cover/curve interpretation; [P09 degeneration and weights](../../work-packages/09-abelian-degeneration-and-weights.md) supplies the finite-field Jacobian weights and period information. Coordinate an abstract graph interface with [Semi-graphs](semi-graphs.md) so that shared combinatorial lemmas are proved once.

## Parallel outputs and acceptance

A graph/group team can prove the conditional reconstruction theorem while a degeneration team proves the arithmetic conditions of its geometric instances. Export recognized cusp/vertex/edge subgroup conjugacy classes with cover/isomorphism naturality. The primary downstream consumer is [AbsTop I](abstop-i.md)'s Lemma 4.5 and chain theorem. This milestone supports independent work on stable-curve fundamental groups and cuspidal recognition.

**Closure task — P14 owner.** Audit each original statement against the caller. The 2020 comments revise the proof ingredients for Theorem 1.6, clarify connected Galois coverings, and correct rank/nonempty-prime assumptions. Integrate the corrected lemmas rather than placing the original and replacement assertions in separate Lean axioms. Identify the minimal abelian-variety weight theorem sufficient for Proposition 2.4; the full Weil conjectures are not implied by this citation.

[Source graph](README.md) · [Project home](../../README.md)
