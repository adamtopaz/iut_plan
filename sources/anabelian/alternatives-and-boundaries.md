# Optional routes and scope boundaries

These are **selected alternatives or boundary references**, not three additional mandatory prerequisites. Owners: [P12](../../work-packages/12-relative-anabelian-geometry.md), [P14](../../work-packages/14-cuspidalization.md), [P16](../../work-packages/16-local-global-galois-reconstruction.md).

| Source / version | Precise candidate or boundary | Status and owner |
|---|---|---|
| Shinichi Mochizuki, [*A Version of the Grothendieck Conjecture for p-adic Local Fields*](https://www.kurims.kyoto-u.ac.jp/~motizuki/A%20Version%20of%20the%20Grothendieck%20Conjecture%20for%20p-adic%20Local%20Fields.pdf), *International Journal of Mathematics* **8** (1997), 499–506 | Theorem 4.2: for finite extensions of `ℚ_p`, reconstruct field isomorphisms from outer Galois isomorphisms preserving the **positive upper-numbering ramification filtration** | **★ REUSABLE, optional enhanced-field theorem.** Target located in prior audit; P16 must verify each caller supplies the filtration before adopting it |
| Akio Tamagawa, [*The Grothendieck Conjecture for Affine Curves*](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/1992BA14A2D63FA076DB39A34EC45E83/S0010437X97000614a.pdf/grothendieck_conjecture_for_affine_curves.pdf), *Compositio Mathematica* **109** (1997), 135–194 | Affine curve Isom results and subgroup/point-recognition lemmas; proper-cuspidalization comments cite Corollary 2.10 and Proposition 3.8; Absolute Anabelian Geometry cites finite-field Theorem 4.3 | **★ REUSABLE.** Full theorem is an alternative for matching field classes; selected lemmas become required if retained by the actual proper-cuspidalization or special-fiber proof. P14/P13 must audit these exact calls |
| Moshe Jarden–Jürgen Ritter, [*On the Characterization of Local Fields by Their Absolute Galois Groups*](https://www.tau.ac.il/~jarden/Articles/paper19.pdf), *Journal of Number Theory* **11** (1979), 1–13 | Classification/counterexample source showing that an unenhanced local absolute Galois group does not in general determine its local field | **Boundary only.** P16 may formalize the needed counterexample to test an interface; it is not a positive dependency of Theorem 3.11 |

## How route choices change the plan

The default proof route remains [Local Pro-p](local-pro-p.md) → [Galois Sections](galois-sections.md) → [Semi-graphs](semi-graphs.md), together with [AbsTop](abstop-iii.md)'s selected reconstruction algorithms. The filtered local-field theorem changes the input contract; it can replace another result only after a theorem proves the required filtration is available. An affine theorem over one field class does not replace a local p-adic theorem over a larger field class.

For each proposed replacement, the package owner should record: the old exported statement, the replacement's exact hypotheses, the construction of its extra data, all consumers, and a proof that their naturality requirements are preserved. Only then remove the displaced source edge. This makes narrower implementation choices parallelizable without hiding their mathematical obligations.

## Other useful optional milestones

The full relative Hom theorem is useful beyond the Isom target; stronger configuration-space results, filtered local reconstruction, and broader tempered/GT theorems can be separate follow-up milestones. Keep their independent usefulness visible while leaving them outside the mandatory P31 proof closure until an actual retained call requires them.

[Source graph](README.md) · [Work-package contract](../../plan/package-contract.md) · [Project home](../../README.md)
